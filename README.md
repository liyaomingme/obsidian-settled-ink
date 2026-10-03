# Settled Ink · 宿墨

**A calm paper theme for Obsidian — porcelain white in light, settled ink in dark. Mobile friendly.**
**宿墨是一方安静的墨:浅色如瓷白纸面,白纸黑字;深色如宿墨夜读,墨底粉白。手机端优先打磨。**

![Settled Ink light](screenshot.png)

## 特性 / Features

- 🀄 **双模式 / Dual mode** — 瓷白浅色(porcelain paper)+ 宿墨深色(settled ink),两套完整调色板
- 📱 **手机优先 / Mobile first** — 触控目标加高、按压态替代悬停态、顶栏与工具栏纸面色一致、移动端去重投影
- 🖋 **纸感排版 / Paper typography** — 正文用宋体系衬线(回退 Georgia),行距 1.78,手机长文更透气
- 🎨 **令牌化 / Tokenized** — 全部颜色经由 `--pp-*` 令牌层映射到官方 CSS 变量,浅深模式各一处定义,改色一处生效
- 🖌 **落款蓝线 / Signature line** — 一级标题下的一根雾蓝短线,全篇唯一的强调装饰

## 安装 / Install

在 Obsidian 中:**设置 → 外观 → 主题 → 管理 → 社区主题**,搜索 "Settled Ink" 安装;
或从本仓库下载 `theme.css` 与 `manifest.json`,放入库的 `.obsidian/themes/Settled Ink/` 文件夹。

In Obsidian: open **Settings → Appearance → Themes → Manage → Community themes**, search for "Settled Ink", and install. You can also grab `theme.css` and `manifest.json` from this repository into `.obsidian/themes/Settled Ink/` of your vault.

## 手机端 / Mobile

主题同样适用于 iOS / Android 版 Obsidian:移动端导航栏、键盘工具栏、抽屉侧栏均已适配,建议手机上同时试浅色与深色两种外观。

Works on Obsidian for iOS and Android: mobile navbar, keyboard toolbar and side drawer are all styled. Try both light and dark modes on your phone.

## 设计基调 / Design notes

| 模式 | 底色 | 正文 | 强调 |
|---|---|---|---|
| Light · 瓷白 | `#F8F6F1` | `#33363B` | 雾蓝 `#3C5AA6` |
| Dark · 宿墨 | `#1C1E21` | `#D8D5CE` | 雾蓝 `#7B93BE` |

界面字体保持系统默认,阅读字体用衬线;如果你偏好无衬线正文,在 外观 设置中单独覆盖字体即可。

## License

[MIT](LICENSE) · Author **Qilinora** ([@liyaomingme](https://github.com/liyaomingme))
