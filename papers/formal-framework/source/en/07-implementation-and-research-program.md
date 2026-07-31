# 13. From Formal Framework to an Implementation-Oriented UOHF Architecture

## 13.1 UOHF as semantic and rule foundation

UOHF defines and governs the domain objects, relations, constraints,
evidence requirements, authority rules, provenance, versions, and
lifecycle status. It should not be reduced to a static terminology list.
The formal framework supplies the runtime meaning of relations among
demand, human function, engagement, manifestation, cost, boundary,
state, action, and feedback.

## 13.2 Human Function Engine

The proposed Human Function Engine would execute bounded reasoning and
action workflows. It would identify required functions, check evidence,
distinguish capacity from pattern specification and actual engagement,
preserve unknowns, apply action-specific safety, authority, and evidence
gates, generate problem hypotheses with separate evidence status, select
the next admissible action, and produce a traceable reasoning artifact.
This paper specifies an implementation contract; it does not claim that
the complete Engine or all formal modules are already operational.
Candidate AI output must never be silently converted into a formal fact.

## 13.3 Individual Human Function Model

The proposed Individual Human Function Model preserves one person’s
versioned longitudinal state memory: demands encountered, capacities
evidenced, pattern specifications considered, actual engagement
processes observed, predicted and observed responses, manifestations,
costs, boundaries, actions, actual changes, and unresolved
uncertainties. Historical states remain replayable rather than being
overwritten by the latest interpretation.

## 13.4 Human Function World Model

The proposed Human Function World Model represents possible state
transitions across demand, context, time, exposure, endogenous
regulation, and external action. Pattern specifications, potential
results, predicted future states, current inferred states, actual
processes, and observed facts must remain distinct. Domain-specific
physiological and biomechanical models may be composed through explicit
interfaces while retaining their scale, identifiers, assumptions, and
validation status.

## 13.5 Reified Functional Engagement Assertion contract

A future OWL implementation should instantiate
FunctionalEngagementAssertion as a relation object rather than
attempting to encode the full n-ary relation as one object property.
Minimum links are hasPerson, hasDemand, requiresHumanFunction,
hasContext, hasTimeInterval, supportedByActualProcess,
instantiatesPatternSpecification, hasEngagementInference,
hasEvidenceStatus, generatedByAssessment, hasProvenance, and
usesRuleVersion. Positive and negative assertions must be explicit;
absence of an assertion entails neither. SHACL or an equivalent
validation layer should enforce required fields, value sets, provenance,
and lifecycle state.

**Table 7. Illustrative alignment between the formal framework and UOHF
implementation roles.**

| **Implementation semantic role**    | **Formal responsibility**                                                     |
|-------------------------------------|-------------------------------------------------------------------------------|
| Person / role / authority           | Who is described and who may observe, infer, confirm, or act.                 |
| Context and environment             | Conditions under which demands, engagement, evidence, and action occur.       |
| Bodily structure and process        | Realization, constraint, burden, and observation anchors.                     |
| Human-function capacity             | What the body is capable of being appropriately engaged to do.                |
| Demand / task                       | What must be met under specified conditions.                                  |
| Manifestation and measured response | What was experienced, observed, or measured.                                  |
| Problem and background hypothesis   | Evidence-bounded candidate explanation, not automatic fact.                   |
| Assessment                          | How discriminating evidence is acquired and interpreted.                      |
| Recommendation direction            | Governed statement of what should happen next and why.                        |
| Solution / execution template       | Authorized method with progression, regression, stop, and reassessment rules. |
| Execution fact                      | What was actually done and what happened.                                     |
| Learning / governance               | Rule revision, case learning, provenance, and version control.                |
| Monitoring                          | Trend, alert, reassessment, and boundary-change triggers.                     |

# 14. Scientific Research Program

The formal framework becomes scientifically useful only when its
variables and operators are operationalized and tested against simpler
alternatives. The appropriate development path is staged.

**Table 8. Staged validation program for the formal framework.**

| **Research stage**            | **Primary work**                                                                                           | **Minimum success criterion**                                                         |
|-------------------------------|------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|
| Stage 1. Formal specification | Encode types, relations, axioms, and constraints; test consistency and competency questions.               | No category contradictions; explicit unknown; reproducible inference traces.          |
| Stage 2. Content validity     | Expert and stakeholder review of demand, capacity, engagement, cost, boundary, and recovery constructs.    | Agreement that constructs are necessary, distinct, and comprehensible.                |
| Stage 3. Operationalization   | Define measurement procedures and evidence packages for a narrow demand, such as stair climbing.           | Every variable has an observable or explicitly latent status and collection protocol. |
| Stage 4. Reliability          | Test inter-rater, intra-rater, test-retest, and data-quality reliability.                                  | Predefined reliability thresholds and error estimates.                                |
| Stage 5. Construct validity   | Test whether capacity, engagement, cost, boundary, and recovery are empirically distinguishable.           | Factorial, convergent, discriminant, and known-groups evidence.                       |
| Stage 6. Predictive validity  | Compare the structured model with pain score, isolated capacity tests, or ordinary professional judgment.  | Out-of-sample prediction of task persistence, deterioration, recovery, or escalation. |
| Stage 7. Decision utility     | Test whether model-guided assessment and action improve safety, efficiency, outcomes, or information gain. | Prospective comparative or adaptive intervention studies.                             |
| Stage 8. Generalization       | Replicate across demands, populations, professional settings, languages, and data sources.                 | Stable core relations with domain-specific measurement extensions.                    |

## 14.1 Initial empirical study

A defensible first study should not attempt to validate the complete
human-function system. It should select one bounded demand and evaluate
whether capacity, engagement, response cost, boundary, and recovery can
be measured distinctly. For example, a prospective stair-climbing study
could compare a UOHF classification with isolated knee-extension
strength, pain intensity, and conventional clinical judgment for
predicting repeated-task tolerance and short-term recovery.

## 14.2 AI evaluation

The framework also supports an auditable AI benchmark. Models could be
tested on whether they distinguish observation from inference, preserve
insufficient evidence, avoid direct symptom-to-structure attribution,
select appropriate additional evidence, obey safety and authority gates,
and update conclusions after contradictory feedback. The comparison
should include unconstrained language models and structured UOHF-guided
systems.

## 14.3 Interoperability and FAIR research assets

Public research artifacts should use persistent identifiers, versioned
ontology releases, explicit mappings, provenance, and, when implemented,
machine-readable validation rules and reusable data dictionaries
consistent with FAIR principles [18]. Reproducible implementations
should preserve the exact ontology, rules, evidence snapshot, and
parameter version used for each inference.
