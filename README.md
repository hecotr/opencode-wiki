# OpenCode Wiki

OpenCode 中文文档知识库，基于 [graphify](https://github.com/safishamsi/graphify) 构建了可交互的知识图谱。

## 内容

- `opencode-docs/` — 35 篇 OpenCode 中文文档，涵盖配置、代理、工具、插件、权限等主题
- `graphify-out/` — 知识图谱输出

## 知识图谱

| 指标 | 数值 |
|------|------|
| 节点 | 172 |
| 边 | 162 |
| 社区 | 30 |
| Token 压缩 | 37.4x |

### 图谱文件

- `graphify-out/graph.html` — 可交互 HTML 图谱，浏览器打开即可使用
- `graphify-out/graph.json` — 图谱原始数据（可用于查询）
- `graphify-out/GRAPH_REPORT.md` — 审计报告，包含 God Nodes、意外连接、建议提问

### 核心 God Nodes

| 节点 | 连接数 |
|------|--------|
| Permission System | 11 |
| opencode.json Configuration | 10 |
| OpenCode HTTP Server | 10 |
| LLM Provider System | 7 |
| Primary Agent Mode | 6 |

## 文档目录

| 文件 | 主题 |
|------|------|
| [agents.md](opencode-docs/agents.md) | 代理配置 |
| [skills.md](opencode-docs/skills.md) | 代理技能 |
| [config.md](opencode-docs/config.md) | 配置系统 |
| [providers.md](opencode-docs/providers.md) | LLM 提供商 |
| [plugins.md](opencode-docs/plugins.md) | 插件开发 |
| [permissions.md](opencode-docs/permissions.md) | 权限管理 |
| [tools.md](opencode-docs/tools.md) | 内置工具 |
| [rules.md](opencode-docs/rules.md) | 规则系统 |
| [mcp-servers.md](opencode-docs/mcp-servers.md) | MCP 服务器 |
| [troubleshooting.md](opencode-docs/troubleshooting.md) | 故障排除 |

完整文档列表见 `opencode-docs/` 目录。

## 工具

- [graphify](https://github.com/safishamsi/graphify) — 知识图谱构建
- [OpenCode](https://opencode.ai) — AI 编码助手

## License

文档来源于 [OpenCode 官方文档](https://opencode.ai/docs/zh-cn/)，仅供学习参考。
