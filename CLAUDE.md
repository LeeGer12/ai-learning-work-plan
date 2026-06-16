# AI Learning 工作区规范

## 目录结构与用途

```
Work Plan/
├── AGENTS.md       # 项目开发路线与计划
├── CLAUDE.md       # 工作区规范（本文件）
├── docs/           # 产品文档、技术文档、需求说明
├── assets/         # 视觉素材
│   ├── design/     # 设计稿、UI 图、布局图
│   ├── bug/        # Bug 截图、问题复现图
│   └── reference/  # 参考素材、灵感图、竞品截图
├── notes/          # 学习笔记、知识总结、踩坑记录
└── code/           # 独立代码项目、实验代码、脚本
```

## 文件归属规则

| 内容类型 | 放哪里 | 命名建议 |
|---------|--------|---------|
| 产品/技术文档 | `docs/` | `YYYY-MM-DD_主题.md` |
| 设计稿、UI 图 | `assets/design/` | 项目名_版本_日期.png |
| Bug 截图 | `assets/bug/` | bug-简述_日期.png |
| 参考/灵感图 | `assets/reference/` | 来源_关键词.png |
| 学习笔记 | `notes/` | `YYYY-MM-DD_主题.md` |
| 代码项目 | `code/项目名/` | 按项目独立目录 |

## 注意事项

- 根目录不再直接放散落的图片，已有的暂时保留
- 新截图/素材按类型放入 `assets/` 对应子目录
- `notes/` 记录学习过程中的新知识、踩坑经验
- `docs/` 放成品文档，草稿也在 docs 但用 `draft-` 前缀
