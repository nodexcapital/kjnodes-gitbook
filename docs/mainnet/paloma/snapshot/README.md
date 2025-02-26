---
description: Catch the latest block faster by using our daily snapshots.
---

# Snapshot

<figure><img src="https://raw.githubusercontent.com/kj89/testnet_manuals/main/pingpub/logos/paloma.png" width="150" alt=""><figcaption></figcaption></figure>

{% hint style='info' %}
Snapshots allows a new node to join the network by recovering application state from a backup file. 
Snapshot contains compressed copy of chain data directory. To keep backup files as small as plausible, 
snapshot server is periodically beeing state-synced.
{% endhint %}

Snapshots are taken automatically every 6 hours starting at **06:15 UTC**

**pruning**: 100/0/19 | **indexer**: null | **version tag**: v0.11.6

| BLOCK             | AGE             | DOWNLOAD                                                                                            |
| ----------------- | --------------- | --------------------------------------------------------------------------------------------------- |
| 147854 | 5 hours | [snapshot (0.21 GB)](https://snapshots.kjnodes.com/paloma/snapshot\_latest.tar.lz4) |

## Instructions

### Stop the service and reset the data

```bash
sudo systemctl stop palomad
cp $HOME/.paloma/data/priv_validator_state.json $HOME/.paloma/priv_validator_state.json.backup
rm -rf $HOME/.paloma/data
```

### Download latest snapshot

```bash
curl -L https://snapshots.kjnodes.com/paloma/snapshot_latest.tar.lz4 | tar -Ilz4 -xf - -C $HOME/.paloma
mv $HOME/.paloma/priv_validator_state.json.backup $HOME/.paloma/data/priv_validator_state.json
```

### Restart the service and check the log

```bash
sudo systemctl start palomad && sudo journalctl -u palomad -f --no-hostname -o cat
```
