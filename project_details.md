# GitHub Trending Projects - Detailed Information
# Collection Date: 2026-02-07

## Project 1: openai/skills

**基本信息**
- 仓库地址: https://github.com/openai/skills
- Star数: 4,864
- Fork数: 279
- 编程语言: Python (90.1%), Shell (5.0%), JavaScript (1.9%)
- 今日新增Star: 279

**项目描述**

Agent Skills是一个包含指令、脚本和资源的文件夹集合，AI代理可以发现并使用这些技能来完成特定任务。该项目的核心理念是"编写一次，到处使用"（Write once, use everywhere）。OpenAI的Codex使用这些技能来帮助团队和个人以可重复的方式完成特定任务。

**核心特性**

1. **技能目录管理**: 提供了系统级（.system）、精选（curated）和实验性（experimental）三个层级的技能目录
2. **技能安装器**: 内置$skill-installer工具，可以通过名称或GitHub URL安装技能
3. **Codex集成**: 与OpenAI Codex深度集成，自动安装系统级技能
4. **开放标准**: 遵循Agent Skills开放标准，支持跨平台使用
5. **社区贡献**: 支持自定义技能创建和贡献

**技术栈**

- Python: 主要开发语言，占比90.1%
- Shell脚本: 用于自动化任务
- JavaScript: 部分功能实现
- GitHub Actions: CI/CD自动化

**适用场景**

1. **AI代理开发**: 为AI代理提供可复用的技能模块
2. **Codex用户**: OpenAI Codex用户可直接使用这些预定义技能
3. **团队协作**: 团队可以创建和共享自定义技能，提高工作效率
4. **自动化任务**: 通过技能封装实现复杂任务的自动化执行
5. **技能标准化**: 建立统一的AI代理技能标准和最佳实践

**安装使用**

系统技能会自动安装在最新版Codex中。精选和实验性技能可通过以下方式安装：

```bash
# 安装精选技能（按名称）
$skill-installer gh-address-comments

# 安装实验性技能（指定文件夹）
$skill-installer install the create-plan skill from the .experimental folder

# 通过GitHub URL安装
$skill-installer install https://github.com/openai/skills/tree/main/skills/.experimental/create-plan
```

**项目亮点**

- OpenAI官方维护的技能目录
- 16位贡献者活跃参与
- 支持自定义技能创建和分发
- 完善的文档和使用指南
- 与Codex无缝集成

---

## Project 2: bytedance/UI-TARS-desktop

**基本信息**
- 仓库地址: https://github.com/bytedance/UI-TARS-desktop
- Star数: 27,113
- Fork数: 2,642
- 编程语言: TypeScript (89.0%), MDX (8.3%), JavaScript (1.1%)
- 今日新增Star: 573
- 最新版本: v0.3.0

**项目描述**

TARS是一个开源的多模态AI代理技术栈，由字节跳动开发。该项目包含两个核心产品：**Agent TARS**（通用多模态AI代理栈）和**UI-TARS Desktop**（原生GUI代理桌面应用）。Agent TARS将GUI代理和视觉能力带入终端、计算机、浏览器和产品中，通过前沿的多模态大语言模型和与各种现实世界MCP工具的无缝集成，提供更接近人类任务完成方式的工作流程。

**核心特性**

1. **一键开箱即用CLI**: 支持有界面的Web UI和无界面的服务器执行模式
2. **混合浏览器代理**: 可使用GUI代理、DOM或混合策略控制浏览器
3. **事件流驱动**: 基于协议的事件流驱动上下文工程和代理UI
4. **MCP集成**: 内核基于MCP构建，支持挂载MCP服务器连接现实世界工具
5. **自然语言控制**: 由视觉-语言模型驱动的自然语言控制
6. **跨平台支持**: 支持Windows/MacOS/浏览器多平台
7. **本地/远程操作**: 支持本地和远程计算机及浏览器操作
8. **隐私安全**: 完全本地处理，保护用户隐私

**技术栈**

- TypeScript: 主要开发语言，占比89%
- MDX: 文档和内容管理，占比8.3%
- Node.js: 运行环境（要求>=22版本）
- MCP (Model Context Protocol): 工具集成协议
- Vision-Language Models: UI-TARS、Seed-1.5-VL/1.6系列模型
- 支持多种AI提供商: Anthropic Claude、Volcengine Doubao等

**适用场景**

1. **自动化任务执行**: 通过自然语言指令完成复杂的计算机操作任务
2. **浏览器自动化**: 自动化网页操作，如预订机票、酒店等
3. **桌面应用控制**: 通过自然语言控制桌面应用程序（如VS Code配置）
4. **远程操作**: 远程控制计算机和浏览器，无需配置
5. **开发者工具**: 为开发者提供GUI自动化工具包
6. **企业级应用**: 构建企业级AI代理解决方案

**安装使用**

Agent TARS CLI快速启动：

```bash
# 使用npx启动
npx @agent-tars/cli@latest

# 全局安装（需要Node.js >= 22）
npm install @agent-tars/cli@latest -g

# 使用指定模型提供商运行
agent-tars --provider volcengine --model doubao-1-5-thinking-vision-pro-250428 --apiKey your-api-key
agent-tars --provider anthropic --model claude-3-7-sonnet-latest --apiKey your-api-key
```

**项目亮点**

- 字节跳动官方开源项目
- 45位贡献者活跃参与
- 完善的文档和教程体系
- 支持多种前沿AI模型
- 活跃的社区支持（Discord、GitHub Discussions）
- 已发布38个版本，持续迭代更新
- 提供丰富的使用案例和演示视频
- 支持流式输出和实时反馈
- 独家支持AIO agent Sandbox隔离执行环境

**相关论文**

Qin, Yujia, et al. "UI-TARS: Pioneering Automated GUI Interaction with Native Agents." arXiv preprint arXiv:2501.12326 (2025).

---

