# Services

<figure><img src="https://raw.githubusercontent.com/kj89/testnet_manuals/main/pingpub/logos/paloma.png" width="150" alt=""><figcaption></figcaption></figure>

Paloma is a fast, permissionless, Cosmos-SDK blockchain that  moves messages securely, between any other blockchains.

**Chain ID**: messenger | **Latest Version Tag**: v0.11.6 | **Wasm**: ON

[Website](https://www.palomachain.com) | [Discord](https://discord.gg/tKVFpfdSw4) | [Twitter](https://twitter.com/paloma_chain)




## Chain explorer
[https://explorer.kjnodes.com/paloma](https://explorer.kjnodes.com/paloma)

## Public endpoints

* api: [https://paloma.api.kjnodes.com](https://paloma.api.kjnodes.com)
* rpc: [https://paloma.rpc.kjnodes.com](https://paloma.rpc.kjnodes.com)
* grpc: [https://paloma.grpc.kjnodes.com](https://paloma.grpc.kjnodes.com)

## Peering

**state-sync**

```text
d9bfa29e0cf9c4ce0cc9c26d98e5d97228f93b0b@paloma.rpc.kjnodes.com:10656
```

**seed-node**

```text
400f3d9e30b69e78a7fb891f60d76fa3c73f0ecc@paloma.rpc.kjnodes.com:10659
```

**addrbook**
```bash
curl -Ls https://snapshots.kjnodes.com/paloma/addrbook.json > $HOME/.paloma/config/addrbook.json
```

**live-peers** (14)
```bash
peers="317141e329bc214a76ba92201f6818574ebe5323@135.181.114.98:36656,31177b544fcf1cae76e3560812f4f901cab27126@65.109.61.175:26656,4569193b58dfc6d9ca9acd4e2bcabf596e5b6b3c@65.21.7.251:10656,874ccf9df2e4c678a18a1fb45a1d3bb703f87fa0@65.109.172.249:26656,7e93f6409ade895fe301b502d6fb9dfb96343a34@135.125.5.34:54056,9581fadb9a32f2af89d575bb0f2661b9bb216d41@46.4.23.108:26656,2c6772b11c1f9eff2a923eb2bf808543cdd501c5@79.143.179.196:26656,d9bfa29e0cf9c4ce0cc9c26d98e5d97228f93b0b@65.109.88.38:10656,22e7a98b54070bee0f504305d9ed0fb7a2b24ab6@34.221.60.207:26656,7fc87c698d58bcbd1c6092f951d5f150eed05744@138.201.156.255:26656,b92c94f00b46500a5ff8920acd438c0873c2f9da@50.116.13.101:26656,6ee0ed8ddb1eaaf095686962d71fddb1383b5199@65.21.138.123:26656,9cf215d69773173a4c40eb2e811cea8aa7e37432@213.239.216.252:21656,106350c704aa5e2e0af1464cd3269372d86a9b24@148.113.137.33:26656"
sed -i -e "s|^persistent_peers *=.*|persistent_peers = \"$peers\"|" $HOME/.paloma/config/config.toml
```
