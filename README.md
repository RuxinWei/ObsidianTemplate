# Obsidian Template：研究与知识管理工作流

这是一个面向学习、论文阅读、LLM/强化学习研究和项目记录的轻量 Obsidian Vault。

## 设计思路

这套模板借鉴了三种成熟做法：

1. **文献笔记**：先记录来源、主张、证据和局限，不把摘抄直接当成自己的结论。
2. **原子概念笔记**：一篇笔记尽量只回答一个问题，便于链接和复用。
3. **MOC（Map of Content）主题索引**：用人工维护的主题页组织相关笔记，而不是依赖复杂查询。

整个工作流可以理解为：

**原始资料 → 文献笔记 → 概念卡片 → 主题索引 → 项目/实验产出**

## 目录建议

| 目录 | 用途 |
|---|---|
| Attachment/Templates | 可插入的 Obsidian 笔记模板 |
| Attachment/Copilot | AI 对话副本 |
| Attachment/Excalidraw | Excalidraw 白板文件 |
| Source | PDF、EPUB、网页存档、手写笔记等原始资料 |
| Notes | 自己理解后的知识笔记 |
| Projects | 项目、实验和产出 |
| Plugins | 插件自身资源，不建议日常修改 |
| .obsidian | Vault 配置、主题、插件和快捷键 |

建议逐步创建以下个人目录：

- Notes/LLM
- Notes/强化学习
- Notes/论文
- Projects
- Projects/实验记录

不要一开始就建立过深的文件夹层级。文件夹负责粗分，MOC 和双向链接负责表达知识之间的关系。

## 已提供的模板

| 文件 | 用途 |
|---|---|
| 00-通用笔记.md | 快速记录想法、暂存问题和普通学习笔记 |
| 01-文献笔记.md | 论文、书籍、报告和网页资料 |
| 02-概念卡片.md | 一个概念、一条原理或一个技术问题 |
| 03-研究问题.md | 把模糊兴趣整理成可验证问题 |
| 04-实验记录.md | 模型、数据、超参数和实验结果 |
| 05-会议讨论.md | 会议、讨论和行动项 |
| 06-MOC主题索引.md | 维护一个领域或项目的导航页 |
| 07-周复盘.md | 每周回顾、沉淀和下周计划 |
| 08-LLM强化学习实验.md | 记录 PPO、DPO、GRPO、RLVR 等实验 |

## 使用方法

1. 打开 Obsidian 的设置。
2. 确认核心插件 Templates 已启用。
3. 将模板目录设置为 Attachment/Templates。
4. 新建一篇普通笔记。
5. 按 Cmd + P，执行 Templates: Insert template。
6. 选择需要的模板。

这些模板只使用 Obsidian 核心 Templates 插件支持的变量：

- {{title}}
- {{date:YYYY-MM-DD}}
- {{time:HH:mm}}

因此不依赖 Templater、Dataview 或其他社区插件。

## 推荐使用顺序

### 阅读论文

1. 把 PDF 放到 Source/论文。
2. 用 01-文献笔记.md 建立文献笔记。
3. 将值得长期保留的结论拆成 02-概念卡片.md。
4. 在对应 MOC 中补充链接和一句话说明。

### 做研究或项目

1. 用 03-研究问题.md 明确问题和假设。
2. 用 04-实验记录.md 记录每次实验。
3. 用 05-会议讨论.md 固化决策和行动项。
4. 在项目 MOC 中汇总当前状态、关键结论和下一步。

### 记录临时想法

先用 00-通用笔记.md 快速记录，不要为了分类打断思考。之后再把其中值得保留的内容转成概念卡片、文献笔记或研究问题。

## 维护原则

- 一篇笔记只承担一个主要用途。
- 摘录、解释、个人判断要分开写。
- 每篇长期笔记至少保留一个来源或上下文链接。
- 不要为了“看起来完整”填满所有字段。
- 模板服务于思考，不要让填写模板变成额外负担。

## 外部参考

- [Obsidian Templates 官方说明](https://obsidian.md/help/Plugins/Templates)
- [Obsidian Starter Templates](https://github.com/masonlr/obsidian-starter-templates)
- [Vaultorial Obsidian Templates](https://github.com/Vaultorial/obsidian-templates)

