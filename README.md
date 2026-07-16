# MUFO — MoveTips Unified Functional Ontology

## A Unified Ontology for Human Function and the Human Function World Model

[English](README.md) | [中文](MUFO_DEFINITION_ZH.md)

**Current authoritative framework definition:** MUFO Definition 2.1  
**Author:** Lei Che  
**Contributors:** MoveTips Research & Engineering Team  
**Affiliation:** MoveTips Technology (Beijing) Co., Ltd.  
**Correspondence:** dlehche@gmail.com  
**Version:** 2.1  
**Release date:** July 16, 2026  
**Canonical publication:** [MUFO Definition 2.1: A Unified Ontology for Human Function](https://zenodo.org/records/21399269)  
**DOI:** [`10.5281/zenodo.21399269`](https://doi.org/10.5281/zenodo.21399269)  
**Copyright:** © 2026 Lei Che and MoveTips Technology (Beijing) Co., Ltd.

> **Human function is the body's capacity to be appropriately engaged to meet internal and external demands.**

> **“Demand” includes ongoing internal requirements for physiological maintenance, regulation, development, defense, adaptation, repair, and recovery, as well as external behavioral, environmental, and real-world task demands.**

The compact Chinese philosophical definition remains:

> **人体功能，就是身体被正常调用的能力。**

MUFO provides a governed ontology and semantic-rule foundation for representing human function as a shared domain object in computational systems. It is designed to support continuous, evidence-bounded, safety-constrained, traceable, auditable, and revisable reasoning across medicine, physiology, rehabilitation, movement training, behavior, environment, and longitudinal whole-person modeling.

---

## 1. Why MUFO Is Needed

Knowledge about disease, anatomy, physiology, rehabilitation, movement, behavior, and health is extensive. The unresolved problem appears when different professional and computational systems face the same person.

A medical record may describe diagnoses, imaging, laboratory findings, medications, and clinical events. A physiological model may describe organ-system regulation and mechanism. A rehabilitation record may describe pain, task difficulty, and treatment response. A training system may describe load, performance, and recovery. A person may report fatigue, instability, slower recovery, or declining ability to sustain ordinary life tasks.

Each representation may be valid within its own scope, but they do not automatically form one shared object that can continuously answer:

- What internal or external demand is present?
- What must the body organize to meet that demand?
- How is the body actually organizing itself?
- What was observed, reported, or measured?
- What cost and accumulated burden are being carried?
- Where are the current boundaries, and how much reserve remains?
- What human function state is supported under the specified demand, context, evidence, and time?
- What endogenous regulation is occurring?
- What external action, reassessment, or professional entry point is permissible?
- What actually changed after time, exposure, regulation, intervention, or execution?

MUFO addresses this representation, inference, governance, and longitudinal write-back problem at the human function layer.

---

## 2. What Changed in Version 2.1

MUFO Definition 2.1 is a cross-language scope correction and ontology-architecture clarification.

The original Chinese philosophical definition did not limit human function to real-world tasks. Version 2.0 used a task-centered English wording that could be read as the final boundary of the framework. Version 2.1 restores and formally expresses the complete scope:

- **Internal demands:** physiological maintenance, regulation, development, defense, adaptation, repair, and recovery.
- **External demands:** behavioral, environmental, and real-world task demands.
- **Real-world tasks:** a principal operational specialization of external demand, not the total boundary of human function.
- **Functional Engagement:** generalized from task-conditioned organization to demand-conditioned organization.
- **Multiscale trajectory:** molecular, cellular, tissue, organ, organ-system, behavioral, environmental, and whole-person state transitions are included in the intended modeling range, without claiming completed multiscale implementation.

The task-centered operational architecture of Version 2.0 remains valid within its stated scope. Its English root definition is superseded by Version 2.1.

---

## 3. Root Objects

### 3.1 Demand

**Demand** is an internal or external requirement that calls upon the body and creates the conditions under which engagement, burden, boundary, reserve, and state may be evaluated.

MUFO distinguishes:

- **Demand** — the real requirement condition;
- **Demand Specification** — a versioned information object describing that demand;
- **Task** — a goal-directed activity or activity situation;
- **Task Demand** — the external requirement generated, imposed, or specified by the task under relevant context, load, duration, complexity, environment, and consequences;
- **Task Demand Specification** — a versioned representation of that task demand.

A Task is not identical to a Task Demand.

### 3.2 Functional Engagement

**Functional Engagement** is the process through which the body organizes what is required to meet a specified internal or external demand.

Depending on scale and context, engagement may involve molecular and cellular processes, tissues and organs, organ-system interactions, structural support, functional capacities, sensory feedback, motor control, energy supply, metabolic regulation, protective responses, defense, repair, recovery, cognitive participation, behavioral participation, and interaction with environmental conditions.

Functional Engagement is not equivalent to conscious command, one muscle contraction, one joint motion, one organ process, one laboratory value, or one isolated capacity.

### 3.3 Required and Actual Engagement

MUFO separates:

- **Engagement Requirement** — what organization must be realized for a demand to be adequately met;
- **Required Engagement Process Type** — the type of process expected to realize that requirement;
- **Actual Engagement Process** — the real process that occurs;
- **Actual Engagement Inference** — an evidence-bounded conclusion about that process;
- **Actual Engagement Representation** — a versioned information object representing the inference.

A requirement, a process type, a real process, an inference, and an information representation are not the same entity.

### 3.4 Appropriate Engagement

At the generalized level, appropriate engagement requires:

1. the demand is adequately met;
2. the organization remains sufficiently stable and adaptive;
3. cost and regulatory burden remain within context-, time-, and demand-dependent sustainable boundaries.

Safety remains a separate constraint layer.

For real-world tasks, the current operational specialization remains:

1. task goal achievable;
2. organization relatively stable;
3. associated cost controllable.

---

## 4. Core Object Distinctions

MUFO explicitly separates domain objects, processes, inferences, and information representations. Core distinctions include:

- Human Function is not Human Function State.
- Human Function State is not State Inference.
- State Inference is not State Representation.
- Task is not Task Demand.
- Demand is not Demand Specification.
- Actual Engagement Process is not Actual Engagement Inference or Representation.
- Actual Response is not Manifestation.
- Manifestation is not Measurement Result.
- Immediate Cost is not Accumulated Burden.
- Boundary is not Reserve.
- Endogenous Regulation is not Governed External Action.
- Actual Response is not necessarily identical to Actual Change.
- Actual Change is not Feedback Information.
- Observation is not explanation.

Unverified explanations must not silently become factual records. Candidate inferences remain open to verification, falsification, revision, and recomputation.

---

## 5. Generalized Semantic Architecture

The generalized MUFO architecture is a governed state-transition loop rather than one undifferentiated chain:

> **Internal or External Demand**  
> → **Engagement Requirement**  
> → **Required Engagement Process Type**  
> → **Actual Engagement Process**  
> → **Actual Response**  
> → **Manifestation and Measurement Result**  
> → **Immediate Cost and Accumulated Burden**  
> → **Boundary and Reserve Estimates**  
> → **Domain-/Scale-Specific State Inference and Representation**  
> → **Person-Level Human Function State Inference and Representation, where applicable**

Actual Change may arise through external action, endogenous regulation, continued time, exposure, or uncontrolled events:

> **Governed External Action where applicable and permitted, and/or Endogenous Regulation / Time / Exposure / Event**  
> → **Actual Change**  
> → **New Evidence**  
> → **Feedback Interpretation**  
> → **Reassessment**  
> → **Versioned Write-back**

MUFO does not authorize endogenous regulation. It observes, represents, and evaluates it. Governance gates apply to external action, professional response, and system behavior.

---

## 6. Current Task-Centered Operational Specialization

Current implementation is strongest in real-world task reasoning and longitudinal service workflows.

The task-centered operational chain is:

> **Safety Boundary**  
> → **Task + Context**  
> → **Task Demand / Task Demand Specification**  
> → **Engagement Requirement**  
> → **Required Engagement Process Type**  
> → **Actual Engagement Process, Inference, and Representation**  
> → **Actual Response**  
> → **Manifestation and Measurement Result**  
> → **Immediate Cost, Accumulated Burden, Boundary, and Reserve Estimate**  
> → **Limiting-Factor Hypotheses**  
> → **Evidence Convergence**  
> → **Primary-Problem Convergence**  
> → **Person-Level Human Function State Inference and Representation**  
> → **Governed Action Direction and Execution**  
> → **Actual Change**  
> → **New Evidence**  
> → **Feedback and Reassessment**  
> → **Versioned Write-back**

This chain supports assessment, safety gating, action selection, execution, feedback, reassessment, and longitudinal updating without treating one observation or score as a final explanation.

---

## 7. Person-Level Task-Centered State Framework

MUFO currently retains four foundational state classes for person-level, task-centered inference:

| State | Functional interpretation |
|---|---|
| **Normal Functional State** | The task is achievable; engagement is relatively stable; cost is controllable; usable reserve remains. |
| **Compensatory Functional State** | The task remains achievable, but engagement has changed and higher cost or burden is being carried. |
| **Boundary-Critical Functional State** | The task may remain achievable, but usable reserve has substantially narrowed and small demand changes may cross the current boundary. |
| **Functional Incapacity State** | The demand cannot be adequately met through any currently available or admissible Required Engagement Process Type; the task is impossible or severely limited under the stated conditions. |

These states:

- are task-, context-, evidence-, and time-dependent;
- are not medical diagnoses;
- are not permanent identities;
- are not asserted as universal labels for organ, cellular, molecular, or other multiscale processes.

Internal-demand and multiscale contexts may require linked or different domain-specific state frameworks.

---

## 8. Governed Architecture

MUFO Definition 2.1 distinguishes four connected components.

### MUFO

The governed ontology and semantic-rule layer. It defines objects, relations, constraints, evidence semantics, state rules, safety boundaries, action semantics, provenance, versioning, and lifecycle governance.

### Human Function Engine

The bounded runtime layer that reads governed MUFO assets and evidence, applies constraints and inference logic, produces current inferences and representations, and supports versioned write-back.

### Individual Human Function Model — IHFM

The person-specific longitudinal state memory. It preserves current and historical state representations, context, evidence, boundaries, reserve estimates, actions, feedback, reassessments, provenance, and version identity.

### Human Function World Model — HFWM

The temporal and action-conditioned modeling layer. It represents or learns how relevant states may change under demand, context, time, exposure, endogenous regulation, and external action.

A predicted state representation is not a current inferred state representation. Prediction must remain separately identified, evaluated, revised, or expired.

---

## 9. Bidirectional Disease–Function Reasoning

Disease and human function are distinct but connected objects.

### Disease, mechanism, and medical events → human function impact

Diseases, injuries, surgeries, medications, abnormal tests, pathological mechanisms, and clinical events may alter structures, capacities, regulation, recovery, boundaries, reserve, task tolerance, engagement strategies, and permissible action.

### Longitudinal human function change → disease-risk candidates

Persistent compensatory engagement, repeated exposure beyond current boundaries, progressive reserve narrowing, declining recovery capacity, repeated unexplained manifestations, and longitudinal decline in life-task ability may become candidate risk signals.

MUFO may support risk-window identification, escalation triggers, and evidence packaging for clinical review. This is upward signal reasoning, not autonomous diagnosis.

---

## 10. Specialized AI and Model Coordination

Medicine, physiology, rehabilitation, movement training, nutrition, psychology, sleep, behavior, and environmental-health systems may each contribute specialized models.

MUFO does not collapse them into one universal model. It provides a governed coordination layer for:

- object identity and semantic mapping;
- relation alignment;
- evidence and uncertainty annotation;
- scale, time, and context preservation;
- authority and professional-scope constraints;
- conflict identification;
- state-impact analysis;
- provenance and version control;
- write-back to the same IHFM.

The objective is to allow specialized models to work around the same whole person without losing scientific scope, semantic identity, professional boundaries, or longitudinal continuity.

---

## 11. Relationship With Existing Standards and Models

MUFO does not replace ICF, SNOMED CT, UMLS, PROV-O, OWL, JSON-LD, OBO Foundry ontologies, BFO, Uberon, Gene Ontology, the Human Reference Atlas, Physiome, CellML, or domain-specific physiological and clinical models.

MUFO uses mapping, provenance, and interoperability strategies. External concepts should retain their established identifiers and meanings. MUFO-specific objects and relations provide a human-function coordination and governance layer across demands, engagement, state, action, feedback, and longitudinal change.

---

## 12. Current Implementation and Claim Boundary

The governed implementation currently supports concept domains, stable internal identifiers, typed relations, relation contracts, evidence structures, authority constraints, lifecycle governance, task-centered state convergence, action semantics, execution feedback, reassessment, and longitudinal monitoring.

The complete production ontology, relation topology, implementation rules, and operational data assets are not reproduced in full in this public framework definition.

Version 2.1 does **not** claim:

- completed BFO conformance;
- completed OWL axiomatization;
- universal physiological state classification;
- external expert consensus;
- clinical outcome validation;
- a completed molecular-to-person simulator;
- autonomous diagnosis or treatment.

Internal-demand operationalization and multiscale modeling remain research, formalization, and validation work.

---

## 13. Four-Stage Development Pathway

1. **MUFO Object–Relation Topology and Human Function Collaboration Network**  
   Governed objects, relations, evidence, authority, safety, and lifecycle rules.

2. **Human Function Engine and IHFM Operational Loop**  
   Evidence-bounded current-state inference, action support, feedback, reassessment, and longitudinal write-back.

3. **Multiscale Human Function World Model**  
   Temporal and action-conditioned modeling across physiological, behavioral, environmental, and whole-person state transitions.

4. **Integrated Computable Whole-Person System**  
   Coordinated use of validated domain models, multiscale representations, person-specific memory, prediction, and governed decision support.

> **Governed ontology topology → Human Function Engine → Human Function World Model → Integrated computable whole-person system**

---

## 14. Scope Clarification

MUFO is a knowledge-representation, semantic-governance, and decision-support framework.

It is not:

- a medical diagnosis system;
- an autonomous treatment system;
- a completed whole-person physiological simulator;
- a replacement for licensed professional judgment;
- a movement library or test collection;
- a universal black-box AI model.

Disease diagnosis, medical restrictions, prescriptions, surgery decisions, emergency assessment, and other regulated clinical actions remain within the relevant professional and legal scope.

---

## 15. Read and Cite

**Canonical publication**

> Che, Lei. *MUFO Definition 2.1: A Unified Ontology for Human Function*. MoveTips Technology (Beijing) Co., Ltd., 2026. DOI: [10.5281/zenodo.21399269](https://doi.org/10.5281/zenodo.21399269).

Zenodo record: <https://zenodo.org/records/21399269>

Repository citation metadata is maintained in [`CITATION.cff`](CITATION.cff).

### Version history

- **MUFO V1.0** — initial ontology-driven, safety-constrained, auditable human function inference framework and early TCM/MVSS operationalization.
- **MUFO Definition 2.0** — task-centered functional-engagement architecture, semantic state–action spine, operational inference sequence, continuous write-back, and separation of MUFO, IHFM, and HFWM.
- **MUFO Definition 2.1** — current authoritative framework definition; restores the full English scope of the Chinese philosophical definition, introduces internal and external Demand, separates Task from Task Demand, generalizes Functional Engagement, and defines the multiscale development trajectory.

---

## 16. Copyright and Reuse

**Copyright © 2026 Lei Che and MoveTips Technology (Beijing) Co., Ltd.**

The copyright holders retain authorship and version identity for the MUFO framework definition. Record-specific access, license, attribution, and reuse terms are governed by the canonical Zenodo record:

<https://zenodo.org/records/21399269>

When citing, adapting, translating, mapping, or implementing MUFO, preserve:

- the author and copyright attribution;
- the MUFO name and version number;
- the canonical DOI;
- provenance of modifications and mappings;
- the distinction between the public framework definition and governed production assets;
- the medical, safety, evidence, and professional-scope limitations stated in the paper.

---

MoveTips Technology (Beijing) Co., Ltd.  
**MOVETIPS**  
Human Function, in One Shared Language.
