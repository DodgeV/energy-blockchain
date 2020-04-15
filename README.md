# energy-blockchain
+ ![去中心化](https://github.com/DodgeV/energy-blockchain/blob/master/timg.png)
+ [VAKT](https://www.thoughtworks.com/cn/clients/vakt)
+ [Blockchain Demo](https://andersbrownworth.com/blockchain)

## distributed system
- [系统设计入门](https://github.com/donnemartin/system-design-primer/blob/master/README-zh-Hans.md)
- [2020 MIT 6.824 distributed system](https://www.bilibili.com/video/BV1R7411t71W)
- [初识分布式系统](https://zhuanlan.zhihu.com/p/35573082)
- [分布式中心化与去中心化](https://baijiahao.baidu.com/s?id=1600500806691832299&wfr=spider&for=pc)
- [关于一致性](http://www.hollischuang.com/archives/663)
- [分布式系统的一致性与共识性](https://zhuanlan.zhihu.com/p/35596768)
- [两段提交协议与三段提交协议](https://zhuanlan.zhihu.com/p/35616810)
- [分布式系统中的FLP不可能原理、CAP理论与BASE理论](https://zhuanlan.zhihu.com/p/35608244)


## Cryptography
- [区块链中的密码学与安全技术](https://zhuanlan.zhihu.com/p/35649160)
- [去中心化：可信与验证 | 非对称加密](https://zhuanlan.zhihu.com/p/39543108)


## various consensus mechanism(algorithm)
+ [从分布式一致性到共识机制（一）Paxos算法](https://www.cnblogs.com/binyue/p/8645565.html)
+ [DPOS](https://github.com/liuchengxu/blockchain-tutorial/blob/master/content/misc/dpos-consensus-algorithm-this-missing-white-paper.md)
+ [RAFT](https://www.cnblogs.com/xybaby/p/10124083.html)


## dissertations for blockchain
+ [Merkle tree](https://github.com/wujinsen/LearnBlockChain/wiki/Merkle-Tree%E4%B8%8E%E5%8C%BA%E5%9D%97%E9%93%BE)
+ [精通BTC](http://v1.8btc.com/books/834/masterbitcoin2cn/_book/)
+ [区块链教程](https://github.com/liuchengxu/blockchain-tutorial/blob/master/content/SUMMARY.md)
+ [区块链教程gitbook](https://liuchengxu.gitbooks.io/blockchain-tutorial/content/)
+ [区块链教程wiki纯英文](https://github.com/liuchengxu/blockchain-tutorial/wiki)
+ [不可能三角：区块链最大的谎言](https://baijiahao.baidu.com/s?id=1615661769014560837&wfr=spider&for=pc)
+ [图灵奖得主破解不可能三角--Algorand](https://www.jianshu.com/p/1c17ab53380a)
+ [Algorand是啥](https://blog.csdn.net/sanganqi_wusuierzi/article/details/78846430)

## dissertation for energy
+ [中国石油垄断现状及破解垄断之法](https://www.ixueshu.com/document/7cb1870cbb87480a318947a18e7f9386.html)


## Ethereum and smart contracts
+ Ethereum whitepaper: https://github.com/ethereum/wiki/wiki/White-Paper
+ Ethereum course (highly recommended - paid): https://www.udemy.com/ethereum-and-solidity-the-complete-developers-guide/
+ A good resource to learn dApp development by coding your own game: https://cryptozombies.io/
+ A good grasp on concepts of Decentralised Applications: https://www.theschool.ai/courses/decentralized-application/
+ Excellent course on Coursera: https://www.coursera.org/learn/blockchain-foundations-and-use-cases
+ Best Handon course by DApp University (highly recommended) complete playlist: [Youtube](https://www.youtube.com/playlist?list=PLS5SEs8ZftgWFuKg2wbm_0GLV0Tiy1R-n)
+ Course on Coursera : https://www.coursera.org/learn/blockchain-basics


## For setting up truffle for ethereum-test Blockchain developement
**Requisites**
+ **npm** 
  - before npm install node.js
  ```
  wget -qO- https://deb.nodesource.com/setup_8.x | sudo -E bash -
  sudo apt-get install -y nodejs
  ```

  - now install npm 
  ```
  brew install node
  ```
    
+ **truffle ganache** framework
  - download .appimage file from [ganache](https://truffleframework.com/ganache) 
  ```
  cd ~/Downloads
  chmod a+x <.appimage filename>
  ./<.appimage filename>
  ```
+ Metamask Chrome Extension - to live track transactions on the Ethereum test network
  [Metamask Website](https://metamask.io/)
+ Sublime text package highlighting for solidity language


## codes for energy blockchain 
+ [用Python实现简单的区块链系统](https://www.jianshu.com/p/03844ab5af12)
- [手把手：用Python实现一个基于RSA算法的区块链客户端](https://www.jianshu.com/p/2ba6a9a184b6)
- [20分钟，我用简单的Python代码创建了一个完整的区块链](https://blog.csdn.net/blockchain_lemon/article/details/80891527)
+ [How to Build Your Own Blockchain Part 1 — Creating, Storing, Syncing, Displaying, Mining, and Proving Work](https://bigishdata.com/2017/10/17/write-your-own-blockchain-part-1-creating-storing-syncing-displaying-mining-and-proving-work/)
+ [用fabric 1.0模拟多用户在能源互联网环节中使用能源区块链进行能源交易(完整的项目)](https://github.com/zdpleon/energy_blockchain)


## Multichain
+ Getting started for developers: https://www.multichain.com/developers/


## Hyperledger Composer
+ For getting started: https://hyperledger.github.io/composer/latest/tutorials/tutorials.html
+ Get your hands dirty | Explore online playground: https://composer-playground.mybluemix.net/
- [Fabric 区块链技术开发专栏](https://zhuanlan.zhihu.com/c_154064303)

## Hyperledger fabric
+ For getting started: https://hyperledger-fabric.readthedocs.io
+ Fabric samples - Chaincode, SDKs and Network setup:  https://github.com/hyperledger/fabric-samples
+ Hyperledger tutorials and articles: [Medium](https://medium.com/coinmonks/top-hyperledger-tutorials-and-articles-b77cf3e4d1eb)
+ Linux foundation free course on Hyperledger Technologies (includes Fabric): https://training.linuxfoundation.org/training/blockchain-for-business-an-introduction-to-hyperledger-technologies/
+ Paid but worth it Udemy course: https://www.udemy.com/hyperledger/
+ IBM hyperledger fabric study material : https://www.ibm.com/blockchain/hyperledger
+ really valuable course by linux foundation: https://www.edx.org/course/blockchain-for-business-an-introduction-to-hyperledger-technologies


## some tutorials about Blockchain
+ [北京大学肖臻区块链](https://www.bilibili.com/video/av37065233) [对应笔记](https://xuthus.cc/misc/blockchain-exploration.html)
+ [李永乐BTC](https://www.bilibili.com/video/BV1Bb411B7dq)
+ Blockchain 101 - A Visual Demo: [YouTube](https://www.youtube.com/watch?v=_160oMzblY8)
+ Blockchain basics: [Lynda](https://www.lynda.com/Data-Science-tutorials/Blockchain-Basics/574704-2.html)
+ Simply Explained Playlist by SAVJEE (highly recommended): [YouTube](https://www.youtube.com/playlist?list=PLzvRQMJ9HDiSbvXWQ7OdgVccdr7Wni5Qw)
+ Simple Handon using JAVASCRIPT - SAVJEE (highly recommended): [YouTube](https://www.youtube.com/playlist?list=PLzvRQMJ9HDiSbvXWQ7OdgVccdr7Wni5Qw)
+ Siraj Raval youtube cryptocurrencies series: [YouTube](https://www.youtube.com/playlist?list=PL2-dafEMk2A7jW7CYUJsBu58JH27bqaNL)
+ Basic Blockchain Essentials course by IBM: https://cognitiveclass.ai/courses/blockchain-course/
+ Blockchain on IBM: https://www.ibm.com/blockchain/getting-started 
+ Step by step guide for beginners: https://blockgeeks.com/guides/what-is-blockchain-technology/
+ Step by step Guide in Building a blockchain application with Hyperledger&GO: https://chainhero.io/2018/06/tutorial-build-blockchain-app-v1-1-0/ 

A tip before watching all the resources : Bitcoin!=Blockchain, that means blockchain is not only bitcoin.
+ What is Blockchain Technology: https://www.coindesk.com/information/what-is-blockchain-technology/

Some of the above websites may need these tools to access：
* [zlnlsw205/www](https://github.com/zlnlsw205/www) 
* [jdzs1/fq](https://github.com/jdzs1/fq)
