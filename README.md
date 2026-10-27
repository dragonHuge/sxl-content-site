# sxl-content-site

个人内容发布站。架构：**Obsidian 写作 → 标记 published → GitHub → 自动生成网页 → 自动部署**。

- 内容源：Obsidian 库 `~/ai-super-individual`（`02-输入/`、`03-学习/` 等）
- 内容协议：Frontmatter 字段 `published` / `category` / `parent` / `order`
- 生成器：Quartz v4（Obsidian 原生兼容）
- 部署：GitHub Pages（push 即自动构建）

## 状态

初始化骨架，待接入 Quartz 与内容同步脚本。
