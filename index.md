# Bodhi 项目 OKF 知识包

Bodhi v2 是一个把“想法发行成代币，并让代币通过行动和给币流向贡献者”的链上协议知识包。它的核心不是单纯 Launchpad，而是把代币从交易对象变成组织协作中的支付和激励媒介。

## 来源与范围

- 来源：[Bodhi Docs](https://bodhi.wtf/docs)，本地来源说明见 [sources/来源-001.md](sources/来源-001.md)；补充材料“一座没有市长的城市”见 [sources/来源-002.md](sources/来源-002.md)；创始人项目级叙事“Bodhi Thesis”见 [sources/来源-003.md](sources/来源-003.md)；创建者回答用户提问见 [sources/来源-004.md](sources/来源-004.md)；luyao 回答“发项目是否等于发币”见 [sources/来源-005.md](sources/来源-005.md)；luyao 关于 Cursor 多智能体实验与 Bodhi 去中心化效率命题的随想见 [sources/来源-006.md](sources/来源-006.md)。
- 固定文本：`sources/full_text-20260630.txt`，共 140 行，md5 `dad18ee51aff05143e36c288548893ef`；`sources/full_text-20260630-2.txt`，共 25 行，md5 `c38a2511171ec1a2f06ee7e3f8ac69b8`；`sources/full_text-20260713.txt`，共 106 行，md5 `aac8935b8edf37a5f617a9986e54919f`；`sources/full_text-20260713-2.txt`，共 61 行，md5 `34a509f57b6402de965618e810c6bf1c`；`sources/full_text-20260713-3.txt`，共 41 行，md5 `55101c8976366e02452a2f4adcc617d3`；`sources/full_text-20260721.txt`，共 23 行，md5 `38eef2d6bca17ec9bf57a48bc54972f3`。
- 范围：概览、代币生命周期、行动和给币、小发明、FAQ、城市代币与“没有市长的城市”、创始人叙事与产品方法论（source-003）、机制演进史与设计动机（source-004）、发币监管边界与责任形态演进（source-005）、协作结构与去中心化效率命题（source-006）。
- 不包含：合约源码逐行审计、链上实时状态、外部数据验证、法律意见、source-003 / source-004 / source-005 / source-006 中个人回忆、状态判断与外部转述（如 Cursor 实验数据）的事实核验。

## 人类阅读路径

1. 先读 [概览](chapters/第00章-概览.md)，抓住“代币即无工资公司”的组织隐喻。
2. 再读 [代币生命周期](chapters/第01章-代币生命周期.md)，理解创建、Bonding Curve、迁移和 DEX。
3. 接着读 [行动和给币](chapters/第02章-行动和给币.md)，这是 Bodhi 区别于普通 Launchpad 的核心。
4. 再读 [没有市长的城市](chapters/第05章-没有市长的城市.md)，理解城市代币、政治性组织和给钱/给币差异。
5. 最后读 [小发明](chapters/第03章-小发明.md) 和 [常见问题](chapters/第04章-常见问题.md)。
6. 想理解“为什么这样做”再读 [Bodhi 产品叙事框架](frameworks/Bodhi产品叙事框架.md) 和它的概念页（source-003）。
7. 想理解“发项目算不算发币 / 创建者还要不要负责”读 [责任形态演进框架](frameworks/责任形态演进框架.md)（source-005）。
8. 想理解“Bodhi 到底在赌什么 / 为什么去中心化”读 [协作结构张力框架](frameworks/协作结构张力框架.md)（source-006）。

## 代理上下文路径

- 快速建模：读 [概念索引](concepts/index.md) 和 [框架索引](frameworks/index.md)。
- 事实核验：读 [主张索引](claims/index.md) 和 [来源页](sources/来源-001.md)。
- 术语查找：读 [glossary/术语.md](glossary/术语.md)。
- 不确定性：读 [questions/待解决问题.md](questions/待解决问题.md)。
- 代理规则：读 [AGENTS.md](AGENTS.md)。

## 顶层概念

- [代币即无工资公司](concepts/代币即无工资公司.md)
- [代币现实反馈回路](concepts/代币现实反馈回路.md)
- [行动与给币](concepts/行动与给币.md)
- [Bonding Curve 启动阶段](concepts/启动曲线阶段.md)
- [迁移与 LP 销毁](concepts/迁移与流动性锁定.md)
- [无管理员合约规则](concepts/无管理员合约规则.md)
- [小型贡献市场](concepts/小型贡献市场.md)
- [辅助基础设施](concepts/辅助基础设施.md)
- [城市代币](concepts/城市代币.md)
- [无市长城市](concepts/无市长城市.md)
- [给钱与给币的激励差异](concepts/给钱与给币的激励差异.md)
- [群体基础与时机](concepts/群体基础与时机.md)
- [两种盒子模型](concepts/两种盒子模型.md)（source-004）
- [市场驱动可信度](concepts/市场驱动可信度.md)（source-004）
- [低成本发币的监管模糊性](concepts/低成本发币的监管模糊性.md)（source-005）
- [创建者与代币关系模糊化](concepts/创建者与代币关系模糊化.md)（source-005）
- [领导者与执行者分工](concepts/领导者与执行者分工.md)（source-006）
- [去中心化效率命题](concepts/去中心化效率命题.md)（source-006）
- [反预判策略](concepts/反预判策略.md)（source-003）
- [正方形哲学](concepts/正方形哲学.md)（source-003）
- [体验优于逻辑](concepts/体验优于逻辑.md)（source-003）
- [热闹大于整齐](concepts/热闹大于整齐.md)（source-003）

## 顶层框架

- [Bodhi 协作循环](frameworks/Bodhi协作循环.md)
- [代币生命周期框架](frameworks/代币生命周期框架.md)
- [行动给币机制框架](frameworks/行动给币机制框架.md)
- [机制简化演进框架](frameworks/机制简化演进框架.md)
- [城市代币循环](frameworks/城市代币循环.md)
- [政治性组织框架](frameworks/政治性组织框架.md)
- [Bodhi 产品叙事框架](frameworks/Bodhi产品叙事框架.md)（source-003）
- [责任形态演进框架](frameworks/责任形态演进框架.md)（source-005）
- [协作结构张力框架](frameworks/协作结构张力框架.md)（source-006）

## 目录

- [sources/](sources/)
- [chapters/](chapters/)
- [chapters/subsections/](chapters/subsections/)
- [concepts/](concepts/)
- [frameworks/](frameworks/)
- [claims/](claims/)
- [glossary/](glossary/)
- [questions/](questions/)
