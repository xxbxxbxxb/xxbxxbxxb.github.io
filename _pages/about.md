---
permalink: /
title: "个人基本信息"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


## 教育背景

### 东北大学

**计算机科学与技术** | 2022.09 - 至今

- 专业排名：25/191（TOP 13.07%）
- GPA：4.11/5.00

#### 核心课程成绩

| 课程 | 成绩 |
|------|------|
| C++程序设计 | 98 |
| Java程序设计 | 97 |
| 数据库原理 | 97 |
| 高等数学 | 97 |
| 概率论与数理统计 | 97 |
| 电路原理 | 97 |
| 软件工程 | 96 |
| 计算机网络 | 95 |
| 人工智能导论 | 95 |

## 荣誉殿堂

### AI竞赛

- **全球校园人工智能算法精英大赛（算法挑战赛）** (2024.11)
  - 作品《公共巴士辅助无线充电的电动汽车调度》，国家级一等奖（赛道第一名）
  ![公共巴士辅助无线充电的电动汽车调度](images/挑战国.jpg "挑战国")
  - 技术路线
    - 基础架构：`马尔可夫`决策过程(MDP)建模
    系统将电动汽车调度问题建模为马尔可夫决策过程，其中：

    1. 智能体(Agent)：每辆需要完成调度的电动汽车
    2. 状态(State)：车辆在时间t的位置、剩余电量、已消耗时间、当前路径段信息
    3. 动作(Action)：下一个目标节点、当前路径段速度选择、充电决策
    4. 奖励函数(Reward)：结合电池使用效率和时间效率的加权和

    - 核心算法：DQN与SARSA融合
    系统创新地结合了两种强化学习算法：

    1. `DQN(深度Q网络)`：擅长生成全局最优路径,负责生成初步路径并进行局部优化

       - 使用经验回放缓冲区存储历史经验
       - 使用目标网络提高训练稳定性
       - 每10步更新一次目标网络

    2. `SARSA算法`：确保在环境变化时做出稳定决策,负责策略学习,确保在动态环境中做出稳定决策

       - 基于当前策略选择行动，而非总是选择最大Q值
  - 国赛榜单
  ![榜单](images/bus.png "榜单")

- **全球校园人工智能算法精英大赛（算法挑战赛）** (2024.11)
  - 作品《公共巴士辅助无线充电的电动汽车调度》，省级一等奖
  ![公共巴士辅助无线充电的电动汽车调度](images/挑战省.jpg "挑战省")

- **中国大学生计算机设计大赛** (2024.06)
  - 作品《本草悟道》，省级二等奖
  ![计设](images/激射.jpg "计设")
  - 技术路线
  "本草悟道"项目采用了多阶段优化的技术路线，将现代AI与传统中医智慧结合：

  1. 基座模型选择：选用`Qwen1.5-14B`作为基础，通过`Ollama`框架在本地部署，平衡了性能与资源消耗
  2. 知识增强：

     - 预训练阶段：使用分割后的中医古籍语料进行领域知识预训练
     - 向量库外挂：将中医书籍转化为向量存储，实现高效知识检索
     - 对比普通微调，这种"预训练+知识库外挂"方案大幅提升了专业知识深度
  3. 微调与行为调整：

     - `LoRA低秩`微调：减少可训练参数量，优化计算资源使用
     - `CO-STAR`框架指令优化：构建结构化提示词，规范模型回复格式
     - 多轮问诊训练：基于真实医患对话数据培养连续交互能力

  4. 多模态功能扩展：

     - 语音交互：集成语音识别与合成，解决打字不便问题
     - 文生图功能：通过`Playground-v2.5`模型生成中药材和经脉图片
     - 本草悟道模型构建流程图
  
  - 本草悟道部署流程图
  
    ![流程图](images/wudao流程.svg "流程图")

  - 本草悟道与基座模型回答对比图
  
    ![pre](images/wudaopre.png "pre")

    ![now](images/wudaonow.png "now")

  - 本草悟道文生图功能
    ![文生图](images/stablediffusion.png "文生图")

### 数学类竞赛

- **国际大学生数学建模竞赛** (2024.04)
  - 作品《Submerged Symphony: Optimizing Rescues for Submersible with Predictive Models》，H奖（国家级二等奖）
  ![美赛](images/数学建模H奖.jpg "美赛h")

- **亚太地区大学生数学建模竞赛** (2024.04)
  - 国三等奖
  ![亚太数模](images/apmcm.jpg "apmcm")

- **全国大学生数学竞赛** (2024.04)
  - 省一等奖
  ![数竞](images/math.jpg "math")

- **MathorCup数学应用挑战赛** (2024.04)
  - 赛区三等奖
  ![mmb赛](images/mmb.jpg "mmb")

### 荣誉称号

- **校级三好学生** (2023.11)
  - 2022-2023学年
![三好](images/3h.jpg "三好")

### 奖学金

- **校综合二等奖学金** (2024.12)
  - 2023-2024学年第二学期
![241](images/241.jpg "241")

- **校综合二等奖学金** (2024.12)
  - 2023-2024学年第二学期
![232](images/232.jpg "232")

- **校综合二等奖学金** (2024.04)
  - 2023-2024学年第一学期
![231](images/231.jpg "231")

- **校综合二等奖学金** (2023.10)
  - 2022-2023学年第二学期
![222](images/222.jpg "222")

- **校综合二等奖学金** (2023.05)
  - 2022-2023学年第一学期
![221](images/221.jpg "221")

### 语言能力

- **全国大学英语六级考试** (2023.06)
  - 450分
![cet6](images/cet6.png "cet6")
- **全国大学英语四级考试** (2023.03)
  - 528分
![cet4](images/cet4.png "cet4")