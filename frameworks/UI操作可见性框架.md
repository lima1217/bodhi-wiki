---
type: Framework
title: UI操作可见性框架
description: 新版 UI 让四种核心操作（买/卖/发/给）在界面上更显眼的一组设计决策，目标是缩短新人理解代币的路径。
sources:
  - id: source-007
    resource: /sources/full_text-20260805.txt
    title: luyao：Bodhi 新版 UI 的设计说明（2026-08-05）
    author: luyao
    last_modified: 2026-08-05
chapter_refs: []
tags: [framework, ui, design]
status: stable
generated: { by: cursor/claude-opus-4, at: 2026-08-05T00:00:00Z }
---

# UI操作可见性框架

## 框架

让 Bodhi 的四种核心操作（买、卖、发、给）在界面上明显呈现，本身就构成一套完整叙事，能帮新人更快弄明白“这里是什么”“我要如何跟它互动”。[^source-007] 据此新版 UI 做了如下决策：

1. **让给币可见** — 旧 UI 出于视觉考量把“给币”这类操作隐藏，要点开内容才看到。这会让新人花更长时间才能弄明白。新版把给币做得大且好点。[^source-007]
2. **CTA 随持仓状态集中** — 未持有当前代币时，唯一重点是“买入”，给币不可点；已持有当前代币时，买入按钮弱化，给币成为重点按钮。[^source-007]
3. **操作简化为一次点击** — 买入、给币等操作做成只点一次，然后倒计时进度条自动触发确认。[^source-007]
4. **代币列表带微型事件图** — 过去只有市值数字，现在展示最近发生的事情和一张微型柱状图，原因同前（让“活”的状态被看见）。[^source-007]
5. **个人页语境化** — 过去每个人是一个总的 profile（含持仓），现在点开人的 emoji 或名字，看到的是“这个人在当前代币下做了些什么”。[^source-007]

## 使用场景

- 评估某个 Bodhi UI 改动是否帮新人更快理解代币。
- 判断界面是否把“发/给”当作与“买/卖”同等可见的操作，而非附属。

## 证据

- 四操作可见性：`sources/full_text-20260805.txt:11-13`
- CTA 集中与持仓状态：`sources/full_text-20260805.txt:14`
- 操作简化：`sources/full_text-20260805.txt:16`
- 列表微型图：`sources/full_text-20260805.txt:17`
- 个人页语境化：`sources/full_text-20260805.txt:18`

## 注意

这是产品取向的具体落地，不是可验证假设。“每条内容都有给币按钮可能显得混乱，正在尝试解决”是创始人承认的待解问题。[^source-007] 是否真的“更合理”仍待真实使用验证。

## 关联概念

- [四种核心操作](/concepts/四种核心操作.md)
- [代币活跃度指标](/concepts/代币活跃度指标.md)
- [代币能量系统隐喻](/concepts/代币能量系统隐喻.md)
- [热闹大于整齐](/concepts/热闹大于整齐.md)

[^source-007]: luyao《Bodhi 新版 UI 的设计说明》，full_text-20260805.txt L11-L18, L15
