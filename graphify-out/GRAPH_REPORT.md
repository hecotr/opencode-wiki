# Graph Report - .  (2026-04-21)

## Corpus Check
- Corpus is ~24,237 words - fits in a single context window. You may not need a graph.

## Summary
- 172 nodes ¡¤ 162 edges ¡¤ 30 communities detected
- Extraction: 81% EXTRACTED ¡¤ 19% INFERRED ¡¤ 0% AMBIGUOUS ¡¤ INFERRED: 30 edges (avg confidence: 0.8)
- Token cost: 0 input ¡¤ 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Agent System & Permissions|Agent System & Permissions]]
- [[_COMMUNITY_Modes & Agent Behavior|Modes & Agent Behavior]]
- [[_COMMUNITY_Providers & SDK|Providers & SDK]]
- [[_COMMUNITY_Configuration & Enterprise|Configuration & Enterprise]]
- [[_COMMUNITY_CLI Commands & Go Backend|CLI Commands & Go Backend]]
- [[_COMMUNITY_Rules & Skills|Rules & Skills]]
- [[_COMMUNITY_Networking & Server|Networking & Server]]
- [[_COMMUNITY_Commands & Config System|Commands & Config System]]
- [[_COMMUNITY_IDE Integration & ACP|IDE Integration & ACP]]
- [[_COMMUNITY_GitHub & GitLab CI|GitHub & GitLab CI]]
- [[_COMMUNITY_Custom Tools|Custom Tools]]
- [[_COMMUNITY_Formatters & LSP|Formatters & LSP]]
- [[_COMMUNITY_Search Tools|Search Tools]]
- [[_COMMUNITY_Enterprise Data Policy|Enterprise Data Policy]]
- [[_COMMUNITY_Keybinds|Keybinds]]
- [[_COMMUNITY_Custom Providers|Custom Providers]]
- [[_COMMUNITY_TUI-Server Bridge|TUI-Server Bridge]]
- [[_COMMUNITY_Web Search Tools|Web Search Tools]]
- [[_COMMUNITY_Session Management|Session Management]]
- [[_COMMUNITY_Usage Statistics|Usage Statistics]]
- [[_COMMUNITY_Data ExportImport|Data Export/Import]]
- [[_COMMUNITY_Config Watcher|Config Watcher]]
- [[_COMMUNITY_Ecosystem Projects|Ecosystem Projects]]
- [[_COMMUNITY_Plugin Loading|Plugin Loading]]
- [[_COMMUNITY_Custom Themes|Custom Themes]]
- [[_COMMUNITY_Question Tool|Question Tool]]
- [[_COMMUNITY_Troubleshooting|Troubleshooting]]
- [[_COMMUNITY_File References|File References]]
- [[_COMMUNITY_Editor Setup|Editor Setup]]
- [[_COMMUNITY_Zen Pricing|Zen Pricing]]

## God Nodes (most connected - your core abstractions)
1. `Permission System` - 11 edges
2. `opencode.json Configuration` - 10 edges
3. `OpenCode HTTP Server` - 10 edges
4. `LLM Provider System` - 7 edges
5. `Primary Agent Mode` - 6 edges
6. `AGENTS.md Rules System` - 6 edges
7. `opencode acp Command` - 5 edges
8. `Model Selection Mechanism` - 5 edges
9. `Built-in Tools` - 5 edges
10. `Terminal User Interface` - 5 edges

## Surprising Connections (you probably didn't know these)
- `Temperature Configuration` --references--> `LLM Provider System`  [INFERRED]
  opencode-docs/modes.md ¡ú opencode-docs/providers.md
- `AGENTS.md Rules System` --semantically_similar_to--> `SKILL.md Frontmatter`  [INFERRED] [semantically similar]
  opencode-docs/rules.md ¡ú opencode-docs/skills.md
- `VS Code Extension` --semantically_similar_to--> `Zed Editor ACP Integration`  [INFERRED] [semantically similar]
  opencode-docs/ide.md ¡ú opencode-docs/acp.md
- `OpenCode Ecosystem Plugins` --references--> `opencode.json Configuration`  [INFERRED]
  opencode-docs/ecosystem.md ¡ú opencode-docs/config.md
- `Built-in Formatters` --semantically_similar_to--> `LSP Auto-Detection Mechanism`  [INFERRED] [semantically similar]
  opencode-docs/formatters.md ¡ú opencode-docs/lsp.md

