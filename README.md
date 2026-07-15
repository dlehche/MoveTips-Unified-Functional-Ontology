# MUFO — MoveTips Unified Functional Ontology

## A Unified Ontology for Human Function and the Human Function World Model

**MUFO Definition Version 2.0**

**Proposed by:** Lei Che  
**Developed by:** Lei Che Research & Engineering Team, MoveTips Technology (Beijing) Co., Ltd.  
**Current authoritative definition:** MUFO Definition 2.0  
**Canonical publication:** [MUFO Definition 2.0: A Unified Ontology for Human Function](https://doi.org/10.5281/zenodo.21368412)  
**DOI:** `10.5281/zenodo.21368412`  
**Copyright © 2026 Lei Che and MoveTips Technology (Beijing) Co., Ltd.**

For formal citation, please use the canonical publication above or the repository citation metadata in `CITATION.cff`.

MUFO (MoveTips Unified Functional Ontology) is a domain ontology for human function. It provides a unified semantic and rule foundation for human function inference, state modeling, safety constraints, longitudinal write-back, and the Human Function World Model.

**MOVETIPS**

---

## Preface

Modern medicine, rehabilitation, movement training, nursing, health management, and artificial intelligence have accumulated extensive knowledge, technologies, and data about the human body.

Medicine is highly capable of identifying diseases, injuries, structural abnormalities, and pathological mechanisms.

Rehabilitation develops recovery pathways around functional limitations.

Movement and exercise training improve human capacity through loading and adaptation.

Psychology, nutrition, and lifestyle disciplines influence long-term human states from their respective perspectives.

The problem is not a lack of knowledge.

The deeper problem emerges when these disciplines face **the same individual**.

They often lack a stable, shared, continuously updatable object of understanding.

Diseases, symptoms, movements, laboratory values, assessment scores, exercise records, sleep data, fatigue, and real-life feedback are typically recorded in different systems.

Each source of information may be valuable.

Yet these fragmented records do not automatically answer a more fundamental question:

> **Can this person's body still be appropriately engaged for the task at hand?**

What real-world tasks can the person currently undertake?

How is the body actually organizing itself to complete those tasks?

What cost is being paid?

Where are the current boundaries?

Is functional reserve improving, remaining stable, or gradually narrowing?

Should the next step be continuation, adjustment, suspension, reassessment, or transfer to another professional system?

The **MoveTips Unified Functional Ontology (MUFO)** is designed around these questions.

MUFO does not reinvent medicine, rehabilitation, or movement training.

It does not replace any professional discipline.

Instead, MUFO establishes **human function as an independent object of representation and computation**.

It formally organizes tasks, functional engagement, manifestations, costs, boundaries, states, evidence, limiting factors, actions, and feedback that are otherwise distributed across different professional systems.

Its purpose is to establish a shared semantic coordinate system, relationship structure, and rule foundation for continuous human function inference.

---

# 1. Definition of MUFO

**MUFO** stands for:

> **MoveTips Unified Functional Ontology**

MUFO is a domain ontology for the real-world domain of human function.

It takes the body's capacity to be appropriately engaged as its core object of study and formally represents:

* task demands,
* functional engagement,
* observable manifestations,
* costs,
* boundaries,
* limiting factors,
* evidence,
* inference,
* actions,
* and feedback

within real-world human tasks.

The primary objective of MUFO is to establish a human function semantic and inference foundation that is:

> **computable, constrained, traceable, auditable, and continuously updatable.**

MUFO specifies:

What kinds of entities may enter a human function inference process.

What relationships may exist between those entities.

Which information represents observation or recorded fact.

Which information represents interpretation, attribution, or candidate inference.

What the available evidence can support.

Under what conditions ordinary functional interpretation must stop.

How a current functional state is inferred.

How actions are constrained by safety and professional boundaries.

How post-action changes return to the inference process.

MUFO is therefore not merely a terminology system.

It is also not merely a knowledge graph.

MUFO establishes:

> **a unified semantic coordinate system and state inference rule framework for the human function domain.**

---

# 2. The Root Definition of Human Function

MUFO defines human function as:

> **Human function is the body's capacity to be appropriately engaged for real-world tasks.**

The body exists in real life.

A person must stand, walk, climb stairs, work, learn, communicate, eat, care for themselves, care for others, exercise, recover, participate in sport, and respond to changing demands.

Human function therefore cannot be understood independently from real-world tasks.

In MUFO, **functional engagement** refers to the process through which the body organizes the resources required to undertake a specific task.

These resources may include:

* structural support,
* functional capacities,
* sensory feedback,
* motor control,
* energy supply,
* protective responses,
* recovery regulation,
* cognition,
* and behavioral participation.

Completing a movement does not necessarily mean that functional engagement is appropriate.

A person may complete a squat through breath holding, marked displacement, or excessive tension.

A person may continue exercising while post-exercise reactions progressively worsen and the next training session can no longer be tolerated.

A person may finish a walking task while repeatedly slowing down, stopping, or relying on external support.

MUFO therefore does not ask only:

> Can the task be completed?

It also asks:

> **How is the task being completed?**

> **What cost is being paid?**

> **Where is the current boundary?**

> **Can the engagement strategy be maintained and adjusted?**

MUFO describes appropriate functional engagement through three foundational conditions:

> **The task goal is achievable.**

> **The organization of engagement is relatively stable.**

> **The associated cost remains controllable.**

Here, "appropriate" does not mean biomechanically perfect.

It does not require every individual to use the same movement pattern.

It means that, under the current task and context, the body can still undertake the real-world demand with relative stability, controllable cost, and acceptable safety boundaries.

---

# 3. Why Human Function Must Be Established as a Shared Object

Existing disciplines do not lack concepts related to function.

Medicine evaluates organ function, disease impact, and clinical outcomes.

Rehabilitation evaluates body functions, activity limitations, and participation.

Movement training evaluates strength, endurance, speed, control, and performance.

Assessment instruments continuously measure capacities and task outcomes.

The missing element is not the word **function**.

The missing element is:

> **a unified computational object that allows different professional systems to work on the continuous functional state of the same person.**

Disease may define medical context and risk.

Movement may provide an observable window into functional organization.

Assessment instruments may generate standardized measurements.

Devices may continuously produce data.

Professional interventions may alter a person's state.

None of these, in isolation, is equivalent to human function itself.

The same disease may correspond to very different functional states in different individuals.

The same visible movement may result from completely different patterns of functional engagement.

The same test score may have different meanings under different tasks, environments, and individual contexts.

MUFO therefore establishes **human function as the shared object**.

Other concepts return to their appropriate positions:

> Disease provides medical context, mechanism, and safety constraints.

> Movement provides an observable window into function.

> Structure provides anatomical anchors for functional engagement.

> Tests and assessments provide evidence.

> Techniques and programs provide means of changing a state.

> Human function is the object continuously observed, inferred, and influenced by multiple disciplines.

---

# 4. MUFO as a Unified Semantic Coordinate System

MUFO does not place the terminology of one profession at the center of the system.

Instead, it organizes information around the real functional process of a specific person.

The MUFO object system includes, but is not limited to:

* real-world tasks and task contexts,
* functional capacities,
* anatomical structures and structural anchors,
* actual engagement patterns,
* observable manifestations such as pain, instability, deviation, interruption, fatigue, and recovery change,
* safety boundaries and task boundaries,
* diseases, injuries, surgery, clinical events, and other contextual constraints,
* assessment items, tests, scales, observations, and evidence,
* limiting factors and primary problem candidates,
* current human function states,
* recommendation directions and professional entry points,
* concrete solution methods and execution arrangements,
* execution feedback,
* reassessment,
* and longitudinal monitoring.

These objects are not merely stored together in one database.

MUFO defines the relationships that may exist between them, including:

* relationship direction,
* semantic type,
* applicable conditions,
* evidence requirements,
* and governance boundaries.

For example:

What functional capacities are required by a real-world task?

What anatomical structures support a functional capacity?

Under which task conditions was a manifestation observed?

Which limiting factor candidates may be supported or excluded by an assessment?

How may a medical event constrain functional engagement or safety boundaries?

Under what state, goal, and boundary conditions may a solution method be considered?

Only when objects, relationships, and constraints are represented together can human function knowledge become computable rather than remain a collection of fragmented terms.

---

# 5. The Core Human Function Inference Chain

MUFO organizes human function inference along a continuous chain:

> **Task → Engagement → Manifestation → Cost → Boundary → State → Action → Feedback**

### Task

What real-world demand does the person need to undertake?

### Engagement

What capacities are required by the task, and how is the body actually organizing those capacities?

### Manifestation

What has actually been observed, reported, or measured?

### Cost

What pain, fatigue, compensatory burden, recovery burden, or other cost is associated with task completion?

### Boundary

How far can the current system continue?

What changes in load, speed, duration, complexity, or environment may cause the current strategy to fail?

Under what conditions must the task or inference process stop?

### State

Considering the task, engagement, manifestations, cost, boundaries, and available evidence, what is the person's current functional state?

### Action

Should the next step be continuation, modification, regression, additional assessment, a different solution direction, or entry into another professional system?

### Feedback

What happened after execution?

Does the previous inference still hold?

This chain is not a fixed questionnaire.

It is not a rigid workflow.

Its role is to prevent premature inferential jumps.

MUFO does not permit reasoning patterns such as:

> Pain was observed, therefore the cause is known.

> A movement differs from a reference pattern, therefore compensation is confirmed.

> One assessment result is poor, therefore the limiting factor is established.

> A disease is present, therefore the individual's current functional state is known.

> One improvement occurred, therefore the problem is resolved.

Inference must remain constrained by object relationships, evidence, and boundaries.

---

# 6. Observations and Inferences Must Remain Separate

One of the fundamental governance principles of MUFO is:

> **What was observed and why it may have occurred must be represented separately.**

Examples of observations include:

* pain appeared,
* stair descent speed decreased,
* handrail support was used,
* next-day fatigue increased after training,
* a measured strength result decreased.

These are observations, reports, or measured results.

Statements such as:

* a specific capacity is insufficient,
* a structural constraint is responsible,
* pain protection altered the task strategy,
* recovery regulation is impaired,
* chronic load has exceeded the current functional boundary

are interpretations, attributions, or candidate inferences.

MUFO does not allow an unverified interpretation to be stored as a confirmed fact.

Every inference should make explicit:

* which observations support it,
* which entities were connected,
* which relationships and rules were applied,
* how strongly the current evidence supports it,
* what evidence remains missing,
* and what future findings may support or refute the inference.

Human function inference is therefore not treated as a one-time conclusion.

It must remain open to:

> **verification, falsification, revision, and recomputation.**

This separation is essential for AI-assisted human function inference while preserving professional boundaries and auditability.

---

# 7. Safety Boundaries Precede Functional Interpretation

MUFO does not treat "producing an answer" as the highest system objective.

In human health-related contexts, the first question must be:

> **Is ordinary human function inference and action recommendation currently permitted to continue?**

Diseases, injuries, abnormal symptoms, examination findings, contraindications, red-flag signals, and professional scope may create safety constraints.

When a safety gate is triggered, the system must be capable of:

* suspending the current inference pathway,
* restricting downstream actions,
* requesting additional information,
* requiring medical or other professional confirmation,
* and recording the basis and handling pathway of the triggered constraint.

MUFO does not remove medical diagnosis from the process.

On the contrary, medical safety boundaries are an important source of constraints in human function inference.

A shared language also does not imply shared professional authority.

Physicians, therapists, trainers, and other professionals may collaborate around the same human function object.

However, each role may only infer, confirm, and act within its own professional scope and evidence boundary.

---

# 8. Human Function State as the Current Inference Outcome

MUFO does not treat human function as a static label.

Human function is the object.

**State is the current result of human function inference.**

MUFO currently uses four foundational functional states.

## Normal State

The body can establish relatively stable functional engagement under the current task.

The goal remains achievable.

Cost is controllable.

Usable functional reserve remains available.

## Compensatory State

The task can still be completed, but the body has altered its engagement strategy and is paying a higher cost to maintain task completion.

## Critical State

The task may still be achievable, but functional reserve has significantly narrowed.

Small increases in load, speed, duration, complexity, fatigue, or environmental demand may cause the current system to cross its boundary.

## Disabled State

The body can no longer effectively establish or maintain the functional engagement required for the task.

The real-world task is clearly impossible or severely limited.

These four states are not medical diagnoses.

They are also not permanent identity labels.

They describe:

> **the current task-bearing condition of a person under a specific task, context, and time point.**

States can change.

The same person may also occupy different states for different tasks.

MUFO must therefore associate every state inference with:

* the relevant task,
* context,
* evidence,
* boundaries,
* and time.

Without these conditions, a functional state loses its inferential meaning.

---

# 9. Human Function Is a Continuous State Process

Traditional systems often store examinations, assessments, treatment sessions, and training sessions as separate events.

The human body does not stop changing when one service event ends.

Disease may progress.

Injury may recover.

Capacity may increase or decline.

Life tasks may change.

Training load may change.

Pain and fatigue may fluctuate.

Sleep, nutrition, psychology, and environment may alter the conditions under which the body must perform.

MUFO is therefore designed around **continuous write-back**.

A simplified operating cycle is:

> **Real-world events and multi-source information input**

↓

> **Objectization and semantic normalization**

↓

> **Safety boundary inference**

↓

> **Comparison between required and actual functional engagement**

↓

> **Manifestation, cost, and boundary analysis**

↓

> **Limiting factor and evidence convergence**

↓

> **Human function state inference**

↓

> **Action and solution execution**

↓

> **Execution feedback and reassessment**

↓

> **Write-back to the individual's longitudinal human function model**

↓

> **Re-inference**

Each new observation is not simply another record.

It may:

* support a previous inference,
* weaken a previous inference,
* change a boundary,
* change the primary problem,
* change the inferred state,
* or change the next action.

Human function therefore becomes a dynamic object that can be longitudinally observed and continuously updated.

---

# 10. Bidirectional Reasoning Between Disease and Human Function

MUFO does not position human function outside medicine.

Disease and human function are different classes of objects, but they continuously affect one another.

The first reasoning direction is:

> **Disease and medical events → Human function impact**

Diseases, injuries, surgeries, abnormal examination results, medication, and pathological mechanisms may alter:

* anatomical structures,
* functional capacities,
* recovery conditions,
* safety boundaries,
* and task engagement strategies.

MUFO must be able to ask:

Which tasks may be affected by this medical event?

Which functional engagements may change?

May the event increase functional cost?

May it narrow safety boundaries?

May it change recovery capacity or long-term ability to participate in life?

The second reasoning direction is:

> **Longitudinal human function change → Disease risk candidates**

Examples include:

* persistent compensatory engagement,
* repeated exposure beyond current boundaries,
* declining recovery capacity,
* progressive narrowing of task reserve,
* persistent abnormal engagement strategies,
* and longitudinal decline in real-world task ability.

These patterns cannot replace medical diagnosis.

However, when they form stable longitudinal sequences, they may become important inputs for identifying:

> disease risk windows, early change signals, and possible development trends.

The purpose of MUFO is therefore not to replace disease concepts with human function.

Its objective is to establish:

> **downward reasoning from disease to functional impact, and upward signal reasoning from long-term functional change to disease risk.**

Medical events and real-life functional change can then enter the continuous model of the same individual.

---

# 11. MUFO as an AI-Native Unified Ontology

Artificial intelligence is rapidly improving information extraction, knowledge integration, and domain-specific reasoning.

Medical models, rehabilitation models, movement training models, nutrition models, and psychological models may all develop increasingly powerful professional capabilities.

As the number of specialized models grows, a new problem becomes increasingly important:

> **How can different models work around the same individual?**

A medical model may output disease risk.

A rehabilitation model may identify a functional limitation candidate.

A movement model may estimate capacity or load tolerance.

A nutrition model may analyze recovery conditions.

A psychological model may identify fear, behavior, or adherence factors.

These outputs do not naturally exist in the same semantic coordinate system.

MUFO provides a unified human function semantic layer for specialized models.

Each professional model may generate candidate inferences within its own:

* professional scope,
* data sources,
* and evidence boundaries.

MUFO can then support:

* objectization,
* semantic normalization,
* relationship positioning,
* evidence annotation,
* authority constraints,
* conflict identification,
* functional state impact analysis,
* auditing,
* and write-back to the same individual's human function model.

MUFO is therefore not intended to become a single "super model" that replaces every professional AI system.

Instead, it establishes:

> **the shared coordinate system and state arbitration foundation required for specialized models to collaborate around the continuous human function state of the same person.**

AI models may change rapidly.

Model capabilities may continue to improve.

However, concepts such as:

* What is the task?
* What must be engaged?
* What was observed?
* What cost occurred?
* Where is the boundary?
* What does the evidence support?
* What is the current state?
* What changed after execution?

require relatively stable semantics and governance rules.

MUFO is designed to provide that layer.

---

# 12. The Relationship Between MUFO and the Human Function World Model

MUFO is not itself identical to the Human Function World Model.

The relationship can be expressed as follows:

> **MUFO defines how the human function world is represented and made computable.**

> **An Individual Human Function Model records the longitudinal state of a specific person within that semantic coordinate system.**

> **The Human Function World Model introduces time, action, state transition, and memory write-back to learn and project how human function may evolve.**

MUFO provides:

* objects,
* relationships,
* constraints,
* evidence semantics,
* state rules,
* safety boundaries,
* action semantics,
* and feedback and write-back standards.

The Human Function World Model further asks:

> Where is this person now?

> Why might the person be in this state?

> What changes are currently taking place?

> If the current load continues, where may the state move?

> If different actions are taken, how might the state transition pathway change?

> Which predictions are later supported or refuted by real-world feedback?

Therefore:

> **MUFO is the unified ontology and semantic-rule foundation of the Human Function World Model.**

Without stable objects, relationships, and boundaries, a world model cannot clearly define what it is predicting.

Without continuous state and feedback write-back, an ontology remains only a static knowledge structure.

The connection between MUFO and the Human Function World Model brings knowledge, real-world state, and temporal change into the same computational process.

---

# 13. Relationship With Existing International Standards

MUFO does not replace ICF, SNOMED CT, UMLS, or other established medical and health information standards.

The **International Classification of Functioning, Disability and Health (ICF)** provides an international framework for body functions, body structures, activities, participation, and environmental factors.

**SNOMED CT** provides standardized clinical terminology and clinical semantic representation.

The **Unified Medical Language System (UMLS)** supports semantic connections between medical vocabularies and concept systems.

These systems address important and foundational problems.

MUFO occupies a different position.

MUFO focuses on:

> **how the human body is engaged in real-world tasks, how a human function state is inferred, how inference is constrained by evidence and safety boundaries, and how state enters action, feedback, and longitudinal updating.**

The relationship between MUFO and existing standards is therefore one of **mapping and interoperability**, rather than replacement.

Medical concepts remain within medical terminology systems.

Disease coding continues to use established clinical standards.

Human anatomical entities may remain aligned with established anatomy systems.

MUFO maintains its own governed concepts and relationships and connects them to external standards through explicit mapping objects.

This allows MUFO to evolve without collapsing the boundaries of existing professional semantic systems.

---

# 14. What MUFO Is Not

MUFO is not a disease diagnosis system.

It does not replace physicians or medical diagnosis.

MUFO is not a clinical treatment guideline.

It cannot automatically generate medical prescriptions beyond professional authority.

MUFO is not a movement library.

Movement is only one class of object within tasks, assessment, and execution.

MUFO is not a collection of scales.

Tests and scales are methods for obtaining evidence.

MUFO is not an ordinary knowledge graph.

Graph structures may store entities and relationships.

MUFO additionally requires relationships to have explicit:

* semantics,
* direction,
* conditions,
* evidence requirements,
* versioning,
* and governance boundaries

and to participate in state inference and action constraints.

MUFO is also not a black-box AI system intended to replace professional judgment.

Its purpose is the opposite:

> **to make human function inference clearer, more bounded, replayable, inspectable, and revisable.**

---

# 15. Core Functions of MUFO

MUFO addresses five foundational problems.

## 15.1 Unified Object

Medicine, rehabilitation, movement training, and other professional systems can work around the same person's human function state.

## 15.2 Unified Representation

Tasks, manifestations, capacities, structures, boundaries, evidence, and actions are placed within a shared semantic coordinate system.

## 15.3 Unified Inference

Inference processes that previously existed largely as tacit professional experience can be made explicit, recorded, reviewed, compared, and revised.

## 15.4 Unified Boundaries

Questions such as:

* When may the task continue?
* When should it be regressed?
* When must it stop?
* When must another professional system enter?

can become explicit governance rules.

## 15.5 Unified Longitudinal State

Assessments, solution methods, execution feedback, medical events, and real-world life changes can continuously write back to the same individual's human function model.

This creates a longitudinal functional state timeline.

---

# 16. Application and Evolution Path of MUFO

MUFO initially supports a **Human Function Collaboration Network**.

Medicine, rehabilitation, movement training, and other professional roles can collaborate around the same person's:

* tasks,
* state,
* boundaries,
* and longitudinal changes.

On this foundation, MUFO supports human function state parsing and inference.

Multi-source information is mapped into a unified human function coordinate system.

The system organizes:

* tasks,
* functional engagement,
* manifestations,
* costs,
* boundaries,
* and evidence

to infer the current state.

As execution feedback, medical events, and real-world task data accumulate over time, the Individual Human Function Model is continuously updated.

When time, action, individual differences, and state transitions are further incorporated, the system evolves toward a:

> **Human Function World Model**

Its long-term objective is not to simulate every biological process of the human body.

Instead, at the human function level, it seeks to progressively establish:

> **a computable model capable of understanding current human state, identifying change, constraining safety boundaries, and supporting longitudinal decision-making.**

---

# Conclusion

The significance of the MoveTips Unified Functional Ontology is not the creation of more terminology about the human body.

Human knowledge is already extensive.

The deeper problem is:

> **How can this knowledge return to the same real person?**

MUFO takes the body's capacity to be appropriately engaged as its core object.

It begins with real-world tasks and organizes human function inference through:

> **Task → Engagement → Manifestation → Cost → Boundary → State → Action → Feedback**

It provides a shared human function coordinate system for diseases, rehabilitation, movement training, and real-world changes in the body.

It separates observed facts from inferred explanations.

It introduces professional scope and safety constraints into computation.

It allows an inference to be verified, challenged, and revised through future feedback.

It enables different professionals and different artificial intelligence models to work around the continuous human function state of the same person.

The ultimate objective of MUFO is not only to establish a common language for human function.

It is to establish:

> **a unified semantic and rule foundation capable of continuously understanding how the human body is engaged by real-world demands, what state it is currently in, why that state may be changing, and what should happen next.**

> **MUFO — the unified ontology and semantic foundation of the Human Function World Model.**

---

**MoveTips Technology (Beijing) Co., Ltd.**

**MOVETIPS**

**Human Function, in One Shared Language.**