---
description: Catch the latest block faster by using our daily snapshots.
---

# Snapshot

<figure><img src="https://raw.githubusercontent.com/kj89/testnet_manuals/main/pingpub/logos/defund.png" width="150" alt=""><figcaption></figcaption></figure>

{% hint style='info' %}
Snapshots allows a new node to join the network by recovering application state from a backup file. 
Snapshot contains compressed copy of chain data directory. To keep backup files as small as plausible, 
snapshot server is periodically beeing state-synced.
{% endhint %}

Snapshots are taken automatically every 6 hours starting at **04:30 UTC**

**pruning**: 100/0/19 | **indexer**: null | **version tag**: v0.2.3

| BLOCK             | AGE             | DOWNLOAD                                                                                            |
| ----------------- | --------------- | --------------------------------------------------------------------------------------------------- |
| 4134115 | 1 hours | [snapshot (20.53 GB)](https://snapshots.kjnodes.com/defund-testnet/snapshot\_latest.tar.lz4) |

## Instructions

### Stop the service and reset the data

```bash
sudo systemctl stop defundd
cp $HOME/.defund/data/priv_validator_state.json $HOME/.defund/priv_validator_state.json.backup
rm -rf $HOME/.defund/data
```

### Download latest snapshot

```bash
curl -L https://snapshots.kjnodes.com/defund-testnet/snapshot_latest.tar.lz4 | tar -Ilz4 -xf - -C $HOME/.defund
mv $HOME/.defund/priv_validator_state.json.backup $HOME/.defund/data/priv_validator_state.json
```

### Restart the service and check the log

```bash
sudo systemctl start defundd && sudo journalctl -u defundd -f --no-hostname -o cat
```
