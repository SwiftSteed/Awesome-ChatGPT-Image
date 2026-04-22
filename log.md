# 工作日志

## 2026-04-22 12:33 — README 改造为中英文双版

**总结**：将单一中文混合版 `README.md` 改造为 GitHub Awesome 系列常见的中英文双版结构。

**改动**：
- `README.md`：改为英文主版，顶部加语言切换行 `**English** | [简体中文](./README.zh-CN.md)`。
- `README.zh-CN.md`：新建中文版，顶部加语言切换行 `[English](./README.md) | **简体中文**`。
- 两个版本内容结构完全对齐（标题 / tagline / 提示词库章节 / 列表项）。
- 列表项链接文本 `PythagoreanTheorem（勾股定理图解）` 保持原样，两版共用（文件本身是中文详情页）。

**设计选择**：
- 采用 GitHub 国际化项目的约定俗成：`README.md` 默认英文（国际受众友好），`README.zh-CN.md` 使用 IETF BCP 47 语言标签作为后缀。
- 当前语言用 `**粗体**` 标识，另一语言用链接，视觉上一眼可辨。
