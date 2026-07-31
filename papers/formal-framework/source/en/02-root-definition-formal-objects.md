# 4. Root Definition and Formal Commitments

## 4.1 Root definition

> *Human function is the body’s capacity to be appropriately engaged to
> meet internal and external demands.*

The grammatical center of the definition is capacity. Human function is
not identical to engagement, although the capacity is defined in
relation to the possibility of ex ante appropriate pattern. A
human-function capacity is body-dependent and person-bound. Its
existence, degree, range, reserve, and current availability may depend
on bodily structures, bodily processes, history, environment, and time.

## 4.2 Functional engagement

An Engagement-Pattern Specification describes a possible organization or
trajectory through which required human functions could operate; it is
an information or mathematical object, not a bodily process. The Actual
Engagement Process is the demand-conditioned operation and organization
that actually occurs in a particular person, context, and time. A
reified Functional Engagement Assertion binds the person, demand,
required human function, context, time, supported process, evidence,
provenance, and rule version. An Engagement-Pattern Inference is a
revisable classification of that evidence. These objects must remain
distinct.

## 4.3 Appropriateness

Appropriateness cannot be defined by one universal movement pattern or
population mean. The ex ante appropriate-pattern set for a person must
be conditioned by the demand, context, time, safety restrictions,
current state, available reserve, acceptable load, maintainability,
recovery, and—where relevant—the person’s preferences and environmental
options. It is a constrained set of specifications available before the
result is observed, not a retrospective label derived from the same
outcome it is intended to evaluate.

## 4.4 Internal and external demand

A Demand is a requirement that must be met through the body’s
organization. Internal demands include maintenance, regulation,
development, defense, adaptation, repair, and recovery. External demands
include behavior, environmental exposure, and real-world tasks. A Task
is a goal-directed activity or activity situation. A Task Demand is the
external requirement generated or imposed by that task under a specified
context. The distinction is necessary because the same task can generate
different demands under different loads, environments, speeds, tools,
and person-specific conditions.

## 4.5 Relationship to the UOHF V1.0 task-centered operational definition

UOHF Definition 2.1 is the current root definition and has priority
throughout this paper. The earlier UOHF V1.0 task-centered
statement—human function as the capacity to complete a task stably and
efficiently under bounded physiological, biomechanical, and cognitive
cost within explicit safety constraints—should be read as an operational
criterion for a major class of external demands [3]. It is not a
second root definition.

Task-Capacity Matching (TCM) is therefore a governed rule family for
operationalizing external task demands. It is not the complete equation
of human function, does not exhaust internal demands, and cannot replace
the person-, demand-, context-, time-, engagement-, cost-, boundary-,
and recovery-sensitive framework developed here.

## 4.6 BFO relationship and non-equivalence

This paper uses the BFO distinction between realizable entities and the
processes in which they are realized as a type-separation aid
[16,17,31]. It does not assert owl:equivalentClass between a UOHF
human-function capacity and BFO:Function or BFO:Disposition. Any future
mapping must state its necessary and sufficient conditions, domain and
range, direction, and scope; until then, the relationship is an explicit
alignment hypothesis rather than formal equivalence.

# 5. Formal Objects and Type System

Let the domains of persons, demands, contexts, and time be denoted by P,
D, K, and T. The framework uses the following core objects. None may be
silently substituted for another.

**Table 1. Core formal objects and type constraints.**

