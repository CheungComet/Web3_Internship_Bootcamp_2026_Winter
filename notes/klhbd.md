---
timezone: UTC+8
---

# klhbd

**GitHub ID:** klhbd

**Telegram:** 

## Self-introduction

Web3 实习计划 2025 冬季实习生

## Notes

<!-- Content_START -->
# 2026-01-12
<!-- DAILY_CHECKIN_2026-01-12_START -->
**区块链**

**一、定义**：去中心化的分布式账本技术，用于在网络节点之间安全、透明且不可篡改地记录事务数据。数据按照时间顺序打包成“区块”并链接城“链”。

☞**区块**：区块链的基本组成单位，包含一组交易数据，通过哈希链形成一个不可篡改的链式结构。每个区块由区块头（元数据，用于标识和验证区块链中的区块）和区块体（包含该区块内所有的交易记录，记录账户间的交易信息）组成。

☞**链**：通过密码学哈希函数将多个数据区块按时间顺序连接形成的链式数据结构。

![image.png](https://raw.githubusercontent.com/IntensiveCoLearning/Web3_Internship_Bootcamp_2026_Winter/main/assets/klhbd/images/2026-01-12-1768202129257-image.png)

**二、关键特性：**

1.  不可篡改：无法修改历史信息，一旦某个区块被修改，后续所有区块的哈希值都会发生变化。
    
2.  公开透明、匿名：交易信息公开透明、用户身份匿名。
    
3.  快速交易：交易不受金额、时间等限制，只要交易记录被打包在区块链中，交易就能自动完成。
    
4.  去中心化：区块链分布在全球，每个节点都储存一份相同的区块数据→**如何实现可信：分布式网络记账模式→区块链实现真正的不可篡改**
    

_△ 本质上是一个创造信任的技术，由大家共同维护、不可篡改、历史记录可查的分布式数据库，降低了信任成本。_

**三、核心组成部分**

-   **去中心化的网络和区块链：**
    

1.  区块链核心是记录全量信息的 “链”
    
2.  链存储于去中心化网络（无数节点组成）
    
3.  节点验证交易，获取代币奖励
    

![image.png](https://raw.githubusercontent.com/IntensiveCoLearning/Web3_Internship_Bootcamp_2026_Winter/main/assets/klhbd/images/2026-01-12-1768202388661-image.png)

-   **维持网络运行的代币激励**：
    

1.  **网络运行基础**：去中心化网络依赖全球节点（矿工）提供服务以维持运行，这一过程称为“挖矿”。
    
2.  **矿工与奖励**：矿工通过维护网络安全和处理交易获得奖励，形式为网络代币（如ETH、BTC）。类似工作获取工资。
    
3.  **燃料费（Gas Fee）**：用户使用网络进行交易、转账或铸造NFT时需支付的费用，即矿工的主要收入来源。
    
4.  **获取代币**：若没有相应代币，需通过交易所用法币或其他代币兑换，才能使用该区块链服务。
    

☞比特币（BTC）→节点代币奖励；具有货币属性（有限供应、可自由转账），成为加密货币

**定义**：一种去中心化的数字货币，允许用户在无需通过中央银行或第三方支付处理器的情况下进行点对点的电子现金交易，价格由供需决定。

**特点**：有限供应、具有货币属性、账户匿名、交易公开透明、不可篡改、完全在虚拟网络中

**风险**：难以追踪和限制，常被黑产利用；打包区块时间影响交易实时性；区块储存数据有限

**底层原理**：去中心化的点对点支付网络

**记账方式**：全球公共记账本

![image.png](https://raw.githubusercontent.com/IntensiveCoLearning/Web3_Internship_Bootcamp_2026_Winter/main/assets/klhbd/images/2026-01-12-1768203552540-image.png)

**获取方式：**

挖矿：运行特定软件解决复杂数学问题，从而验证交易并获得比特币奖励

交易：比特币交易平台进行交易

接受支付：可作为支付方式

_△ 区块链像一个“全民共享的公共账本”，它的运行依赖一套“大家一起记账，干活有奖”的激励系统。_

![deepseek_mermaid_20260112_9c841f.png](https://raw.githubusercontent.com/IntensiveCoLearning/Web3_Internship_Bootcamp_2026_Winter/main/assets/klhbd/images/2026-01-12-1768202837121-deepseek_mermaid_20260112_9c841f.png)

**四、区块链运行模式**

⭐一条区块链的运行模式：用户发起交易→交易广播→节点验证→打包成块→链接上联→奖励发放

![ecosystem-BrsPk-pm.jpg](https://raw.githubusercontent.com/IntensiveCoLearning/Web3_Internship_Bootcamp_2026_Winter/main/assets/klhbd/images/2026-01-12-1768204174088-ecosystem-BrsPk-pm.jpg)

四、公链 VS 私链 VS 联盟链（根据访问权限与治理模式分类）

按去中心化程度从高到低：

![image.png](https://raw.githubusercontent.com/IntensiveCoLearning/Web3_Internship_Bootcamp_2026_Winter/main/assets/klhbd/images/2026-01-12-1768204242896-image.png)

来源：[**4\. 总结对比**](https://web3intern.xyz/zh/blockchain-basic/#_4-%E6%80%BB%E7%BB%93%E5%AF%B9%E6%AF%94)

|   | 公链（公共公园）public chain | 联盟链（多公司联合董事会）consortium chain | 私链（私人俱乐部）private blockchain |
| --- | --- | --- | --- |
| 成为节点的方法 | 无需申请，自由进出 | 需要邀请或申请权限分级（决策者、观察者） | 数据完全私有老板说了算 |
| 共同管理数据的模式 | 所有人可见去中心化决策 | 半公开数据联合决策 | 数据完全私有老板说了算 |
| 优点 | 创造了一种全新的、无需中间人的信任与协作范式 | 效率比公链高（因为成员少）隐私比公链好（数据不对外公开），但不如私链灵活（需要多方协调） | 效率极高（因为只有少数人参与）隐私极强（数据不对外公开） |
| 缺点 | 决策效率低（交易确认慢）维护成本高（比如电费、人力） | 去中心化程度有限（多中心化、存在共谋风险）治理决策复杂（治理效率、准入与退出机制复杂）安全悖论（攻击面集中、依赖成员安全）激励不足（缺乏原生代币经济模型） | 缺乏公链的透明性 |

五、web3 vs web3.0 vs web2

来源：[https://web3intern.xyz/zh/blockchain-basic/#%E5%9B%9B%E3%80%81web3-vs-web-3-0-vs-web2-%E7%9A%84%E8%8C%83%E5%BC%8F%E9%9D%A9%E5%91%BD](https://web3intern.xyz/zh/blockchain-basic/#%E5%9B%9B%E3%80%81web3-vs-web-3-0-vs-web2-%E7%9A%84%E8%8C%83%E5%BC%8F%E9%9D%A9%E5%91%BD)

DApp（ Decentralized Application，去中心化应用）是基于区块链技术构建的应用程序，其核心特点是**去中心化**和**开源**。与传统应用不同，DApp的后端代码运行在去中心化的区块链网络上，而不是集中式服务器上。
<!-- DAILY_CHECKIN_2026-01-12_END -->
<!-- Content_END -->
