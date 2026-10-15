# Harness Agent Resources

> 本手册/课程的知识来源。概念讲解优先引用这里的高可信来源，仓库级事实以本地源码走读为准。

## Knowledge

- [Article: "Building Effective Agents" — Anthropic](https://www.anthropic.com/engineering/building-effective-agents)
  智能体设计的权威入门：workflow 与 agent 的区分、常见编排模式、何时不要用 agent。用于：设计模式与术语的基准参照（手册第 1、7 章）。
- [Article: "What is an agent harness?" — Parallel](https://parallel.ai/articles/what-is-an-agent-harness)
  简明定义 harness：「包裹模型、运行工具/记忆/编排的那一层；同一个模型，不同的 harness，不同的结果」。用于：入门第一读（手册第 1 章）。
- [Article: "The Anatomy of an Agent Harness" — LangChain Blog](https://www.langchain.com/blog/the-anatomy-of-an-agent-harness)
  harness 组件解剖：文件系统、沙箱、记忆等核心组成。用于：组件清单的交叉验证。
- [Article: "The Evolution of the Agent Harness" — Latent Space (Dan McAteer)](https://www.latent.space/p/attention-interface)
  harness 概念的演化史：为什么 harness 成为独立的工程学科。用于：建立大局观（手册第 1 章）。
- [Article: "Extreme Harness Engineering for Token Billionaires" — Latent Space](https://www.latent.space/p/harness-eng)
  大规模 harness 工程实践：环境设计、代码不可见区域等。用于：进阶阅读（学完手册后）。
- [Docs: Model Context Protocol](https://modelcontextprotocol.io)
  MCP 官方文档。用于：手册第 8 章扩展生态的权威依据。
- [Article: "How to Build an Agent" — Thorsten Ball (Amp)](https://ampcode.com/notes/how-to-build-an-agent)
  几百行代码写出一个能改代码的智能体（"The Emperor Has No Clothes"）——agents 不是魔法的最佳佐证。用于：手册第 3 章的第一推荐延伸阅读、后期动手选修。
- [Workshop: "how to build a coding agent" — Geoffrey Huntley](https://ghuntley.com/agent)
  免费上机工坊，围绕 agent 核心循环展开。用于：后期动手选修。

## Wisdom (Communities)

- [Latent Space Discord](https://latent.space/about)
  AI 工程师社区，harness / agent 工程讨论最集中的中文可参与英文社区。用于：设计取舍的实战讨论。
- Anthropic Discord（Claude Code / Claude Developers 频道）
  Claude Code 用户与开发者的实战讨论。用于：对照商业 harness 的行为细节。

## Gaps

- 中文世界缺少系统性的 harness 教材 —— 本手册（`index.html`，工作区根目录入口）正是为此而写。
- ZCode 与 Deepseek-Harness 均无公开官方文档，仓库级知识只能靠本地源码走读获得（手册第 9、10 章）。
- 待补：两仓库各自的 issue/内部文档渠道（如存在），由用户在学习过程中补充。
