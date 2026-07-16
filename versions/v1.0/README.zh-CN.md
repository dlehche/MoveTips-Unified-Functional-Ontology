# 人体功能统一本体 MUFO V1.0——中文历史版本

[English](README.md) | [中文](README.zh-CN.md) | [版本档案](../README.md)

> **历史版本说明：** MUFO V1.0 是人体功能统一本体正式发展历史的一部分，但不是当前权威根定义。当前框架请参见 [MUFO Definition 2.1](../../MUFO_DEFINITION_ZH.md)。

## 出版信息

**英文标题：** *MUFO: A Unified Functional Ontology for Auditable Human Function Inference and Safety-Constrained Decision Support*  
**中文参考译名：**《MUFO：面向可审计人体功能推理与安全约束决策支持的统一本体》  
**作者：** 车雷（Lei Che），木梯研究与工程团队参与  
**机构：** 木梯科技（北京）有限公司  
**发表日期：** 2026年2月6日  
**版本：** 1.0  
**权威出版记录：** [Zenodo 记录 20711332](https://zenodo.org/records/20711332)  
**DOI：** [10.5281/zenodo.20711332](https://doi.org/10.5281/zenodo.20711332)  
**著作权：** © 2026 车雷与木梯科技（北京）有限公司

## 历史定位

MUFO V1.0 首次系统提出一套本体驱动、治理导向、安全约束和可审计的人体功能推理框架，主要面向康复与运动训练场景中那些可能尚未形成明确疾病诊断、但已经表现为疼痛、代偿、耐受下降、表现不稳定和风险升高的人体功能问题。

V1.0 重点建立了四项工程原则：

1. 将人体功能分解为八项最小充分决策因素；
2. 严格区分可观察事实与推断性归因；
3. 在下游行动之前设置硬性安全门控；
4. 生成带来源、版本和参数信息、可以确定性回放与审计的推理工件。

## V1.0 的历史运行定义

V1.0 使用的英文运行定义为：

> **The capacity to complete a task stably and efficiently under bounded physiological, biomechanical, and cognitive cost within explicit safety constraints.**

中文可理解为：

> **在明确安全约束下，以有界的生理、力学与认知成本，稳定且高效完成任务的能力。**

这一表述属于 V1.0 的历史运行框架，为保证版本真实性予以保留。当前 MUFO Definition 2.1 的权威根定义为：

> **人体功能，就是身体被正常调用的能力。**

其正式英文表达为：

> **Human function is the body's capacity to be appropriately engaged to meet internal and external demands.**

## 八项决策因素

V1.0 将人体功能表达为：

> **Human Function = Task × Movement × Strategy × Capacity × System × Structure × Psychology × Behavior**

对应八项因素：

- 任务；
- 动作；
- 策略；
- 能力；
- 系统；
- 结构；
- 心理；
- 行为。

这八项因素在 V1.0 中被视为一个面向决策的最小充分分解，要求每个因素能够被证据锚定、能够随时间更新、能够进入干预，并能够支持解释和审计。

## 任务—能力匹配

任务—能力匹配（Task–Capacity Matching，TCM）是 V1.0 的核心判断主轴：

- 任务条件形成需求；
- 人体提供能力供给；
- 能力与需求的差值形成当前功能裕度；
- 负裕度表示缺口；
- 很小的正裕度表示勉强覆盖；
- 较大的正裕度表示存在可用储备。

基础表达为：

> **M = C − D**

其中：

- `C` 表示能力供给向量；
- `D` 表示任务需求向量；
- `M` 表示功能裕度向量。

## 最小可行状态空间

V1.0 建立了早期 **MVSS-12** 运行表达，包含十二项归一化维度：

1. 恢复储备；
2. 敏化代理指标；
3. 自主神经负荷代理指标；
4. 动作控制精度；
5. 本体感觉与感觉质量；
6. 保护策略强度；
7. 可用活动窗口；
8. 刚度调节；
9. 负荷分配效率；
10. 任务能力；
11. 协调与节律；
12. 代偿依赖程度。

证据通过带版本的规则、阈值和参数映射为有界分数，从而保证结果可以被复现和回放。

## 事实与归因的边界

V1.0 区分：

- **维度（Dimensions）：** 可观察、可记录、可评分的事实；
- **归因（Attributions）：** 基于任务情境和维度组合形成的解释或假设。

归因不能作为事实直接写入记录，而必须保留证据链接、置信边界、模型版本和来源信息。

## 安全门控与推理工件

V1.0 把安全约束作为硬门控。一个完整推理工件应当保留：

- 本体版本与参数版本；
- 输入快照；
- 已应用的约束与触发的门控；
- 计算得到的裕度与风险估计；
- 候选归因及其证据链接；
- 优先决策杠杆；
- 允许进入的行动模板；
- 支持确定性回放的来源信息。

## 与后续版本的关系

- **V1.0** 建立了早期确定性、任务—能力、安全门控和可审计的运行方向；
- **Definition 2.0** 从因素与评分中心进一步进入任务中心本体架构、Functional Engagement、持续回写以及 MUFO—IHFM—HFWM 分层；
- **Definition 2.1** 成为当前权威框架定义，恢复内部需求与外部需求的完整范围，并明确多尺度本体与人体功能世界模型的发展路径。

V1.0 具有重要历史价值，对特定的任务—能力匹配应用仍有参考意义，但不应被视为当前 MUFO 完整的上层本体架构。

## 引用方式

> Che, Lei, and the MoveTips Research & Engineering Team. *MUFO: A Unified Functional Ontology for Auditable Human Function Inference and Safety-Constrained Decision Support*. Zenodo, 2026. DOI: [10.5281/zenodo.20711332](https://doi.org/10.5281/zenodo.20711332).

## 著作权与复用

**著作权 © 2026 车雷与木梯科技（北京）有限公司。**

该版本具体的访问、许可、署名和复用条件，以对应的 Zenodo 权威记录为准。任何引用、翻译、实现或衍生工作，应保留版本号、DOI、作者署名、来源链以及原文中的安全边界和专业权限限制。
