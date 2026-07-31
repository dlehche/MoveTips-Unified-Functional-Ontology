# 1. Introduction

Human knowledge about the body is extensive. Anatomy represents bodily
structure. Physiology represents processes of maintenance, regulation,
adaptation, defense, repair, and recovery. Medicine identifies disease,
injury, pathological mechanism, and safety risk. Rehabilitation studies
and restores functioning in activities and participation. Exercise
science develops capacity, tolerance, skill, and performance through
structured exposure. Psychology, nutrition, sleep, behavior science, and
environmental health add further explanatory and intervention layers.
Computational physiology, musculoskeletal simulation, and digital-twin
research increasingly attempt to connect these domains across scales
[4–12].

The central problem addressed here is not a lack of specialized
knowledge. It is the absence of a sufficiently explicit formal object
that connects that knowledge around the same person. A laboratory test,
imaging finding, muscle-strength measure, movement observation, pain
report, task outcome, and intervention record may all be valid. Yet
their coexistence does not automatically answer whether the body has the
functions required by the present demand, whether those functions
actually operate, whether the operation is appropriate to the person’s
current boundary and reserve, or what should be inferred when the
available evidence is incomplete.

The World Health Organization’s International Classification of
Functioning, Disability and Health (ICF) established an indispensable
framework for body functions and structures, activities, participation,
environmental factors, and the distinction between capacity and
performance [4,5]. The Physiome Project and the Virtual Physiological
Human seek multiscale integration of physiological models [7,8]. The
U.S. National Institutes of Health Whole Person initiative is building a
cross-system reference physiome and integrated knowledge network of
healthy physiological function [6]. OpenSim demonstrates the
scientific value of explicit, reusable models for musculoskeletal
structure and movement [9]. Digital-twin research emphasizes
individualized, dynamic, data-updated models [10–12]. These
developments establish the need for integration but do not remove the
requirement for a formal interface between internal bodily states,
human-function capacities, concrete demands, actual engagement, lived
results, and longitudinal action.

UOHF was developed to provide that interface. UOHF Definition 2.1
states: human function is the body’s capacity to be appropriately
engaged to meet internal and external demands [1]. Internal demands
include physiological maintenance, regulation, development, defense,
adaptation, repair, and recovery. External demands include behavioral,
environmental, and real-world task demands. A Task is therefore a
principal operational specialization of external demand, not the total
boundary of human function.

Earlier UOHF work established task-capacity matching, safety-gated
inference, separation of observable facts from inferred attribution,
functional engagement, person-level state classes, and longitudinal
write-back [1–3]. The present paper asks a narrower but deeper
question: what formal architecture is required if those commitments are
to become a coherent, extensible, falsifiable, and
implementation-oriented framework rather than a sequence of verbal
rules?

> *Human function is not represented here as one universal score. It is
> represented as a family of person-bound capacities whose adequacy
> becomes meaningful only relative to a specified demand, context, time,
> boundary, and possible engagement process.*

The paper makes six contributions. First, it defines a strict type
system separating capacities, possible engagement-pattern
specifications, actual engagement processes, potential, predicted, and
observed responses, evidence, hypotheses, and representations. Second,
it introduces a capacity-to-pattern realizability operator, preventing
both the direct intersection of unlike domains and the treatment of a
merely possible process as an already existing occurrent. Third, it
defines ontic and epistemic forms of demand-bounded realizability and
derives their immediate set-theoretic consequences. Fourth, it states
and proves a result non-identifiability proposition and derives
open-world rules for evidence and causal attribution. Fifth, it
separates problem hypotheses from evidence status and formalizes a
dynamic decision and update layer. Sixth, it sets out an empirical
research program by which the framework can fail, be revised, or acquire
predictive and decision validity.

# 2. Aim, Method, and Scope

## 2.1 Aim

The aim is to specify the minimum formal architecture required to
represent human function consistently across internal and external
demands while preserving the boundaries among reality, evidence,
inference, representation, and action. The framework must be broad
enough to accept future physiological, biomechanical, behavioral, and
environmental models, but constrained enough to prevent automatic causal
claims, unsafe action, and category errors.

## 2.2 Method

The paper uses conceptual analysis, formal type separation, ontology
competency questions, axiomatic specification, criterion construction,
counterexample analysis, and worked-case testing. The method follows
established ontology-engineering principles: define scope and competency
questions, identify classes and relations, separate types that must not
be conflated, reuse external standards through explicit mappings, and
maintain provenance and version identity [13–21].

The formal statements are evaluated in two different senses. Internal
validity asks whether the conclusions follow from the definitions and
axioms without contradiction. Empirical validity asks whether the
operationalized variables can be measured reliably, distinguish relevant
states, predict future outcomes, and improve decisions. The paper does
not confuse these forms of validation. A formally valid proposition may
still have weak empirical value if its mappings and measurement models
are poorly specified.

## 2.3 Scope

This is a formal-framework and computational-architecture paper. It is
not a systematic review, clinical guideline, diagnostic standard,
randomized trial, or completed whole-person simulator. It does not claim
that the current UOHF catalogue exhausts every human function, that a
unique cause can be calculated from a symptom, or that an intervention
can be selected without domain evidence and professional authority.

The claim of coverage is therefore structural rather than omniscient.
The framework seeks representational closure: every relevant item should
have a valid typed position—as a demand, capacity, realization
mechanism, engagement process, response, measurement, hypothesis,
boundary, action, change, or explicit unknown. It does not claim that
all such items are already known or measurable.

# 3. Positioning Relative to Existing Frameworks

## 3.1 ICF: functioning, capacity, and performance