| Symbol             | Formal role                                          | Non-equivalence / implementation note                                                                                                       |
|--------------------|------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| p ∈ P              | A particular person.                                 | The same measurement in different persons does not imply the same state or boundary.                                                        |
| d ∈ D              | A specified internal or external demand.             | A task is an external-demand specialization; d is not restricted to tasks.                                                                  |
| k ∈ K              | Conditions and context.                              | Includes environment, load, tools, timing, assistance, and relevant personal conditions.                                                    |
| t ∈ T              | Specified time or interval.                          | Capacities, boundaries, and engagement may change over time.                                                                                |
| X_t                | Latent or modeled whole-person state.                | Not fully observable; may include multiscale physiological, structural, cognitive, behavioral, and recovery states.                         |
| H_t                | Relevant history.                                    | Includes prior exposure, disease, injury, intervention, adaptation, recovery, and previous state versions.                                  |
| 𝒞_t^real           | Real human-function capacity domain/profile.         | Person-bound capacities that exist in reality; not directly observable as a complete set.                                                   |
| Ĉ_t                | Evidence-supported capacity estimate.                | The model’s revisable epistemic estimate; not identical to 𝒞_t^real.                                                                        |
| Q(d,k)             | Demand or engagement-requirement specification.      | Describes what must be organized under the specified demand and conditions.                                                                 |
| Σ                  | Engagement-pattern specification space.              | Contains possible organization or trajectory specifications, not actual bodily processes.                                                   |
| σ ∈ Σ              | One engagement-pattern specification.                | A possible process pattern that may or may not be realizable, accessible, appropriate, or instantiated.                                     |
| Γ_Σ                | Capacity-to-pattern realizability operator.          | Maps capacities and state to currently realizable pattern specifications.                                                                   |
| Σ_t^real(p,d,k)    | Ontically realizable pattern-specification set.      | A modal or model-level set; its members are not already occurring processes.                                                                |
| 𝒜_pre^Σ(p,d,t,k)   | Ex ante appropriate-pattern set.                     | Specifications satisfying person-, demand-, context-, safety-, load-, maintenance-, and recovery constraints before the result is observed. |
| Access_t(σ\|p,d,k) | Operational accessibility and reliability predicate. | Prevents a theoretically possible but non-repeatable or practically inaccessible pattern from satisfying DHR.                               |
| a_obs              | Actual engagement process supported as occurring.    | An occurrent bodily process; it may instantiate a specification but is not identical to that specification.                                 |
| a_obs ⊨ σ_obs      | Instantiation / conformance relation.                | Connects the observed actual process to the supported engagement-pattern specification.                                                     |
| FEA                | Functional Engagement Assertion.                     | Reified evidence-bearing relation instance binding person, demand, required function, context, time, process, provenance, and rule version. |
| J_eng              | Engagement-pattern inference.                        | Revisable classification such as appropriate, compensatory, limited, not established, or undetermined.                                      |
| E_t^pot(σ)         | Potential-result relation.                           | Ontic set of results compatible with executing σ under the specified state and conditions.                                                  |
| Ê_t(σ)             | Predicted result.                                    | Revisable model prediction based on current evidence; not the result itself.                                                                |
| E_t^obs            | Observed response after an actual process.           | Includes demand attainment, manifestations, cost, burden, boundary, reserve, maintainability, and recovery evidence.                        |
| Y_t                | Evidence and measurement results.                    | Observed, reported, tested, measured, or device-captured information.                                                                       |
| Z_t^problem        | Problem or limiting-factor hypothesis set.           | May include capacity-coverage failure, engagement difficulty, and other/residual explanations concurrently.                                 |
| S_t^evidence       | Evidence status.                                     | Supported, weakened, contradicted, not assessed, insufficient, or undetermined; not a human-function problem type.                          |
| Π_t                | Evidence-conditioned belief state.                   | A governed state of support and uncertainty; probability is optional and requires calibration.                                              |
| U_t                | Governed action domain.                              | Includes observation, assessment, environmental modification, pause, referral, treatment, rehabilitation, exercise, and monitoring.         |

## 5.1 Latent state and observable evidence

The complete bodily state is not directly observable. Evidence is
generated from or related to that state under an observation procedure
and collection conditions. A general observation model is Y_t = O(X_t,
procedure, conditions, ε_t), or probabilistically Y_t ~ P_O(· \| X_t,
procedure, conditions). This form accommodates numeric values, ordinal
grades, categorical findings, text reports, images, device time series,
and missing observations without assuming additive error. The ontology
must preserve the distinction among underlying state, procedure, result,
interpretation, and versioned representation.

## 5.2 Ontic capacity support and epistemic capacity estimation

A person’s human-function capacities are real, person-bound properties
enabled, constrained, or modified by bodily state and history. The
runtime model does not directly observe the complete capacity domain; it
estimates capacities from evidence. The framework therefore separates
the ontic capacity domain from the epistemic capacity estimate.

$$
\mathcal{C}^{\mathrm{real}}_{t}=\Phi_{\mathrm{ontic}}(X_t,H_t),
\qquad
\widehat{\mathcal{C}}_{t}=\Phi_{\mathrm{epistemic}}(Y_{0:t})
$$
(1)

The two mappings are not one universal numerical formula. Φ_ontic
denotes the real dependence of capacities on bodily state and history;
Φ_epistemic denotes the model’s evidence-based estimation process.
Runtime decisions act on the evidence-supported capacity estimate with
an explicit evidence status and must not silently treat that estimate as
complete access to the real capacity domain. Domain-specific models may
contribute to either mapping. A cardiovascular model may constrain
cardiorespiratory tolerance; a musculoskeletal model may constrain force
production and load tolerance; a swallowing model may constrain
ingestion-related capacities; and a cognitive model may constrain
planning, communication, or self-management capacities. UOHF provides
the common type and relation interface through which these mappings can
contribute.

