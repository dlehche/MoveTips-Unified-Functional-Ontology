# Unified Ontology of Human Function (UOHF)

## A governed semantic and computational ontology for human function and the Human Function World Model

[中文](README.zh-CN.md) · [Definition 2.1 paper](https://doi.org/10.5281/zenodo.21399269) · [Unification paper](papers/unification/README.md) · [Version archive](versions/README.md) · [Citation metadata](CITATION.cff) · [Rights and reuse](RIGHTS_AND_REUSE.md) · [Collaboration](COLLABORATION.md)

**Official name:** Unified Ontology of Human Function  
**Official abbreviation:** UOHF  
**Current authoritative framework:** UOHF Definition 2.1  
**Author:** Lei Che  
**Affiliation:** MoveTips Technology (Beijing) Co., Ltd.  
**Correspondence:** dlehche@gmail.com  
**DOI:** [10.5281/zenodo.21399269](https://doi.org/10.5281/zenodo.21399269)  
**Copyright:** © 2026 Lei Che and MoveTips Technology (Beijing) Co., Ltd.

**Philosophical starting point:**

> **Life continually calls upon the body.**

**Formal definition:**

> **Human function is the body's capacity to be appropriately engaged to meet internal and external demands.**

**Chinese philosophical definition:**

> **人体功能，就是身体被正常调用的能力。**

---

## Latest focused publication

### Unification in the Unified Ontology of Human Function

**A Whole-Person Conceptual Framework Centered on Human Function and Functional Engagement**

This focused Version 1.0 paper explains what UOHF unifies, why functional engagement belongs inside the concept of human function, and how function, demand, bodily structure, bodily process, coordination, compensation, boundaries, state, time, and change are returned to the same whole person.

- **[Read the English text](papers/unification/UOHF_Unification_EN_V1.0.md)**
- **[阅读中文全文](papers/unification/UOHF_Unification_ZH_V1.0.md)**
- [Canonical Zenodo publication: 10.5281/zenodo.21618293](https://doi.org/10.5281/zenodo.21618293)
- [Paper overview and citation](papers/unification/README.md)

> **Unification in UOHF means using one coherent semantic system to describe human functions as they exist within an integrated whole person, together with their functional engagement.**

---

## What problem does UOHF solve?

Medicine, physiology, rehabilitation, movement training, behavior, environment, and personal health records can all describe the same person, but they do not automatically form one shared computational object.

UOHF establishes **human function** as that shared object and provides a governed semantic and rule foundation for asking:

- What internal or external demand is present?
- What must the body organize to meet it?
- How is the body actually being engaged?
- What was observed, reported, measured, or inferred?
- What cost, burden, boundary, and reserve are relevant?
- What state is supported by the current evidence?
- What action is permissible, and what changed afterward?

The objective is not to replace domain expertise. It is to make cross-domain human-function reasoning **computable, constrained, traceable, auditable, revisable, and longitudinally continuous**.

---

## Why UOHF is different

UOHF is not a terminology list, a generic knowledge graph, a medical diagnosis engine, or a black-box recommendation model.

It explicitly separates:

- **Demand** from **Demand Specification**;
- **Task** from **Task Demand**;
- **Engagement Requirement** from **Actual Engagement Process**;
- **Actual Engagement Process** from its **Inference** and **Representation**;
- **Actual Response** from **Manifestation** and **Measurement Result**;
- **Immediate Cost** from **Accumulated Burden**;
- **Boundary** from **Reserve**;
- **Human Function State** from **State Inference** and **State Representation**;
- **Endogenous Regulation** from **Governed External Action**;
- **Actual Change** from **Feedback Information**.

This distinction between reality, evidence, inference, and representation is central to auditable AI and governed decision support.

---

## Core architecture

```mermaid
flowchart LR
    D[Internal or External Demand] --> ER[Engagement Requirement]
    ER --> REP[Required Engagement Process Type]
    REP --> AEP[Actual Engagement Process]
    AEP --> AR[Actual Response]
    AR --> E[Manifestation and Measurement]
    E --> C[Cost, Burden, Boundary, Reserve]
    C --> SI[State Inference and Representation]
    SI --> G[Governed Action / Endogenous Regulation / Time / Exposure]
    G --> AC[Actual Change]
    AC --> F[New Evidence and Feedback]
    F --> R[Reassessment and Versioned Write-back]
    R --> SI
```

UOHF Definition 2.1 distinguishes four connected components:

1. **UOHF** — governed ontology and semantic-rule layer;
2. **Human Function Engine** — bounded runtime inference and write-back layer;
3. **Individual Human Function Model (IHFM)** — person-specific longitudinal state memory;
4. **Human Function World Model (HFWM)** — temporal and action-conditioned state-transition modeling.

> **Governed ontology topology → Human Function Engine → Individual longitudinal model → Human Function World Model**

---

## Current operational specialization

Current implementation is strongest in real-world task reasoning and longitudinal service workflows:

> **Safety Boundary → Task and Context → Task Demand → Required Engagement → Actual Engagement → Manifestation and Measurement → Cost and Boundary → Limiting-Factor Hypotheses → Evidence Convergence → Primary Problem → State → Governed Action → Execution → Actual Change → Feedback → Reassessment → Write-back**

The four current person-level task-centered state classes are:

- **Normal Functional State**
- **Compensatory Functional State**
- **Boundary-Critical Functional State**
- **Functional Incapacity State**

These are not medical diagnoses, permanent identities, or universal labels for organ, cellular, or molecular processes.

---

## Start here

| Resource | Purpose |
|---|---|
| [UOHF Definition 2.1](https://doi.org/10.5281/zenodo.21399269) | Current authoritative framework paper |
| [Unification paper — English text](papers/unification/UOHF_Unification_EN_V1.0.md) | Version-controlled English academic text |
| [“统一”论文——中文全文](papers/unification/UOHF_Unification_ZH_V1.0.md) | 中文概念预印本全文 |
| [中文概览](README.zh-CN.md) | Concise Chinese repository introduction |
| [中文完整定义](UOHF_DEFINITION_ZH.md) | Detailed Chinese framework definition |
| [Public ontology release status](ontology/README.md) | Current machine-readable release boundary and release requirements |
| [Version archive](versions/README.md) | V1.0, Definition 2.0, and Definition 2.1 history |
| [Minimal task-centered example](examples/minimal-task-centered-case.json) | Non-normative example of structured reasoning objects |
| [CITATION.cff](CITATION.cff) | Formal citation metadata |
| [Rights and reuse](RIGHTS_AND_REUSE.md) | Publication, reuse, attribution, and repository-rights guidance |
| [Research and collaboration](COLLABORATION.md) | Collaboration priorities and contribution routes |

---

## Version history

- **UOHF V1.0** — initial ontology-driven, safety-constrained, auditable human-function inference framework; eight decision factors, Task–Capacity Matching, and early MVSS operationalization.
- **UOHF Definition 2.0** — task-centered Functional Engagement architecture, semantic state–action spine, observation–inference separation, continuous write-back, and separation of UOHF, IHFM, and HFWM.
- **UOHF Definition 2.1** — current authoritative framework; restores the full internal-and-external-demand scope, distinguishes Task from Task Demand, generalizes Functional Engagement, and defines the multiscale development trajectory.

Historical versions remain citable under their own DOI and are preserved in the [version archive](versions/README.md).

---

## Current implementation and claim boundary

The governed implementation currently supports concept domains, stable identifiers, typed relations, relation contracts, evidence structures, authority constraints, lifecycle governance, task-centered state convergence, action semantics, execution feedback, reassessment, and longitudinal monitoring.

The complete production ontology, relation topology, implementation rules, and operational data assets are not reproduced in full in this public repository.

UOHF Definition 2.1 does **not** claim:

- completed BFO conformance;
- completed OWL axiomatization;
- universal physiological state classification;
- external expert consensus;
- clinical outcome validation;
- a completed molecular-to-person simulator;
- autonomous diagnosis or treatment.

Internal-demand operationalization and multiscale modeling remain active research, formalization, and validation work.

The status and release requirements for a future reviewed public OWL/Turtle/RDF/JSON-LD/SHACL subset are documented in [`ontology/README.md`](ontology/README.md). No unreviewed formal file is presented as the authoritative production ontology.

---

## Relationship to existing standards and models

UOHF does not replace ICF, SNOMED CT, UMLS, PROV-O, OWL, JSON-LD, OBO Foundry ontologies, BFO, Uberon, Gene Ontology, the Human Reference Atlas, Physiome, CellML, or domain-specific physiological and clinical models.

UOHF uses mapping, provenance, and interoperability strategies so that external concepts retain their established identity and scientific scope while contributing to a shared human-function model.

---

## Research and collaboration

Relevant collaboration areas include ontology engineering, whole-person and multiscale physiological modeling, rehabilitation and movement science, longitudinal health-state modeling, auditable health AI, semantic interoperability, and task-centered assessment, action, feedback, and reassessment systems.

See [`COLLABORATION.md`](COLLABORATION.md) for contribution routes, current priorities, and claim boundaries.

For research, interoperability, implementation, or institutional collaboration: **dlehche@gmail.com**

---

## Citation

> Che, Lei. *UOHF Definition 2.1: Unified Ontology of Human Function*. MoveTips Technology (Beijing) Co., Ltd., 2026. DOI: [10.5281/zenodo.21399269](https://doi.org/10.5281/zenodo.21399269).

Repository citation metadata is maintained in [`CITATION.cff`](CITATION.cff). The focused unification paper has separate citation metadata in [`papers/unification/CITATION.cff`](papers/unification/CITATION.cff).

---

## Copyright and reuse

**Copyright © 2026 Lei Che and MoveTips Technology (Beijing) Co., Ltd.**

Record-specific access, license, attribution, and reuse terms are governed by the corresponding canonical Zenodo record. Repository-wide guidance is maintained in [`RIGHTS_AND_REUSE.md`](RIGHTS_AND_REUSE.md).

When citing, adapting, translating, mapping, or implementing UOHF, preserve the author, version identity, canonical DOI, provenance of modifications, and the medical, safety, evidence, and professional-scope limitations stated in the publication.
