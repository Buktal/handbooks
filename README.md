# Handbooks

按主题整理的交互式 HTML 学习手册。每个主题一个目录，手册本体为目录内的 `index.html`，内容、样式、图标和交互全部内嵌，下载后即可离线阅读；目录中的 Markdown 文件是配套工作区材料。

## 手册目录

| 手册 | 内容 |
| --- | --- |
| [Harness Agent 全景手册](harness-agent/index.html) | 从零理解智能体运行时，覆盖 Agent Loop、工具系统、上下文管理、权限与安全、子智能体和扩展生态，并对照 ZCode 与 Deepseek-Harness 源码走读。 |

## 如何阅读

1. 进入手册目录，在 `index.html` 页面点击 **Download raw file**，下载 `.html` 文件。
2. 用现代浏览器打开下载的文件，无需安装依赖或启动服务。
3. 分享时直接发送对应的 `index.html` 文件即可。

Harness Agent 手册支持明暗主题、全文搜索、章节导航、阅读进度、代码复制和章节自测。按 `Ctrl K`（macOS 为 `⌘ K`）可以搜索。

## 新增手册

- 每个主题一个目录，目录名语义明确（例如 `harness-agent/`），手册本体固定为 `index.html`。
- `index.html` 保持自包含，不依赖外部样式、脚本、字体或图片，也不加载同目录的 Markdown 文件。
- 配套材料（`MISSION.md`、`NOTES.md`、`RESOURCES.md` 等）与手册同目录存放，仅作工作区参考。
- 在上方目录中补充链接与内容简介。
- 教学内容引用的原始资料在手册正文中注明。
