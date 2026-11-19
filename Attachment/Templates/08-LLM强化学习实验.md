---
title: "{{title}}"
type: llm-rl-experiment
status: planned
project:
date: "{{date:YYYY-MM-DD}}"
tags:
  - LLM
  - reinforcement-learning
  - experiment
created: "{{date:YYYY-MM-DD}}"
updated: "{{date:YYYY-MM-DD}}"
---

# {{title}}

> [!abstract] 实验摘要
> 这次实验想验证什么？使用什么奖励？最终是否改善了目标能力？

## 1. 研究问题

## 2. 基线与对照

- 基础模型：
- SFT 模型：
- 参考策略：
- 对照方法：

## 3. 任务与数据

- Prompt 或任务来源：
- 训练集：
- 验证集：
- 分布外测试集：
- 数据规模：

## 4. 策略优化配置

- 算法：PPO / DPO / GRPO / RLVR / 其他
- rollout 数量：
- 最大生成长度：
- 温度与采样策略：
- 学习率：
- batch size：
- KL 系数：
- 其他：

## 5. 奖励设计

| 奖励项 | 来源 | 范围或规则 | 权重 |
|---|---|---|---:|
| 结果奖励 |  |  |  |
| 过程奖励 |  |  |  |
| 格式奖励 |  |  |  |
| 安全或约束奖励 |  |  |  |
| KL 惩罚 |  |  |  |

## 6. Verifier 或奖励模型

- 验证器/奖励模型：
- 检查的属性：
- 已知漏洞：
- 误报与漏报：
- 是否使用独立评估器：

## 7. 训练监控

- 平均 reward：
- 任务正确率：
- 平均输出长度：
- KL：
- Entropy：
- 截断率：
- verifier 通过率：

## 8. 结果

| 指标 | SFT/基线 | RL 后 | 变化 |
|---|---:|---:|---:|
| 任务正确率 |  |  |  |
| OOD 正确率 |  |  |  |
| 平均长度 |  |  |  |
| 推理成本 |  |  |  |

## 9. 失败分析

### 奖励黑客

- 

### 能力退化

- 

### 典型错误样本

- 

## 10. 结论

## 11. 可复现信息

- 代码仓库与 commit：
- 配置文件：
- 模型 checkpoint：
- 数据版本：
- 随机种子：

## 12. 下一步

- [ ] 

