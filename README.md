# Stop Slop · 中英双语版

一个用于起草、润色和审阅中英文文章的 Agent Skill。支持从口述或笔记整理成稿，也能只诊断已有稿件。编辑时保留事实、证据强度、作者语气和文体。

安装到 Codex 的用户级 Skills 目录，或用 Agent Skills CLI 选择目标客户端。

```sh
npx skills add blacksheep81/stop-slop --skill stop-slop
```

用法示例

- 用 stop-slop 润色这篇中文博客，保留我的语气和观点。
- 先用 stop-slop 审阅这份英文草稿，指出三处最影响阅读的地方。
- 用我的口述笔记整理大纲，确认重点后再成稿。

## 来源与许可

- 英文参考保留自 [Hardik Pandya 的 Stop Slop](https://github.com/hardikpandya/stop-slop)，原 MIT 许可见 [LICENSE](LICENSE)。本版重写入口，保留同名调用方式。
- 中文编辑约束参考 [歸藏的 Humanizer-zh](https://github.com/op7418/Humanizer-zh)，许可见 [Humanizer-zh MIT](licenses/Humanizer-zh-MIT.txt)。中文表格和例子为本版整理。
- [躺平的实验文章](https://x.com/lieflat_3/status/2118355780474937831)提供了诊断思路。关联项目 [lieflat-less-ai-tone](https://github.com/larashero3-dotcom/lieflat-less-ai-tone)采用 CC BY-NC 4.0，本仓库未分发其脚本、语料或规则原文。
- [Lonely__MH 的写作流程](https://x.com/lonely__mh/status/2118319043388309704)提供了从口述、确认大纲到成稿的工作思路。

该 Skill 评审文本表达，不鉴定作者身份或预测检测器结果。