## 5.3 Capacity-to-engagement-pattern realizability

A capacity domain cannot be intersected directly with an actual-process
domain because the two contain entities of different types. Nor should a
merely possible process be represented as if it already exists. The
framework therefore introduces a specification space Σ and a
capacity-to-pattern realizability operator Γ_Σ.

$$
\Sigma^{\mathrm{real}}_{t}(p,d,k)
=
\Gamma_{\Sigma}\!\left(\mathcal{C}^{\mathrm{real}}_{t},X_t,d,k\right)
$$
(2)

The ontic set Σ_t^real contains engagement-pattern specifications that
the person’s current capacities and state can realize under the
specified demand and conditions. A specification may be realizable yet
inappropriate, unsafe, costly, inaccessible, or unreliable. Conversely,
a theoretically appropriate specification may not be realizable by the
person at the present time. Only the occurrent a_obs is an actual
engagement process; evidence may support that a_obs instantiates σ_obs.

## 5.4 Ex ante appropriate-pattern domain

The ex ante appropriate-pattern set 𝒜_pre^Σ(p,d,t,k) is defined
independently of the observed result to avoid circular reasoning. It
contains specifications satisfying constraints supportable before or at
the decision point: safety, demand requirements, professional
restrictions, current boundary, acceptable load, and feasible
maintenance or recovery conditions. Operational accessibility and
required reliability are represented separately by Access_t. A
specification is not rendered appropriate merely because a favorable
result was later observed.

## 5.5 Potential, predicted, and observed response

The framework distinguishes three response objects. E_t^pot(σ \|
X_t,d,k) is the ontic set of outcomes compatible with executing
specification σ under the given state and conditions. Ê_t(σ) is the
model’s revisable prediction before execution. E_t^obs =
e_obs(X_t,a_obs,d,k) is the response supported after an actual process
occurs. A minimum response vector may include demand attainment,
manifestations, immediate cost, accumulated burden, boundary margin,
reserve, maintainability, post-demand response, and recovery. The exact
dimensions are domain-dependent, but potential, predicted, and observed
results must not be collapsed.

## 5.6 Functional Engagement Assertion as a reified relation instance

Functional engagement is inherently multi-argument: it concerns one
person, one demand, one or more required human functions, a context, a
time interval, an actual process when supported, evidence status,
provenance, and rule version. OWL 2 object properties are binary [19].
A machine implementation should therefore represent a
FunctionalEngagementAssertion individual and connect it through
properties such as hasPerson, hasDemand, requiresHumanFunction,
hasContext, hasTimeInterval, supportedByActualProcess,
hasEvidenceStatus, generatedByAssessment, hasProvenance, and
usesRuleVersion. A missing assertion entails neither positive nor
negative engagement.

**Table 2. Required identity and non-identity rules.**

| Object A                         | Must not be equated with                                      | Reason                                                                                                              |
|----------------------------------|---------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|
| Human-function capacity          | Engagement-pattern specification or actual engagement process | A capacity may exist without one specified pattern being accessible or operating under the demand.                  |
| Engagement-pattern specification | Actual engagement process                                     | A specification is possible or informational; an actual process is occurrent.                                       |
| Potential or predicted result    | Observed response                                             | A compatible or predicted outcome is not an event or measurement that has already occurred.                         |
| Problem hypothesis               | Evidence status                                               | A proposed explanation is not identical to the degree of support currently available for it.                        |
| Actual engagement process        | Manifestation                                                 | A process may occur without a visible manifestation; one manifestation may arise from different processes.          |
| Manifestation                    | Measurement result                                            | A manifestation exists in the person; a measurement result is information generated by a procedure.                 |
| Measurement result               | Inference                                                     | A measured value does not contain its causal explanation.                                                           |
| Structure anchor                 | Cause                                                         | An anchored structure may realize, bear, constrain, or evidence a function without being the unique pain generator. |
| Immediate cost                   | Accumulated burden                                            | A low immediate cost can coexist with rising longitudinal burden.                                                   |
| Boundary                         | Reserve                                                       | Boundary marks a limit; reserve is remaining capacity relative to that limit and demand.                            |
| Underlying state                 | State inference / representation                              | A person’s reality is not identical to the information object describing it.                                        |
| Missing assertion                | Negative fact                                                 | Under open-world semantics, absence of evidence is not evidence of absence.                                         |
