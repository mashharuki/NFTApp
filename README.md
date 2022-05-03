# NFTApp
イーロンマスクのNFTを発行するためのリポジトリです。

### Rinkebyにデプロイする場合


### hardhatを使ってEtherScanからコードを見れるようにしたいとき
  ` npx hardhat verify --network rinkeby {デプロイしたコントラクトのアドレス}` 

  うまくいけば下記のように表示される。
  ``` 
   Nothing to compile
    Successfully submitted source code for contract
    contracts/ElonNFT.sol:ElonNFT at 0x398004F2698648159b8E82A13fd87ea0B1f8f84e
    for verification on the block explorer. Waiting for verification result...

    Successfully verified contract ElonNFT on Etherscan.
    https://rinkeby.etherscan.io/address/0x398004F2698648159b8E82A13fd87ea0B1f8f84e#code
  ```