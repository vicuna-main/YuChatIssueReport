# ✨ YuChat Issue Report | 问题反馈处 ✨

<p align="center">
  <strong>💬 为 Minecraft Java 版服务器打造的跨版本聊天称呼与昵称显示插件</strong><br>
  <em>Cross-version chat title, nickname, and display plugin for Minecraft: Java Edition Servers</em>
</p>

---

## 🇨🇳 中文版

### 📌 问题反馈处
若您在使用 **YuChat** 过程中遇到任何问题、Bug、兼容性异常或功能建议，请在此处提交反馈。  
> ✨ **格式完整、内容详实** 的反馈将会获得 **优先处理**！  
感谢您的支持与理解，每一份反馈都是让插件变得更好的动力 ❤️

### 🧩 插件简介
**YuChat** 是一款围绕“聊天展示、称呼与昵称个性化”打造的 Bukkit 插件，支持多称呼激活、昵称唯一校验、RGB / 渐变 / 彩虹渲染、聊天格式、TAB、头顶名、加入 / 退出 / 死亡消息、个性签名、LuckPerms 前后缀读取、PlaceholderAPI 变量、Vault / PlayerPoints 支付、SQLite / MySQL 存储与 GUI 管理等功能。它适合生存服、RPG 服、社交服、会员体系服务器以及需要统一聊天展示风格的服务器使用。

### ✨ 核心能力
- `/yuchat` 主命令，别名 `/yc`、`/chat`
- 玩家 GUI：称呼、昵称、颜色、格式、个性签名与死亡消息设置
- 管理员 GUI：称呼创建、经济配置、LuckPerms 显示配置等入口
- 多称呼同时激活，显示顺序按玩家激活顺序排列
- RGB、渐变、彩虹与 MiniMessage 风格标签，低版本自动降级
- 聊天、TAB、头顶名、加入 / 退出 / 死亡消息统一展示
- 支持 PlaceholderAPI 变量与 LuckPerms 前后缀 / meta 读取
- Vault / PlayerPoints 支付，支持 none / vault / playerpoints / both / either 模式
- SQLite / MySQL 存储、授权过期清理、配置热重载

### 🛠️ 兼容性说明
YuChat 基于 **Spigot 1.8 API** 设计，目标运行兼容 **Minecraft 1.8 - 1.21.x**，并会在 1.16+ 使用 Hex / RGB 显示，在 1.8 - 1.15 自动降级为 legacy 颜色。

支持的服务端核心包括但不限于：

- Paper
- Spigot
- Paper 衍生核心
- Youer
- Arclight
- Mohist
- 其他 Bukkit / Spigot / Paper 系服务端核心

可选联动：**PlaceholderAPI、LuckPerms、Vault、PlayerPoints**。如遇兼容性问题，请在 QQ 群或 Issues 内反馈，并尽量附带服务端核心、Minecraft 版本、插件版本、相关联动插件版本、报错日志与复现步骤。

