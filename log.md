# 更新日志

## 2026-08-24

- 摄取 luyao 帖子为 `source-008`（固定文本 `full_text-20260824.txt`，20 行，md5 `fcc11f611731954d1bcbae6cea0e98e8`）。议题：代币生长顺序反转——不是买卖长出建设，而是闲聊、关系里长出建设，代币最后才拿到意义，投机在链末尾，土壤是人待在一起的空间；代币被当频道用是种子形态；Paul Graham 兴趣指南针移植到代币筛选。与 source-003（不预判最优场景）互补：source-003 讲方法论，本源给出观察到的实际生长顺序。
- 新增 3 个概念（闲聊是土壤、代币即频道、兴趣指南针）、1 个框架（代币生长顺序框架）、2 个主张（不是买卖长出建设而是闲聊长出建设、代币被当频道用是种子形态）。
- 补强 3 个既有页：热闹大于整齐（土壤论把热闹推进到生长机制层）、反预判策略（兴趣指南针是其筛选层具体化）、群体基础与时机（频道是群体基础的种子阶段）；Bodhi 产品叙事框架新增“阶段策略”条目。
- glossary 增 4 条术语（闲聊是土壤、代币即频道/种子形态、兴趣指南针、GameFi 代币案例）并给 pump.fun 词条补对照证据；questions 新增“代币生长与土壤”组；README 补登 source-007 并同步 source-008；AGENTS.md、index.md 与各目录 index/log 同步指向 source-008。
- 注意：本次固定文本与 metadata 手写（未运行 extractor），未触碰根 `metadata.json` 与 `full_text.txt`，二者仍为 source-001 状态。

## 2026-08-05（v0.2 全包迁移）

- 对全包做 OKF v0.2 sweep，彻底清除 v0.1 残留字段：86 个页面的 `source_refs` + `timestamp` + `status: active` 迁移为 v0.2 的 `sources` 列表（带 `id`/`resource`/`title`/`author`/`last_modified`）、`generated: { by, at }` 与 `status: stable`。
- 链接全部 `/`-rooted 化：75 处 `../` 相对链接、跨目录 `.md`/`.txt`/`.json` 引用，以及裸目录链接（`concepts/` 等）统一改为从包根解析的绝对路径，使每条引用可全局 grep。
- 根 `index.md` 补 v0.2 必需的 `okf_version: "0.2"`；`tools/validate_okf_wiki.py` 用 skill 最新版覆盖。
- 校验：非严格与 strict 模式均通过，零 v0.1 警告；strict 唯一 advisory 是 README.md 为孤儿页（既存情况，无页面链接到它），不影响通过。

## 2026-08-05

- 摄取 luyao 帖子为 `source-007`（固定文本 `full_text-20260805.txt`，19 行，md5 `b554aee1ff4f59a82dcff12b0e3b44dd`）。议题：新版 UI 设计思路——事件柱状图呈现代币“活跃度”、四种操作（买/卖/发/给）的能量系统隐喻、核心操作在界面上更显眼以缩短新人理解路径。与 source-003（产品叙事方法论）互补：source-003 讲价值取向，本源讲这些取向如何在 UI 落地。
- 新增 3 个概念（四种核心操作、代币能量系统隐喻、代币活跃度指标）、1 个框架（UI操作可见性框架）、2 个主张（价格图表反映不了代币活跃度、做事做功决定系统是电池还是有机体）。
- 补强 3 个已有页：热闹大于整齐（UI 落地证据）、行动与给币（给币被 UI 显著呈现）、Bodhi 产品叙事框架（产品取向的 UI 落地）。
- glossary 增 4 条术语（四种核心操作、代币能量系统隐喻、代币活跃度指标、事件柱状图）；questions 新增“产品 UI”组；AGENTS.md、index.md 与各目录 index/log 同步指向 source-007。
- 注意：本次固定文本与 metadata 手写（未运行 extractor），未触碰根 `metadata.json` 与 `full_text.txt`，二者仍为 source-001 状态。

## 2026-07-21

- 摄取创始人手写片段为 `source-006`（固定文本 `full_text-20260721.txt`，23 行，md5 `38eef2d6bca17ec9bf57a48bc54972f3`）。议题：借 Cursor 多智能体实验（昂贵领导者+便宜执行者的成本最优分工）点出 Bodhi 总命题——crypto 能否不依赖中心化达到类似甚至更高效。
- 新增 2 个概念（领导者与执行者分工、去中心化效率命题）、1 个框架（协作结构张力框架）、2 个主张（中心化领导是历史验证的成本最优协作、Bodhi探索去中心化能否达到类似效率）。
- glossary 增 3 条术语（领导者与执行者分工、去中心化效率命题、Cursor 多智能体实验）；questions 新增“协作结构与去中心化效率”组；AGENTS.md、index.md 与各目录 index/log 同步指向 source-006。
- 注意：本次固定文本与 metadata 手写（未运行 extractor），未触碰根 `metadata.json` 与 `full_text.txt`，二者仍为 source-001 状态。

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
