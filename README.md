# Unified Ontology of Human Function (UOHF)

## A governed semantic and computational ontology for human function and the Human Function World Model

[中文](README.zh-CN.md) · [Definition 2.1](https://doi.org/10.5281/zenodo.21630406) · **[18 Core + 104 Specific Capacities](papers/capacity-system/README.md)** · [Formal framework](papers/formal-framework/README.md) · [Unification](papers/unification/README.md) · [Papers](papers/README.md) · [Version archive](versions/README.md) · [Publication map](PUBLICATIONS.json) · [Rights and reuse](RIGHTS_AND_REUSE.md) · [Collaboration](COLLABORATION.md)

**Official name:** Unified Ontology of Human Function  
**Official abbreviation:** UOHF  
**Current authoritative framework:** UOHF Definition 2.1  
**Current authoritative publication revision:** 2.1.1  
**Author:** Lei Che  
**Affiliation:** MoveTips Technology (Beijing) Co., Ltd.  
**Correspondence:** dlehche@gmail.com  
**Authoritative framework DOI:** [10.5281/zenodo.21630406](https://doi.org/10.5281/zenodo.21630406)  
**Repository/publication licensing:** see each publication record; current UOHF publications use CC BY-NC 4.0

> **Life continually calls upon the body.**

> **Human function is the body's capacity to be appropriately engaged to meet internal and external demands.**

> **人体功能，就是身体被正常调用的能力。**

---

## Latest repository preprint: the Version 1.0 human-function capacity system

### 18 core human functional capacities + 104 specific human functional capacities

The Version 1.0 capacity-system repository preprint makes the UOHF human-function capacity catalogue a public, citable scientific object. It defines **18 core capacities and 104 specific capacities**, each at the whole-person level and with traceable scientific or professional source support. It also publishes the catalogue-construction method, adjacent-capacity boundaries, version rule, and explicit public/non-public boundary.

- **[Publication overview](papers/capacity-system/README.md)**
- **[Complete English paper](papers/capacity-system/source/en/README.md)**
- **[中文完整论文](papers/capacity-system/source/zh/README.md)**
- Reserved Zenodo DOI: `10.5281/zenodo.21975100` — registration occurs when the Zenodo record is published
- License: **CC BY-NC 4.0**

The public catalogue is a versioned scientific coordinate set, not a claim of permanent exhaustiveness. “Specific capacity” is a public-reading umbrella term; the formal fine-grained ontology types remain `SUBCAPACITY` and `CAPACITY_COMPONENT` under their respective `CORE_CAPACITY`. The complete demand-to-capacity matrix, anatomical/physiological realization network, assessment/intervention mappings, person-specific reasoning rules, decision weights, production payloads, and real-user operational data are not released by this publication.

---

## Current focused publications

### A Formal Framework for Human Function in UOHF

**Capacity, Functional Engagement, Demand-Bounded Realizability, and Evidence-Constrained Decision Support**

This Version 1.0 paper develops the formal mathematical and implementation-oriented core under UOHF Definition 2.1: typed formal objects, twelve axioms, demand-bounded realizability, result non-identifiability, evidence-bounded hypotheses, governed action selection, dynamic state update, falsification conditions, and a staged empirical research program.

- [Zenodo: 10.5281/zenodo.21721599](https://doi.org/10.5281/zenodo.21721599)
- [Complete English paper](papers/formal-framework/UOHF_Formal_Framework_EN_V1.0.md)
- [中文完整论文](papers/formal-framework/UOHF_Formal_Framework_ZH_V1.0.md)
- [Overview](papers/formal-framework/README.md)

### Unification in the Unified Ontology of Human Function

**A Whole-Person Conceptual Framework Centered on Human Function and Functional Engagement**

This focused paper explains what UOHF unifies, why functional engagement belongs inside the concept of human function, and how function, demand, bodily structure, bodily process, coordination, compensation, boundaries, state, time, and change are returned to the same whole person.

- [Zenodo: 10.5281/zenodo.21635694](https://doi.org/10.5281/zenodo.21635694)
- [English complete-text index](papers/unification/UOHF_Unification_EN_V1.0.2.md)
- [中文完整全文索引](papers/unification/UOHF_Unification_ZH_V1.0.2.md)
- [Overview](papers/unification/README.md)

---

## What problem does UOHF solve?

Medicine, physiology, rehabilitation, exercise science, behavior, environment, and personal health records can all describe the same person, but they do not automatically form one shared computational object. UOHF establishes **human function** as that shared object and provides a governed semantic and rule foundation for asking:

- What internal or external task is present, and what demand does it generate?
- Which human functional capacities are required?
- Which of those capacities are currently available and within what boundary?
- How are those capacities actually engaged under the specified demand?
- What was observed, reported, measured, or inferred?
- What cost, burden, boundary, reserve, and recovery consequence are relevant?
- What state is supported by the current evidence?
- What governed action is admissible, and what changed afterward?

The objective is not to replace domain expertise. It is to make cross-domain human-function reasoning **computable, constrained, traceable, auditable, revisable, and longitudinally continuous**.

---

## Core architecture

```mermaid
flowchart LR
    T[Internal or External Task] --> D[Task Demand / Demand Specification]
    D --> RC[Required Human Functional Capacities]
    RC --> FE[Functional Engagement]
    FE --> R[Response / Manifestation / Measurement]
    R --> C[Cost / Boundary / Reserve / Recovery]
    C --> E[Evidence and Hypotheses]
    E --> S[Human Function State]
    S --> A[Governed Action]
    A --> CH[Actual Change]
    CH --> FB[Feedback and Reassessment]
    FB --> S
```

UOHF distinguishes the governed ontology and semantic-rule layer, the Human Function Engine, the Individual Human Function Model (IHFM), and the Human Function World Model (HFWM).

> **Governed ontology topology → Human Function Engine → Individual longitudinal model → Human Function World Model**

---

## Start here

| Resource | Purpose |
|---|---|
| [UOHF Definition 2.1](https://doi.org/10.5281/zenodo.21630406) | Current authoritative overall framework |
| **[Human Function Capacity System V1.0](papers/capacity-system/README.md)** | **18 core + 104 specific capacity catalogue, definitions, sources and citation metadata** |
| [Capacity System — English full text](papers/capacity-system/source/en/README.md) | Complete English Version 1.0 paper |
| [人体功能能力体系——中文完整论文](papers/capacity-system/source/zh/README.md) | 第一版18项核心能力与104项具体能力全文 |
| [Formal framework](papers/formal-framework/README.md) | Mathematical and computational formalization |
| [Unification paper](papers/unification/README.md) | Whole-person conceptual unification |
| [Papers index](papers/README.md) | All focused publications |
| [Version archive](versions/README.md) | Public version and focused-publication history |
| [Publication map](PUBLICATIONS.json) | Machine-readable version, DOI, date, license and status map |
| [Public ontology release status](ontology/README.md) | Current machine-readable release boundary |
| [Rights and reuse](RIGHTS_AND_REUSE.md) | Attribution, licensing and commercial-use boundaries |
| [Research and collaboration](COLLABORATION.md) | Collaboration priorities and routes |

---

## Publication and version history

- **UOHF V1.0 / publication revision 1.0.1** — initial ontology-driven, safety-constrained, auditable human-function inference framework. DOI: [10.5281/zenodo.21630183](https://doi.org/10.5281/zenodo.21630183).
- **UOHF Definition 2.0 / publication revision 2.0.1** — task-centered Functional Engagement architecture and continuous write-back. DOI: [10.5281/zenodo.21630339](https://doi.org/10.5281/zenodo.21630339).
- **UOHF Definition 2.1 / publication revision 2.1.1** — current authoritative overall framework, restoring the full internal-and-external-demand scope. DOI: [10.5281/zenodo.21630406](https://doi.org/10.5281/zenodo.21630406).
- **Unification in UOHF / publication revision 1.0.2** — focused conceptual publication. DOI: [10.5281/zenodo.21635694](https://doi.org/10.5281/zenodo.21635694).
- **A Formal Framework for Human Function in UOHF / Version 1.0** — focused formal and computational publication. DOI: [10.5281/zenodo.21721599](https://doi.org/10.5281/zenodo.21721599).
- **The UOHF Human Function Capacity System / Version 1.0** — public repository preprint of the 18-core/104-specific human-function capacity catalogue. Reserved DOI: `10.5281/zenodo.21975100` (pending Zenodo publication).

UOHF Definition 2.1 remains the current authoritative overall framework. Focused publications develop specific scientific layers under that framework and do not silently replace the root definition.

---

## Current implementation and claim boundary

The governed implementation supports concept domains, stable identifiers, typed relations, relation contracts, evidence structures, authority constraints, lifecycle governance, task-centered state convergence, action semantics, execution feedback, reassessment, and longitudinal monitoring.

This infrastructure-level statement does **not** mean that all 104 fine-grained Version 1.0 capacity objects already have complete production lifecycle activation, task/structure/assessment/intervention endpoint coverage, or Runtime release. Catalogue publication and production release are governed separately.

The complete production ontology, relation topology, implementation rules, and operational data assets are not reproduced in full in this public repository. UOHF does not currently claim completed BFO conformance, completed OWL axiomatization, universal physiological state classification, external expert consensus, clinical outcome validation, a completed molecular-to-person simulator, or autonomous diagnosis/treatment.

---

## Research and collaboration

Relevant collaboration areas include ontology engineering, whole-person and multiscale physiological modeling, human-function reference systems, rehabilitation and exercise science, longitudinal health-state modeling, auditable health AI, semantic interoperability, capacity measurement, and task-centered assessment/action/feedback systems.

See [`COLLABORATION.md`](COLLABORATION.md). For research, interoperability, implementation, or institutional collaboration: **dlehche@gmail.com**

---

## Citation

> Che, Lei. *UOHF Definition 2.1: Unified Ontology of Human Function*. Version 2.1.1. MoveTips Technology (Beijing) Co., Ltd., 2026. DOI: [10.5281/zenodo.21630406](https://doi.org/10.5281/zenodo.21630406).

> Che, Lei. *The UOHF Human Function Capacity System, Version 1.0: Unified Definitions of 18 Core and 104 Specific Human Functional Capacities*. Repository preprint. MoveTips Technology (Beijing) Co., Ltd., 2026. Reserved DOI: `10.5281/zenodo.21975100`.

Paper-specific citation metadata is maintained in each paper directory. Repository-level citation metadata remains in [`CITATION.cff`](CITATION.cff).

---

## Copyright and reuse

**Copyright © 2026 Lei Che and MoveTips Technology (Beijing) Co., Ltd.**

Current UOHF publications are identified as **CC BY-NC 4.0**. Academic citation and non-commercial reuse are permitted subject to the applicable license terms. Commercial use of copyright-protected publication content requires separate permission where copyright permission is required. Repository-wide guidance is maintained in [`RIGHTS_AND_REUSE.md`](RIGHTS_AND_REUSE.md).
