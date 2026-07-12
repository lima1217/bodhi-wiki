# 更新日志

## 2026-07-13

- 摄取 `docs/bodhi-thesis.md` 为 `source-003`（固定文本 `full_text-20260713.txt`，106 行）。
- 新增 4 个概念（反预判策略、正方形哲学、体验优于逻辑、热闹大于整齐）、1 个框架（Bodhi 产品叙事框架）、3 个主张（v1 简陋是设计、v2 是叙事平台、自身建设窄切入）。
- glossary 增 6 条术语；questions 新增“叙事与历史”问题组；AGENTS.md、index.md 与各目录 index/log 同步指向 source-003。
- 注意：extractor 默认覆盖了 `metadata.json` 与 `full_text.txt`，已恢复为 source-001 状态。

## 2026-07-12

- Lint 全包后修复：补登 `source-002` 元数据（新增 `sources/metadata-002.json`）、修小节链 ch04-02→ch05-01 的不对称（`第04章-第02节` 的 `下一节` 改指 `第05章-第01节`）、收紧 concepts/frameworks/claims 共 16 个页面的 `chapter_refs` 到证据实际所在章。validator 正常与 strict 模式均通过。

## 2026-06-30

- 摄取补充材料“一座没有市长的城市”，新增 `source-002`、第05章、城市代币相关概念/框架/主张，并补充边界问题。
- 从 `https://bodhi.wtf/docs` 的 React 文档对象摄取中文文档。
- 生成固定来源 `sources/full_text-20260630.txt` 与 `sources/metadata.json`。
- 创建章节、小节、概念、框架、主张、术语和待解决问题页面。
- 执行 OKF validator 前的链接和 frontmatter 结构整理。
