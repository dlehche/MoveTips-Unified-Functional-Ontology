# 人体功能统一本体（UOHF）

## 正式英文名称：Unified Ontology of Human Function

[English](README.md) · [UOHF Definition 2.1](https://doi.org/10.5281/zenodo.21630406) · **[18项核心 + 104项具体能力](papers/capacity-system/README.zh-CN.md)** · [形式化框架](papers/formal-framework/README.zh-CN.md) · [“统一”论文](papers/unification/README.md) · [论文总览](papers/README.md) · [版本档案](versions/README.md) · [出版映射](PUBLICATIONS.json) · [权利与复用](RIGHTS_AND_REUSE.md) · [研究与合作](COLLABORATION.md)

**正式简称：** UOHF  
**当前权威总体框架：** UOHF Definition 2.1  
**当前权威出版修订版本：** 2.1.1  
**作者：** 车雷（Lei Che）  
**机构：** 木梯科技（北京）有限公司  
**联系邮箱：** dlehche@gmail.com  
**权威总体框架 DOI：** [10.5281/zenodo.21630406](https://doi.org/10.5281/zenodo.21630406)  
**许可：** 各篇以对应出版记录为准；当前 UOHF 出版物采用 CC BY-NC 4.0

> **生活不断调用身体。**

> **人体功能，就是身体被正常调用的能力。**

> **Human function is the body's capacity to be appropriately engaged to meet internal and external demands.**

---

## 最新专题论文：人体功能能力体系第一版

[![UOHF 人体功能能力体系第一版](papers/capacity-system/assets/uohf-capacity-system-v1-cover.svg)](papers/capacity-system/README.zh-CN.md)

### 18项核心人体功能能力 + 104项具体人体功能能力

第一版能力体系论文正式把 UOHF 的人体功能能力目录作为一个**公开、可引用、可版本化的科学对象**发布：统一定义18项核心人体功能能力及其下104项具体人体功能能力，每项能力均以整个人为主体，并绑定可追溯的科学或专业来源。论文同时公开目录构建方法、关键相邻能力边界、版本规则以及明确的公开/不公开边界。

- **[论文概览](papers/capacity-system/README.zh-CN.md)**
- **[中文完整论文](papers/capacity-system/source/zh/README.md)**
- **[English full paper](papers/capacity-system/source/en/README.md)**
- 预留 Zenodo DOI：`10.5281/zenodo.21975100`——Zenodo 正式发布后注册生效
- 许可：**CC BY-NC 4.0**

第一版目录不是“人体功能已经永远穷尽”的声明，而是一套可持续修订的科学坐标。论文不公开完整任务—能力需求矩阵、解剖/生理过程实现网络、完整评估与干预映射、个体推理规则、决策权重、生产 payload 或真实用户运行数据。

---

## 当前专题论文

### 人体功能形式化与计算框架

**能力、功能调用、需求有界可实现性与证据约束决策支持**

Version 1.0 建立 UOHF Definition 2.1 之下的数学和实现层形式内核，包括类型化形式对象、12条核心公理、需求有界可实现性、结果不可识别性、证据约束假设、受治理行动、动态状态更新、可证伪条件和分阶段实证研究路线。

- [Zenodo：10.5281/zenodo.21721599](https://doi.org/10.5281/zenodo.21721599)
- [中文完整论文](papers/formal-framework/UOHF_Formal_Framework_ZH_V1.0.md)
- [英文完整论文](papers/formal-framework/UOHF_Formal_Framework_EN_V1.0.md)
- [论文概览](papers/formal-framework/README.zh-CN.md)

### 人体功能统一本体中的“统一”

**以人体功能及其调用为核心的完整人体概念框架**

这篇论文解释 UOHF 到底统一什么，为什么功能调用属于人体功能概念内部，以及功能、需求、身体结构、身体过程、协作、代偿、边界、状态、时间和变化如何重新回到同一个完整人体中表达。

- [Zenodo：10.5281/zenodo.21635694](https://doi.org/10.5281/zenodo.21635694)
- [中文完整全文索引](papers/unification/UOHF_Unification_ZH_V1.0.2.md)
- [英文完整全文索引](papers/unification/UOHF_Unification_EN_V1.0.2.md)
- [论文概览](papers/unification/README.md)

---

## UOHF 解决什么问题

医学、生理学、康复、运动科学、行为、环境和个人健康记录都在描述同一个人，但不会自动形成一个共同、连续、可计算的人体功能对象。UOHF 把**人体功能**确立为这个共同对象，用统一语义持续回答：

- 当前存在什么内部任务、外部任务或需求；
- 当前需求需要哪些人体功能能力；
- 这些能力当前是否存在、可用到什么程度、边界在哪里；
- 这些已有能力在当前需求中实际上怎样被调用；
- 当前看到、报告、测量或推断到了什么；
- 当前代价、负担、边界、储备和恢复后果是什么；
- 当前证据支持什么人体功能状态；
- 允许进入什么行动，行动以后实际发生了什么变化。

UOHF 不替代专业知识，而是让跨专业人体功能判断变得：

> **可计算、可约束、可追溯、可审计、可修正、可持续更新。**

---

## 核心架构

```mermaid
flowchart LR
    D[内部或外部需求] --> RC[所需人体功能能力]
    RC --> FE[实际功能调用]
    FE --> R[反应 / 表现 / 测量]
    R --> C[代价 / 边界 / 储备 / 恢复]
    C --> E[证据与假设]
    E --> S[人体功能状态]
    S --> A[受治理行动]
    A --> CH[实际变化]
    CH --> FB[反馈与复评]
    FB --> S
```

UOHF 区分受治理本体与语义规则层、人体功能引擎、个人人体功能模型（IHFM）和人体功能世界模型（HFWM）。

> **受治理本体拓扑 → 人体功能引擎 → 个体长期模型 → 人体功能世界模型**

---

## 从这里开始

| 内容 | 用途 |
|---|---|
| [UOHF Definition 2.1](https://doi.org/10.5281/zenodo.21630406) | 当前权威总体框架 |
| **[人体功能能力体系第一版](papers/capacity-system/README.zh-CN.md)** | **18项核心 + 104项具体能力、统一定义、来源与引用信息** |
| [能力体系——中文完整论文](papers/capacity-system/source/zh/README.md) | 18+104 第一版全文 |
| [Capacity System — English full text](papers/capacity-system/source/en/README.md) | English Version 1.0 full paper |
| [人体功能形式化框架](papers/formal-framework/README.zh-CN.md) | 数学与计算形式化 |
| [“统一”论文](papers/unification/README.md) | 完整人体概念统一 |
| [论文总览](papers/README.md) | 全部专题出版物 |
| [版本档案](versions/README.md) | UOHF 版本与专题论文历史 |
| [出版映射](PUBLICATIONS.json) | 机器可读版本、DOI、日期、许可与状态 |
| [公共机器可读本体状态](ontology/README.md) | 当前公开本体边界 |
| [权利与复用](RIGHTS_AND_REUSE.md) | 署名、许可与商业使用边界 |
| [研究与合作](COLLABORATION.md) | 合作方向与参与方式 |

---

## 出版与版本关系

- **UOHF V1.0 / 出版修订1.0.1**：早期本体驱动、安全约束、可审计的人体功能推理框架。DOI：[10.5281/zenodo.21630183](https://doi.org/10.5281/zenodo.21630183)。
- **UOHF Definition 2.0 / 出版修订2.0.1**：任务中心 Functional Engagement 架构与持续回写。DOI：[10.5281/zenodo.21630339](https://doi.org/10.5281/zenodo.21630339)。
- **UOHF Definition 2.1 / 出版修订2.1.1**：当前权威总体框架，恢复内部与外部需求的完整范围。DOI：[10.5281/zenodo.21630406](https://doi.org/10.5281/zenodo.21630406)。
- **“统一”专题论文 / 出版修订1.0.2**：完整人体概念统一与功能调用。DOI：[10.5281/zenodo.21635694](https://doi.org/10.5281/zenodo.21635694)。
- **人体功能形式化框架 / Version 1.0**：能力、调用、需求有界可实现性、证据约束推理和动态更新。DOI：[10.5281/zenodo.21721599](https://doi.org/10.5281/zenodo.21721599)。
- **人体功能能力体系第一版 / Version 1.0**：首次公开18项核心与104项具体人体功能能力目录。预留 DOI：`10.5281/zenodo.21975100`（待 Zenodo 正式发布）。

UOHF Definition 2.1 仍是当前权威总体框架。专题论文用于在该总体框架下进一步建立特定科学层，不会静默替代根定义。

---

## 当前边界

当前受治理实现已经支持概念域、稳定标识符、类型化关系、关系合同、证据结构、权限约束、生命周期治理、任务中心状态收束、行动语义、执行反馈、复评与长期监控。

完整生产本体、关系拓扑、运行规则和业务数据资产不会全部公开复制到本仓库。UOHF 当前不宣称已完成 BFO 全面符合、完整 OWL 公理化、通用生理状态分类、外部专家共识、临床结局验证、分子到整个人统一仿真或自动诊断/自动治疗。

---

## 研究与合作

当前重点合作方向包括本体工程、完整人体与多尺度生理建模、人体功能参考体系、康复与运动科学、长期状态建模、可审计健康 AI、语义互操作、人体功能能力测量，以及任务—评估—行动—反馈—复评系统。

见 [`COLLABORATION.md`](COLLABORATION.md)。研究、互操作、工程实施或机构合作：**dlehche@gmail.com**

---

## 引用

> Che, Lei. *UOHF Definition 2.1: Unified Ontology of Human Function*. Version 2.1.1. MoveTips Technology (Beijing) Co., Ltd., 2026. DOI: [10.5281/zenodo.21630406](https://doi.org/10.5281/zenodo.21630406).

> Che, Lei. *The UOHF Human Function Capacity System, Version 1.0: Unified Definitions of 18 Core and 104 Specific Human Functional Capacities*. MoveTips Technology (Beijing) Co., Ltd., 2026. Reserved DOI: `10.5281/zenodo.21975100`.

各篇独立引用元数据维护在对应论文目录中。仓库总体引用信息仍维护在 [`CITATION.cff`](CITATION.cff)。

---

## 著作权与复用

**著作权 © 2026 车雷与木梯科技（北京）有限公司。**

当前 UOHF 出版物采用 **CC BY-NC 4.0**。允许按照许可证条款进行学术引用和非商业复用；商业使用出版物中受著作权保护的内容，在需要著作权许可的情况下须另行取得许可。仓库总体说明见 [`RIGHTS_AND_REUSE.md`](RIGHTS_AND_REUSE.md)。
