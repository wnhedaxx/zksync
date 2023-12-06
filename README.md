# zkSync: scaling and privacy engine for Ethereum

[![Logo](zkSyncLogo.svg)](https://zksync.io/)

[![Live on Mainnet](https://img.shields.io/badge/wallet-Live%20on%20Mainnet-blue)](https://wallet.zksync.io)
[![Live on Rinkeby](https://img.shields.io/badge/wallet-Live%20on%20Rinkeby-blue)](https://rinkeby.zksync.io)
[![Live on Ropsten](https://img.shields.io/badge/wallet-Live%20on%20Ropsten-blue)](https://ropsten.zksync.io)

zkSync is a scaling and privacy engine for Ethereum. Its current functionality scope includes low gas transfers of ETH
and ERC20 tokens in the Ethereum network.


# degods.zksync

Hello everyone, twitter id oxdoxo
![image](https://avatars.githubusercontent.com/u/70830772?s=400&u=2ed023fa0865132977919170696b9503aa8a2107&v=100)


```

## 程序说明【我用的开发链，以下命令针对开发链】
### 1.部署程序
 developer deploy degods.aleo --private-key xxxx --query "http://localhost:3030" --path "build/" --broadcast "http://localhost:3030/testnet3/transaction/broadcast" --fee 91169000 --record  xxxxx
### 2.开启一期双色球

### 3.投注
developer execute double_color_ball.aleo ticket_purchase "{user:wnhedaxx,round_number:2u32,count:1u32,gates:100000000u64,red_ball_1:1u32,red_ball_2:2u32,red_ball_3:15u32,red_ball_4:16u32,red_ball_5:13u32,red_ball_6:30u32,blue_ball_1:8u32}" --query "http://localhost:3030" --broadcast "http://localhost:3030/testnet3/transaction/broadcast" --private-key xxxxxx --fee 91169000 --record  xxxx
### 4.停止投注

. developer execute degods.aleo draw_price 2u32 --query "http://localhost:3030" --broadcast "http://localhost:3030/testnet3/transaction/broadcast" --private-key xxxxxx --fee 1091169000 --record xxxx
