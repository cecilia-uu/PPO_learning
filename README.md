# Proximal Policy Optimization
## 小游戏
* action：行为选择
* reward：每一步行动都会获得不同的结果（奖励）
* state：每一步都有一个新状态
* 停止时间（生命周期）：episode
* 整个生命周期的奖励：
* $$R = \sum_{t=1}^{T}{r_t}$$
* 最看重这个
## 网络的输入和输出
* 一次游戏记录结果
* 包括了每一步的状态和行动(trajectory): t = {s1, a1, ...st, at}
## 行为的产生
## 目标函数
- 优化的是权重参数，找到最优的
- 训练好模型，得到最多的奖励
- 每次有点随机性，所以我们需要求期望值

## resources：
* https://www.bilibili.com/video/BV1eC4y1m7TA?p=3&vd_source=fc6eb08dba1d4a93b59f72b9b0d9af17
* 