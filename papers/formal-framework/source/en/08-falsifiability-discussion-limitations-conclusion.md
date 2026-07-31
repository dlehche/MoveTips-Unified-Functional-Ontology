# 15. Falsifiability and Failure Conditions

The framework should be rejected, narrowed, or revised if its central
distinctions cannot be supported. The following are not minor
implementation defects; they are potential falsifiers of substantive
claims.

**Table 9. Falsification and major failure conditions.**

| **Failure condition**                                              | **Scientific implication**                                                                                                                                |
|--------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Capacity and engagement cannot be measured distinctly              | If operational measures collapse into one factor across well-designed studies, the claimed separation may lack empirical utility.                         |
| The model does not outperform simpler baselines                    | If pain, one capacity measure, or ordinary judgment predicts outcomes equally well with less burden, the added complexity is not justified for that use.  |
| Appropriateness cannot be specified without circularity            | If 𝒜_pre^Σ can only be defined from the same observed outcome it is meant to evaluate, the central realizability criterion becomes unusable.              |
| Inter-rater judgments remain unstable                              | If trained raters cannot reproduce capacity, engagement, boundary, or state judgments, the ontology has not operationalized the constructs adequately.    |
| The same rules fail across minor context changes                   | If person-, demand-, time-, context-, accessibility-, and reliability-binding cannot account for observed variation, the formal variables are incomplete. |
| Anchors systematically produce false causal attribution            | If implementation encourages structure-as-cause errors despite the formal rule, governance has failed.                                                    |
| Unknown cannot be preserved                                        | If system pressure forces every case into a known category, open-world coverage and safety claims are false.                                              |
| Longitudinal updates cannot revise prior conclusions transparently | If new evidence overwrites history or cannot explain why the state changed, auditability is not achieved.                                                 |

A negative result in one demand domain does not automatically refute the
root definition, but it may refute a measurement model, capacity
catalogue, engagement rule, state classifier, or decision policy. The
framework is deliberately modular so that falsification can be localized
without protecting every component from revision.

# 16. Discussion

## 16.1 What is genuinely new

The individual components of the framework have precedents. ICF
distinguishes capacity and performance [4,5]. Physiology and
biomechanics model bodily processes [7–9]. Digital twins model dynamic
individual states [10–12]. Sequential decision theory maps state
information to actions [22,23,25]. Formal ontologies and provenance
standards support semantic consistency and auditability [13–21,31–35].
Person-environment-performance models and functional-capacity evaluation
also precede UOHF in relating person attributes, context, occupation or
work demands, and observed performance [33,34,36]. The proposed
contribution is the governed integration of these elements around one
root object: the body’s capacity to be appropriately engaged to meet
internal and external demands.

The distinctive structure is not a new claim that demand must be matched
by capacity. It is the combined separation and reconnection of
human-function capacity, engagement requirement, realizable pattern
specification, ex ante appropriate pattern, operational accessibility,
actual engagement process, potential, predicted, and observed response,
manifestation, measurement, cost, boundary, reserve, problem hypothesis,
evidence status, governed action, actual change, feedback, and versioned
state representation.

## 16.2 Why one total score is inadequate

A total score can be useful for screening or communication, but it
cannot be the foundational representation. Human-function dimensions are
heterogeneous, critical safety requirements are non-compensable, and two
people with the same total score may have different demands, boundaries,
engagement routes, and risks. Any summary score must therefore remain
traceable to the structured vector and must not erase unknown or
hard-gate failures.

## 16.3 Professional coordination

The framework permits a common interpretation of medicine,
rehabilitation, and exercise without erasing professional boundaries.
Medicine primarily addresses human-function capacities, their biological
foundations, and safety boundaries. Rehabilitation primarily restores
required capacities into ex ante appropriate pattern in real demands.
Exercise maintains and enhances human function and expands engagement
boundaries through sustained, appropriate, progressive engagement. These
are organizing emphases, not exclusive scopes. Psychology, nutrition,
sleep, nursing, occupational therapy, speech and language therapy, and
other domains enter according to the current limiting factors, evidence,
and authority.

## 16.4 Relation to complete human computation

