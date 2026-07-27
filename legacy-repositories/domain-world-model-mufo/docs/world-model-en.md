# `docs/world-model-en.md`

# World Models: A Unified Ontology for Human Functional Dynamics

## Executive Summary

World models are not about storing more facts. They are about building stable internal representations of the present and predicting the consequences of actions across time, so that an agent can plan and act under explicit constraints. Yann LeCun’s 2022 position paper frames this as a central path toward autonomous machine intelligence: predictive world models, multi-scale abstraction, and hierarchical planning, developed largely through self-supervised learning rather than relying exclusively on next-token prediction [1]. In March 2026, Advanced Machine Intelligence (AMI) brought renewed industry attention to this direction by positioning world models, reasoning, planning, and controllability as an alternative to scaling-only large language model strategies [5][6][7][8].

This document presents MUFO as a domain-specific world model for human function. Its engineering path is organized into three layers. The first layer freezes functional cooperation as a governed constraint topology. The second layer parses observations into a functional state distribution with evidence trace, safety filtering, and replayable outputs. The third layer introduces action-conditioned state transition, persistent memory writeback, and long-horizon planning under guardrails.

MUFO is not a diagnostic engine, not a treatment guideline, and not a replacement for professional judgment. It is a computable, auditable, and safety-constrained substrate for representing human function. Its aim is to move human-functional reasoning from fragmented narrative practice toward a governed dynamic system that can support rehabilitation, movement training, and health-related decision support in a consistent and accountable way.

---

## 1. Problem Statement

Modern healthcare is strong at disease naming, pathology, and protocol execution. It is much weaker at representing **human function** as a unified reasoning object. Pain, reduced tolerance, compensation, instability, and degraded performance often appear before a stable diagnosis exists. Across rehabilitation, movement training, and health management, such states are frequently interpreted through fragmented heuristics, local discipline-specific language, and partially incompatible recording habits.

The bottleneck is not a lack of knowledge. The bottleneck is the absence of a stable, computable coordinate system for human function.

The World Health Organization’s ICF provides a globally endorsed framework for describing functioning and disability, formally adopted through WHA54.21 in 2001 [9][10]. This is foundational for communication and interoperability. However, ICF is primarily a classification and descriptive framework. It does not, by itself, define an operational loop of **observation → state inference → constrained action → writeback → recalibration**. For a domain world model, that loop is essential.

As long as human function remains split across anatomy, movement, symptom language, assessment scales, intervention templates, and heterogeneous records, functional decision support will remain difficult to standardize, replay, and govern.

---

## 2. MUFO Scope and Boundaries

MUFO stands for **MoveTips Unified Functional Ontology**. It is a knowledge-and-rules substrate for the human functional world.

MUFO is designed as a **knowledge representation and reasoning framework**, not as a clinical protocol or therapeutic guideline [MUFO paper]. Its role is to define concepts, relations, constraints, mappings, payload structures, and reproducible reasoning artifacts for function-first decision support. It does not claim to replace diagnosis, medical supervision, or professional judgment.

In MUFO, human function is defined as:

> The capacity to complete a task stably and efficiently under bounded physiological, biomechanical, and cognitive cost within explicit safety constraints. [MUFO paper]

This definition is task-oriented rather than disease-first. It is also bounded rather than idealized. The objective is not to model the entirety of human biology, but to make human function representable in a form that supports interpretation, action selection, audit, and longitudinal recalibration.

The theoretical backbone here should come from LeCun’s 2022 argument: autonomous intelligence requires predictive world models, hierarchical planning, and multi-scale abstraction [1]. Recent industry developments around AMI are useful as signals that world-model approaches remain strategically relevant, but they are not the primary theoretical basis of MUFO [5][6][7][8].

MUFO therefore has a narrow but important scope:

* to represent human function as a structured and governable domain
* to separate observation from explanation
* to make safety boundaries first-class constraints
* to support replayable reasoning and longitudinal update
* to provide a substrate for human–AI collaboration under accountability

