# 3. thedotmack/claude-mem

**URL:** [https://github.com/thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
**Stars:** 23700
**Language:** TypeScript
**Description:** 一个Claude Code插件，自动捕获Claude在编码会话中的所有操作，通过AI压缩并注入相关上下文到未来的会话中。

---
## Detailed Description

Claude-Mem是一个为Claude Code设计的插件，它能自动捕获Claude在编码会话中的所有操作，通过AI（使用Claude的agent-sdk）进行压缩，并将相关上下文注入到未来的会话中，从而实现跨会话的上下文持久化。

**核心功能与特性：**
*   **持久化记忆**：上下文在不同会话中得以保留。
*   **渐进式披露**：分层记忆检索，并显示token成本。
*   **基于技能的搜索**：通过mem-search技能查询项目历史。
*   **Web查看器UI**：在http://localhost:37777提供实时记忆流。
*   **Claude桌面技能**：从Claude桌面对话中搜索记忆。
*   **隐私控制**：使用<private>标签排除敏感内容。
*   **上下文配置**：对注入的上下文进行细粒度控制。
*   **自动化操作**：无需手动干预。
*   **引用**：通过ID引用过去的观察（可通过http://localhost:37777/api/observation/{id}访问或在web查看器中查看）。
*   **Beta通道**：尝试如“无尽模式”等实验性功能。

**工作原理：**
Claude-Mem通过自动捕获工具使用观察、生成语义摘要，并将其提供给未来的会话，从而无缝地在会话之间保留上下文。这使得Claude即使在会话结束或重新连接后，也能保持对项目的知识连续性。

**核心组件：**
1.  **5个生命周期钩子**：SessionStart, UserPromptSubmit, PostToolUse, Stop, SessionEnd。
2.  **智能安装**：缓存的依赖检查器。
3.  **工作服务**：在端口37777上提供HTTP API，包含web查看器UI和10个搜索端点，由Bun管理。
4.  **SQLite数据库**：存储会话、观察和摘要。
5.  **mem-search技能**：通过渐进式披露进行自然语言查询。
6.  **Chroma向量数据库**：用于智能上下文检索的混合语义+关键词搜索。

**MCP搜索工具：**
Claude-Mem通过4个MCP工具提供智能记忆搜索，遵循高效的3层工作流模式：
1.  `search`：获取带有ID的紧凑索引。
2.  `timeline`：获取围绕相关结果的时间顺序上下文。
3.  `get_observations`：仅获取过滤后的ID的完整详细信息。

## Tech Stack

主要编程语言：TypeScript (83.6%), JavaScript (12.5%), HTML (3.4%)
构建技术：Claude Agent SDK, Claude Code
系统要求：Node.js (18.0.0+), Claude Code (最新版), Bun, uv (Python包管理器), SQLite 3
数据库：SQLite, Chroma Vector Database
其他技术：AI, SQLite, Embeddings, Artificial-Intelligence, AI-Agents, Claude, Memory-Engine, Long-Term-Memory, RAG, Anthropic, ChromaDB, AI-Memory, Mem0, Claude-Code, Supermemory, Openmemory, Claude-Agents, Claude-Agent-SDK, Claude-Code-Plugin, Claude-Skills

## Use Cases

1.  **AI辅助编程**：为Claude Code用户提供持久化的编程上下文。
2.  **项目记忆管理**：自动记录和检索项目开发过程中的关键信息。
3.  **智能代码会话**：在不同编码会话之间保持知识连续性。
4.  **调试与问题排查**：通过记忆搜索和时间线功能快速定位问题。
5.  **知识库构建**：为AI代理构建和维护项目相关的长期记忆库。

## Screenshot

![Screenshot](./images/03_thedotmack_claude-mem.webp)