### 🔗 官方链接
- 💬 **插件 QQ 交流群**：[点击加入](https://qm.qq.com/q/CihYemKufS)
- 📚 **插件 Wiki / 使用文档**：[YuPluginHub](https://vicuna-main.github.io/YuPluginHub/)
- 🐛 **Bug 与建议反馈**：[GitHub Issues](https://github.com/vicuna-main/YuChatIssueReport)
- ☕ **高级版本赞助**：[爱发电支持](https://afdian.com/item/5913558252bc11f1a1e15254001e7c00)

> ⚠️ 免费版本仅供体验与基础使用，不承诺提供免费定制支持。

### 📝 反馈建议格式
为了更快定位问题，提交反馈时建议包含以下信息：

```text
插件版本：
服务端核心：
Minecraft 版本：
是否为混合端：
是否安装 PlaceholderAPI / LuckPerms / Vault / PlayerPoints：
数据库类型（SQLite/MySQL）：
聊天显示模式或相关配置：
问题描述：
复现步骤：
完整报错日志：
截图或视频：
```

### 🧾 使用此插件的服务器信息
> 欢迎已安装 YuChat 的服主在此登记您的服务器～  
> 每条信息请包含：服务器名称、地址、QQ群（若有）、官网（若有）、版本。

| 服务器名称 | 服务器地址 | 服务器 QQ 群 | 官网 | 版本 |
|-----------|------------|--------------|------|------|
| 宇钛纪元 | mc.yutay.cn | 1011284597 | 待补充 | 1.21.1 |

---

## 🇬🇧 English Version

### 📌 Issue Tracker
If you encounter any issues, bugs, compatibility problems, or have suggestions while using **YuChat**, please submit your feedback here.  
> ✨ **Well-formatted and detailed reports** will be **prioritized**!  
Thank you for your support and understanding. Every report helps make the plugin better ❤️

### 🧩 Plugin Introduction
**YuChat** is a Bukkit plugin built around chat display, titles, and nickname personalization. It supports multiple active titles, nickname uniqueness checks, RGB / gradient / rainbow rendering, chat formats, TAB names, nameplates, join / quit / death messages, personal signatures, LuckPerms prefix / suffix reading, PlaceholderAPI placeholders, Vault / PlayerPoints payments, SQLite / MySQL storage, and GUI management. It is suitable for survival, RPG, social, rank-based, and display-focused servers.

### ✨ Core Features
- `/yuchat` main command with `/yc` and `/chat` aliases
- Player GUI for titles, nicknames, colors, formats, signatures, and death messages
- Admin GUI for title creation, economy settings, and LuckPerms display settings
- Multiple active titles with player-defined activation order
- RGB, gradient, rainbow, and MiniMessage-style tags with legacy fallback
- Unified chat, TAB, nameplate, join / quit / death message display
- PlaceholderAPI variables and LuckPerms prefix / suffix / meta integration
- Vault / PlayerPoints payments with none / vault / playerpoints / both / either modes
- SQLite / MySQL storage, authorization expiration cleanup, and config reload

### 🛠️ Compatibility
YuChat is built on the **Spigot 1.8 API** and targets **Minecraft 1.8 - 1.21.x** runtime compatibility. It uses Hex / RGB colors on 1.16+ and automatically falls back to legacy colors on 1.8 - 1.15.

Supported server cores include but are not limited to:

- Paper
- Spigot
- Paper forks
- Youer
- Arclight
- Mohist
- Other Bukkit / Spigot / Paper-based server cores

Optional integrations: **PlaceholderAPI, LuckPerms, Vault, PlayerPoints**. If you encounter compatibility issues, please report them in the QQ group or GitHub Issues and include your server core, Minecraft version, plugin version, hook plugin versions, error logs, and reproduction steps whenever possible.

### 🔗 Official Links
- 💬 **Plugin QQ Group**: [Click to join](https://qm.qq.com/q/CihYemKufS)
- 📚 **Plugin Wiki / Documentation**: [YuPluginHub](https://vicuna-main.github.io/YuPluginHub/)
- 🐛 **Bug Reports & Suggestions**: [GitHub Issues](https://github.com/vicuna-main/YuChatIssueReport)
- ☕ **Sponsor Advanced Version**: [Support via AiFaDian](https://afdian.com/item/5913558252bc11f1a1e15254001e7c00)

> ⚠️ The free version is for basic use and testing only. Free custom support is not guaranteed.

### 📝 Suggested Report Format
To help us locate issues faster, please include the following information when submitting feedback:

```text
Plugin version:
Server core:
Minecraft version:
Hybrid server or not:
PlaceholderAPI / LuckPerms / Vault / PlayerPoints installed:
Database type (SQLite/MySQL):
Chat display mode or related config:
Issue description:
Steps to reproduce:
Full error log:
Screenshots or videos:
```

### 🧾 Server Information Using This Plugin
> Server owners using YuChat are welcome to register their servers here.  
> Each entry should include: server name, address, QQ group if available, website if available, and version.

| Server Name | Server Address | Server QQ Group | Website | Version |
|-------------|----------------|-----------------|---------|---------|
| Yutay Era | mc.yutay.cn | 1011284597 | To be added | 1.21.1 |

---

<p align="center">
  <sub>Made with ❤️ for the Minecraft community</sub>
</p>