## Hyperedges (group relationships)
- **Layered Configuration Merge Pattern** ¡ª config_remote_config, config_global_config, config_project_config, config_opencode_json [EXTRACTED 0.95]
- **Plan-Build Agent Switching Cycle** ¡ª index_plan_build_workflow, agents_plan_agent, agents_build_agent, keybinds_tui_json [EXTRACTED 0.90]
- **MCP Tool Registration and Agent Scoping Flow** ¡ª mcp_model_context_protocol, mcp_glob_tools, agents_permissions, config_tools_section [INFERRED 0.80]
- **Client-Server Architecture** ¡ª server_http, tui_interface, web_interface, sdk_client [EXTRACTED 0.90]
- **Three Axes of Extensibility** ¡ª plugins_system, skills_system, tools_system [INFERRED 0.80]
- **Layered Security Model** ¡ª permissions_system, server_auth, share_enterprise, permissions_external_directory [INFERRED 0.75]

## Communities

### Community 0 - "Agent System & Permissions"
Cohesion: 0.12
Nodes (20): Build Agent, Compaction Agent, Explore Subagent, General Subagent, Agent Permissions System, Plan Agent, Primary Agent Mode, Subagent Mode (+12 more)

### Community 1 - "Modes & Agent Behavior"
Cohesion: 0.11
Nodes (20): Build Mode, Custom Mode Configuration, Mode Option Deprecation Rationale, Plan Mode, Temperature Configuration, Agent Permission Override, Doom Loop Detection, .env File Default Deny Rationale (+12 more)

### Community 2 - "Providers & SDK"
Cohesion: 0.11
Nodes (19): Custom CA Certificates, Session Compaction Hook, Plugin System, Amazon Bedrock Authentication Chain, LLM Provider System, OpenCode JS/TS SDK, SDK Session API, SDK Structured Output (+11 more)

### Community 3 - "Configuration & Enterprise"
Cohesion: 0.15
Nodes (14): opencode mcp Command, Disabled Providers Configuration, Enabled Providers Configuration, Global Configuration, Configuration Precedence Order, Project Configuration, Remote Configuration (.well-known/opencode), Enterprise Internal AI Gateway (+6 more)

### Community 4 - "CLI Commands & Go Backend"
Cohesion: 0.15
Nodes (13): opencode attach Command, opencode auth Command, opencode models Command, opencode run Command, opencode serve Command, opencode web Command, Rationale: OpenCode Go Goals, OpenCode Go Subscription (+5 more)

### Community 5 - "Rules & Skills"
Cohesion: 0.18
Nodes (13): /connect Command, AGENTS.md Rules System, Claude Code Compatibility Layer, Custom Instructions (opencode.json), Rules File Priority, Skill Discovery Mechanism, SKILL.md Frontmatter, Agent Skills System (+5 more)

### Community 6 - "Networking & Server"
Cohesion: 0.19
Nodes (13): NO_PROXY Requirement Rationale, Network Proxy Configuration, Plugin Hooks/Events, Server Authentication, OpenCode HTTP Server, Log File Locations, Terminal User Interface, Undo/Redo via Git Rationale (+5 more)

### Community 7 - "Commands & Config System"
Cohesion: 0.18
Nodes (11): OpenCode Environment Variables, $ARGUMENTS Placeholder, Custom Commands, File Reference in Commands, Shell Output Injection in Commands, Command Template, opencode.json Configuration, Configuration Variable Substitution (+3 more)

### Community 8 - "IDE Integration & ACP"
Cohesion: 0.25
Nodes (8): Agent Client Protocol (ACP), Avante.nvim ACP Integration, CodeCompanion.nvim ACP Integration, JetBrains IDE ACP Integration, opencode acp Command, Zed Editor ACP Integration, IDE Context Awareness, VS Code Extension

### Community 9 - "GitHub & GitLab CI"
Cohesion: 0.25
Nodes (8): opencode github Command, GitHub Actions Workflow, OpenCode GitHub App, GitHub Supported Events, GitHub OpenCode Integration, GitLab CI Component, GitLab Duo Integration, GitLab OpenCode Integration

### Community 10 - "Custom Tools"
Cohesion: 0.5
Nodes (4): Custom Tool Context, Multi-Tool Export Pattern, tool() Helper Function, Zod Schema for Tool Arguments

### Community 11 - "Formatters & LSP"
Cohesion: 0.5
Nodes (4): Built-in Formatters, Prettier Formatter, LSP Auto-Detection Mechanism, Built-in LSP Servers

### Community 12 - "Search Tools"
Cohesion: 0.67
Nodes (3): glob Tool, grep Tool, Ripgrep Internal Engine

### Community 13 - "Enterprise Data Policy"
Cohesion: 1.0
Nodes (2): Enterprise Data Handling Policy, Rationale: Disable Share for Enterprise

### Community 14 - "Keybinds"
Cohesion: 1.0
Nodes (2): Leader Key Concept, tui.json Keybind Configuration

### Community 15 - "Custom Providers"
Cohesion: 1.0
Nodes (2): Custom Provider Configuration, OpenAI-Compatible Provider Pattern