ICF provides the most influential international framework for describing
functioning and disability. Its separation of capacity in a standardized
environment from performance in the person’s actual environment is
directly relevant to UOHF [4,5]. UOHF does not replace this
distinction. It adds a process-level question between them: which
required human functions actually operate under the specified demand,
through which bodily structures and processes, at what cost, within what
boundary, and with what recovery consequence?

Accordingly, UOHF functional engagement is not a synonym for ICF
performance. Performance is a description of what the person does in the
current environment. Engagement represents whether each required human
function actually operates in the demand context. A person may complete
a task through compensatory engagement, high cost, narrow reserve,
assistance, or environmental modification. The performance may therefore
be achieved while the person-level human-function state is not normal.

## 3.2 Physiome, whole-person research, and multiscale models

The Physiome Project develops a multiscale modeling framework in which
physiological models can be combined hierarchically, from molecular and
cellular mechanisms to organs and organ systems [7,8]. NIH Whole
Person research similarly seeks integrated maps and models across
physiological systems and multiple biological, behavioral, social, and
environmental domains [6]. UOHF is complementary: those models can
estimate or constrain bodily state and capacity, while UOHF provides a
demand-conditioned interface for asking whether the resulting capacities
can be appropriately engaged in the same person.

This division is architectural, not territorial. A future whole-person
model may directly include both physiological transitions and task-level
human-function transitions. UOHF does not insist that physiological
modeling remain external. It insists that scale, model identity,
evidence, and inferential scope remain explicit when they are connected.

## 3.3 Musculoskeletal simulation and specialized models

Specialized models such as OpenSim can estimate movement, muscle
coordination, and internal musculoskeletal loading [9]. Such models
can materially improve human-function inference, but their outputs do
not independently determine person-level human function. A joint-load
estimate, for example, may provide evidence about a burden or structural
constraint. Whether a real-world demand is appropriately met also
depends on the person’s broader capacities, actual engagement process,
safety boundary, persistence, recovery, and context.

## 3.4 Digital twins and sequential decisions

Digital-twin research stresses personalized model states, repeated data
assimilation, simulation of possible futures, and dynamic decision
support [10–12]. Dynamic treatment-regime research similarly
formalizes intervention as a sequence of decision rules that map current
and historical information to an action [22,23]. UOHF adopts this
longitudinal logic while adding a domain ontology and
evidence-governance layer. A model must preserve what was observed, what
was inferred, which version of the person-specific state was used, what
action was authorized, and what actually changed afterward.

## 3.5 Formal ontologies and provenance

Formal ontologies support explicit shared vocabularies, reusable
relations, logical constraints, and data integration [13–18]. OWL 2
provides formal class and property semantics, SHACL supports graph
validation, and PROV-O supports representation of provenance [19–21].
UOHF uses these technologies as implementation methods rather than
sources of the root definition. The framework presented here identifies
the domain distinctions that a future machine-readable implementation
must preserve.

## 3.6 Adjacent formal and practice models

The components assembled here have important precedents. Basic Formal
Ontology represents function as a realizable entity and distinguishes a
function from the process that realizes it [31]. Formal ICF modeling
has translated parts of the classification into ontology structures and
has exposed category and relationship issues that classifications alone
do not resolve [32]. The Person-Environment-Occupation model and the
Ecology of Human Performance framework place performance in a dynamic
person, occupation or task, and context relation [33,34].
Mental-functioning ontology work demonstrates the value of explicit
functioning concepts for interdisciplinary communication and health
informatics [35]. Functional Capacity Evaluation research directly
compares a person’s tested abilities with work-related demands while
also showing that reliability, validity, and transfer to real-world
outcomes require separate evidence [36].

UOHF therefore does not claim priority for capacity-performance
distinctions, person-environment interaction, function realization,
task-demand comparison, dynamic state updating, or ontology-based
representation considered separately. The narrower originality claim is
the governed integration of a person-bound human-function capacity
domain, possible engagement-pattern specifications, typed actual
engagement processes, ex ante appropriate-pattern constraints,
potential, predicted, and observed response objects, explicit unknowns,
evidence-constrained attribution, governed next action, and longitudinal
write-back under one root definition.

**Box 1. Comparison with adjacent formal and practice models.**

| **Adjacent model**                 | **Primary contribution**                                                                                                | **Boundary relevant to this paper**                                                                                         | **Claimed UOHF distinction**                                                                             |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|
| ICF and formal ICF models          | Functioning, body functions and structures, activities, participation, environmental factors; capacity and performance. | Does not centrally type the actual operation of each required human function as a separate engagement process.              | UOHF adds demand-conditioned engagement, cost, boundary, evidence status, and action/update rules.       |
| BFO function theory                | Function as a realizable entity and its realization in process.                                                         | Top-level formal ontology, not a complete person-demand assessment and decision framework.                                  | UOHF specializes the capacity-process distinction around whole-person demands and governed evidence.     |
| PEO / Ecology of Human Performance | Dynamic person-environment-occupation or task-context-performance relations.                                            | Primarily conceptual practice models rather than a machine-governed typed evidence system.                                  | UOHF adds explicit realizability, engagement assertions, causal limits, anchors, and versioned update.   |
| Functional Capacity Evaluation     | Tested ability relative to work-related demands.                                                                        | Usually domain-specific; engagement process, recovery, and longitudinal whole-person state are not universally represented. | UOHF generalizes demand binding while preserving context, cost, engagement, and unknown.                 |
| Mental-functioning ontologies      | Explicit concepts and relations for mental functioning and informatics.                                                 | Domain-focused rather than a cross-domain whole-person operational core.                                                    | UOHF supplies a common upper domain interface while requiring explicit mappings rather than equivalence. |