It explicitly does **not** attempt to serve as:

* diagnostic automation
* unrestricted recommendation generation
* a pure content library
* a black-box substitute for expert review

---

## 3. Layer 1: Functional Cooperation Layer

The first layer of MUFO freezes the **constraint topology** of human function.

This layer is not a list of functions. It is a structured network of how functional units support, constrain, transmit, coordinate, or compensate for one another. It answers questions such as:

* which functions provide stability boundaries for which downstream tasks
* which functional deficits tend to trigger compensation paths
* which combinations open risk windows
* which constraints must be applied before downstream actions are allowed

The purpose of this layer is to define structure, not to compute current state.

In practical terms, this is the layer where functional knowledge becomes a governed graph rather than a loose vocabulary. Edges are not merely “related to”; they must carry explicit meaning such as dependency, indication, constraint, or support. Their direction, conditions, and versioning status matter.

This is also where ontology discipline matters. OBO Foundry principles are useful references here because they emphasize relation reuse, stable concept boundaries, and governance discipline rather than uncontrolled relation growth [11][12]. MUFO can align with that tradition without being reduced to an imported vocabulary.

If this layer is built only as a semantic web of names, it will collapse into a knowledge graph. If it is built as a typed and governed functional constraint network, it becomes the structural skeleton of a domain world model.

---

## 4. Layer 2: Human State Parsing Engine

The second layer is where MUFO moves from structure into dynamics.

The role of the **Human State Parsing Engine** is to map structured observations into a functional state distribution. Observations may come from assessments, questionnaires, structured notes, movement observation, or optional sensor streams. These inputs are transformed into a bounded state representation that supports margin calculation, bottleneck identification, risk-window detection, and constrained next-step generation.

This layer does not begin by predicting the future. It begins by locating the present.

That is the decisive engineering step. A world model cannot operate without a stable account of “where the system is now.”

MUFO’s core decision spine here is **Task–Capacity Matching (TCM)**. The idea is deliberately simple:

* task conditions define a demand structure
* human function defines a capacity structure
* the meaningful question is whether capacity covers demand under explicit constraints

At the most basic level, this can be written as:

**M = C − D**

Where:

* **C** = capacity vector
* **D** = task demand vector
* **M** = margin / reserve

This leads directly to three operational outputs:

1. **Current functional state**
   Which zone the system currently occupies

2. **Risk and boundary**
   Where the system should not be pushed

3. **Action path**
   Whether the next lever should primarily target task adjustment, strategy reconstruction, or capacity development

As the MFLS framework makes explicit, the computability of TCM does not come from modeling “the whole truth” of the human body. It comes from modeling **the relation between demand, capacity, and constraint-triggered boundary conditions**. In practice, judging relations is easier to engineer than fully explaining mechanisms, and more directly useful for answering the real-world question: **when should the system not be pushed further?** 

A minimal parsing pipeline can therefore be described as:

* observation intake
* evidence structuring
* local state inference
* constraint propagation
* risk-window derivation
* guardrail application
* evidence-linked output generation

This is precisely the layer where MUFO becomes more than ontology. It becomes a decision-support infrastructure.

---

## 5. Layer 3: Human Functional World Model

The third layer introduces time, action, and persistent memory.

Once a structured topology exists and the current state can be parsed, MUFO can begin to operate as a **human functional world model**. The question is no longer only “what is the current state?” but also:

* what happens if load is increased
* what happens if strategy is changed
* what happens if intervention is delayed
* which path is likely to improve stability
* which path is likely to open a risk window

This is where **action-conditioned state transition** becomes central.

LeCun’s 2022 position paper directly links predictive world models to hierarchical planning [1]. JEPA-style work further strengthens the argument that prediction in **representation space** is more useful than trying to reproduce every observable detail. I-JEPA predicts target representations from image context [2]. V-JEPA extends this logic to masked spatio-temporal regions in latent space, showing why predictive structure matters more than pixel-level generation for control-relevant modeling [3].

