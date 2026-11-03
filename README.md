# AI 工具使用者入门课程｜学习计划

> Notion 课程计划：https://app.notion.com/p/40d19faa63d68169ac6cff8c3e8dc943

**版本**：v0.1（初步规划）
**制定日期**：2026-11-03
**状态**：学习中（Day 1 已完成；后续课程按需推进）
**定位**：AI 工具高级使用者，不以开发 Agent 或训练模型为目标。
**时间预算**：4 周 × 每周 5 天 × 每天 2 小时 = 40 小时。每周 5 天与“理解优先”是当前暂定节奏，可调整。
**学习结构**：每天概念 30 分钟、实际操作 60 分钟、复盘 30 分钟；全程约 12h 概念、20h 实践、8h 复盘。按掌握情况灵活调整。

## 一、学习目标与边界

完成后应能：解释 LLM、Prompt、Context、Token、Tool Calling、Agent、API、MCP、Skills、RAG、Workflow 的主要作用及联系；独立在 VS Code 中使用 Codex 处理有边界的开发任务；检查代码 Diff、执行结果与权限；配置并辨别 MCP 适用场景；设计可复用的 AI 辅助 SQL 开发工作流。

**案例主线**：VS Code + Codex + Dune Spellbook（SQL、dbt）+ Git/GitHub。使用已有数据工程知识作为学习载体，不把本课程变成第二门 dbt 或 Web3 专业课程。所有实操应遵守仓库的安全边界，避免将凭据、Token、私密配置上传至公开仓库。

## 二、20 个学习单元（每单元预算 2 小时）

### 第 1 周｜AI 基础认知（10h）

| 单元 | 核心概念 | 关联实践 |
| --- | --- | --- |
| Day 1 | LLM、ChatGPT、Codex 的关系 | 比较同一 SQL 分析任务在聊天与 Codex 中的处理方式 |
| Day 2 | Prompt、Instructions | 为 Spellbook 编写明确的只读分析指令 |
| Day 3 | Context、Token、上下文窗口 | 比较给出/不给出项目背景的 SQL 分析结果 |
| Day 4 | Tool Calling、Agent | 观察 Codex 如何检索、读取文件和决定下一步 |
| Day 5 | 综合复盘 | 绘制个人 AI 工具结构图，解释一个任务的执行链路 |

**周验收**：能准确区分模型、产品、Agent、工具与上下文；能说清 Codex 使用本地文件的必要条件。

### 第 2 周｜工具连接与扩展（10h）

| 单元 | 核心概念 | 关联实践 |
| --- | --- | --- |
| Day 6 | API、Function Calling | 识别一次工具调用的参数、返回值和错误 |
| Day 7 | MCP、Host、Client、Server | 描述 MCP 的组件与数据流 |
| Day 8 | MCP 配置与验证 | 在兼容环境中配置一个权限最小化的只读工具 |
| Day 9 | Skills、Rules、`AGENTS.md` | 草拟 Spellbook AI 操作规则与任务检查清单 |
| Day 10 | 机制对比 | 判断何时用内置工具、MCP、Skills 或普通提示词 |

**周验收**：能解释 MCP 不等于 Agent、不是每个工具都需要 MCP；能描述并验证一次工具连接。

### 第 3 周｜VS Code + Codex 实践（10h）

| 单元 | 核心概念 | 关联实践 |
| --- | --- | --- |
| Day 11 | Codex 任务流程 | 追踪一个 SQL 任务从需求到结果的步骤 |
| Day 12 | 文件修改、Diff | 检查 Codex 修改前后的差异 |
| Day 13 | Sandbox、Approval、权限 | 设计只读、有限写入、需审批的权限边界 |
| Day 14 | Git、分支、Commit、PR | 在练习分支上模拟文档或 SQL 贡献 |
| Day 15 | 测试与错误恢复 | 区分 dbt compile、实际查询和数据质量验证 |

**周验收**：可独立限定改动范围，审查 Diff，说明验证证据与尚未验证的部分。

### 第 4 周｜个人 AI 工作流（10h）

| 单元 | 核心概念 | 关联实践 |
| --- | --- | --- |
| Day 16 | RAG、检索与项目上下文 | 比较搜索仓库资料与直接生成答案 |
| Day 17 | Workflow、自动化 | 设计 SQL 任务分解、执行、检查与回退流程 |
| Day 18 | 多工具协作 | 衔接 Codex、GitHub 与学习文档 |
| Day 19 | 综合项目 | 完成一次受控 Spellbook 任务演练 |
| Day 20 | 总验收 | 固化指令模板、权限规则、验证清单和学习记录 |

**周验收**：能复用完整的「需求 → 上下文 → 工具 → 执行 → 测试 → 审查 → 记录」流程，并明确人工复核环节。

## 三、教学与记录原则

- 每次只突出一个核心问题；先简单类比、再专业解释、再真实案例。
- 每个单元包含：概念要点、具体任务、观察结果、理解检查。
- 学会再进入下一课；4 周是参考预算，不强制按日历赶进度。
- 每次复盘只记录：概念、使用工具、验证结果、尚存疑问。
- GitHub 只保存可公开的学习文档和实践；**不把“编译成功”等同于真实链上数据验证通过**。
- 课程规划可随学习实际情况调整；截至最新进度记录，Day 1 已按结课审核完成，其余单元仍待开始。

## 四、阶段产出

1. Week 1：AI 工具认知图与任务执行流程说明。
2. Week 2：MCP 连接记录与 AI 开发规则草案。
3. Week 3：Codex 操作、Diff 审查与测试验证清单。
4. Week 4：可复用的 Spellbook AI 辅助开发工作流与最终验收记录。

**下一动作**：先审查课程计划与学习安排，正式学习需另行启动。

## 课程配置与进度

- [ChatGPT 项目指令模板](docs/project-instructions.md) — 由用户手动粘贴到 ChatGPT 项目设置。
- [学习与验收规范](docs/learning-rules.md)
- [实践环境说明](docs/environment.md)
- [学习进度（当前 1/20，Day 2 待开始）](docs/progress.md)

Notion：[课程计划](https://app.notion.com/p/40d19faa63d68169ac6cff8c3e8dc943) · [学习规范](https://app.notion.com/p/40d19faa63d68104972bf0239b6eaded) · [学习进度](https://app.notion.com/p/40d19faa63d68132b697d0e8601bf7ab) · [实践环境](https://app.notion.com/p/40d19faa63d6814084bade45d8ccea83) · [项目指令模板](https://app.notion.com/p/40d19faa63d6812aa36bfbe719b17646)

> ChatGPT 项目指令与项目文件需要用户在项目界面自行添加；GitHub 与 Notion 不会自动双向同步。
