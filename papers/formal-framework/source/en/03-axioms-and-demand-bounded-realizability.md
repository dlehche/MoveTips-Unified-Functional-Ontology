# 6. Axioms

**Table 3. Core axioms of the formal framework.**

| **Axiom**                                                  | **Statement**                                                                                                                                                                                                                                                                             |
|------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| A1. Person binding                                         | Every human-function assertion concerns a particular person or an explicitly defined population-level type; instance inference must not silently move between persons.                                                                                                                    |
| A2. Demand binding                                         | Adequacy, engagement, cost, and boundary claims must be bound to a specified internal or external demand.                                                                                                                                                                                 |
| A3. Context and time binding                               | The same person and demand may yield different realizability and engagement under different conditions or times.                                                                                                                                                                          |
| A4. Type separation                                        | Capacity, pattern specification, actual engagement process, potential result, predicted result, observed response, evidence, hypothesis, evidence status, representation, and action are distinct formal types.                                                                           |
| A5. Realizability mediation                                | Capacities influence engagement through an explicit operator over pattern specifications; capacity, specification, and actual-process domains are not directly intersected.                                                                                                               |
| A6. Ex ante appropriateness                                | The ex ante appropriate-pattern set is constrained without using the same ex post outcome that it is intended to evaluate.                                                                                                                                                                |
| A7. Open-world evidence                                    | Missing evidence does not establish a negative capacity, engagement, or causal assertion.                                                                                                                                                                                                 |
| A8. Non-unique attribution                                 | A manifestation or measurement result does not uniquely identify a limiting factor unless identifiability is independently established.                                                                                                                                                   |
| A9. Safety, authority, and action-specific evidence gating | Every action type has a minimum evidence threshold EvidenceThreshold(u). Substantive action is inadmissible when its safety, authority, consent, scope, or evidence threshold fails; information-gathering action may be selected precisely because substantive evidence is insufficient. |
| A10. Longitudinal revision                                 | State inferences and action policies remain revisable by new evidence, actual change, reassessment, and versioned write-back.                                                                                                                                                             |
| A11. Anchor non-causality                                  | A structural or physiological anchor denotes a governed relation to realization, burden, observation, or constraint; it does not by itself assert causal pathology.                                                                                                                       |
| A12. Explicit unknown                                      | When the current ontology, measurement model, or evidence cannot support a determination, unknown is a valid formal result.                                                                                                                                                               |

These axioms are normative commitments of the representation. They do
not assert that a particular measurement tool is valid or that a
particular causal model is correct. They specify the conditions under
which claims may be formed without category error or unsupported
certainty.

# 7. Demand-Bounded Human-Function Realizability

## 7.1 Definition of demand-bounded realizability

Define DHR^ontic(p,d,t,k) as the proposition that the specified demand
is appropriately meetable by the person at the specified time and
context. DHR^ontic is not the human function itself and is not the
runtime judgment; it is an ontic demand-bounded proposition about
whether current capacities support at least one operationally
accessible, ex ante appropriate engagement-pattern specification with an
acceptable potential result.

$$
\begin{aligned}
\mathrm{DHR}^{\mathrm{ontic}}(p,d,t,k)=1
\iff {} & \exists\,\sigma\in
\Sigma^{\mathrm{real}}_{t}(p,d,k)
\cap
\mathcal{A}^{\Sigma}_{\mathrm{pre}}(p,d,t,k)\\
& \mathrm{Access}_{t}(\sigma\mid p,d,k)\ge r_{\min}
\quad\text{and}\quad
E^{\mathrm{pot}}_{t}(\sigma)\cap
\mathcal{E}^{*}(p,d,t,k)\ne\varnothing .
\end{aligned}
$$
(3)

## 7.2 Demand-Bounded Realizability Criterion

Criterion 1 (definition). DHR^ontic(p,d,t,k) is true exactly when at
least one engagement-pattern specification σ is (i) ontically realizable
from the person’s current capacities and state; (ii) contained in the
person-specific ex ante appropriate-pattern set; (iii) operationally
accessible at or above the required reliability under bounded
perturbation; and (iv) compatible with at least one acceptable potential
result. The runtime model cannot observe the complete ontic sets
directly. It therefore reports an epistemic judgment DHR_hat_t ∈
{supported, not supported, insufficient evidence}.

Equation (3) is a definition of the ontic demand-bounded proposition,
not an empirical biological law and not a non-trivial theorem. Its
scientific value depends on whether Σ_t^real, its evidence-supported
estimate, 𝒜_pre^Σ, Access_t, E_t^pot, and the acceptable-result set 𝓔\*
can be operationalized and validated without circularity. The epistemic
runtime judgment must remain explicitly distinct from the proposition it
estimates.

## 7.3 Immediate set-theoretic consequence

Proposition 1 (empty admissible-pattern consequence). If no σ belongs to
both Σ_t^real(p,d,k) and 𝒜_pre^Σ(p,d,t,k) while also satisfying the
required Access_t threshold and having a potential-result set that
intersects 𝓔\*, then DHR^ontic(p,d,t,k)=0. Partial attainment through an
actual process that does not instantiate such a specification cannot
satisfy the defined proposition.

Proof. Criterion 1 requires at least one specification satisfying all
four predicates. If no such specification exists, the existential
condition is false; therefore DHR^ontic=0. An observed process may still
produce partial attainment, but that does not make the defined
conjunction true. □

The runtime system may be unable to determine whether the conjunction is
satisfied because 𝒞_t^real, Σ_t^real, potential results, and
accessibility are only partially observed. In that case the valid
epistemic output is insufficient evidence, not DHR^ontic=0.

## 7.4 Hard gates and non-compensability

The acceptable-result set, ex ante appropriate-pattern set, and
accessibility threshold may contain hard constraints. A critical safety
requirement cannot be averaged away by high performance in another
dimension. Similarly, failure of an indispensable engagement requirement
cannot be compensated by unrelated capacity, and a one-off accidental
success cannot establish stable accessibility. This is why UOHF does not
reduce human function to an unconstrained weighted sum.

## 7.5 Vector-valued person-level state

For practical inference, DHR should be accompanied by a structured state
vector rather than a single score. A minimum vector can report demand
attainment, engagement quality, immediate cost, accumulated burden,
boundary margin, reserve, maintainability, recovery, and uncertainty.
The current four foundational person-level, task-centered state
classes—Normal, Compensatory, Critical, and Functional Incapacity
(失能)—are summaries of this structured evidence, not universal labels
for every organ, cell, or molecular state [1].
