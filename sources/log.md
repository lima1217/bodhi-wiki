# 来源日志

## 2026-06-30

- 新增补充材料“一座没有市长的城市”，固定文本为 `full_text-20260630-2.txt`。
- 抓取 `https://bodhi.wtf/docs` 单页应用壳。
- 定位懒加载 chunk `AboutPage-CFFInlZV.js` 中的 `E.zh` 文档对象。
- 转换为 Markdown 后用 `book-to-okf-wiki` extractor 生成 pinned text。

## 2026-07-13

- 摄取 `docs/bodhi-thesis.md` 为 `source-003`，固定文本 `full_text-20260713.txt`（106 行），新增 `metadata-003.json` 与 `来源-003.md`。
- 注意：extractor 默认会覆盖 `metadata.json` 与移动别名 `full_text.txt`，本次已将两者恢复为 `source-001` 的状态（`full_text.txt` md5 = `dad18ee51aff05143e36c288548893ef`）。

## 2026-07-12

- 补登 `source-002` 的抽取元数据：新增 `metadata-002.json`（md5、行数、字数与 token 估算），并在 `来源-002.md` 补指向。原 `metadata.json` 只覆盖 `source-001`，`source-002` 此前缺登记。
