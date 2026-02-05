# GitHub热门项目日报 (2026-02-05)

## 热门项目 Top 5

1. **openclaw/openclaw** (Stars: 164,812)
2. **nvm-sh/nvm** (Stars: 91,277)
3. **LadybirdBrowser/ladybird** (Stars: 58,325)
4. **microsoft/qlib** (Stars: 36,611)
5. **OpenBMB/ChatDev** (Stars: 30,100)

---

## 项目列表


Project 1: thedotmack/claude-mem
================================
Stars: 23,000 (+2,638 today)
Language: TypeScript
URL: https://github.com/thedotmack/claude-mem

Description:
A Claude Code plugin that automatically captures everything Claude does during your coding sessions, compresses it with AI (using Claude's agent-sdk), and injects relevant context back into future sessions.

Core Features:
- 🧠 Persistent Memory - Context survives across sessions
- 📊 Progressive Disclosure - Layered memory retrieval with token cost visibility
- 🔍 Skill-Based Search - Query your project history with mem-search skill
- 🖥️ Web Viewer UI - Real-time memory stream at http://localhost:37777
- 💻 Claude Desktop Skill - Search memory from Claude Desktop conversations
- 🔒 Privacy Control - Use <private> tags to exclude sensitive content from storage
- ⚙️ Context Configuration - Fine-grained control over what context gets injected
- 🤖 Automatic Operation - No manual intervention required
- 🔗 Citations - Reference past observations with IDs
- 🧪 Beta Channel - Try experimental features like Endless Mode via version switching

Technical Stack:
- TypeScript
- Bun (Worker Service)
- SQLite Database (sessions, observations, summaries)
- Chroma Vector Database (hybrid semantic + keyword search)
- HTTP API on port 37777
- 5 Lifecycle Hooks (SessionStart, UserPromptSubmit, PostToolUse, Stop, SessionEnd)
- MCP (Model Context Protocol) Tools

Use Cases:
- AI-powered coding sessions with persistent context
- Project history tracking and retrieval
- Intelligent memory search across coding sessions
- Context-aware development workflows
- Privacy-controlled session recording

Screenshot: ./images/01-claude-mem.webp


Project 2: openai/skills
================================
Stars: 3,900 (+746 today)
Language: Python (90.5%)
URL: https://github.com/openai/skills

Description:
Skills Catalog for Codex. Agent Skills are folders of instructions, scripts, and resources that AI agents can discover and use to perform at specific tasks. Write once, use everywhere.

Core Features:
- Agent Skills catalog for Codex
- Folders containing instructions, scripts, and resources
- Discoverable and reusable by AI agents
- Package capabilities for teams and individuals
- Repeatable task completion
- $skill-installer for easy installation
- Three categories: .system (auto-installed), curated, experimental

Technical Stack:
- Python (90.5%)
- Shell (4.8%)
- JavaScript (1.9%)
- Codex integration
- GitHub-based distribution

Use Cases:
- AI agent capability packaging
- Repeatable task automation
- Team collaboration on AI workflows
- Custom skill creation for Codex
- Standardized agent behaviors
- Enterprise AI agent deployment

Screenshot: ./images/02-openai-skills.webp


Project 3: disler/claude-code-hooks-mastery
================================
Stars: 2,500 (+47 today)
Language: Python (92.8%), TypeScript (7.2%)
URL: https://github.com/disler/claude-code-hooks-mastery

Description:
Master Claude Code Hooks - Quickly master how to use Claude Code hooks to add deterministic (or non-deterministic) control over Claude Code's behavior. Plus learn about Claude Code Sub-Agents, the powerful Meta-Agent, and Team-Based Validation with agent orchestration.

Core Features:
- Complete hook lifecycle coverage (13 hook events)
- Flow control & security through exit codes and structured JSON
- Prompt validation & enhancement
- Diverse output styles (HTML, Markdown, YAML, tables, minimalist)
- Dynamic status line display
- Sub-Agents (system prompt-driven task delegation)
- Team collaboration & validation
- Automated planning with /plan_w_team
- JSON logging for all hook events
- UV single-file script architecture
- TTS integration (ElevenLabs, OpenAI, pyttsx3)

Technical Stack:
- Python (92.8%)
- UV (single-file script architecture)
- JSON/YAML configuration
- TTS (ElevenLabs, OpenAI, pyttsx3)
- LLM APIs (OpenAI, Anthropic, Ollama)
- Code quality tools (Ruff, Typer)
- Regular expressions for validation
- Terminal status line scripts

Use Cases:
- AI behavior control and safety
- Prompt management and filtering
- Automated operations and monitoring
- Security auditing and permission tracking
- Multi-agent collaboration
- Development debugging
- Personalized customization
- Complex workflow orchestration
- Code quality assurance
- Extension and integration with other tools

Screenshot: ./images/03-claude-code-hooks-mastery.webp


Project 4: OpenBMB/ChatDev
================================
Stars: 30,100 (+227 today)
Language: Python (68.6%), Vue (29.1%), JavaScript (1.9%)
URL: https://github.com/OpenBMB/ChatDev

Description:
ChatDev 2.0: Dev All through LLM-powered Multi-Agent Collaboration. A Zero-Code Multi-Agent Platform for "Developing Everything". It empowers users to rapidly build and execute customized multi-agent systems through simple configuration.

Core Features:
- Zero-code multi-agent platform
- Simple configuration-based agent orchestration
- Pre-built workflow templates
- Support for various scenarios (data visualization, 3D generation, deep research)
- Virtual software company paradigm (CEO, CTO, Programmer agents)
- Automated software development lifecycle
- Multi-agent collaboration framework
- Batch execution API
- Frontend UI for workflow management
- MCP (Model Context Protocol) integration

Technical Stack:
- Python (68.6%) - Backend runtime and agent logic
- Vue (29.1%) - Frontend interface
- JavaScript (1.9%)
- LLM integration (OpenAI, Anthropic, etc.)
- YAML-based workflow configuration
- Schema registry for function definitions
- Server-client architecture

Use Cases:
- Automated software development
- Data visualization and analysis
- 3D content generation
- Game development
- Deep research and documentation
- Complex task orchestration
- Multi-agent collaboration scenarios
- Rapid prototyping without coding
- Enterprise automation workflows
- Educational AI agent demonstrations

Screenshot: ./images/04-chatdev.webp


Project 5: ankitects/anki
================================
Stars: 26,200 (+28 today)
Language: Rust (46.4%), Python (29.4%), Svelte (11.3%), TypeScript (11.1%)
URL: https://github.com/ankitects/anki

Description:
Anki is a smart spaced repetition flashcard program for efficient learning and memorization.

Core Features:
- Spaced repetition algorithm
- Smart flashcard management
- Cross-platform support (Desktop, Mobile, Web)
- Customizable card templates
- Rich media support (images, audio, video)
- Add-on ecosystem
- Sync across devices
- Statistics and progress tracking

Technical Stack:
- Rust (46.4%) - Core backend
- Python (29.4%) - Add-ons and scripting
- Svelte (11.3%) - Frontend UI
- TypeScript (11.1%)
- SCSS (1.0%)
- SQLite database

Use Cases:
- Language learning
- Medical education
- Exam preparation
- Knowledge retention
- Academic study
- Professional certification prep

Screenshot: ./images/05-anki.webp


Project 6: open-telemetry/opentelemetry-collector-contrib
================================
Stars: 4,365 (+3 today)
Language: Go
URL: https://github.com/open-telemetry/opentelemetry-collector-contrib

Description:
Contrib repository for the OpenTelemetry Collector - a vendor-agnostic implementation for receiving, processing and exporting telemetry data.

Core Features:
- Vendor-agnostic telemetry collection
- Multiple receivers, processors, and exporters
- Extensible architecture
- Support for traces, metrics, and logs
- High performance and scalability
- Community-contributed components

Technical Stack:
- Go
- OpenTelemetry Protocol (OTLP)
- gRPC and HTTP protocols
- Prometheus integration
- Jaeger integration

Use Cases:
- Observability infrastructure
- Distributed tracing
- Metrics collection and export
- Log aggregation
- Multi-vendor telemetry pipelines
- Cloud-native monitoring


Project 7: Canner/WrenAI
================================
Stars: 14,031 (+89 today)
Language: TypeScript
URL: https://github.com/Canner/WrenAI

Description:
⚡️ GenBI (Generative BI) queries any database in natural language, generates accurate SQL (Text-to-SQL), charts (Text-to-Chart), and AI-powered business intelligence in seconds.

Core Features:
- Natural language to SQL conversion
- Text-to-Chart generation
- AI-powered business intelligence
- Multi-database support
- Real-time query execution
- Interactive data visualization
- Semantic layer for data modeling

Technical Stack:
- TypeScript
- LLM integration (GPT, Claude)
- SQL query engine
- Chart.js / D3.js for visualization
- React frontend
- Node.js backend

Use Cases:
- Business intelligence without SQL knowledge
- Data exploration and analysis
- Self-service analytics
- Report generation
- Dashboard creation
- Data democratization


Project 8: pedramamini/Maestro
================================
Stars: 1,719 (+187 today)
Language: TypeScript
URL: https://github.com/pedramamini/Maestro

Description:
Agent Orchestration Command Center - a platform for managing and coordinating multiple AI agents.

Core Features:
- Multi-agent orchestration
- Command center interface
- Agent lifecycle management
- Task delegation and coordination
- Real-time monitoring
- Agent communication protocols

Technical Stack:
- TypeScript
- Node.js
- WebSocket for real-time communication
- React frontend
- Agent SDK integration

Use Cases:
- Multi-agent system management
- Complex task automation
- Agent coordination and collaboration
- Workflow orchestration
- Enterprise AI agent deployment


Project 9: nvm-sh/nvm
================================
Stars: 91,277 (+35 today)
Language: Shell
URL: https://github.com/nvm-sh/nvm

Description:
Node Version Manager - POSIX-compliant bash script to manage multiple active node.js versions.

Core Features:
- Multiple Node.js version management
- Easy version switching
- Per-project Node.js versions
- Simple installation
- Cross-platform support (Unix, macOS, WSL)
- .nvmrc file support

Technical Stack:
- Shell script (Bash)
- POSIX-compliant
- curl/wget for downloads

Use Cases:
- Node.js development
- Version compatibility testing
- Project-specific Node.js versions
- CI/CD pipelines
- Development environment management


Project 10: microsoft/qlib
================================
Stars: 36,611 (+83 today)
Language: Python
URL: https://github.com/microsoft/qlib

Description:
Qlib is an AI-oriented Quant investment platform that aims to use AI tech to empower Quant Research, from exploring ideas to implementing productions. Qlib supports diverse ML modeling paradigms, including supervised learning, market dynamics modeling, and RL.

Core Features:
- AI-oriented quantitative investment platform
- Diverse ML modeling paradigms
- Market dynamics modeling
- Reinforcement learning support
- RD-Agent for automated R&D
- Backtesting framework
- Data processing pipeline

Technical Stack:
- Python
- PyTorch / TensorFlow
- Pandas for data processing
- RL frameworks
- Time series analysis

Use Cases:
- Quantitative trading
- Financial market research
- AI-powered investment strategies
- Algorithmic trading
- Portfolio optimization
- Risk management


Project 11: LadybirdBrowser/ladybird
================================
Stars: 58,325 (+68 today)
Language: C++
URL: https://github.com/LadybirdBrowser/ladybird

Description:
Truly independent web browser built from scratch without using existing browser engines.

Core Features:
- Independent browser engine
- Built from scratch
- Standards-compliant HTML/CSS/JS
- No dependency on Chromium or WebKit
- Open source and community-driven
- Cross-platform support

Technical Stack:
- C++ (core engine)
- Custom rendering engine
- Custom JavaScript engine
- Custom HTML/CSS parser

Use Cases:
- Alternative web browser
- Browser engine research
- Web standards implementation
- Privacy-focused browsing
- Educational purposes


Project 12: likec4/likec4
================================
Stars: 1,547 (+29 today)
Language: TypeScript
URL: https://github.com/likec4/likec4

Description:
Visualize, collaborate, and evolve the software architecture with always actual and live diagrams from your code.

Core Features:
- Architecture diagrams from code
- Live and always up-to-date diagrams
- Collaboration features
- Version control integration
- Multiple diagram types
- Export capabilities

Technical Stack:
- TypeScript
- Diagram rendering libraries
- Code parsing and analysis
- Git integration

Use Cases:
- Software architecture documentation
- Team collaboration on architecture
- Architecture evolution tracking
- Code-to-diagram automation
- Technical documentation


Project 13: openclaw/openclaw
================================
Stars: 164,812 (+79,566 this week)
Language: TypeScript
URL: https://github.com/openclaw/openclaw

Description:
Your own personal AI assistant. Any OS. Any Platform. The lobster way. 🦞

Core Features:
- Personal AI assistant
- Cross-platform support
- Multi-OS compatibility
- Extensible architecture
- Privacy-focused
- Local-first approach

Technical Stack:
- TypeScript
- Electron or similar framework
- LLM integration
- Cross-platform APIs

Use Cases:
- Personal productivity
- Task automation
- Information retrieval
- Cross-platform AI assistance
- Privacy-conscious AI usage


Project 14: asgeirtj/system_prompts_leaks
================================
Stars: 30,151 (+4,301 this week)
Language: JavaScript
URL: https://github.com/asgeirtj/system_prompts_leaks

Description:
Collection of extracted System Prompts from popular chatbots like ChatGPT, Claude & Gemini.

Core Features:
- System prompt collection
- Multiple chatbot coverage
- Regular updates
- Community contributions
- Analysis and comparison

Technical Stack:
- JavaScript
- Markdown documentation
- Web scraping tools

Use Cases:
- Prompt engineering research
- AI behavior analysis
- Educational purposes
- Prompt optimization
- Chatbot comparison


Project 15: badlogic/pi-mono
================================
Stars: 6,795 (+3,554 this week)
Language: TypeScript
URL: https://github.com/badlogic/pi-mono

Description:
AI agent toolkit: coding agent CLI, unified LLM API, TUI & web UI libraries, Slack bot, vLLM pods.

Core Features:
- Coding agent CLI
- Unified LLM API
- TUI & web UI libraries
- Slack bot integration
- vLLM pods support
- Comprehensive agent toolkit

Technical Stack:
- TypeScript
- Node.js
- LLM API integrations
- Slack API
- Terminal UI libraries

Use Cases:
- AI agent development
- Coding assistance
- Team collaboration via Slack
- LLM application development
- Agent toolkit integration


Project 16: microsoft/BitNet
================================
Stars: 27,884 (+1,984 this week)
Language: Python
URL: https://github.com/microsoft/BitNet

Description:
Official inference framework for 1-bit LLMs - extreme quantization for efficient language models.

Core Features:
- 1-bit LLM inference
- Extreme model quantization
- High performance
- Memory efficient
- Compatible with popular models
- Optimized kernels

Technical Stack:
- Python
- PyTorch
- CUDA optimization
- Quantization algorithms
- Custom kernels

Use Cases:
- Edge device deployment
- Resource-constrained environments
- Cost-effective LLM inference
- Mobile AI applications
- IoT devices


Project 17: NevaMind-AI/memU
================================
Stars: 7,711 (+2,289 this week)
Language: Python
URL: https://github.com/NevaMind-AI/memU

Description:
Memory for 24/7 proactive agents like openclaw (moltbot, clawdbot).

Core Features:
- 24/7 agent memory
- Proactive agent support
- Long-term context retention
- Memory indexing and retrieval
- Integration with popular agents

Technical Stack:
- Python
- Vector databases
- Memory indexing systems
- Agent SDK integration

Use Cases:
- Persistent agent memory
- Long-running AI assistants
- Context-aware agents
- Proactive AI systems
- Agent memory management


Project 18: VectifyAI/PageIndex
================================
Stars: 13,362 (+2,845 this week)
Language: Python
URL: https://github.com/VectifyAI/PageIndex

Description:
📑 PageIndex: Document Index for Vectorless, Reasoning-based RAG.

Core Features:
- Vectorless RAG approach
- Reasoning-based retrieval
- Document indexing
- Efficient search
- No vector embeddings required
- LLM-powered retrieval

Technical Stack:
- Python
- LLM integration
- Document processing
- Indexing algorithms

Use Cases:
- Document retrieval
- RAG applications without vectors
- Knowledge base search
- Reasoning-based QA
- Efficient document indexing


---

## 趋势分析

本次日报揭示了AI领域的持续火热，特别是以大型语言模型（LLM）为核心的智能体（Agent）和AI辅助开发工具成为焦点。具体趋势如下：

- **AI智能体与多智能体系统**：多个项目如 `openclaw/openclaw`、`OpenBMB/ChatDev`、`pedramamini/Maestro` 均专注于AI智能体的开发与协同，显示出从单一模型应用向复杂任务处理的多智能体系统演进的趋势。
- **AI驱动的开发工具**：`thedotmack/claude-mem`、`disler/claude-code-hooks-mastery`、`badlogic/pi-mono` 等项目，致力于通过AI技术增强开发工作流，例如代码记忆、钩子机制、统一API等，旨在提升开发者效率。
- **模型量化与高效推理**：`microsoft/BitNet` 项目专注于1-bit LLM的推理框架，代表了业界在保证模型性能的同时，对降低模型部署成本和能耗的持续探索。
- **RAG技术的演进**：`VectifyAI/PageIndex` 提出的无向量、基于推理的RAG方案，预示着信息检索和生成领域的范式革新，可能降低对向量数据库的依赖。
- **编程语言分布**：**Python** 和 **TypeScript** 依然是AI和Web开发领域的主流语言，占据了本次热门榜单的大部分席位。

## 分类统计

| 分类 | 项目数量 | 代表项目 |
| :--- | :--- | :--- |
| **AI/ML** | 13 | `openclaw/openclaw`, `OpenBMB/ChatDev`, `microsoft/BitNet` |
| **开发者工具** | 3 | `nvm-sh/nvm`, `open-telemetry/opentelemetry-collector-contrib`, `likec4/likec4` |
| **Web浏览器** | 1 | `LadybirdBrowser/ladybird` |
| **学习工具** | 1 | `ankitects/anki` |

` |
