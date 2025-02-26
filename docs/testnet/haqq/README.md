# Services

<figure><img src="https://raw.githubusercontent.com/kj89/testnet_manuals/main/pingpub/logos/haqq.png" width="150" alt=""><figcaption></figcaption></figure>

Haqq is the blockchain network that issues Islamic Coin,  its native cryptocurrency. Haqq is fast, trusted and  compatible with thousands of applications around the world.

**Chain ID**: haqq_54211-3 | **Latest Version Tag**: v1.3.1 | **Wasm**: OFF

[Website](https://islamiccoin.net) | [Discord](https://discord.gg/hU9MHG5kZq) | [Twitter](https://twitter.com/Islamic_Coin)




## Chain explorer
[https://explorer.kjnodes.com/haqq-testnet](https://explorer.kjnodes.com/haqq-testnet)

## Public endpoints

* api: [https://haqq-testnet.api.kjnodes.com](https://haqq-testnet.api.kjnodes.com)
* rpc: [https://haqq-testnet.rpc.kjnodes.com](https://haqq-testnet.rpc.kjnodes.com)
* grpc: [https://haqq-testnet.grpc.kjnodes.com](https://haqq-testnet.grpc.kjnodes.com)

## Peering

**state-sync**

```text
d5519e378247dfb61dfe90652d1fe3e2b3005a5b@haqq-testnet.rpc.kjnodes.com:35656
```

**seed-node**

```text
3f472746f46493309650e5a033076689996c8881@haqq-testnet.rpc.kjnodes.com:35659
```

**addrbook**
```bash
curl -Ls https://snapshots.kjnodes.com/haqq-testnet/addrbook.json > $HOME/.haqqd/config/addrbook.json
```

**live-peers** (36)
```bash
peers="f93085d78df16bbd16a525683af7f857ce1cd983@188.40.98.169:36656,2d13d679b64e1a574904a140f72815644ec71131@65.21.133.125:30656,d5519e378247dfb61dfe90652d1fe3e2b3005a5b@65.109.68.190:35656,56158e0f2acf850114e82644afceb565a73b08cc@185.144.99.95:26656,0833039f717227ccd156d156ea772746b8ac6d71@146.19.24.139:26656,6771e65c1b30cc514faf5943320fdda480fe9124@95.216.39.183:26656,23a1176c9911eac442d6d1bf15f92eeabb3981d5@45.83.173.18:26656,dd5ebfba86d8b5ff9c6ea3eb340fdb30e4c6990f@162.55.102.45:26656,48a2a7762a579d25bca95b0a3548b714238dd60b@213.239.216.252:20656,43dc2d5ab6fa30cb10959717d26f31bc45b56fdd@149.102.133.67:35656,4990ed7074424046184dd474df40902c30f34182@65.108.250.241:26656,c1daefce01efd7ab1c10bd503d386d08cf03c573@78.47.51.242:26656,23ff658b56fbb8bc73372973a34733ff5d79b435@142.132.202.50:11604,32a8eec046b95e8646ff0810b4596dc7083a0beb@65.108.145.131:26656,9eb507f9365313dbe7f426050fec9648298f58ee@109.205.183.51:26656,927a323649e7dd8d4c75da6e5edaee439652b46f@65.109.92.241:20116,3df5a68b919177179c6dcb0b9c9354fd6bbba1c8@65.109.92.240:20116,24e894d4d8a18276acf6051cccf369a1ce69842d@65.108.151.105:26656,62bf004201a90ce00df6f69390378c3d90f6dd7e@45.83.173.19:26656,00864d91f9a8c9431c3bc12422ae9593bc12db66@185.211.5.228:26656,f57fae1bdea281392b563a58978a2d8c0a37725f@95.217.233.234:26656,45bc6d84ffb3bb725cf78e82205639797c30af67@65.108.199.62:26656,93ae3fa625f55b98225b870e4fd4052ad8a97b97@109.123.252.231:26656,a884387139109784cad9193652b82ef20a85d713@38.242.159.148:26656,90b40d2b773090b82aa7788c2d1937e4fd6d2dc0@65.108.231.124:19656,0f56d6cd1eae6fd5de684bcc6ee63622e17436af@149.102.149.117:35656,d7ac44bf8f8d760c3df1a8695145021f35feb985@34.88.220.124:26656,47a269c3e30f70d8234a2afd8e9055e74129fde0@65.108.129.29:36656,b72f2156db8c87e679dc853730746ff40038120c@213.239.215.77:26656,59af99085c961a6a5c8dc4bc8b3abffda16ddccb@135.181.38.62:26656,ed145a35b436878c1f1c10634bd18600f3696e17@95.217.181.142:26656,077d5d9169efb4b070ce7895d680a9d2148d522c@195.201.195.40:36656,5a223d77d01319a8c7f648eddfc8549cafcd8ca5@34.147.118.211:26656,78e3ef8adf819b479acc13a2f92ab5c0fa350aeb@66.45.231.30:11464,04e76400e2ad0063e18a2174adad69853a13e8bc@149.102.133.20:35656,1a68f19b58e0c4e99c907a3c43923641a1595c88@149.102.133.29:35656"
sed -i -e "s|^persistent_peers *=.*|persistent_peers = \"$peers\"|" $HOME/.haqqd/config/config.toml
```
