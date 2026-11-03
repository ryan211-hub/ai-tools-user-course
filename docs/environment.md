# 实践环境说明（学习用）

**状态**：历史已确认环境摘要；正式实践开始前重新检查版本、路径和权限。不要将此文件视为当前机器的实时检测结果。

## 已有工具与项目
- Windows + PowerShell + VS Code + Codex 扩展。
- Git、Python、uv、dbt-core 和 dbt-trino 曾在本地使用。
- Spellbook 工作目录曾使用 `C:\Dev\spellbook`。
- 课程文档仓库：https://github.com/ryan211-hub/ai-tools-user-course
- 原有 Web3 实践记录仓库：https://github.com/ryan211-hub/blockchain-data-engineering-journey
- Dune Spellbook 项目可作为 SQL/dbt 案例。

## 历史验证与局限
- 过去已在 Windows 使用 dbt compile（dex）并生成 manifest.json。
- 编译通过不能替代 Trino/Dune 实际查询或数据正确性测试。
- 本课程配置阶段没有检查当前电脑、登录状态或实际 MCP Server 的可用性。

## 课程开始前的检查项
- [ ] 确认 VS Code 中 Codex 扩展已登录及可用。
- [ ] 确认正在操作的仓库及 Git 分支，先检查 `git status`。
- [ ] 记录 Python、uv、dbt、Git 的实际版本（只记录非敏感信息）。
- [ ] 说明 Codex 对工作区和命令执行的权限边界。
- [ ] 任何 MCP 连接从最小权限、只读或测试数据开始。

## 安全边界
不要记录或提交个人凭据、Token、SSH 私钥、钱包助记词、API Key、数据库密码或带敏感信息的 profiles.yml。