MUFO adopts this logic at the domain level of human function.

Instead of predicting raw sensory scenes, it predicts changes in **functional state** under specific actions, loads, or plans. At the simplest level:

**s(t+1) = f(s(t), a(t), u(t))**

Where:

* **s(t)** is the current functional state
* **a(t)** is the intervention, strategy change, or load decision
* **u(t)** is contextual influence such as pain, fatigue, sleep, recovery, or environment

This layer also requires **persistent memory writeback**. Outcomes from execution, follow-up, and reassessment are written back into the longitudinal record so that future inference can be recalibrated. Without writeback, the world model cannot evolve. Without safety guardrails, it cannot be trusted.

This is why MUFO does not treat action generation as free-form output. It must remain bounded by explicit contraindications, degrade rules, rollback rules, and evidence-linked accountability.

---

## 6. Three-Layer Integration

The three layers are not parallel ideas. They are an engineering stack.

* **Layer 1** defines the topology of the functional world
* **Layer 2** locates the current state within that world
* **Layer 3** simulates controlled evolution under action and memory

Their relation can be summarized as:

**topology → state inference → controlled evolution**

The MFLS execution logic already reflects this same order. Its frozen closed loop is:

**D-records → C-zone safety filtering → A/B knowledge retrieval and semantic reasoning → L-zone inference and template generation → writeback to D as longitudinal sequence** 

The practical meaning is straightforward:

* structure provides the inferable space
* parsing provides the present-state anchor
* world modeling provides future-path reasoning
* writeback turns one-off judgments into a learning system

This is what makes MUFO governable over time rather than static in design.

---

## 7. MUFO’s Position in the Multi-Scale Biological World-Model Stack

World models are more likely to develop as a **layered stack** than as a single monolithic model across all biological scales.

An engineering view of the stack can be written as:

* **L0 Physics / Chemistry**: atoms, forces, energy landscapes
* **L1 Molecular Structure**: proteins, complexes
* **L2 Molecular Interaction**: docking, affinity, induced fit
* **L3 Biological Mechanism**: pathways, regulation, cell and tissue responses
* **L4 Human Functional Dynamics**: stability domains, compensation, control, boundaries, risk windows
* **L5 Behavior and Task**: ADLs, performance, skill execution
* **L6 Clinical and Decision**: pathways, management, risk decisions

The point of this framing is not taxonomy for its own sake. It is an acknowledgment of a **scale wall**. Observability, noise structure, control variables, and causal closure differ dramatically across layers. That is exactly why LeCun’s emphasis on multi-scale abstraction and hierarchical planning matters here [1].

MUFO’s strategic center is **L4: Human Functional Dynamics**.

This is the layer that most systems still fail to occupy in a coherent way. Many assessment systems stop at **L5**, asking only whether a person can complete a task. MUFO attempts to push downward into **L4**, asking:

* by what stability domain is the task being completed
* whether compensation has already been engaged
* where the active risk boundary lies
* whether the next step should be degradation, progression, or retesting

It is at this layer that human function stops being a superficial summary of behavior, and stops being merely an indirect projection of molecular or pathological language. Human Functional Dynamics becomes the strategic middle axis that links biological constraints below with real-world task performance above, and ultimately grounds decision support in a form that can be computed, audited, and governed. In practice, this is also where medical AI has the clearest near-term foothold: stable coordinates can be established, explanations can be made traceable, and responsibility loops can be enforced. Whoever first builds a computable, auditable, evolvable representation of L4 will be positioned to move medical AI from generating answers to understanding state, constraining risk boundaries, and supporting long-horizon decisions. 

---

## 8. Why MUFO Is Not a Plain Knowledge Graph

A plain knowledge graph is often optimized for retrieval, relation lookup, and graph traversal. MUFO needs more than that.

