# icon-library

图标存档（Archive of icons used across the site and kept for reuse）。

## xp-shell-1024/
118 张 **Windows XP 系统外壳图标**（我的电脑 / 我的文档 / 回收站 / 文件夹 / 网络 / 磁盘 / 附件 / 对话框 …），
原图 **1024×1024 透明 PNG**。

- 来源：`softwarehistorysociety/XPIcons`（XP 目录共 501 张）
- 许可：**公有领域（Unlicense）** — 可自由复制、修改、商用，无需署名
- 说明：页面实际渲染用的 16/32/48 尺寸在 `assets/xp/`；本目录是高清母版，方便以后放大或重出图

## devicon/
页面 `skills.html` 的技能图标（开发语言与工具），**按 devicon 原始目录结构存放**，可直接把 `DEV` 基址指到本地：

```
const DEV = "assets/icon-library/devicon/";
```

- 来源：devicon（`cdn.jsdelivr.net/gh/devicons/devicon`）
- 许可：MIT（图标各自归属其品牌，见 devicon 仓库）
- 内容：页面在用的 26 个 + 已筛选的 54 个候选（IDE / 语言 / 数据与 ML / 数据库与基础设施 / 前后端与构建 / 设计影像游戏 / 嵌入式）

## _replaced/
被替换下来的旧图标（保留以备回溯），例如原来 32×32 的**白底 Windows 旗标 favicon**。
