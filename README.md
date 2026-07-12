# Bodhi Wiki

Bodhi 项目的自包含中文知识包。把仓库链接丢给 AI agent，让它读完作为背景，然后直接提问。每个结论都能追溯到固定来源的行号，agent 引用时不会凭印象发挥。

## 这是什么

把 Bodhi（[bodhi.wtf](https://bodhi.wtf)）的官方文档、城市代币材料和创始人叙事，摄取成一个可溯源的 OKF LLM Wiki。人类能浏览，任何 agent 都能当作 context 使用。

三份固定来源：

- **source-001 Bodhi Docs**：协议概览、代币生命周期、行动与给币、小发明、FAQ
- **source-002 一座没有市长的城市**：城市代币、政治性组织、给钱与给币
- **source-003 Bodhi Thesis**：创始人叙事、价值取向、产品方法论

## 怎么用（重点）

把仓库链接给任何支持上下文的 coding agent（Claude、Cursor、Codex、ZCode 等），让它以 `AGENTS.md` 和 `index.md` 作为导航入口，然后直接问。

```text
读这个仓库作为背景知识：https://github.com/lima1217/bodhi-wiki
先看 AGENTS.md 和 index.md，再回答：Bodhi 的代币是怎么从交易对象变成激励媒介的？
```

agent 会按 `AGENTS.md` 的引用规则，从 `sources/full_text-*.txt` 抽行号支撑回答，而不是自己编。

可以直接问这类问题：

- Bodhi 和普通 launchpad 有什么区别？
- 一个代币从创建到上 DEX 经历什么？
- 行动和给币到底怎么运作？
- 城市代币为什么是“没有市长的城市”？
- 创始人为什么不预判场景、不做 pump.fun？

回答里出现的 `sources/full_text-20260630.txt:60-76` 这类标记，就是证据出处，可以去对应文件核验。

## 仓库结构

```text
├── AGENTS.md          # agent 读取与引用规则，从这里开始
├── index.md           # 全包导航与阅读路径
├── sources/           # 固定来源文本（pinned evidence）
├── chapters/          # 按原文脉络组织的章节与小节
├── concepts/          # 跨章节合成的 durable 概念
├── frameworks/        # 命名方法与模型
├── claims/            # 事实与论证主张，带证据
├── glossary/术语.md   # 术语查找
├── questions/待解决问题.md  # 需外部验证的开放问题
└── tools/validate_okf_wiki.py
```

agent 快速建模的入口：`concepts/index.md` 和 `frameworks/index.md`。事实核验：`claims/index.md` 和 `sources/`。

## 本地使用

克隆后，agent 可以直接指向本地路径，无需联网：

```bash
git clone https://github.com/lima1217/bodhi-wiki.git
```

校验包的链接和结构完整性：

```bash
python3 tools/validate_okf_wiki.py .
python3 tools/validate_okf_wiki.py --strict .
```

## 更新与边界

仓库数据定期更新，会随 Bodhi 文档和叙事的演进而补充来源与概念。如果 agent 缓存了旧版本，让它重新拉取最新内容再提问。

本包不包含：合约源码逐行审计、链上实时状态、外部数据验证。`source-003` 中关于 v1 内容数量、pump.fun 时间线、wishpool 事件、VC 联络等属创始人回忆，引用时应标注“待核实”，不应作为已验证事实。
