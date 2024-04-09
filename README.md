For all general reference, please check the notion document: https://metalanguage.notion.site/BABEL-AGI-d9d6572ac4c543679ec87c93a7a20c1f

# Basic information
 Project name：BABEL
 
 Starting time： 2024-01
 
# Project Description：
 -Build a single Strongest AGI form a peer-to-peer  network. 
 -All for One and One for All!

 ## Problem and Opportunity

### Problm

- AI is monopolized
    - High barrier on Computation
    - High barrier on IQ （algorithm）
    - High barrier on Data
        - Storage
        - Clean-up
        - Ownership
- At present, there is no systematic performance evaluation system for  large-scale AGI models.
- Open-source never had a natural revenue.
- Most people cannot share the revenue from AGI

### Opportunity：

- The AGI era has come, Web3 can unite people.
    - anti-monopolize ClosedAI
    - fairly incentivize whoever contributes to AGI

 ## Our Solution

- Layer 1 public chain for public good
- Meaningful proof of work + Proof of stake for TPS
    - **Consensus Protocol** :
        - **Proof of Work of Compression (PoWoC)** : Incentivize computing power
    - **Decentralized  Storage** :
 
 ## Tokenomics of PoWoC  
<img width="931" alt="截屏2023-07-04 05 21 54" src="https://github.com/GitVerse-HQ/hackathon-2023-summer-1/assets/113095306/02fbf877-a7ac-4746-a8e9-c78c76d80e54">

## Tech Architecture
<img width="912" alt="截屏2023-07-04 05 39 06" src="https://github.com/GitVerse-HQ/hackathon-2023-summer-1/assets/113095306/6ddd1425-7b68-42c8-925e-a431f77e9fe6">

## Work Completed During the Hackathon


**OFF CHAIN**

- `AI`
  - [ ] PoWoC节点预训练AGI模型
  - [ ] 验证节点检验预训练好的模型
**DeStorage**
- `AI Models`
  - [ ] 提交训练好的模型
  - [ ] 提交训练模型的数据
  - [ ] 提交检验模型的数据
  - [ ] 为最优AGI模型的共识提供证明

**ON CHAIN**
- `Substrate Native`
  - [ ] 验证节点通过PoS共识预训练好的模型
  - [ ] Tokennomics：实现了PoWoC+PoS共识机制与双代币奖励
  - [ ] Foundation Model的属性（包括但不限于压缩率c）的记录与共识
  - [ ] PoS出块
        
**Demo Videos**

## 队员信息
| 姓名/昵称 | 角色 | Github账号 | 微信账号 |
| --- | --- | --- | --- |
| Zaki |  队长 | Gitverse-Web3 | Gitverse |
| Strange | 架构师 | Prof-Strange |  |
| Artist  | PM | Artistzxt | zjuzxt |
| 枫叶闲庭 | AI工程师 | lizhanyang505 | soulandyvip |
| 蒹葭苍苍 | AI工程师 | MonicaArnaud | ouahiba0804 |
| lix | 区块链工程师 | ciconia11 | cryptolix |
| cxgd | 区块链工程师 | haisenCx | cxgd123456 |


# Install

编译:
```cargo build --release```

启动:
```./target/release/substrate --dev```

单元测试:
```cargo test```


# 演示视频
## substrate part
https://youtu.be/uKGzB8fPKI8   or  https://v.douyin.com/ijSYTV5/
## AGI model part
https://youtu.be/DXvTyVpHwrg
