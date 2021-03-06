# blockchain-wiki
> 收集所有区块链(BlockChain)的相关资料，包含并不限于区块链的专业词语、理论、技术、实践（挖矿、ico发币、ico购买）。

- 请在为本项目贡献信息前仔细阅读 [操作指南](https://github.com/sindresorhus/awesome/blob/master/contributing.md) 

## Contents

- [介绍](#介绍)
- [专业词汇](#专业词汇)
- [教程](#教程)
- [项目](#项目)
- [应用](#应用)
- [资源](#资源)

## 介绍
### 入门

## 专业词汇
### [比特币(bitcoin)](https://bitcoin.org)
#### [区块链(blockchain)](https://www.blockchain.com/)
##### 分布式账本Distributed ledger
#### 双重支付问题double-spending problem
#### 哈希
通过某种算法计算得出的值，该算法可唯一标识输入数据而不会泄露该数据的内容。哈希值用于确保区块链上数据的准确性。区块头部包含前一个区块的哈希，可以快速验证整个链的完整性。
#### 共识算法
在分布式账本中的节点中使用，并由区块链定义以确定区块链正确性的方法。最普遍的共识算法是“Pow（工作证明）”，“（Pos）股权证明”和“（DPoS）委托股权证明”。石墨烯采用委托股权证明。
##### PoW(工作证明)
一种共识算法，依靠计算难度的挑战来解决问题，以便找到新块的哈希。虽然计算得到新区块的难度很大，但其他节点验证新区块的难度很小，从而允许其他参与节点快速认同新区块的正确性。
##### PoS（股权证明）
一种基于节点的共识算法，节点持有可以参与区块链的股权。通过证明股权，区块可以更快地被添加到链中。
#### [闪电网络](https://lightning.network/lightning-network-paper.pdf)

### 侧链:允许资产在比特币区块链和其它链之间互转。降低核心的区块链上发生交易的次数。
#### [Blockstream](https://blockstream.com/)
##### [liquid](https://blockstream.com/liquid/)

### [以太坊(ethereum)](https://ethereum.org)
#### [An Incomplete Terminology Guide](https://blog.ethereum.org/2014/05/06/daos-dacs-das-and-more-an-incomplete-terminology-guide/)
#### EVM: 以太坊虚拟机，轻量级虚拟机环境，是以太坊中智能合约的运行环境
#### Gas: 燃料，每执行一条合约指令会消耗一定的燃料，当某个交易还未执行结束，而燃料消耗完时，合约执行终止并回滚状态。
#### ERC20
##### [English](https://en.wikipedia.org/wiki/ERC20)
##### [中文](http://blog.csdn.net/diandianxiyu_geek/article/details/78082551)
#### [智能合约(smart contract)](https://en.wikipedia.org/wiki/Smart_contract)
#### [DApp(decentralized application)](https://github.com/DavidJohnstonCEO/DecentralizedApplications)
#### [DApps](http://ethdocs.org/en/latest/contracts-and-transactions/developer-tools.html)
#### [DAC(decentralized autonomous corporations)](https://bitcoinmagazine.com/articles/bootstrapping-a-decentralized-autonomous-corporation-part-i-1379644274/)

### [EOS](https://eos.io)
#### DPOS(委托股权证明)
这是一种变化的股权证明算法，将创建块的责任委托给称为“证人”的第三方节点。
#### 见证者节点
DPoS区块链中的一个节点，负责执行创建新区块的任务。
#### [Web Assembly(wasm)](http://webassembly.org/)

### QTUM

## 应用
### 以太坊
### EOS
#### Steemit
#### Bitshares
### 电子钱包
#### pc 端
##### [Bitcoin Core](https://bitcoin.org/en/bitcoin-core/)
##### [Electrum](https://electrum.org)
##### [Rippex](https://rippex.net)
##### [Exodus](https://www.exodus.io/)
#### 移动端
##### [Jaxx](https://jaxx.io)
##### [bread wallet](https://breadapp.com/)
#### 硬件——把用户的私钥存储在类似于usb设备中
##### [trezor](https://trezor.io/)
##### [ledger nano](https://www.ledgerwallet.com)


## 资源
### 新闻
#### [Coindesk——提供有关区块链和加密货币的及时新闻资源](https://coindesk.com)
#### [bitcoinmagazin——](https://bitcoinmagazine.com/)
#### [巴比特——国内的资讯社区门户，为区块链创业者、投资者提供信息、交流与投融资服务。](http://www.8btc.com/)
#### [火星财经——国内的区块链门户网站](http://www.huoxing24.com/）
### 交易所
#### 美国
##### [coinbase](https://coinbase.com)
##### [bitfinex](https://www.bitfinex.com/)
##### [bitstamp](https://www.bitstamp.net)
#### 英国
##### [cex](https://cex.io/)
#### 日本
##### [BitFlyer](https://bitflyer.com)
##### [Quoine](http://quoine.com/)
##### [coincheck](http://coincheck.com/)
#### 国内
##### [币安](https://binance.com)
##### [火币](https://huobi.com)
##### [okex](https://www.okex.com)

### 加密货币价格的实时报价
#### [对货币的价格进行实时跟踪](https://coinmarketshares.com)
#### [查看加密货币的实时价格和总市值](https://prices.org/)
### [检查DApp的状态](https://www.stateofthedapps.com/)

### 社区
#### forums论坛
##### [reddit](https://www.reddit.com/r/BitcoinBeginners/)
##### [stackexchange](https://bitcoin.stackexchange.com/)
##### [bitcointalk](https://bitcointalk.org/index.php?board=4.0)
#### live chat
##### [bitcoin core](https://webchat.freenode.net/?channels=bitcoin&uio=d4)
##### [bitcoin mining](https://webchat.freenode.net/?channels=bitcoin-mining&uio=d4)
##### [bitcoin pricetalk](https://webchat.freenode.net/?channels=#bitcoin-pricetalk&uio=d4)
##### [more](https://en.bitcoin.it/wiki/IRC_channels)

#### 播客节目
##### [The Bad Crypto Podcast](http://badcryptopodcast.com/)



