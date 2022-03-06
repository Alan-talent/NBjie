# BSC全能分红代币合约

支持分红SHIB/ETH/USDT/DOGE等BSC所有代币。

- 2022-02-19 更新: 修改部分关键词。绕过查币软件检测。

## 源码
https://github.com/misu2022/contracts/blob/master/RedKing.sol

## 实战视频讲解
https://youtu.be/oLt2wd_H9sY


## 编译/开源参数

```
COMPILER: v0.8.7+commit.e28d00a7.js
Enable optimization: 开启并使用默认值200
Other Settings: default evmVersion, MIT license
```

## 部署参数

CONTRACT 选择 `RedKing`，Value `200000000000000000` （0.2BNB）

```
name_: RedKing Token (代币名称)
symbol_: RedKing (代币符号)
totalSupply_: 1000000000000000 (发行量)
rewardAddr_: 要分红的代币合约，BSC常用代币地址在下方
marketingWalletAddr_: 自己的市场营销钱包
serviceAddr_: 0xFe4192C1f01b26b33D89feAA9551bcF6B3637CB4
buyFeeSetting_: [4,3,2,1] (分红、流动性、市场营销、燃烧)
sellFeeSetting_: [5,4,3,2] (分红、流动性、市场营销、燃烧)
tokenBalanceForReward_: 1000000000000000000000000000 (持有多少代币参与分红。数量后要加18个0)
```

## BSC常用代币合约地址

```
SHIB: 0x2859e4544C4bB03966803b044A93563Bd2D0DD4D
USDT: 0x55d398326f99059fF775485246999027B3197955
ETH: 0x2170Ed0880ac9A755fd29B2688956BD959F933F8
DOGE: 0xbA2aE424d960c26247Dd6c32edC70B295c744C43
BUSD: 0xe9e7CEA3DedcA5984780Bafc599bD69ADd087D56
CAKE: 0x0E09FaBB73Bd3Ade0a17ECC321fD13a19e81cE82
```

## Remix国内加速版

https://remix.jishutuan.com

