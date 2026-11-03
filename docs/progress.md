# AI 工具课程学习进度

**更新时间**：2026-11-04  
**总体状态**：In progress（Day 1 已完成；Day 2 待开始）  
**课程版本**：v0.1  
**当前学习入口**：Day 2｜Prompt、Instructions（待开始）  
**已完成课程**：1 / 20  
**预算**：4 周 × 每周 5 天 × 每天 2 小时 ≈ 40 小时（节奏暂定，理解优先）

> 注意：课程规划、仓库配置、Notion/GitHub 同步不计作任何课程学习完成。

## Week 1｜AI 基础认知
- [x] Day 1｜LLM、ChatGPT、Codex 的关系
- [ ] Day 2｜Prompt、Instructions
- [ ] Day 3｜Context、Token、上下文窗口
- [ ] Day 4｜Tool Calling、Agent
- [ ] Day 5｜综合复盘

## Week 2｜AI 工具连接
- [ ] Day 6｜API、Function Calling
- [ ] Day 7｜MCP、Host、Client、Server
- [ ] Day 8｜MCP 配置与验证
- [ ] Day 9｜Skills、Rules、AGENTS.md
- [ ] Day 10｜机制对比与综合实践

## Week 3｜VS Code + Codex
- [ ] Day 11｜Codex 任务执行流程
- [ ] Day 12｜文件修改与 Diff 审查
- [ ] Day 13｜Sandbox、Approval、权限
- [ ] Day 14｜Git、分支、Commit、PR
- [ ] Day 15｜测试、验证与错误恢复

## Week 4｜个人 AI 工作流
- [ ] Day 16｜RAG、检索、项目上下文
- [ ] Day 17｜Workflow 与自动化
- [ ] Day 18｜多工具协作
- [ ] Day 19｜Spellbook 综合任务演练
- [ ] Day 20｜综合验收与复盘

## 学习记录模板
### YYYY-MM-DD｜Day N
- 状态：
- 核心概念：
- 使用工具与操作：
- 实际验证证据：
- 理解检查：
- 遗留疑问：
- 下一步：

## 同步
- 课程大纲（Notion）：https://app.notion.com/p/40d19faa63d68169ac6cff8c3e8dc943
- GitHub：https://github.com/ryan211-hub/ai-tools-user-course
- 项目指令是否已手动加入 ChatGPT 项目：**用户已确认完成**
- 项目文件是否已手动上传 ChatGPT 项目：**用户已确认完成**

## 已完成课程记录

### 2026-11-04｜Day 1｜LLM、ChatGPT、Codex 的关系
- **状态**：Completed（结课审核通过；此日期为记录更新日期）
- **核心概念**：LLM 是模型层；ChatGPT 与 Codex 是产品/应用层；Codex 可以通过获授权的工具读取文件与运行命令。区分 Model、Application、Tool 的职责。
- **实际操作（用户报告）**：在 VS Code + Codex 中对 Spellbook `dbt_subprojects/dex/models/trades/ethereum/platforms/uniswap_v3_ethereum_base_trades.sql` 进行只读分析；观察到文件搜索、文件读取及终端命令。
- **验证（用户报告）**：`git status --short` 无输出，说明 Git 未检测到当前仓库的未提交变更；不能证明所有文件均未变化。
- **理解检查**：基础 3/3（A、B、C）；最终 3/3（B、C、A），共 6/6 正确。
- **证据限制**：未取得 Codex 原始执行日志与 SQL 分析全文，具体命令和 SQL 逻辑准确性未经独立审计。不将 SQL 正确性视为本课通过项。
- **遗留疑问**：无已报告的核心概念疑问；保留上述审计限制。
- **下一课入口**：Day 2｜Prompt、Instructions；仅在用户明确要求开始下一课时授课。
