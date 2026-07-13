---
type: Claim
title: Virtual Foundation 是 v0 机制
description: 每个代币带内置金库、持币者投票决定是否拿固定数量代币奖励贡献者，是早于任务/悬赏版本的机制，后被换掉。
source_refs: [source-004]
chapter_refs: [ch02]
tags: [claim, bodhi]
status: active
timestamp: 2026-07-13T00:00:00Z
---

# Virtual Foundation 是 v0 机制

## 主张

在“任务/悬赏”版本之前，Bodhi 还有一个更早的版本：每个 token 都带一个 virtual foundation（发币时预留的内置金库）。每当有人做出贡献，所有持币者投票决定：金库要不要拿出一笔固定数量的代币奖励这个人。创始人把它比作“一个全自动的 grant 机制”，并认为它包含一些创新、解决了传统 DAO 投票的某些问题，但太复杂、有隐患，后来被换掉。

## 支撑

这条主张澄清了 [机制简化演进框架](../frameworks/机制简化演进框架.md) 的演进顺序：Virtual Foundation（v0，金库+投票）→ 任务/悬赏（v1 内测）→ 当前 v2（Post + 给币）。它直接回应了用户关于“代币价值流动权利是否应留在协议而非持币人手里”的提问——用户描述的“留在协议里的金库”正是 v0 的做法。

## 证据

- virtual foundation 的描述、自动 grant 类比、复杂性与被换掉：`sources/full_text-20260713-2.txt:43-49`
- 它与提问 2 的对应（“听起来有点像我们的上上个版本，也就是最早的那个版本”）：`sources/full_text-20260713-2.txt:45`

## 假设与不确定性

“解决了传统 DAO 投票的一些问题”“有隐患”属创始人概括，具体创新点与隐患未在本源展开，需要更多早期资料核实。v0 的金库参数、投票规则、是否存在部署记录，均待核。

## 关联概念

- [小型贡献市场](../concepts/小型贡献市场.md)
- [给钱与给币的激励差异](../concepts/给钱与给币的激励差异.md)

## 关联框架

- [机制简化演进框架](../frameworks/机制简化演进框架.md)
