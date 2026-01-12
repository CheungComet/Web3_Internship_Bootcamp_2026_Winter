---
timezone: UTC+8
---

# yeqiu

**GitHub ID:** yeqiu260

**Telegram:** 

## Self-introduction

Web3 实习计划 2025 冬季实习生

## Notes

<!-- Content_START -->
# 2026-01-12
<!-- DAILY_CHECKIN_2026-01-12_START -->
# Web3 初学者：从零到一的链上实操笔记

## 阶段零：知识储备与理论学习(长期任务）

**0\. 理论先行与文档研读**

-   **核心课程**：阅读 Web3 实习手册「入门导读」部分，重点完成 **《021 学习以太坊》第 1 & 2 章** 的研读。
    
-   **拓展 & 辅助理解材料**：
    
    -   Day 1: A Developer's Guide to Building on Ethereum - Intro（以太坊开发入门指南）
        
    -   Day 2: Becoming a Power User - Wallets, Mnemonics, Keypairs（成为高级用户：理解钱包、助记词与密钥对）
        
-   **协议进阶**：阅读 **Uniswap V2 官方文档**，建立对去中心化交易（AMM）的初步认知。
    

## 阶段一：身份创建与环境配置

### 1\. 🦊 安装 MetaMask 钱包

-   **操作**：在浏览器扩展商店下载 MetaMask。
    
-   **核心点**：生成并手动抄写 **助记词（Seed Phrase）**。
    
-   **安全警示**：助记词是找回钱包的唯一途径，绝不向任何人泄露，绝不保存在联网设备中。
    

![image.png](https://raw.githubusercontent.com/IntensiveCoLearning/Web3_Internship_Bootcamp_2026_Winter/main/assets/yeqiu260/images/2026-01-12-1768204422774-image.png)

* * *

## 📅 阶段二：获取资源（测试网）

### 2\. 🚰 领取测试币 (Faucet)

-   **网络切换**：将网络从“以太坊主网”切换至 **Sepolia 测试网**。
    
-   **领取过程**：访问 Sepolia 水龙头网站，粘贴地址并领取测试用的 ETH。
    
-   **目的**：测试币没有实际价值，专门用于在实验中支付 **Gas Fee（手续费）**。
    
-   水龙头领取网站：
    
    -   [Faucet Trade](https://faucet.trade/sepolia-eth-faucet)
        
    -   [Google Cloud](https://cloud.google.com/application/web3/faucet/ethereum/sepolia)
        
    -   [PK910挖矿式](https://sepolia-faucet.pk910.de/)
        
    -   [Infura](https://www.infura.io/faucet/sepolia)
        
    -   [Polygon](https://faucet.polygon.technology/)
        
    -   [Binance Smart Chain](https://www.bnbchain.org/en/testnet-faucet)
        
    -   [Chainlink](https://faucets.chain.link/)
        
    -   [Alchemy](https://www.alchemy.com/faucets/ethereum-sepolia)
        
    -   [QuickNode](https://faucet.quicknode.com/ethereum/sepolia)
        

* * *

## 阶段三：链上交互实操

### 3\. 转账与 Gas 原理理解

-   **发起交易**：向另一个地址发送一笔测试币。
    
-   **关键参数**：
    
    -   **Gas Price**：你愿意为每单位“燃料”支付的单价（单位：Gwei）。
        
    -   **Nonce**：你的地址发出的交易序号。
        
-   **实验发现**：当交易卡住时，可以通过提高 Gas Price 发送相同 **Nonce** 的交易来“加速”它。
    

* * *

## 阶段四：数据审计与区块探索

### 4\. 使用区块链浏览器 (Etherscan)

-   **查询方式**：将钱包地址粘贴到 [Sepolia Etherscan](https://sepolia.etherscan.io/)。
    
-   **数据解读**：
    
    -   **Transaction Hash (TxID)**：每笔交易唯一的身份证号。
        
    -   **Block Number**：交易被打包进的区块高度。
        
    -   **链的特性**：观察发现 Nonce 14 和 Nonce 15 之间区块号差距很大，说明全球每秒都有大量交易在进行。
        

> ![6ce02faa01d4eccbcce9a732149513ad.png](https://raw.githubusercontent.com/IntensiveCoLearning/Web3_Internship_Bootcamp_2026_Winter/main/assets/yeqiu260/images/2026-01-12-1768204518011-6ce02faa01d4eccbcce9a732149513ad.png)

![95e05e1d1469ca77df8c6a2bb6e2e4f8.png](https://raw.githubusercontent.com/IntensiveCoLearning/Web3_Internship_Bootcamp_2026_Winter/main/assets/yeqiu260/images/2026-01-12-1768204532437-95e05e1d1469ca77df8c6a2bb6e2e4f8.png)![f2c82a8acf379e4d3075e8ca642a4087.png](https://raw.githubusercontent.com/IntensiveCoLearning/Web3_Internship_Bootcamp_2026_Winter/main/assets/yeqiu260/images/2026-01-12-1768204542243-f2c82a8acf379e4d3075e8ca642a4087.png)
<!-- DAILY_CHECKIN_2026-01-12_END -->
<!-- Content_END -->
