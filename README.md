# MUFO — MoveTips Unified Functional Ontology

## A Unified Ontology for Human Function and the Human Function World Model

**Current authoritative framework: MUFO Definition 2.0**

**Proposed by:** Lei Che  
**Developed by:** Lei Che Research & Engineering Team, MoveTips Technology (Beijing) Co., Ltd.  
**Canonical publication:** [MUFO Definition 2.0: A Unified Ontology for Human Function](https://doi.org/10.5281/zenodo.21368412)  
**DOI:** `10.5281/zenodo.21368412`  
**Version:** 2.0  
**Copyright © 2026 Lei Che and MoveTips Technology (Beijing) Co., Ltd.**

> **Human function is the body's capacity to be appropriately engaged for real-world tasks.**

MUFO establishes **human function as a shared computational object**.

Its purpose is to provide a unified semantic and rule foundation through which medicine, rehabilitation, movement training, other professional systems, and specialized AI models can work around the **continuous human function state of the same person**.

For the complete framework, relation semantics, operational inference sequence, implementation position, limitations, and validation agenda, see **MUFO Definition 2.0**.

---

## The Problem

Human knowledge about disease, anatomy, rehabilitation, movement, behavior, and health is extensive.

The deeper problem appears when different professional systems face **the same individual**.

A medical record may describe diagnoses, imaging, laboratory findings, medication, and clinical events. A rehabilitation record may describe pain, range of motion, balance, task difficulty, and treatment response. A training system may describe load, exercise performance, recovery, and progression. Real life may reveal fatigue, instability, pain, slower recovery, or a growing inability to sustain ordinary tasks.

Each representation may be valid within its own scope.

They do not automatically form a stable shared computational object that can continuously answer:

- What real-world task is this person trying to undertake?
- What must the body engage to meet that task?
- How is the body actually organizing itself?
- What was directly observed?
- What cost is being paid?
- Where is the current boundary?
- What is the person's current functional state?
- What action is permissible now?
- What changed after execution?

MUFO addresses this representation and inference problem at the **human function layer**.

---

## The Root Object: Human Function

MUFO defines human function as:

> **Human function is the body's capacity to be appropriately engaged for real-world tasks.**

This definition is task-oriented, but it is not reducible to task completion.

A person may complete a task through marked breath holding, external support, slowed speed, painful protection, excessive tension, repeated interruption, or a recovery cost that prevents the next task.

MUFO therefore distinguishes between:

> **producing a task outcome**

and

> **establishing appropriate functional engagement**.

### Functional engagement

In MUFO, **functional engagement** is the process through which the body organizes the resources required to undertake a specific task.

These resources may include:

- structural support;
- functional capacities;
- sensory feedback;
- motor control;
- energy supply;
- protective responses;
- recovery regulation;
- cognitive participation;
- behavioral participation.

Functional engagement is not equivalent to conscious command. It is not one muscle contraction, one joint motion, or one isolated capacity.

> **It is a task-conditioned organization process.**

This provides a semantic middle layer between biological mechanism and visible task outcome.

### Appropriate engagement

MUFO currently uses three foundational conditions:

1. **Task goal achievable**
2. **Organization relatively stable**
3. **Associated cost controllable**

Safety boundaries remain a separate constraint layer.

---

## Human Function as a Shared Computational Object

The need for MUFO does not arise from the absence of the word *function*.

It arises from the absence of a sufficiently stable shared object for **longitudinal cross-domain inference**.

MUFO assigns different concepts to different semantic roles:

- **Disease** provides medical context, mechanism, and safety constraints.
- **Movement** provides an observable window into functional organization.
- **Structure** provides anatomical anchors.
- **Functional capacity** represents a capability that may be required and engaged.
- **Assessment and measurement** provide evidence.
- **Action** represents a bounded attempt to alter a state or its conditions.
- **Human function** is the shared object continuously observed, inferred, and influenced.

A shared object does not imply shared professional authority.

MUFO preserves professional scope, evidence requirements, confirmation rights, and bounded action permissions.

---

## A Governed Semantic Coordinate System

MUFO is not a terminology list and is not defined as an ordinary knowledge graph.

A relation in MUFO must be more informative than **"associated with."**

The governed object space includes, but is not limited to:

- real-world tasks and task contexts;
- task demands;
- functional capacities;
- anatomical structures and structural anchors;
- actual engagement patterns;
- observable manifestations;
- costs and post-task burdens;
- safety and task boundaries;
- diseases, injuries, surgeries, medications, and clinical events as contextual constraints;
- assessments, tests, scales, observations, and evidence;
- limiting-factor candidates and primary-problem candidates;
- human function states;
- recommendation directions and professional entry points;
- solution methods and execution arrangements;
- execution feedback;
- reassessment;
- longitudinal monitoring.

MUFO governs how these objects may be related.

A governed relation may require:

- direction;
- relation type;
- domain and range constraints;
- applicable conditions;
- evidence requirements;
- role or authority restrictions;
- provenance;
- version;
- lifecycle status.

The objective is to make human function knowledge **computable, constrained, traceable, auditable, and continuously updatable**.

---

## Core Semantic State–Action Spine

MUFO 2.0 uses the following high-level semantic spine:

> **Task → Engagement → Manifestation → Cost → Boundary → State → Action → Feedback**

The operational inference sequence is more explicit:

> **Safety Boundary → Task → Required Engagement → Actual Engagement → Manifestation → Cost → Boundary → Limiting-Factor Hypotheses → Evidence Convergence → Primary Problem → State → Action Direction → Execution → Feedback → Reassessment → Write-back**

The semantic spine provides a stable cross-domain coordinate system.

The operational sequence preserves evidence handling, limiting-factor hypotheses, primary-problem convergence, action, reassessment, and longitudinal revision.

### Observation is not explanation

A foundational governance rule in MUFO is:

> **What was observed and why it may have happened must remain separate.**

Manifestation is not cause.

An unverified explanation must not silently become a factual record.

Candidate inferences remain open to:

> **verification, falsification, revision, and recomputation.**

---

## Human Function State

State is not a permanent label.

It is a task-, context-, evidence-, and time-dependent inference outcome.

MUFO currently uses four foundational state classes:

| State | Functional interpretation |
|---|---|
| **Normal** | The task is achievable; engagement is relatively stable; cost is controllable; usable reserve remains. |
| **Compensatory** | The task remains achievable, but engagement has changed and a higher cost is being paid. |
| **Critical** | The task may remain achievable, but functional reserve has substantially narrowed and small demand changes may cross the current boundary. |
| **Functional Incapacity** | Required engagement cannot be effectively established or maintained; the task is clearly impossible or severely limited. |

These states are **not medical diagnoses**.

---

## Three-Layer Architecture

MUFO 2.0 explicitly separates three architectural layers.

### 1. MUFO

MUFO defines how the human function domain is represented and constrained.

It provides:

> **objects • relations • constraints • evidence semantics • state rules • safety boundaries • action semantics • feedback semantics • provenance • versioning**

MUFO answers:

> **What kinds of things exist in this reasoning domain, how may they relate, and under what rules may they participate in inference and action?**

### 2. Individual Human Function Model — IHFM

The IHFM records the longitudinal state of one person within the semantic coordinates provided by MUFO.

It is not simply a health record.

> **It is structured person-specific state memory organized around human function.**

### 3. Human Function World Model — HFWM

The HFWM adds time, action, transition, and prediction.

At a high level:

> **s(t+1) ~ F(s(t), a(t), c(t), h(t))**

where:

- `s(t)` is the current functional-state representation;
- `a(t)` is an action or exposure;
- `c(t)` is the current task and context;
- `h(t)` is relevant longitudinal history.

State-transition components may be rule-based, probabilistic, learned, or hybrid, provided that safety constraints, provenance, and inference boundaries remain governed.

The relationship among the three layers is:

> **MUFO defines the human function world.**
>
> **The IHFM records one person's longitudinal position in that world.**
>
> **The HFWM learns or models how that position may change under time, context, and action.**

### Development progression

> **MUFO → Individual Human Function Model → Human Function World Model**

Or operationally:

> **define the domain → infer current state → preserve longitudinal state memory → model action-conditioned transitions**

---

## Bidirectional Disease–Function Reasoning

MUFO does not position human function outside medicine.

Disease and human function are distinct semantic objects that interact in both directions.

### Disease and medical events → human function impact

Diseases, injuries, surgeries, medications, abnormal tests, and pathological mechanisms may affect structures, capacities, recovery conditions, safety boundaries, task tolerance, and engagement strategies.

MUFO organizes how medical context may change functional interpretation and permissible action.

### Longitudinal human function change → disease-risk candidates

Persistent compensatory engagement, repeated exposure beyond current boundaries, progressive narrowing of task reserve, declining recovery capacity, repeated unexplained manifestations, and longitudinal decline in life-task ability may become candidate risk signals.

MUFO may support:

- risk-window identification;
- early-change signal organization;
- escalation triggers;
- evidence packaging for clinical review.

This is **upward signal reasoning**, not autonomous diagnosis.

---

## Specialized AI Model Coordination

Medicine, rehabilitation, movement training, nutrition, psychology, and other fields may each develop increasingly capable specialized AI models.

Their outputs do not automatically share:

- object identity;
- evidence semantics;
- state definitions;
- authority boundaries;
- temporal context.

MUFO provides a human-function semantic coordination layer that can support:

- semantic object mapping;
- semantic normalization;
- relation alignment;
- evidence annotation;
- authority-constraint checking;
- conflict identification;
- state-impact analysis;
- provenance recording;
- write-back to the same IHFM.

The objective is not one universal **"super model."**

> **The objective is to allow specialized models to work around the same person without losing semantic identity, professional boundaries, or longitudinal continuity.**

---

## Current Operational Position

MUFO 2.0 is not presented only as a conceptual ontology proposal.

A governed operational implementation is under active development and is already used to organize:

- governed concept domains;
- stable internal identifiers;
- typed semantic relations;
- relation contracts;
- domain and range constraints;
- relation direction and applicable-condition rules;
- ontology-asset lifecycle governance;
- evidence interpretation structures;
- limiting-factor hypothesis representation;
- primary-problem convergence;
- state convergence;
- action-direction semantics;
- execution and feedback semantics;
- longitudinal write-back and monitoring.

The current operational architecture can be summarized as:

> **Task semantics → Functional capacity requirements → Structural anchors → Assessment evidence → Limiting-factor hypotheses → Primary-problem convergence → State inference → Action direction → Execution → Feedback → Longitudinal monitoring**

The complete production ontology, relationship topology, relation contracts, governance state, and operational data assets are maintained as governed implementation assets and are **not reproduced in full in the public framework definition**.

---

## Relationship With Existing Standards

MUFO does not replace ICF, SNOMED CT, UMLS, or established anatomical and clinical terminology systems.

MUFO uses a **mapping and interoperability strategy**.

External medical, anatomical, assessment, and other domain concepts should retain established identifiers and semantics where available. Human-function-specific concepts and relations may be governed within MUFO and connected to external systems through explicit mapping objects.

MUFO focuses specifically on:

> **how the body is engaged in real-world tasks, how current human function state is inferred, how evidence and safety constrain that inference, and how state enters action, feedback, and longitudinal updating.**

---

## What MUFO Is Not

MUFO is not:

- a medical diagnosis system;
- an autonomous treatment system;
- a replacement for physicians or licensed professional judgment;
- a movement library;
- a collection of tests or scales;
- a universal black-box AI model.

MUFO is a **knowledge-representation, semantic-governance, and decision-support framework**.

Its purpose is to make human function inference more bounded, replayable, inspectable, auditable, and revisable.

---

## Read and Cite MUFO Definition 2.0

**Canonical publication**

> **Lei Che Research & Engineering Team. MUFO Definition 2.0: A Unified Ontology for Human Function. MoveTips Technology (Beijing) Co., Ltd.; 2026.**

**DOI:** `10.5281/zenodo.21368412`

Canonical record: https://doi.org/10.5281/zenodo.21368412

For formal citation, use the canonical publication above or the repository citation metadata in [`CITATION.cff`](CITATION.cff).

MUFO V1.0 remains part of the version history. **MUFO Definition 2.0 is the current authoritative framework definition.**

---

## Scope Clarification

MUFO is a knowledge-representation, semantic-governance, and decision-support framework. It is not a medical diagnosis system, autonomous treatment system, or substitute for licensed professional judgment.

Disease diagnosis, medical restrictions, prescriptions, surgery decisions, emergency assessment, and other regulated clinical actions remain within the relevant professional and legal scope.

---

**MoveTips Technology (Beijing) Co., Ltd.**

**MOVETIPS**

**Human Function, in One Shared Language.**