The formal framework is not a complete equation of the human body. A
computable whole-person system will require many local and multiscale
models. The proposed role of UOHF is to provide a stable top-level
semantic and decision interface through which those models can
contribute to the same person’s demand-conditioned human-function state.
Full coverage therefore means extensible representational closure and
explicit unknowns, not prior possession of every biological variable.

## 16.5 Scientific value

The immediate scientific value lies in creating a measurable research
object. The framework generates testable questions: Does
capacity-plus-engagement evidence predict task outcomes better than
capacity alone? Can high-cost task completion be distinguished from
normal function? Can condition perturbations discriminate capacity
limitations from engagement limitations? Do person-level states predict
future deterioration or recovery? Does a structured AI reduce
unsupported causal attribution? These are empirical questions on which
the framework can succeed or fail.

# 17. Limitations

First, the mathematical objects are formal placeholders until
domain-specific measurement models are specified. Γ_Σ, 𝒜_pre^Σ,
Access_t, E_t^pot, Ê_t, e_obs, 𝓔\*, F, and 𝓑 are not calibrated
universal functions.

Second, the current UOHF human-function catalogue and relation topology
have not been proven complete. New capacities, demands, relations, or
state dimensions may require addition, division, or revision.

Third, appropriateness includes normative and person-specific
constraints. These require transparent governance and cannot be
delegated solely to statistical optimization.

Fourth, latent whole-person state is only partially observable.
Inference will remain uncertain even with extensive data, and
missingness may be systematic rather than random.

Fifth, causal attribution is inherently difficult. Repeated response to
intervention improves evidence but does not guarantee unique
identification.

Sixth, the worked example is illustrative and does not establish
diagnostic or treatment validity for knee pain.

Seventh, interoperability with ICF, SNOMED CT, UMLS, BFO, Relation
Ontology, physiological model repositories, and future whole-person
standards requires explicit mapping and external review. Similarity of
labels must not be represented as automatic equivalence.

Eighth, this paper is authored within an organization developing related
ontology assets, software, training, and services. Independent
replication and governance are necessary.

Ninth, Criterion 1 is definitional. The framework acquires scientific
value only if its operationalizations produce reliable measurement,
discriminating classifications, stronger prediction than simpler
baselines, and beneficial governed decisions.

# 18. Conclusion

This paper formalizes human function without reducing it to a symptom,
isolated measurement, task outcome, or global score. Human function
remains the body’s capacity to be appropriately engaged to meet internal
and external demands. Capacity, engagement-pattern specification, actual
engagement process, and response are related but ontologically distinct.
Capacity becomes relevant to a specified demand through a realizability
operator over pattern specifications. Ex ante appropriateness and
operational accessibility constrain which specifications can support the
demand. Potential and predicted results remain separate from the
observed response produced after an actual engagement process.

The demand-bounded realizability criterion specifies the ontic
conditions under which a demand is appropriately meetable from current
capacities and the separate epistemic judgment available to the runtime
system. The result non-identifiability proposition establishes why pain,
altered performance, or task failure cannot independently reveal one
unique cause. These principles support a two-axis representation:
problem hypotheses may include capacity-coverage failure, engagement
difficulty, and other or residual explanations, while evidence status
records their support, weakening, contradiction, non-assessment,
insufficiency, or indeterminacy. They also determine the correct role of
structure, process, observation, constraint, and action anchors—not to
manufacture causal diagnoses.

The resulting architecture is dynamic. Evidence updates a belief state;
authorized actions are selected under action-specific evidence, safety,
consent, authority, feasibility, stop, and reassessment constraints;
actual change is distinguished from model update; and every conclusion
remains versioned and revisable. The framework therefore provides an
implementation-oriented candidate formal core for the UOHF domain
ontology, Human Function Engine, Individual Human Function Model, and
Human Function World Model.

> *The central scientific claim is not that one equation already
> computes the whole human body. It is that all valid human-function
> knowledge can be required to enter one typed, demand-conditioned,
> evidence-bounded, safety-constrained, longitudinally revisable
> computational framework without changing the root definition.*

Whether this framework becomes scientifically useful now depends on
operationalization and comparative evidence. Its constructs must be
measurable, its judgments reproducible, its predictions stronger than
simpler alternatives, its decisions beneficial, and its failures
transparent. That is the research program opened by the formal
framework.
