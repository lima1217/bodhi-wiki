---
type: AgentGuide
title: Bodhi 项目知识包使用指南
description: 指导代理如何读取、引用和更新 Bodhi OKF 知识包。
sources:
  - id: source-001
    resource: /sources/full_text-20260630.txt
    title: Bodhi Docs
    last_modified: 2026-06-30
  - id: source-002
    resource: /sources/full_text-20260630-2.txt
    title: 一座没有市长的城市
    last_modified: 2026-06-30
  - id: source-003
    resource: /sources/full_text-20260713.txt
    title: Bodhi Thesis
    author: luyao
    last_modified: 2026-07-13
  - id: source-004
    resource: /sources/full_text-20260713-2.txt
    title: Bodhi 创建者回答用户提问（2026-07-13）
    last_modified: 2026-07-13
  - id: source-005
    resource: /sources/full_text-20260713-3.txt
    title: luyao 回答用户提问（发项目是否等于发币）
    author: luyao
    last_modified: 2026-07-13
  - id: source-006
    resource: /sources/full_text-20260721.txt
    title: luyao 随想（Cursor 多智能体实验与 Bodhi 去中心化效率命题）
    author: luyao
    last_modified: 2026-07-21
  - id: source-007
    resource: /sources/full_text-20260805.txt
    title: luyao：Bodhi 新版 UI 的设计说明（2026-08-05）
    author: luyao
    last_modified: 2026-08-05
chapter_refs: [ch00, ch01, ch02, ch03, ch04, ch05]
tags: [agent, okf, bodhi]
status: stable
generated: { by: cursor/claude-opus-4, at: 2026-06-30T09:30:00Z }
---

# Bodhi 项目知识包使用指南

本包是从 `https://bodhi.wtf/docs` 和补充材料“一座没有市长的城市”深度摄取生成的中文 OKF LLM Wiki。回答 Bodhi 项目问题时，先读根 [index.md](/index.md)，再按任务进入 [concepts/](/concepts)、[frameworks/](/frameworks)、[claims/](/claims) 或 [chapters/](/chapters)。

引用事实时使用固定来源 `sources/full_text-20260630.txt:<行号>`、`sources/full_text-20260630-2.txt:<行号>`、`sources/full_text-20260713.txt:<行号>`、`sources/full_text-20260713-2.txt:<行号>`、`sources/full_text-20260713-3.txt:<行号>` 或 `sources/full_text-20260721.txt:<行号>` 或 `sources/full_text-20260805.txt:<行号>`。不要引用 `sources/full_text.txt`，它是 `full_text-20260630.txt` 的移动别名。若需要核对来源元数据，读 [sources/来源-001.md](/sources/来源-001.md)、[sources/来源-002.md](/sources/来源-002.md)、[sources/来源-003.md](/sources/来源-003.md)、[sources/来源-004.md](/sources/来源-004.md)、[sources/来源-005.md](/sources/来源-005.md) 和 [sources/来源-006.md](/sources/来源-006.md)。

`source-001`、`source-002` 承载机制事实；`source-003`（Bodhi Thesis）承载创始人叙事、价值取向和方法论；`source-004`（创建者回答用户提问）承载设计动机与机制演进史，连接前两者；`source-005`（luyao 回答：发项目是否等于发币）承载监管边界、创建者与代币解绑及责任形态历史类比；`source-006`（luyao 随想：Cursor 多智能体实验）承载 Bodhi 的总命题——借助 crypto 能否不依赖中心化结构达到类似甚至更高的协作效率。其中 v1 内容数量、pump.fun 关系、wishpool 事件、VC 联络、virtual foundation 细节、Moloch DAO 简化版、“目前还没遇到验证问题”、发币是否构成证券、Doge/铁路史实简化等属个人回忆或状态判断，引用时应标注为“创始人陈述，待核实”，不要当作已验证事实。`source-005` 尤其不是法律意见；`source-006` 中 Cursor 实验数据（Fable 5 约 2 万美金、Opus 4.8 + Composer 2.5 约 1300 美金、品质相近）引自 Cursor 文章、本包未核验，“成本效益最高/中心化不可避免”是价值判断，“直觉它是可以的”是未经验证的信念，均应标为“创始人陈述/转述，待核实”，不要当作已验证结论。`source-007`（luyao 新版 UI 设计说明）承载产品 UI 设计思路——事件柱状图呈现代币活跃度、四种操作（买/卖/发/给）的能量系统隐喻、操作可见性决策；其中“不确定是否最好”“正在尝试解决”“我觉得更合理”等是创始人当前判断，UI 实际效果待真实使用验证，应标为“创始人陈述，待核实”。

优先使用概念、框架、主张页做综合判断；章节和小节页用于回到原文脉络。任何没有被来源行支持的解释，都应标成推断，并把需要外部验证的点写入 [questions/待解决问题.md](/questions/待解决问题.md)。

更新本包时，先追加对应目录的 `log.md`，再修改索引。新增人类可读页面使用中文文件名；保留目录名和 `index.md`、`log.md`、`AGENTS.md` 的英文命名。
