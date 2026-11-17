# 主权思维训练 (`sovereign-mind`)

一个专为 **逻辑推演、前提假设探讨、历史背景对照与极端场景训练** 打造的 Antigravity 插件，灵感来自 William Rees-Mogg 与 James Dale Davidson 的《主权个人》（*The Sovereign Individual*）与《血流成河》（*Blood in the Streets*）。

它不讲晦涩难懂的金融黑话，也不用填鸭式说教，而是用**简单直白的大白话**做你的苏格拉底式陪练：先定好前提假设，让你自己顺着利益和约束往下推，再帮你找逻辑漏洞、补充历史背景，并在需要时配合交互式 UI 卡片把推演过程可视化。

## 包含模块

- **假设推演训练 (`deductive-drill`)**：围绕技术、货币、规则变化设定极端前提，训练你推演“谁最先受影响 -> 第二步、第三步连锁反应 -> 大家容易看错什么”。
- **历史对照实验室 (`historical-parallel`)**：支持**历史拐点盲测**（隐去结局让你先判断）、**古今对比体检**（找相似更找不同）以及**随时科普历史背景**。
- **观点压力测试 (`thesis-stress-test`)**：把你自己的观点理顺后，从各方真实利益、半路卡死风险和历史反例三个方向“撞一撞”，帮你找到最薄弱的一环。
- **轻量激活规则 (`rules/AGENTS.md`)**：只在你聊逻辑训练、历史周期或前提推演时启动陪练模式，不打扰日常写代码。

## 本地安装

将本仓库软链接（或克隆）到 `~/.gemini/config/plugins/sovereign-mind`：

```bash
ln -s /Users/xinlongyi/Documents/Github/sovereign-mind ~/.gemini/config/plugins/sovereign-mind
```

在其他电脑上从 GitHub 安装：

```bash
git clone https://github.com/<你的用户名>/sovereign-mind.git ~/.gemini/config/plugins/sovereign-mind
```

安装后 Antigravity 会自动发现并加载，你也可以在 Antigravity 的 **Customizations / Plugins** 页面随时开启或关闭。

## 试试这样开始

- *“给我定一个前提假设，带我做一轮极端推演。”*
- *“用历史上的真实拐点考考我，先别告诉我结局。”*
- *“我对这段历史背景很好奇，能用大白话讲讲当时发生了什么吗？”*
- *“帮我挑挑这个观点的毛病：[你的观点]。”*
- *“打开一个交互式推演面板，带我一步步拆解。”*