MUFO must support:

* constraint reasoning
* state inference
* risk-window derivation
* version-locked governance
* longitudinal recalibration
* replayable evidence trace

This is why MUFO cannot be reduced to triples plus paths.

Formally, OWL 2 provides the kind of ontology language needed for explicit semantics and reasoning [13]. JSON-LD provides an interoperable engineering path for structured services that need to move between JSON-native systems and linked data conventions [14]. These are useful representational foundations, but MUFO’s distinguishing requirement lies elsewhere: it must output not only relations, but **state distribution, risk boundaries, and action-conditioned trajectories**.

A practical comparison looks like this:

| Dimension      | Plain Knowledge Graph | MUFO Target                                                       |
| -------------- | --------------------- | ----------------------------------------------------------------- |
| Primary output | triples and paths     | state distribution, risk windows, action-conditioned trajectories |
| Time           | timestamps only       | explicit state transition and longitudinal calibration            |
| Safety         | downstream filtering  | guardrails as first-class constraints                             |
| Governance     | often ad hoc          | version locks, audit, evidence trace                              |

So while a graph can serve as substrate, the actual target is not graph storage. The target is a governed functional reasoning system.

---

## 9. Why MUFO Is Not a Black-Box Large Model

Large language models can generate text, summarize evidence, and propose candidate explanations. They are useful components. But in the human-function domain, useful text is not enough.

High-stakes use requires:

* replayability
* provenance
* versioned rules
* explicit safety defaults
* evidence-linked accountability

That is why MUFO cannot be framed as a black-box end-to-end generator.

W3C PROV-O provides a standard ontology for provenance exchange [15]. FHIR AuditEvent captures operational, security, and privacy-related audit activity [16]. FHIR Provenance captures the entities, activities, and agents that contributed to a resource, making trust and reproducibility more explicit [17]. Together, these point toward the kind of accountability infrastructure a functional reasoning system needs.

A practical contrast looks like this:

| Dimension       | Black-box End-to-End Model | MUFO Recommendation                              |
| --------------- | -------------------------- | ------------------------------------------------ |
| Stability       | prompt/context drift       | graph + rules + versioned substrate              |
| Traceability    | hard to replay why         | evidence trace + rule versions + provenance      |
| Safety          | post-hoc alignment         | precondition checks, degrade/rollback guardrails |
| Personalization | context injection          | persistent memory writeback + recalibration      |

MUFO can use language models where they are helpful, but they must operate inside a governed substrate rather than defining the substrate.

---

## 10. Engineering Value, Application Boundaries, and Long-Term Significance

### Near-term value

The near-term value of MUFO is not grandiose simulation. It is much more practical:

* unify records
* stabilize reasoning
* make outputs replayable
* force safety constraints to appear explicitly
* reduce decision spread across practitioners and settings

### Mid-term value

The mid-term value is **calibratable prediction** of functional state evolution under intervention, load, and strategy change.

This is where the world-model layer becomes genuinely useful: not for claiming certainty, but for narrowing the space of safe and testable next steps.

### Long-term value

The long-term value is to move human function from narrative knowledge into a governed dynamic system.

That does not mean solving all biology. It means making human functional reasoning sufficiently structured that it can be:

* represented
* audited
* updated
* constrained
* accumulated over time

### Explicit boundaries

These boundaries must remain explicit:

* MUFO is **not** diagnostic automation
* outputs remain decision support, not autonomous treatment
* uncertainty must remain visible
* safety guardrails are mandatory, not optional

### Governance risks

Several governance risks are central:

1. **Over-claiming**
   If MUFO is presented as diagnostic authority, its boundary is broken.

2. **Ontology drift**
   Without version locks and relation governance, reasoning becomes non-reproducible. OBO-style discipline is therefore not cosmetic; it is a practical necessity [11][12].

