# MUFO — MoveTips Unified Functional Ontology

## A governed ontology for human function and the Human Function World Model

[中文](README.zh-CN.md) · [Definition 2.1 paper](https://doi.org/10.5281/zenodo.21399269) · [Unification paper](papers/unification/README.md) · [Version archive](versions/README.md) · [Citation metadata](CITATION.cff)

**Current authoritative framework:** MUFO Definition 2.1  
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

## What problem does MUFO solve?

Medicine, physiology, rehabilitation, movement training, behavior, environment, and personal health records can all describe the same person, but they do not automatically form one shared computational object.

MUFO establishes **human function** as that shared object and provides a governed semantic and rule foundation for asking:

- What internal or external demand is present?
- What must the body organize to meet it?
- How is the body actually being engaged?
- What was observed, reported, measured, or inferred?
- What cost, burden, boundary, and reserve are relevant?
- What state is supported by the current evidence?
- What action is permissible, and what changed afterward?

The objective is not to replace domain expertise. It is to make cross-domain human-function reasoning **computable, constrained, traceable, auditable, revisable, and longitudinally continuous**.

---

## Why MUFO is different

MUFO is not a terminology list, a generic knowledge graph, a medical diagnosis engine, or a black-box recommendation model.

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

MUFO Definition 2.1 distinguishes four connected components:

1. **MUFO** — governed ontology and semantic-rule layer;
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
| [MUFO Definition 2.1](https://doi.org/10.5281/zenodo.21399269) | Current authoritative framework paper |
| [Unification in MUFO](papers/unification/README.md) | Bilingual focused paper on unification, human function, and functional engagement; Zenodo DOI 10.5281/zenodo.21618293 |
| [中文概览](README.zh-CN.md) | Concise Chinese repository introduction |
| [中文完整定义](MUFO_DEFINITION_ZH.md) | Detailed Chinese framework definition |
| [Version archive](versions/README.md) | V1.0, Definition 2.0, and Definition 2.1 history |
| [Minimal task-centered example](examples/minimal-task-centered-case.json) | Non-normative example of structured reasoning objects |
| [CITATION.cff](CITATION.cff) | Formal citation metadata |

---

## Version history

- **MUFO V1.0** — initial ontology-driven, safety-constrained, auditable human-function inference framework; eight decision factors, Task–Capacity Matching, and early MVSS operationalization.
- **MUFO Definition 2.0** — task-centered Functional Engagement architecture, semantic state–action spine, observation–inference separation, continuous write-back, and separation of MUFO, IHFM, and HFWM.
- **MUFO Definition 2.1** — current authoritative framework; restores the full internal-and-external-demand scope, distinguishes Task from Task Demand, generalizes Functional Engagement, and defines the multiscale development trajectory.

Historical versions remain citable under their own DOI and are preserved in the [version archive](versions/README.md).

---

## Current implementation and claim boundary

The governed implementation currently supports concept domains, stable identifiers, typed relations, relation contracts, evidence structures, authority constraints, lifecycle governance, task-centered state convergence, action semantics, execution feedback, reassessment, and longitudinal monitoring.

The complete production ontology, relation topology, implementation rules, and operational data assets are not reproduced in full in this public repository.

MUFO Definition 2.1 does **not** claim:

- completed BFO conformance;
- completed OWL axiomatization;
- universal physiological state classification;
- external expert consensus;
- clinical outcome validation;
- a completed molecular-to-person simulator;
- autonomous diagnosis or treatment.

Internal-demand operationalization and multiscale modeling remain active research, formalization, and validation work.

---

## Relationship to existing standards and models

MUFO does not replace ICF, SNOMED CT, UMLS, PROV-O, OWL, JSON-LD, OBO Foundry ontologies, BFO, Uberon, Gene Ontology, the Human Reference Atlas, Physiome, CellML, or domain-specific physiological and clinical models.

MUFO uses mapping, provenance, and interoperability strategies so that external concepts retain their established identity and scientific scope while contributing to a shared human-function model.

---

## Research and collaboration

Relevant collaboration areas include:

- ontology engineering and knowledge representation;
- whole-person and multiscale physiological modeling;
- rehabilitation, movement science, and human performance;
- longitudinal health-state modeling;
- auditable and safety-constrained health AI;
- semantic interoperability across specialized models;
- task-centered assessment, action, feedback, and reassessment systems.

For research, interoperability, implementation, or institutional collaboration: **dlehche@gmail.com**

---

## Citation

> Che, Lei. *MUFO Definition 2.1: A Unified Ontology for Human Function*. MoveTips Technology (Beijing) Co., Ltd., 2026. DOI: [10.5281/zenodo.21399269](https://doi.org/10.5281/zenodo.21399269).

Repository citation metadata is maintained in [`CITATION.cff`](CITATION.cff).

---

## Copyright and reuse

**Copyright © 2026 Lei Che and MoveTips Technology (Beijing) Co., Ltd.**

Record-specific access, license, attribution, and reuse terms are governed by the corresponding canonical Zenodo record. When citing, adapting, translating, mapping, or implementing MUFO, preserve the author, version identity, canonical DOI, provenance of modifications, and the medical, safety, evidence, and professional-scope limitations stated in the publication.
