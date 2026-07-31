**UOHF \| VERSION 1.0**

**A Formal Framework for Human Function in UOHF**

Capacity, Functional Engagement, Demand-Bounded Realizability,  
and Evidence-Constrained Decision Support

**UNIFIED ONTOLOGY OF HUMAN FUNCTION (UOHF)**

**Lei Che**

with contributions from the MoveTips Research & Engineering Team

MoveTips Technology (Beijing) Co., Ltd.

Correspondence: dlehche@gmail.com

July 31, 2026

**Version 1.0 English Academic Preprint**

*Formal and computational research framework*

Copyright © 2026 Lei Che and MoveTips Technology (Beijing) Co., Ltd.  
Licensed under CC BY-NC 4.0.

# Abstract

Research on the human body is distributed across anatomy, physiology,
medicine, rehabilitation, exercise science, behavioral science, clinical
informatics, and multiscale computational modeling. These fields can
describe structures, processes, diseases, capacities, activities,
interventions, and outcomes in considerable detail, but they do not by
themselves provide a single formal account of how a particular person’s
bodily capacities become engaged under a specified internal or external
demand, whether that engagement is appropriate to the person and
context, what responses and costs follow, and how evidence and action
should update the person-specific model over time. This paper develops a
formal framework for human function within the Unified Ontology of Human
Function (UOHF). It retains the root definition: human function is the
body’s capacity to be appropriately engaged to meet internal and
external demands. The framework distinguishes human-function capacity
from the engagement process through which that capacity operates, and
distinguishes both from manifestations, measurements, inferred
explanations, and information representations.

The paper introduces a typed mathematical framework comprising a latent
whole-person state, a human-function capacity domain, demand and context
specifications, an engagement-pattern specification space, a
capacity-to-pattern realizability operator, an ex ante
appropriate-pattern domain, an actual engagement process, potential,
predicted, and observed response objects, evidence, limiting-factor
hypotheses, governed actions, and longitudinal state update. The central
demand-bounded realizability criterion defines when a specified demand
is ontically appropriately meetable for a particular person, time, and
context: at least one engagement-pattern specification must be
realizable from the person’s current capacities, operationally
accessible at the required reliability, admissible under person-specific
ex ante constraints, and compatible with at least one acceptable
potential result. The runtime system does not observe this ontic
condition directly; it can only report whether the proposition is
supported, not supported, or insufficiently evidenced.

The framework separates problem hypotheses from evidence status.
Capacity-coverage failure, functional-engagement difficulty, and other
or residual explanations may coexist as hypotheses, while supported,
weakened, contradicted, not assessed, insufficient, and undetermined
describe the epistemic state of those hypotheses. It also formalizes
anatomical, physiological-process, observation, constraint, and action
anchors without treating an anchor as a causal diagnosis. A governed
decision layer applies action-specific evidence thresholds together with
safety, professional authority, feasibility, stop conditions,
reassessment need, and feedback. A stair-climbing knee-pain case and a
short internal-demand recovery case demonstrate how the framework
generates testable hypotheses and admissible next steps without
converting a manifestation into an automatic diagnosis. The contribution
is an implementation-oriented formal and research framework, not a
completed whole-body equation, validated diagnostic algorithm,
autonomous treatment system, or already machine-executable ontology
release.

**Keywords:** human function; UOHF; functional engagement; capacity;
demand-bounded realizability; ontology; whole-person modeling; evidence;
causal inference; dynamic decision support; longitudinal modeling;
auditable AI

# Terminological Note

Functional engagement is the technical English rendering of the Chinese
term diaoyong (调用). It does not mean patient engagement, service
engagement, conscious command, voluntary participation, or mere neural
activation. To avoid type collapse, this paper distinguishes four
related objects.

Engagement-Pattern Specification is a mathematical or information-level
specification of a possible organization or trajectory through which
required human functions could operate. It is represented by σ ∈ Σ. A
specification is not itself an actual bodily process.

Actual Engagement Process is the occurrent bodily process through which
required human functions actually operate for a particular person,
demand, context, and time. It is represented by a_obs. When evidence
supports that the process instantiates a specification, the relation is
written a_obs ⊨ σ_obs.

Functional Engagement Assertion is a reified, evidence-bearing relation
instance that binds a person, demand, required human function, context,
time interval, supported actual process, evidence status, provenance,
and rule version. It is not reduced to one binary OWL object property.

Engagement-Pattern Inference is an epistemic classification derived from
evidence about the actual engagement process. Governed values may
include appropriate, compensatory, limited, not established, and
undetermined. These inference values must not be encoded as if they were
a pattern specification or the process itself.

The phrase appropriately engaged is retained in the formal definition of
human function because it conveys the normative meaning of zhengchang
diaoyong (正常调用). Appropriateness is person-, demand-, context-,
time-, safety-, cost-, maintenance-, and recovery-dependent. It does not
prescribe one ideal movement pattern or create a universal binary
taxonomy of normal and abnormal bodies.

The term capacity in this paper refers to a body-dependent
human-function capacity. It is not identical to a score, measurement
result, activity performance, physiological process, organ function, or
professional judgment. Those entities may provide evidence for, realize,
constrain, or represent a capacity, but must not be silently treated as
the capacity itself.