3. **Interoperability traps**
   MUFO should map to ICF, ICD-11, and SNOMED CT for exchange, but those systems should not redefine MUFO’s internal boundaries [9][18][19].

4. **Accountability failure**
   Every parse, suggestion, action path, and writeback should be linked to provenance and audit artifacts [15][16][17].

FHIR PlanDefinition is also relevant as a model for executable intervention artifacts. It offers a useful precedent for representing plan logic, conditions, and branching in a shareable and computable form [20].

### What success would actually mean

The most realistic success criteria are not philosophical elegance, but operational stability:

1. identical inputs produce stable conclusions
2. conclusions narrow action to one or two meaningful leverage points
3. high-risk outputs correspond to worse tolerance, slower recovery, or more fragile progression in follow-up
4. repeated assessment, intervention, and review write back into the system and make later decisions more stable

If those conditions are met, MUFO becomes more than a conceptual architecture. It becomes decision infrastructure.

---

## References

```text
[1] LeCun, Y. (2022). A Path Toward Autonomous Machine Intelligence. https://openreview.net/pdf?id=BZ5a1r-kVsf
[2] Assran, M. et al. (2023). I-JEPA: Self-Supervised Learning from Images with a Joint-Embedding Predictive Architecture. https://arxiv.org/abs/2301.08243
[3] Bardes, A. et al. (2024). V-JEPA: Latent Video Prediction for Visual Representation Learning. https://openreview.net/pdf/caaf40acdbe1cd4cd62f82bdda56870797006a68.pdf
[4] Ha, D. & Schmidhuber, J. (2018). World Models. https://arxiv.org/abs/1803.10122
[5] Reuters (2026-03-10). Ex-Meta AI chief Yann LeCun's AMI raises $1.03 billion for alternative AI approach. https://www.reuters.com/business/ex-meta-ai-chief-yann-lecuns-ami-raises-103-billion-alternative-ai-approach-2026-03-10/
[6] TechCrunch (2026-03-09). Yann LeCun’s AMI Labs raises $1.03 billion to build world models. https://techcrunch.com/2026/03/09/yann-lecuns-ami-labs-raises-1-03-billion-to-build-world-models/
[7] WIRED (2026-03-10). Yann LeCun Raises $1 Billion to Build AI That Understands the Physical World. https://www.wired.com/story/yann-lecun-raises-dollar1-billion-to-build-ai-that-understands-the-physical-world/
[8] AMI. https://amilabs.xyz/
[9] WHO. International Classification of Functioning, Disability and Health (ICF). https://www.who.int/standards/classifications/international-classification-of-functioning-disability-and-health
[10] WHO (2001-05-22). WHA54.21 International classification of functioning, disability and health. https://apps.who.int/gb/ebwha/pdf_files/WHA54/ea54r21.pdf
[11] OBO Foundry. Principles Overview (fp-000). https://obofoundry.org/principles/fp-000-summary.html
[12] OBO Foundry. Relations principle (fp-007). https://obofoundry.org/principles/fp-007-relations.html
[13] W3C. OWL 2 Web Ontology Language Document Overview. https://www.w3.org/TR/owl2-overview/
[14] W3C. JSON-LD 1.1. https://www.w3.org/TR/json-ld11/
[15] W3C. PROV-O: The PROV Ontology. https://www.w3.org/TR/prov-o/
[16] HL7 FHIR. AuditEvent. https://build.fhir.org/auditevent.html
[17] HL7 FHIR. Provenance. https://build.fhir.org/provenance.html
[18] WHO. ICD-11. https://icd.who.int/
[19] SNOMED International. What is SNOMED CT. https://www.snomed.org/what-is-snomed-ct
[20] HL7 FHIR. PlanDefinition. https://build.fhir.org/plandefinition.html
```

---

如果你要，我下一条直接继续给你 **`docs/world-model-zh.md` 的 GitHub 发布版中文全文**，风格会和这一版英文完全对齐。