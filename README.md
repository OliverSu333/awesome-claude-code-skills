# GitHub Claude Code Skills & Plugins 完整清单

> 最后更新: 2026-02-14 | 数据来源: GitHub 搜索、awesome 列表、官方仓库

---

## 目录

- [1. 官方资源 (Official)](#1-官方资源-official)
- [2. Awesome 列表 / 策展集合](#2-awesome-列表--策展集合)
- [3. Agent Skills 技能包](#3-agent-skills-技能包)
- [4. Subagents 子代理](#4-subagents-子代理)
- [5. Plugins 插件系统](#5-plugins-插件系统)
- [6. Slash Commands 斜杠命令](#6-slash-commands-斜杠命令)
- [7. Hooks 钩子](#7-hooks-钩子)
- [8. IDE 集成 / 客户端](#8-ide-集成--客户端)
- [9. Agent 编排 / 多代理](#9-agent-编排--多代理)
- [10. Status Lines 状态栏](#10-status-lines-状态栏)
- [11. 使用监控 / 仪表盘](#11-使用监控--仪表盘)
- [12. CLAUDE.md 模板](#12-claudemd-模板)
- [13. MCP Servers (Model Context Protocol)](#13-mcp-servers-model-context-protocol)
- [14. 安全 / 审计技能](#14-安全--审计技能)
- [15. 科学 / 研究技能](#15-科学--研究技能)
- [16. SaaS 自动化集成 (Composio)](#16-saas-自动化集成-composio)
- [17. 工作流 / 方法论](#17-工作流--方法论)
- [18. GUI / 桌面客户端](#18-gui--桌面客户端)
- [19. Proxy / API 中继](#19-proxy--api-中继)
- [20. 指南 / 教程 / 参考](#20-指南--教程--参考)
- [21. 其他工具](#21-其他工具)

---

## 1. 官方资源 (Official)

| 仓库 | 描述 | ⭐ |
|------|------|-----|
| [anthropics/skills](https://github.com/anthropics/skills) | Anthropic 官方 Agent Skills 仓库，含 SKILL.md 规范和示例技能 | 7.4k+ |
| [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | 官方高质量 Claude Code 插件目录 | 7.4k |
| [anthropics/claude-code](https://github.com/anthropics/claude-code) | Claude Code CLI 本体 | — |
| [anthropics/anthropic-cookbook](https://github.com/anthropics/anthropic-cookbook) | 官方 Cookbook，含 MCP 教程 | — |
| [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) | 官方 MCP 参考服务器集合 (Fetch, Filesystem, Git, Memory, Sequential Thinking, Time) | 78.7k |
| [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk) | MCP 官方 Python SDK | 21.7k |
| [modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk) | MCP 官方 TypeScript SDK | 11.6k |
| [modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector) | MCP 可视化测试工具 | 8.7k |
| [modelcontextprotocol/modelcontextprotocol](https://github.com/modelcontextprotocol/modelcontextprotocol) | MCP 规范和文档 | 7.2k |
| [modelcontextprotocol/csharp-sdk](https://github.com/modelcontextprotocol/csharp-sdk) | MCP C# SDK (与 Microsoft 合作) | 3.9k |
| [modelcontextprotocol/rust-sdk](https://github.com/modelcontextprotocol/rust-sdk) | MCP Rust SDK | 3k |
| [modelcontextprotocol/kotlin-sdk](https://github.com/modelcontextprotocol/kotlin-sdk) | MCP Kotlin SDK (与 JetBrains 合作) | 1.3k |
| [modelcontextprotocol/ext-apps](https://github.com/modelcontextprotocol/ext-apps) | MCP Apps 协议规范 | 1.5k |
| [modelcontextprotocol/ruby-sdk](https://github.com/modelcontextprotocol/ruby-sdk) | MCP Ruby SDK (与 Shopify 合作) | 719 |
| [modelcontextprotocol/quickstart-resources](https://github.com/modelcontextprotocol/quickstart-resources) | MCP 快速入门教程资源 | 991 |

---

## 2. Awesome 列表 / 策展集合

| 仓库 | 描述 | ⭐ |
|------|------|-----|
| [affaan-m/everything-claude-code](https://github.com/affaan-m/everything-claude-code) | 最完整的 Claude Code 配置集 (13 agents, 37+ skills, 31+ commands, hooks, rules, MCPs) | 45.8k |
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | 900+ 自动化技能目录 (Composio 维护) | 34.7k |
| [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) | 最全面的 Claude Code 资源策展列表 (skills, hooks, commands, plugins) | 23.7k |
| [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | 最大的 MCP 服务器策展列表 (200+ servers, 40+ 类别) | — |
| [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) | 100+ 专业化 Claude Code 子代理 | 10.4k |
| [sickn33/antigravity-awesome-skills](https://github.com/sickn33/antigravity-awesome-skills) | 800+ agentic skills 集合 | 8.8k |
| [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) | 300+ agent skills，多平台兼容 | 7k |
| [travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills) | Claude Skills 策展列表 (含 progressive disclosure 架构说明) | 7.1k |
| [libukai/awesome-agent-skills](https://github.com/libukai/awesome-agent-skills) | Agent skills 指南 (含快速入门和案例) | 1.9k |
| [Prat011/awesome-llm-skills](https://github.com/Prat011/awesome-llm-skills) | LLM 和 AI Agent Skills 策展列表 | 889 |
| [ccplugins/awesome-claude-code-plugins](https://github.com/ccplugins/awesome-claude-code-plugins) | Claude Code 插件策展列表 (slash commands, subagents, MCP, hooks) | 478 |
| [rohitg00/awesome-claude-code-toolkit](https://github.com/rohitg00/awesome-claude-code-toolkit) | 综合工具包 (135 agents, 35 skills, 42 commands, 120 plugins) | 470 |
| [ComposioHQ/awesome-claude-plugins](https://github.com/ComposioHQ/awesome-claude-plugins) | Claude Code 插件策展列表 (Composio 维护) | 1.3k |
| [rahulvrane/awesome-claude-agents](https://github.com/rahulvrane/awesome-claude-agents) | Claude Code subagents 集合 | 283 |

---

## 3. Agent Skills 技能包

| 仓库 | 描述 | ⭐ |
|------|------|-----|
| [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | AI 设计智能技能 (专业 UI/UX 跨平台) | 31.2k |
| [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) | 持久化 Markdown 计划工作流技能 | 13.9k |
| [trailofbits/skills](https://github.com/trailofbits/skills) | Trail of Bits 安全技能市场 (CodeQL, Semgrep, 智能合约审计, YARA, 逆向工程) | — |
| [SawyerHood/dev-browser](https://github.com/SawyerHood/dev-browser) | 给 agent 浏览器能力的 Claude Skill | 3.6k |
| [Orchestra-Research/AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs) | AI 研究和工程技能开源库 | 3.3k |
| [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) | 搜索 Reddit/X 最近 30 天话题的技能 | 2.6k |
| [Jeffallan/claude-skills](https://github.com/Jeffallan/claude-skills) | 66 个全栈开发专用技能 | 2.4k |
| [davepoon/buildwithclaude](https://github.com/davepoon/buildwithclaude) | Skills, Agents, Commands, Hooks, Plugins 和 Marketplace 集合 | 2.4k |
| [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) | 实用技能集合 (含 subagents 和 commands) | 1.8k |
| [lackeyjb/playwright-skill](https://github.com/lackeyjb/playwright-skill) | Playwright 浏览器自动化测试技能 | 1.7k |
| [obra/superpowers](https://github.com/obra/superpowers) | 20+ 实战技能 (含 /brainstorm, /write-plan 命令) | — |
| [simonw/claude-skills](https://github.com/simonw/claude-skills) | Simon Willison 的技能集 (已指向官方 anthropics/skills) | — |

---

## 4. Subagents 子代理

| 仓库 | 描述 | ⭐ |
|------|------|-----|
| [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) | 100+ 专业化 Claude Code 子代理 | 10.4k |
| [iannuttall/claude-agents](https://github.com/iannuttall/claude-agents) | 自定义 Claude Code 子代理 | 2k |
| [lst97/claude-code-sub-agents](https://github.com/lst97/claude-code-sub-agents) | 全栈开发专用子代理集合 | 1.4k |
| [0xfurai/claude-code-subagents](https://github.com/0xfurai/claude-code-subagents) | 100+ 生产就绪开发子代理 | 705 |
| [NicholasSpisak/claude-code-subagents](https://github.com/NicholasSpisak/claude-code-subagents) | Claude Code 子代理集合 | 190 |

---

## 5. Plugins 插件系统

| 仓库 | 描述 | ⭐ |
|------|------|-----|
| [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) | 自动捕获 Claude 编码会话并 AI 压缩的记忆插件 | 28.1k |
| [EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin) | 官方 compound engineering 插件 | 8.8k |
| [jarrodwatts/claude-hud](https://github.com/jarrodwatts/claude-hud) | 显示上下文使用、活跃工具、运行代理和 todo 进度的 HUD 插件 | 3.4k |
| [brennercruvinel/CCPlugins](https://github.com/brennercruvinel/CCPlugins) | "Best Claude Code framework that actually saves time" | 2.7k |
| [ZeframLou/call-me](https://github.com/ZeframLou/call-me) | 让 Claude Code 打电话给你的极简插件 | 2.3k |
| [jeremylongshore/claude-code-plugins-plus-skills](https://github.com/jeremylongshore/claude-code-plugins-plus-skills) | 270+ 插件 + 739 agent skills + 生产编排模式 | 1.4k |
| [kingbootoshi/cartographer](https://github.com/kingbootoshi/cartographer) | 用并行 AI 子代理映射和文档化代码库的插件 | 465 |

---

## 6. Slash Commands 斜杠命令

| 仓库 | 描述 | ⭐ |
|------|------|-----|
| [wshobson/commands](https://github.com/wshobson/commands) | 生产就绪的 slash commands 集合 | 2k |
| [claude-sessions](https://github.com/claude-sessions/claude-sessions) | 会话管理 slash commands | 1.2k |
| [Claude-Command-Suite](https://github.com/Claude-Command-Suite/Claude-Command-Suite) | 综合 slash command 套件 | 935 |
| [claude-code-tresor](https://github.com/claude-code-tresor/claude-code-tresor) | 安全相关 slash commands | 514 |

---

## 7. Hooks 钩子

> 生命周期自动化工具 (PreToolUse, PostToolUse 等)

| 仓库 | 描述 | ⭐ |
|------|------|-----|
| [nizos/tdd-guard](https://github.com/nizos/tdd-guard) | 通过 hooks 自动强制 TDD 的工具 | 1.8k |
| [nicobailon/claude-code-hooks](https://github.com/nicobailon/claude-code-hooks) | Claude Code hooks 集合 (Britfix 拼写转换, CC Notify 桌面通知等) | — |
| [nicobailon/cchooks](https://github.com/nicobailon/cchooks) | 钩子开发 SDK | — |
| [cc-tools/cc-tools](https://github.com/cc-tools/cc-tools) | Claude Code 工具和钩子集合 | — |

*(详见 [awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) 的 Hooks 章节)*

---

## 8. IDE 集成 / 客户端

| 仓库 | 描述 | ⭐ |
|------|------|-----|
| [coder/claudecode.nvim](https://github.com/coder/claudecode.nvim) | Claude Code Neovim IDE 扩展 | 2k |
| [greggh/claude-code.nvim](https://github.com/greggh/claude-code.nvim) | Claude Code AI 与 Neovim 无缝集成 | 1.8k |
| [folke/sidekick.nvim](https://github.com/folke/sidekick.nvim) | Neovim AI 助手 (lazy.nvim 作者) | 2.3k |
| [olimorris/codecompanion.nvim](https://github.com/olimorris/codecompanion.nvim) | "AI Coding, Vim Style" Neovim 插件 | 6.1k |
| [YishenTu/claudian](https://github.com/YishenTu/claudian) | Obsidian 插件，嵌入 Claude Code 到 vault | 2.3k |
| [op7418/CodePilot](https://github.com/op7418/CodePilot) | Claude Code 原生桌面 GUI (Electron + Next.js) | 1.8k |
| [siteboon/claudecodeui](https://github.com/siteboon/claudecodeui) | 远程管理 Claude Code 会话的 Web UI | 6.2k |

---

## 9. Agent 编排 / 多代理

| 仓库 | 描述 | ⭐ |
|------|------|-----|
| [wshobson/agents](https://github.com/wshobson/agents) | 智能自动化和多代理编排 for Claude Code | 28.6k |
| [ruvnet/claude-flow](https://github.com/ruvnet/claude-flow) | 领先的 agent 编排平台 (多代理 swarms + 分布式智能) | 14k |
| [humanlayer/humanlayer](https://github.com/humanlayer/humanlayer) | 让 AI 编码代理解决复杂代码库问题 | 9.3k |
| [adenhq/hive](https://github.com/adenhq/hive) | "Outcome driven agent development framework that evolves" | 7.4k |
| [automazeio/ccpm](https://github.com/automazeio/ccpm) | Claude Code 项目管理 (GitHub Issues + Git worktrees) | 7.3k |
| [frankbria/ralph-claude-code](https://github.com/frankbria/ralph-claude-code) | 自主 AI 开发循环 (智能退出检测) | 6.9k |
| [Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) | Teams-first 多代理编排 | 6.2k |
| [smtg-ai/claude-squad](https://github.com/smtg-ai/claude-squad) | 管理多个 AI 终端代理 (Claude Code, Aider, Codex, OpenCode) | 6k |
| [parcadei/Continuous-Claude-v3](https://github.com/parcadei/Continuous-Claude-v3) | 上下文管理 (hooks, ledgers, agent orchestration) | 3.5k |
| [stravu/crystal](https://github.com/stravu/crystal) | 在并行 git worktrees 中运行多个 Codex/Claude Code 会话 | 2.9k |
| [michaelshimeles/ralphy](https://github.com/michaelshimeles/ralphy) | 自主 bash 脚本循环运行多个编码代理 | 2.3k |
| [max-sixty/worktrunk](https://github.com/max-sixty/worktrunk) | Git worktree 管理 CLI (为并行 AI agent 设计) | 2.1k |
| [mikeyobrien/ralph-orchestrator](https://github.com/mikeyobrien/ralph-orchestrator) | Ralph Wiggum 技术的改进实现 (自主 AI agent 编排) | 1.8k |
| [superset-sh/superset](https://github.com/superset-sh/superset) | 编码代理指挥中心 (Claude Code, OpenCode, Codex 团队) | 1.6k |
| [0xCrunchyy/10x](https://github.com/0xCrunchyy/10x) | 20x 更快 AI 编码 (智能模型路由) | 1.4k |
| [avifenesh/agentsys](https://github.com/avifenesh/agentsys) | AI 自动化 (12 plugins, 41 agents, 27 skills) | 380 |
| [ayoubben18/ab-method](https://github.com/ayoubben18/ab-method) | 将问题转化为聚焦增量任务的开发方法 | 138 |

---

## 10. Status Lines 状态栏

| 仓库 | 描述 | ⭐ |
|------|------|-----|
| [sirmalloc/ccstatusline](https://github.com/sirmalloc/ccstatusline) | 高度可定制的 Claude Code CLI 状态栏 (powerline 支持) | 3.8k |

*(更多状态栏工具见 [awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) 的 Status Lines 章节)*

---

## 11. 使用监控 / 仪表盘

| 仓库 | 描述 | ⭐ |
|------|------|-----|
| [Maciek-roboblog/Claude-Code-Usage-Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) | 实时使用监控 (预测和警告) | 6.5k |
| [steipete/CodexBar](https://github.com/steipete/CodexBar) | 显示 OpenAI Codex 和 Claude Code 使用统计 | 5.7k |

---

## 12. CLAUDE.md 模板

| 仓库 | 描述 | ⭐ |
|------|------|-----|
| [shanraisshan/claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice) | Claude Code 最佳实践 | 2.5k |
| [centminmod/my-claude-code-setup](https://github.com/centminmod/my-claude-code-setup) | 启动模板配置和 CLAUDE.md memory bank 系统 | 1.9k |
| [claude-reflect/claude-reflect](https://github.com/claude-reflect/claude-reflect) | 自动反思和改进 CLAUDE.md 的工具 | 675 |
| [ClaudeForge/ClaudeForge](https://github.com/ClaudeForge/ClaudeForge) | CLAUDE.md 模板生成器和管理工具 | 151 |
| [claude-code-auto-memory/claude-code-auto-memory](https://github.com/claude-code-auto-memory/claude-code-auto-memory) | 自动记忆管理 CLAUDE.md 系统 | 108 |

---

## 13. MCP Servers (Model Context Protocol)

### 13.1 官方参考服务器

| 服务器 | 描述 |
|--------|------|
| Everything | 参考/测试服务器 (prompts, resources, tools) |
| Fetch | Web 内容获取和转换 |
| Filesystem | 安全文件操作 (可配置访问控制) |
| Git | Git 仓库读取、搜索和操作 |
| Memory | 基于知识图谱的持久记忆系统 |
| Sequential Thinking | 动态反思式问题解决 |
| Time | 时间和时区转换 |

### 13.2 已归档参考服务器

AWS KB Retrieval, Brave Search, EverArt, GitHub, GitLab, Google Drive, Google Maps, PostgreSQL, Puppeteer, Redis, Sentry, Slack, SQLite

### 13.3 社区 MCP 服务器 (按类别)

#### 🔗 聚合器
| 服务器 | 描述 |
|--------|------|
| [nicobailon/pal-mcp-server](https://github.com/nicobailon/pal-mcp-server) | 个人 AI 助手 MCP 服务器 (11.1k⭐) |
| 1mcp/agent | 统一多个 MCP 服务器为一个 |
| metatool-ai/metatool-app | 统一中间件 MCP 服务器 (GUI 管理) |
| mindsdb/mindsdb | 跨平台数据统一 |
| Pipedream | 连接 2,500 APIs 和 8,000+ 预构建工具 |
| tigranbs/mcgravity | 代理工具组合多个 MCP 服务器 |
| wegotdocs/open-mcp | 10 秒将 Web API 变成 MCP 服务器 |

#### 🌐 浏览器自动化
| 服务器 | 描述 |
|--------|------|
| microsoft/playwright-mcp | 官方 Microsoft Playwright MCP 服务器 |
| browsermcp/mcp | 自动化本地 Chrome 浏览器 |
| browserbase/mcp-server-browserbase | 云端浏览器自动化和数据提取 |
| executeautomation/playwright-mcp-server | Playwright 浏览器自动化 |
| agent-infra/mcp-server-browser | Puppeteer 浏览器自动化 |

#### ☁️ 云平台
| 服务器 | 描述 |
|--------|------|
| awslabs/mcp | AWS MCP 服务器集合 |
| cloudflare/mcp-server-cloudflare | Cloudflare Workers, KV, R2, D1 |
| hashicorp/terraform-mcp-server | 官方 Terraform MCP 服务器 |
| pulumi/mcp-server | Pulumi IaC 操作 |
| localstack/localstack-mcp-server | 本地 AWS 环境 |
| Flux159/mcp-server-kubernetes | Kubernetes 集群操作 |
| alexei-led/k8s-mcp-server | Kubernetes CLI (kubectl, helm, istioctl, argocd) |

#### 🗄️ 数据库
| 服务器 | 描述 |
|--------|------|
| PostgreSQL (archived) | PostgreSQL 数据库操作 |
| SQLite (archived) | SQLite 数据库操作 |
| Redis (archived) | Redis 数据操作 |
| redis/mcp-redis-cloud | Redis Cloud 资源管理 |

#### 🧬 生物/医学/生物信息学
| 服务器 | 描述 |
|--------|------|
| genomoncology/biomcp | PubMed, ClinicalTrials.gov, MyVariant.info |
| longevity-genie/biothings-mcp | BioThings API (基因, 变异, 药物) |
| longevity-genie/gget-mcp | 基因组学查询工具包 |
| wso2/fhir-mcp-server | FHIR 医疗互操作资源 |

#### 🎨 艺术/文化/创意
| 服务器 | 描述 |
|--------|------|
| ahujasid/blender-mcp | Blender 3D 建模 |
| burningion/video-editing-mcp | 视频编辑 |
| GenWaveLLC/svgmaker-mcp | AI SVG 生成和编辑 |
| samuelgursky/davinci-resolve-mcp | DaVinci Resolve 视频编辑 |

> 完整 MCP 服务器列表 (200+) 见: [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) 和 [MCP Registry](https://registry.modelcontextprotocol.io)

---

## 14. 安全 / 审计技能

| 技能 | 描述 | 来源 |
|------|------|------|
| building-secure-contracts | 智能合约安全工具包 (6 条区块链) | Trail of Bits |
| entry-point-analyzer | 智能合约入口点安全审计 | Trail of Bits |
| audit-context-building | 超细粒度代码分析构建架构上下文 | Trail of Bits |
| differential-review | 安全聚焦的代码变更差异审查 | Trail of Bits |
| insecure-defaults | 检测不安全默认配置和硬编码凭证 | Trail of Bits |
| semgrep-rule-creator | 创建自定义漏洞检测 Semgrep 规则 | Trail of Bits |
| static-analysis | 静态分析工具包 (CodeQL, Semgrep, SARIF) | Trail of Bits |
| variant-analysis | 基于模式的跨代码库相似漏洞查找 | Trail of Bits |
| yara-authoring | YARA 检测规则编写 | Trail of Bits |
| constant-time-analysis | 检测编译器引入的时序侧信道 | Trail of Bits |
| property-based-testing | 多语言属性测试指导 | Trail of Bits |
| firebase-apk-scanner | Android APK Firebase 安全配置扫描 | Trail of Bits |
| sharp-edges | 识别易错 API 和危险配置 | Trail of Bits |
| spec-to-code-compliance | 规范到代码合规检查 (区块链审计) | Trail of Bits |
| dwarf-expert | DWARF 调试格式交互 | Trail of Bits |

---

## 15. 科学 / 研究技能

> 以下技能来自 claude-scientific-skills 和相关项目

**数据科学库**: anndata, dask, polars, pandas, scikit-learn, statsmodels, shap, umap-learn, vaex
**生物信息学**: biopython, scanpy, pydeseq2, pysam, scvi-tools, esm, etetoolkit
**化学/药物**: rdkit, deepchem, datamol, medchem, molfeat, matchms
**量子计算**: qiskit, cirq, pennylane, qutip
**可视化**: matplotlib, plotly, seaborn
**深度学习**: pytorch-lightning, transformers, stable-baselines3, torch_geometric
**材料科学**: pymatgen
**统计/贝叶斯**: pymc, pymoo, sympy
**数据库接口**: pubmed, uniprot, chembl, clinvar, ensembl, opentargets, pdb, pubchem, kegg, string 等 30+ 数据库

---

## 16. SaaS 自动化集成 (Composio)

> 来自 ComposioHQ/awesome-claude-skills 的 900+ 集成

**通讯**: Slack, Discord, Telegram, WhatsApp, Microsoft Teams, Gmail, Outlook
**项目管理**: Jira, Asana, Trello, ClickUp, Monday, Linear, Basecamp, Wrike
**CRM**: Salesforce, HubSpot, Pipedrive, Zoho CRM, Close
**开发**: GitHub, GitLab, Bitbucket, Vercel, Render, CircleCI, Sentry, Datadog
**文档**: Notion, Confluence, Coda, Airtable, Google Sheets, Google Drive
**营销**: Mailchimp, SendGrid, Brevo, ActiveCampaign, ConvertKit, Klaviyo
**日历**: Google Calendar, Outlook Calendar, Cal.com, Calendly
**支付**: Stripe, Square
**设计**: Figma, Canva, Miro
**社交**: Twitter/X, LinkedIn, Instagram, TikTok, Reddit, YouTube
**HR**: BambooHR
**客服**: Zendesk, Freshdesk, Intercom, HelpDesk
**存储**: Dropbox, Box, OneDrive
**签名**: DocuSign
**自动化**: Make (Integromat)
**分析**: Google Analytics, Mixpanel, Amplitude, Segment, PostHog

---

## 17. 工作流 / 方法论

| 仓库 | 描述 | ⭐ |
|------|------|-----|
| [claude-code-router/claude-code-router](https://github.com/claude-code-router/claude-code-router) | 智能模型路由和工作流编排 | 27.8k |
| [vibe-kanban/vibe-kanban](https://github.com/vibe-kanban/vibe-kanban) | AI 驱动的看板工作流管理 | 21.2k |
| [SuperClaude/SuperClaude_Framework](https://github.com/SuperClaude/SuperClaude_Framework) | 超级 Claude 框架 (增强工作流和方法论) | 20.8k |
| [tukuaiai/vibe-coding-cn](https://github.com/tukuaiai/vibe-coding-cn) | Vibe Coding 指南 (提示词, 技能, 工作流) | 8.2k |
| [zebbern/claude-code-guide](https://github.com/zebbern/claude-code-guide) | Claude Code 设置、命令、工作流、代理、技能指南 | 3.4k |
| [ykdojo/claude-code-tips](https://github.com/ykdojo/claude-code-tips) | 45 个 Claude Code 使用技巧 | 2.8k |
| [gotalab/cc-sdd](https://github.com/gotalab/cc-sdd) | Spec-driven development 团队工作流 | 2.6k |
| [intellectronica/ruler](https://github.com/intellectronica/ruler) | 统一规则应用到所有编码代理 | 2.5k |
| [backnotprop/plannotator](https://github.com/backnotprop/plannotator) | 可视化标注和审查编码代理计划 | 1.9k |

---

## 18. GUI / 桌面客户端

| 仓库 | 描述 | ⭐ |
|------|------|-----|
| [CherryHQ/cherry-studio](https://github.com/CherryHQ/cherry-studio) | AI 生产力工作室 (智能聊天, 自主代理, 300+ 助手) | 39.8k |
| [code-yeongyu/oh-my-opencode](https://github.com/code-yeongyu/oh-my-opencode) | "The best agent harness" 编码代理配置框架 | 31.4k |
| [winfunc/opcode](https://github.com/winfunc/opcode) | 强大的 Claude Code GUI 应用 (自定义代理和会话管理) | 20.5k |
| [farion1231/cc-switch](https://github.com/farion1231/cc-switch) | 跨平台桌面一体化助手 (Claude Code, Codex, OpenCode, Gemini CLI) | 18.1k |
| [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi) | 免费本地开源 24/7 cowork (多 AI 编码工具) | 15.8k |
| [slopus/happy](https://github.com/slopus/happy) | Codex/Claude Code 移动和 Web 客户端 (实时语音 + 加密) | 11.9k |
| [siteboon/claudecodeui](https://github.com/siteboon/claudecodeui) | 远程管理 Claude Code 会话的 Web UI | 6.2k |
| [opactorai/Claudable](https://github.com/opactorai/Claudable) | 开源 web builder (本地 CLI 代理) | 3.7k |
| [op7418/CodePilot](https://github.com/op7418/CodePilot) | Claude Code 原生桌面 GUI (Electron + Next.js) | 1.8k |
| [tiann/hapi](https://github.com/tiann/hapi) | Claude Code/Codex/Gemini/OpenCode App (随时随地 vibe coding) | 1.5k |

---

## 19. Proxy / API 中继

| 仓库 | 描述 | ⭐ |
|------|------|-----|
| [router-for-me/CLIProxyAPI](https://github.com/router-for-me/CLIProxyAPI) | 将 Gemini CLI/Antigravity/Codex/Claude Code 包装为 OpenAI/Gemini 兼容 API | 10.6k |
| [Wei-Shaw/claude-relay-service](https://github.com/Wei-Shaw/claude-relay-service) | 自托管 Claude Code 镜像 (统一 API 中继) | 8.1k |
| [su-kaka/gcli2api](https://github.com/su-kaka/gcli2api) | GeminiCLI/Antigravity 转 OpenAI/Claude API | 3.8k |
| [badrisnarayanan/antigravity-claude-proxy](https://github.com/badrisnarayanan/antigravity-claude-proxy) | Antigravity 模型代理 for Claude Code | 2.8k |
| [Wei-Shaw/sub2api](https://github.com/Wei-Shaw/sub2api) | 一站式中继 (Claude, OpenAI, Gemini, Antigravity 订阅) | 1.7k |
| [ding113/claude-code-hub](https://github.com/ding113/claude-code-hub) | 现代 Claude Code & Codex API 代理 (负载均衡 + 使用统计) | 1.4k |

---

## 20. 指南 / 教程 / 参考

| 仓库 | 描述 | ⭐ |
|------|------|-----|
| [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) | Claude Code 配置和监控 CLI 工具 | 20.2k |
| [shareAI-lab/learn-claude-code](https://github.com/shareAI-lab/learn-claude-code) | "Bash is all you need" — 从 0 到 1 写一个 nano Claude Code | 17k |
| [Piebald-AI/claude-code-system-prompts](https://github.com/Piebald-AI/claude-code-system-prompts) | Claude Code 系统提示词、18 个内置工具描述、子代理提示词 | 4.5k |
| [zebbern/claude-code-guide](https://github.com/zebbern/claude-code-guide) | Claude Code 设置、命令、工作流、代理、技能指南 | 3.4k |
| [ykdojo/claude-code-tips](https://github.com/ykdojo/claude-code-tips) | 45 个 Claude Code 使用技巧 | 2.8k |
| [shanraisshan/claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice) | Claude Code 最佳实践 | 2.5k |
| [KhazP/vibe-coding-prompt-template](https://github.com/KhazP/vibe-coding-prompt-template) | Vibe Coding 提示词模板 (PRD, 技术设计, MVP) | 1.8k |
| [Njengah/claude-code-cheat-sheet](https://github.com/Njengah/claude-code-cheat-sheet) | Claude Code 终极速查表 | 1.3k |
| [wesammustafa/Claude-Code-Everything-You-Need-to-Know](https://github.com/wesammustafa/Claude-Code-Everything-You-Need-to-Know) | 一站式指南 (设置, 提示工程, 命令, hooks, 工作流) | 874 |

---

## 21. 其他工具

| 仓库 | 描述 | ⭐ |
|------|------|-----|
| [oraios/serena](https://github.com/oraios/serena) | 强大的编码代理工具包 (语义检索和编辑) | 20.2k |
| [steveyegge/beads](https://github.com/steveyegge/beads) | Beads — 编码代理的记忆升级 | 16.3k |
| [gsd-build/get-shit-done](https://github.com/gsd-build/get-shit-done) | 轻量级元提示和上下文工程系统 | 13.9k |
| [mcp-use/mcp-use](https://github.com/mcp-use/mcp-use) | 最简单的方式与 MCP 服务器交互 (自定义代理) | 9.2k |
| [xonsh/xonsh](https://github.com/xonsh/xonsh) | Python 驱动的 shell (AI 友好) | 9.2k |
| [qwibitai/nanoclaw](https://github.com/qwibitai/nanoclaw) | 轻量级 Clawdbot 替代 (Apple 容器) | 8.2k |
| [UfoMiao/zcf](https://github.com/UfoMiao/zcf) | Zero-Config Code Flow for Claude Code and Codex | 5.5k |
| [zilliztech/claude-context](https://github.com/zilliztech/claude-context) | 代码搜索 MCP (让整个代码库成为上下文) | 5.3k |
| [breaking-brake/cc-wf-studio](https://github.com/breaking-brake/cc-wf-studio) | CC Workflow Studio (VSCode 扩展) | 3.7k |
| [zgsm-ai/costrict](https://github.com/zgsm-ai/costrict) | 企业级严格 AI 编码器 (Agent + CodeReview) | 3.6k |
| [ComposioHQ/open-claude-cowork](https://github.com/ComposioHQ/open-claude-cowork) | 开源 Claude Cowork (500+ SaaS 集成) | 3k |
| [mindfold-ai/Trellis](https://github.com/mindfold-ai/Trellis) | All-in-one AI 框架 (Claude Code & Cursor) | 2.2k |
| [PeonPing/peon-ping](https://github.com/PeonPing/peon-ping) | Claude Code/Codex 语音通知 | 2k |
| [github/gh-aw](https://github.com/github/gh-aw) | GitHub Agentic Workflows | 2.3k |
| [superagent-ai/vibekit](https://github.com/superagent-ai/vibekit) | 在隔离沙箱中运行 Claude Code/Gemini/Codex (敏感数据脱敏) | 1.7k |
| [pchalasani/claude-code-tools](https://github.com/pchalasani/claude-code-tools) | Claude Code 实用生产力工具 | 1.4k |
| [doobidoo/mcp-memory-service](https://github.com/doobidoo/mcp-memory-service) | 自动上下文记忆 (不再每次重新解释项目) | 1.3k |
| [dbenn8/claude-slack](https://github.com/dbenn8/claude-slack) | Claude Code 双向 Slack 集成 | 18 |
| [claude-agent-sdk-demos/claude-agent-sdk-demos](https://github.com/claude-agent-sdk-demos/claude-agent-sdk-demos) | Claude Agent SDK 示例和演示 | 1.4k |
| [raptor-security/raptor](https://github.com/raptor-security/raptor) | AI 安全代理 (Claude Code 集成) | 1.1k |

---

## 统计摘要

| 类别 | 数量 |
|------|------|
| 官方资源 | 15 |
| Awesome 列表 / 策展集合 | 14 |
| Agent Skills 技能包 | 12+ |
| Subagents 子代理 | 5+ |
| Plugins 插件系统 | 7+ |
| Slash Commands | 4+ |
| Hooks 钩子 | 4+ |
| IDE 集成 | 7+ |
| Agent 编排 / 多代理 | 17+ |
| Status Lines | 1+ |
| 使用监控 | 2+ |
| CLAUDE.md 模板 | 5+ |
| GUI / 桌面客户端 | 10+ |
| Proxy / API 中继 | 6+ |
| 指南 / 教程 | 9+ |
| 安全/审计技能 | 15 (Trail of Bits) |
| 科学/研究技能 | 100+ (跨 30+ 数据库) |
| SaaS 自动化 | 900+ (Composio) |
| MCP 服务器 | 200+ (社区) + 7 (官方) |
| 其他工具 | 20+ |
| **总计** | **1,350+ 独立项目/技能** |

---

> 📌 本清单持续更新。主要参考源:
> - [awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) (23.7k ⭐)
> - [awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) (34.7k ⭐)
> - [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)
> - [MCP Registry](https://registry.modelcontextprotocol.io)
