# 更新日志

## 2026-07-13

- 摄取 `luyao回答用户提问.md` 为 `source-005`（固定文本 `full_text-20260713-3.txt`，41 行）。
- 新增 2 个概念（低成本发币的监管模糊性、创建者与代币关系模糊化）、1 个框架（责任形态演进框架）、2 个主张（发项目理论上等于发币、模糊关系是历史进程的一部分）。
- 补强 `代币即无工资公司`（“每天创建一家公司”）；glossary 增 5 条术语；questions 新增“监管与责任形态”组；AGENTS.md、index.md 与各目录 index/log 同步指向 source-005。
- 注意：extractor `--pkg` 仍会覆盖根 `metadata.json` 与 `full_text.txt`，先备份再恢复为 source-001 状态。
- 摄取 `bodhi创建者回答用户提问-20260713.md` 为 `source-004`（固定文本 `full_text-20260713-2.txt`，61 行）。
- 新增 2 个概念（两种盒子模型、市场驱动可信度）、2 个主张（Virtual Foundation 是 v0 机制、悬赏任务是未实现的规划）。
- 补强 4 个已有页：机制简化演进框架（三代演进+弃用原因）、小型贡献市场（为什么是这种形态）、行动给币机制框架（无验收人）、ch02-04 机制演变小节。
- glossary 增 7 条术语（virtual foundation、任务/悬赏、Moloch DAO、两种盒子、悬赏任务未实现、市场驱动可信度）；questions 新增“机制演进与悬赏任务”“验证机制”两组；AGENTS.md、index.md 与各目录 index/log 同步指向 source-004。
- 注意：extractor `--pkg` 仍会覆盖根 `metadata.json` 与 `full_text.txt`，先备份再恢复为 source-001 状态。
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
