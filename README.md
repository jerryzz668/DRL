DRL学习的时policy π函数或者Q*
通过价值选行为: Q learning, Sarsa, Deep Q Network
直接选行为: Policy Gradients
想象环境并从中学习: Model based RL

### 强化学习分类: 
1. 不理解环境(Model-Free RL): Q learning, Sarsa, Policy Gradients (直接和环境交互，不能炸地球，要不你也挂了)
2. 理解环境(Model-Based RL): Q learning, Sarsa, Policy Gradients (为现实世界建模，扔个炸弹炸一下地球，你在地球上，你不会死)

### 强化学习分类:
1. 基于概率(Policy-Based RL)  Policy Gradients
2. 基于价值(Value-Based RL)  Q learning, Sarsa,

### 强化学习更新方式
1. 回合更新(Monte-Carlo update) Monte-Carlo Learning, 基础版Policy Gradients
2. 单步更新(Temporal-Difference update)  Q learning, Sarsa, 升级版Policy Gradients

### 强化学习学习方式
1. 在线学习(On-policy) Sarsa, Sarsa(\lambda)
2. 离线学习(Off-policy) Q learning, Deep Q Network