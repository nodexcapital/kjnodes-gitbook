# Services

<figure><img src="https://raw.githubusercontent.com/kj89/testnet_manuals/main/pingpub/logos/lava.png" width="150" alt=""><figcaption></figcaption></figure>

Lava powers a trustless market for RPC data access. The protocol  governs over peer to peer and private Provider-Application pairings,  ensuring high quality RPC service while creating consensus around data served.

**Chain ID**: lava-testnet-1 | **Latest Version Tag**: v0.5.2 | **Wasm**: OFF

[Website](https://lavanet.xyz) | [Discord](https://discord.com/invite/Tbk5NxTCdA) | [Twitter](https://twitter.com/lavanetxyz)




## Chain explorer
[https://explorer.kjnodes.com/lava-testnet](https://explorer.kjnodes.com/lava-testnet)

## Public endpoints

* api: [https://lava-testnet.api.kjnodes.com](https://lava-testnet.api.kjnodes.com)
* rpc: [https://lava-testnet.rpc.kjnodes.com](https://lava-testnet.rpc.kjnodes.com)
* grpc: [https://lava-testnet.grpc.kjnodes.com](https://lava-testnet.grpc.kjnodes.com)

## Peering

**state-sync**

```text
d5519e378247dfb61dfe90652d1fe3e2b3005a5b@lava-testnet.rpc.kjnodes.com:44656
```

**seed-node**

```text
3f472746f46493309650e5a033076689996c8881@lava-testnet.rpc.kjnodes.com:44659
```

**addrbook**
```bash
curl -Ls https://snapshots.kjnodes.com/lava-testnet/addrbook.json > $HOME/.lava/config/addrbook.json
```

**live-peers** (42)
```bash
peers="e1383b216c42acc842193c5ac7321ce6c0d73db0@78.47.37.142:26656,3173b2d34ce415ee9a1bf08646d85688bf49e299@5.189.186.222:36656,d5519e378247dfb61dfe90652d1fe3e2b3005a5b@65.109.68.190:44656,e593c7a9ca61f5616119d6beb5bd8ef5dd28d62d@34.246.190.1:26656,4732ed188fbe7603f81d9f4c825397277bb72217@5.75.235.195:26656,370ae92bd28701e0c1d8dc912ccf0d40fe0db3d5@157.90.245.166:26656,8a089094624f27698f365402a059b8b810532805@207.180.229.129:26656,821c9347c927db52138dcd4bb54478fdf17f273e@81.0.218.53:26656,45648ca8c891d2b37a66d91ce19edf31a1d651cd@95.214.55.25:26656,e268a2ce255d51a93e6ec89ee73c233bbaec70f4@49.12.185.46:26656,b7c3cedc778d93296f179373c3bc6a521e4b682e@65.109.69.160:30656,c0efea9152aed75fcf3022b8af45243818c59d6a@49.12.13.104:26656,dfa93668152cb6b3a822c987f9c22110a1c2f314@178.18.255.221:26656,474e2436e097c28472a1fe269e1825762fa340d6@38.242.128.19:26656,c83d7b205b2e80bd9a33c13161bd39d520988455@38.242.139.189:26656,d5ad7ae6caf54ef20a6dc04d30a55caac6c540c9@5.61.41.138:26656,1598a86c04a64d17fa15a07eb201f50c5d760842@75.119.136.106:26656,d53152e10f4de9e968eb98afc0f000343ebb3b02@135.181.115.115:33656,5c2a752c9b1952dbed075c56c600c3a79b58c395@185.16.39.172:27066,4634ca7cefe997035440df1095915ed255e81296@49.12.189.98:26656,3a445bfdbe2d0c8ee82461633aa3af31bc2b4dc0@3.252.219.158:26656,22c51515eea1df09dc872dc8843efb7fc73770b1@199.175.98.102:26656,4ad3f3731073a016fa0c99118b2a5a2d313928f5@207.180.233.148:26656,6a55747d1f93e46696f233ac563e28fea24afc47@38.242.237.192:36656,2c2353c872b0c5af562c518b1aa48a2649a4c927@65.108.199.62:11656,30720f6cc3c7c1c97817a168ffb7d7bfc036ebef@45.14.194.180:26656,944389dd08321247c8ad687d904591a3d73d16c6@173.249.38.130:26656,a2afdc48785be73f208af349e78d632b5556cc01@5.75.226.151:26656,9a151159039fd8abce61ddb21e5342605787792b@5.75.228.39:26656,c5c98017339ce6d4d5d2a4fd0fb1aaeb966ef0f7@65.108.124.57:36656,fdc3bd914360b1be8ee2e9f4a447223830527497@78.46.36.203:26656,e83c0fdeb2b0e258bb559d657d0907b63635127a@159.69.149.85:26656,ade02cddf71489b79a2054a7c6ba2cab8a0abb18@185.163.125.232:26656,3a0f10539eb8e0f46432564edaf6303bd67c18f3@23.88.71.247:26656,1b09acd86e1a2db56c72db7848ada3ad581f027a@95.217.109.222:36656,bec79fab73dbbe345d8b26cdeeeee4ab83fdf80e@176.9.22.117:35656,07c8a4eea1f6826509d9da5ec7eee7a1a145ab09@20.24.72.210:26656,d894084a12a25fac29f8296e20bf4c8f60da36eb@89.252.21.37:36656,5e8d65796d939fc16fa0c955dfbd16c9c519606b@222.71.35.43:26656,d53f227f0682ec552ae1932de2547fa717119253@95.216.102.235:39043,5c744987d17199b2f07efd7bad9d9466d1a457a4@80.76.235.194:7054,ade4d8bc8cbe014af6ebdf3cb7b1e9ad36f412c0@176.9.82.221:19956"
sed -i -e "s|^persistent_peers *=.*|persistent_peers = \"$peers\"|" $HOME/.lava/config/config.toml
```
