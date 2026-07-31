# Appendix A. Minimum Competency Questions

1.  What internal or external demand is present, at what scale, under
    what conditions, and at what time?

2.  What human functions are required to meet that demand?

3.  What current capacities are supported, contradicted, or not
    assessed?

4.  Which engagement-pattern specifications are ontically realizable
    from the current capacities and state?

5.  Which specifications are ex ante appropriate and operationally
    accessible at the required reliability under current safety, load,
    maintenance, and recovery constraints?

6.  What Actual Engagement Process is supported as occurring, which
    specification does it instantiate, which reified Functional
    Engagement Assertions are supported, and what Engagement-Pattern
    Inference remains justified?

7.  What was observed, reported, measured, inferred, predicted, or
    represented?

8.  What immediate cost, accumulated burden, boundary, and reserve are
    supported?

9.  What problem hypotheses remain plausible, what is the evidence
    status of each, and what evidence would discriminate among them?

10. What action is safe, authorized, within scope, above its
    action-specific evidence threshold, and valuable now?

11. What actually changed after demand, exposure, endogenous regulation,
    or external action?

12. What must be revised in the person-specific model, and what
    historical state must remain preserved?

# Appendix B. Minimum Requirements for a Future Machine-Readable Implementation

- A specified person bears a specified human-function capacity at a
  specified time, with evidence and uncertainty metadata.

- A specified demand requires specified human functions under a
  specified context.

- Engagement-pattern specifications, realizability assertions, ex ante
  appropriateness, operational accessibility, and actual engagement
  processes are represented as distinct types.

- A FunctionalEngagementAssertion is reified and binds one person, one
  demand, required functions, context, time, actual process when
  supported, evidence status, provenance, and rule version.

- A positive engagement assertion and a negative engagement assertion
  are represented explicitly; missing data entail neither.

- Potential result, predicted result, observed response, manifestation,
  and measurement result are represented separately and linked to their
  procedures, times, contexts, and sources.

- Problem hypotheses and evidence statuses are represented on separate
  axes; coexisting hypotheses are represented by multiple memberships
  rather than a primitive mixed type.

- Bodily-structure, physiological-process, observation, constraint, and
  action anchors use distinct relation types.

- Immediate cost, accumulated burden, boundary, reserve,
  maintainability, and recovery are represented separately.

- An action records action-specific evidence threshold, safety gate,
  authority, consent, rationale, feasibility, stop conditions, execution
  facts, and reassessment trigger.

- A state inference is versioned and traceable to the exact ontology,
  rules, evidence snapshot, actor or model, and lifecycle status that
  produced it.

- A future OWL/SHACL release should publish stable IRIs, domain and
  range constraints, cardinalities, shapes, competency questions,
  example instances, and validation results; this paper alone does not
  constitute that release.

**UOHF — the unified ontology, formal framework, and semantic-rule
foundation of the Human Function World Model.**