### Community 16 - "TUI-Server Bridge"
Cohesion: 1.0
Nodes (2): SDK TUI Control API, TUI REST Endpoints

### Community 17 - "Web Search Tools"
Cohesion: 1.0
Nodes (2): webfetch Tool, websearch Tool

### Community 18 - "Session Management"
Cohesion: 1.0
Nodes (1): opencode session Command

### Community 19 - "Usage Statistics"
Cohesion: 1.0
Nodes (1): opencode stats Command

### Community 20 - "Data Export/Import"
Cohesion: 1.0
Nodes (1): opencode export/import Commands

### Community 21 - "Config Watcher"
Cohesion: 1.0
Nodes (1): File Watcher Configuration

### Community 22 - "Ecosystem Projects"
Cohesion: 1.0
Nodes (1): OpenCode Ecosystem Projects

### Community 23 - "Plugin Loading"
Cohesion: 1.0
Nodes (1): Plugin Loading Order

### Community 24 - "Custom Themes"
Cohesion: 1.0
Nodes (1): Custom Theme JSON Format

### Community 25 - "Question Tool"
Cohesion: 1.0
Nodes (1): question Tool

### Community 26 - "Troubleshooting"
Cohesion: 1.0
Nodes (1): Linux Clipboard Fix

### Community 27 - "File References"
Cohesion: 1.0
Nodes (1): File References (@ syntax)

### Community 28 - "Editor Setup"
Cohesion: 1.0
Nodes (1): Editor Setup

### Community 29 - "Zen Pricing"
Cohesion: 1.0
Nodes (1): Zen Pricing Model

## Knowledge Gaps
- **100 isolated node(s):** `Agent Client Protocol (ACP)`, `JetBrains IDE ACP Integration`, `Avante.nvim ACP Integration`, `CodeCompanion.nvim ACP Integration`, `General Subagent` (+95 more)
  These have ¡Ü1 connection - possible missing edges or undocumented components.
- **Thin community `Enterprise Data Policy`** (2 nodes): `Enterprise Data Handling Policy`, `Rationale: Disable Share for Enterprise`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Keybinds`** (2 nodes): `Leader Key Concept`, `tui.json Keybind Configuration`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Custom Providers`** (2 nodes): `Custom Provider Configuration`, `OpenAI-Compatible Provider Pattern`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `TUI-Server Bridge`** (2 nodes): `SDK TUI Control API`, `TUI REST Endpoints`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Web Search Tools`** (2 nodes): `webfetch Tool`, `websearch Tool`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Session Management`** (1 nodes): `opencode session Command`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Usage Statistics`** (1 nodes): `opencode stats Command`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Data Export/Import`** (1 nodes): `opencode export/import Commands`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Config Watcher`** (1 nodes): `File Watcher Configuration`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Ecosystem Projects`** (1 nodes): `OpenCode Ecosystem Projects`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Plugin Loading`** (1 nodes): `Plugin Loading Order`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Custom Themes`** (1 nodes): `Custom Theme JSON Format`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Question Tool`** (1 nodes): `question Tool`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Troubleshooting`** (1 nodes): `Linux Clipboard Fix`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `File References`** (1 nodes): `File References (@ syntax)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Editor Setup`** (1 nodes): `Editor Setup`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Zen Pricing`** (1 nodes): `Zen Pricing Model`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `opencode.json Configuration` connect `Commands & Config System` to `Agent System & Permissions`, `Configuration & Enterprise`, `CLI Commands & Go Backend`?**
  _High betweenness centrality (0.085) - this node is a cross-community bridge._
- **Why does `OpenCode HTTP Server` connect `Networking & Server` to `Providers & SDK`?**
  _High betweenness centrality (0.065) - this node is a cross-community bridge._
- **Why does `OpenCode JS/TS SDK` connect `Providers & SDK` to `Networking & Server`?**
  _High betweenness centrality (0.064) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `Permission System` (e.g. with `Custom Mode Configuration` and `Plugin System`) actually correct?**
  _`Permission System` has 2 INFERRED edges - model-reasoned connections that need verification._
- **Are the 2 inferred relationships involving `OpenCode HTTP Server` (e.g. with `Plugin Hooks/Events` and `Log File Locations`) actually correct?**
  _`OpenCode HTTP Server` has 2 INFERRED edges - model-reasoned connections that need verification._
- **Are the 4 inferred relationships involving `LLM Provider System` (e.g. with `Temperature Configuration` and `Custom CA Certificates`) actually correct?**
  _`LLM Provider System` has 4 INFERRED edges - model-reasoned connections that need verification._
- **What connects `Agent Client Protocol (ACP)`, `JetBrains IDE ACP Integration`, `Avante.nvim ACP Integration` to the rest of the system?**
  _100 weakly-connected nodes found - possible documentation gaps or missing edges._