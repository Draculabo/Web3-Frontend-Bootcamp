# Task2 Blockchain Basic

本任务分为简答题、分析题和选择题，以此为模板，在下方填写你的答案即可。

选择题，请在你选中的项目中，将 `[ ]` 改为 `[x]` 即可

## [单选题] 如果你莫名奇妙收到了一个 NFT，那么

- [ ] 天上掉米，我应该马上点开他的链接
- [x] 这可能是在对我进行诈骗！

## [单选题] 群里大哥给我发的网站，说能赚大米，我应该

- [ ] 赶紧冲啊，待会米被人抢了
- [x] 谨慎判断，不在不信任的网站链接钱包

## [单选题] 下列说法正确的是

- [x] 一个私钥对应一个地址
- [ ] 一个私钥对应多个地址
- [ ] 多个私钥对应一个地址
- [ ] 多个私钥对应多个地址

## [单选题] 下列哪个是以太坊虚拟机的简称

- [ ] CLR
- [x] EVM
- [ ] JVM

## [单选题] 以下哪个是以太坊上正确的地址格式？

- [ ] 1A4BHoT2sXFuHsyL6bnTcD1m6AP9C5uyT1
- [ ] TEEuMMSc6zPJD36gfjBAR2GmqT6Tu1Rcut
- [ ] 0x997fd71a4cf5d214009619808176b947aec122890a7fcee02e78e329596c94ba
- [x] 0xf39Fd6e51aad88F6F4ce6aB8827279cffFb92266

## [多选题] 有一天某个大哥说要按市场价的 80% 出油给你，有可能

- [x] 他在洗米
- [ ] 他良心发现
- [x] 要给我黒米
- [x] 给我下套呢

## [多选题] 以下哪些是以太坊的二层扩容方案？

- [] Lightning Network（闪电网络）
- [x] Optimsitic Rollup
- [x] Zk Rollup

## [简答题] 简述区块链的网络结构

```
区块链网络没有中央控制节点，所有节点都是平等的，确保数据分布式存储和处理。
点对点网络 (P2P)：

区块链通过点对点网络进行信息传递，每个节点都可以与其他节点直接通信，数据共享透明。
分布式账本：

所有节点共同维护一个账本副本，任何变动都需要全网共识，确保数据的不可篡改性和一致性。
```

## [简答题] 智能合约是什么，有何作用？

```
智能合约是一种基于区块链技术的自动化合约系统，它是一种以代码形式编写、部署和执行的可编程合约。智能合约可以在没有第三方干预的情况下执行、管理和强制合约条款，从而实现安全、透明和可靠的交易和协议。
```

## [简答题] 怎么理解大家常说的 `EVM` 这个词汇？

```
EVM 是 "Ethereum Virtual Machine"（以太坊虚拟机）的缩写。它是以太坊网络的核心组件之一，负责执行智能合约。
```

## [分析题] 你对去中心化的理解

```
去中心化（Decentralization）是指将权力、控制和决策分散到多个节点、个体或实体，而不是集中在单一的中央机构或权威之中。去中心化的理念广泛应用于多个领域，如区块链技术、网络架构、组织治理等。
```

## [分析题] 比较区块链与传统数据库，你的看法？

```
区块链：通过去中心化的分布式账本，确保数据的安全性和透明性。每个节点都有完整的数据副本，不依赖于单一的中心化管理机构，因此更难受到攻击或篡改。
传统数据库：通常是集中式的，数据存储在单一的服务器或数据中心中，依赖于中心化的管理和控制。安全性依赖于访问控制和服务器的防护措施。
数据完整性和可追溯性：

区块链：由于每个区块包含前一区块的哈希值，形成了链式连接，一旦记录在区块链上，几乎不可能篡改。这使得数据具有极高的完整性和可追溯性。
传统数据库：虽然也可以通过备份和日志记录来确保数据的完整性，但相比之下，传统数据库的可追溯性和防篡改性不如区块链。


## 操作题

安装一个 WEB3 钱包，创建账户后与 [openbuild.xyz](https://openbuild.xyz/profile) 进行绑定，截图后文件命名为 `./bind-wallet.jpg`.