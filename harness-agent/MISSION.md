# Mission: Harness Agent（智能体运行时架构）

## Why
用户在工作中接触到 ZCode 与 Deepseek-Harness 两个高质量编码智能体（Harness Agent）仓库，想从纯小白起步，系统建立 Harness Agent 的完整概念地图，并最终能真正读懂这两个仓库的源码实现。

## Success looks like
- 能独立讲清 Agent Loop、工具系统、上下文管理、权限安全、子智能体、扩展机制这六大子系统的原理与相互关系
- 给出一个概念（如 compaction、tool dispatch），能在 ZCode / Deepseek-Harness 中定位到对应实现文件并读懂主流程
- 能完整描述一次用户请求在 harness 内部的生命周期（输入 → 组装上下文 → 模型调用 → 工具执行 → 最终回复）
- 能以此为基线，评估与讨论其他 Harness Agent（如 Claude Code、OpenCode）的设计取舍

## Constraints
- 纯小白起点：默认不了解 LLM API 细节与 agent 内部机制，从零讲起，尽可能全面
- 偏好手册式学习材料：静态 HTML、明/暗双模式、不花哨但优于 Markdown
- 实证参考：`D:\GitHub\ZCode` 与 `D:\GitHub\Deepseek-Harness`（本地仓库，概念落地的对照物）
- 教学语言：中文

## Out of scope
- LLM 模型训练 / 微调原理
- 从零实现一个产品级 harness（概念 + 读码为主；动手迷你实现可作后期选修）
- 前端 UI 层实现细节（只关注与 harness 运行时相关的部分）
