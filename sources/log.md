# 来源日志

## 2026-07-21

- 摄取创始人手写片段为 `source-006`，固定文本 `full_text-20260721.txt`（23 行，md5 `38eef2d6bca17ec9bf57a48bc54972f3`），新增 `metadata-006.json` 与 `来源-006.md`。议题：借 Cursor 多智能体实验（昂贵领导者+便宜执行者成本最优）点出 Bodhi 总命题——crypto 能否不依赖中心化达到类似甚至更高效。与 source-003（项目叙事）互补：source-003 讲“为什么这样做”，本源用一个跨域类比讲“Bodhi 在根本上想验证什么”。未运行 extractor，固定文本与元数据手写。

## 2026-07-13

- 摄取 `luyao回答用户提问.md` 为 `source-005`，固定文本 `full_text-20260713-3.txt`（41 行，md5 `55101c8976366e02452a2f4adcc617d3`），新增 `metadata-005.json` 与 `来源-005.md`。议题：发项目是否等于发币、创建者与代币解绑、责任形态历史类比。与 `source-004` 同属创始人 Q&A，但主题不同。
- 注意：extractor `--pkg` 仍会覆盖根 `metadata.json` 与移动别名 `full_text.txt`，本次先备份再恢复为 `source-001` 状态（`full_text.txt` md5 = `dad18ee51aff05143e36c288548893ef`），并用 `-3` 后缀避开已占用的 `full_text-20260713.txt` / `-2.txt`。
- 摄取 `bodhi创建者回答用户提问-20260713.md` 为 `source-004`，固定文本 `full_text-20260713-2.txt`（61 行，md5 `34a509f57b6402de965618e810c6bf1c`），新增 `metadata-004.json` 与 `来源-004.md`。
- 注意：extractor `--pkg` 仍会覆盖根 `metadata.json` 与移动别名 `full_text.txt`，本次先备份再恢复为 `source-001` 状态（`full_text.txt` md5 = `dad18ee51aff05143e36c288548893ef`），并用 `-2` 后缀避开已被 `source-003` 占用的 `full_text-20260713.txt`。
- 摄取 `docs/bodhi-thesis.md` 为 `source-003`，固定文本 `full_text-20260713.txt`（106 行），新增 `metadata-003.json` 与 `来源-003.md`。
- 注意：extractor 默认会覆盖 `metadata.json` 与移动别名 `full_text.txt`，本次已将两者恢复为 `source-001` 的状态（`full_text.txt` md5 = `dad18ee51aff05143e36c288548893ef`）。

## 2026-07-12

- 补登 `source-002` 的抽取元数据：新增 `metadata-002.json`（md5、行数、字数与 token 估算），并在 `来源-002.md` 补指向。原 `metadata.json` 只覆盖 `source-001`，`source-002` 此前缺登记。

## 2026-06-30

- 新增补充材料“一座没有市长的城市”，固定文本为 `full_text-20260630-2.txt`。
- 抓取 `https://bodhi.wtf/docs` 单页应用壳。
- 定位懒加载 chunk `AboutPage-CFFInlZV.js` 中的 `E.zh` 文档对象。
- 转换为 Markdown 后用 `book-to-okf-wiki` extractor 生成 pinned text。
