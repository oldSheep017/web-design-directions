# Web Design Directions

做网页前，智能体先在聊天里用简短文字给出三套排版与视觉方案。每套都写清访客第一眼看到什么、下一步可以做什么，以及配色、字体、画面和控件怎么设计。你可以整套选，也可以组合不同方案的布局和风格。选定后再开始做页面。

适用于桌面网页、手机网页和响应式网站。设计方向从主要使用设备出发。

也可以保留现有布局，只比较几组配色。提案会写出色值、用法和各自适合的场景。[配色选择参考](references/color-palettes.md)

## 安装到 Codex

在要使用这个 Skill 的项目目录运行以下命令。

```sh
npx skills add oldSheep017/web-design-directions -a codex
```

如果已下载本仓库，可以从本地安装。将路径替换为解压后含有 `SKILL.md` 的目录。

```sh
npx skills add /path/to/web-design-directions -a codex
```

默认安装到当前项目。希望在自己的所有项目中使用时，可在命令末尾加 `-g`。[安装工具与运行要求](https://github.com/vercel-labs/skills#install-a-skill)

## 试一次

在 Codex 中输入：

> 用 $web-design-directions 帮我设计个人博客首页。我写项目复盘，也发日常随笔。很多读者用手机访问。

> 用 $web-design-directions 帮我设计桌面端的快递代收后台。店员主要用电脑录入包裹，峰值时要连续处理多条记录。

可以直接选一个方向，也可以用自己的话调整，例如“我喜欢打开就能读正文的方案，但希望老读者能从首屏找到文章索引”。[查看完整技能指令](SKILL.md)
