2.  the current primary demand, engagement manifestations, cost, and boundaries;

3.  causes that have been excluded and causes that remain to be tested;

4.  the precise question the next profession is asked to clarify;

5.  the authority and safety boundaries the current profession must not exceed.

### 12.9 Reality, Epistemic, and Application Layers Remain Distinct

Within the interpretive framework proposed here, medicine, rehabilitation, and exercise form a core professional axis around human function. Psychology and nutrition enter when they become the current primary limitation or a necessary enabling condition. These responsibilities belong to professional work in the epistemic and application layers; they are not themselves the core ontology of human function.

The MUFO core ontology describes what human functions exist, which functions are required by internal and external demands, the structures and processes through which those functions are realized, whether they are engaged, and their coordination, compensation, boundaries, states, time, and change. Professions use assessment, diagnosis, treatment, rehabilitation, exercise, psychological intervention, and nutritional support to change these realities. Professional action must not be allowed to define the human-function object in reverse.

## 13. Minimum Formal Framework for MUFO

To move unification from a philosophical proposition to a machine-readable ontology, MUFO must represent at least the following core objects, relations, and descriptive dimensions. Whether each item should ultimately be modeled as a continuant, process, relation, quality, disposition, or information entity must be determined through upper-ontology mapping and logical testing. This paper does not prematurely force all items into one ontological category.

In formal modeling, **functional engagement** should be represented as a contextualized engagement assertion linking one specified demand to one specified required human function for a particular person, under specified conditions and at a specified time. The assertion explicitly records whether evidence supports actual operation of that function; a negative engagement fact must not be inferred from a missing assertion. Bodily structures and bodily processes explain how actual operation is realized. By contrast, the statement that a type of demand requires a type of human function is a more stable domain relation between demand and function. Keeping these distinctions prevents demand-function requirements, engagement facts, and realization processes from being conflated.

The minimum framework includes:

- person;

- internal demand;

- external demand;

- human function;

- bodily structure;

- bodily process;

- functional engagement;

- coordination;

- compensation;

- conditions and environment;

- boundary;

- state;

- time;

- change.

At minimum, MUFO must express the following relations:

1.  a human function belongs to a person;

2.  meeting a demand requires a human function;

3.  a human function serves one or more internal or external demands;

4.  a human function depends on particular bodily structures;

5.  a human function is realized through particular bodily processes;

6.  a functional-engagement fact concerns a specific person;

7.  a functional-engagement fact is contextualized by an internal or external demand, conditions, and time;

8.  a functional-engagement fact links one specified demand to one specified required human function and explicitly records whether that function actually operates;

9.  the actual operation involved in engagement depends on particular bodily structures and is realized through particular bodily processes;

10. several functional operations may be coordinated within the same functional-engagement context;

11. functional engagement is conditioned by environment, load, and time;

12. the operation of a human function under engagement is bounded;

13. function, engagement, coordination, compensation, boundaries, and state change over time;

14. assessments, evidence, and professional actions refer to human-function facts but are not identical to those facts.

The minimum judgment logic is:

- for each specified demand-function pair, when evidence supports that the required function actually operates, engagement is present;

- when evidence establishes that the specified required function does not actually operate, a negative engagement assertion is represented explicitly rather than inferred from missing data;

- when the functional capacity itself is insufficient, impaired, or absent, a functional-capacity problem exists;

- when evidence supports the presence of the capacity but it does not operate under the concrete demand, a functional-engagement problem exists;

- when evidence is insufficient, no definitive judgment about engagement or causal attribution is made.

The framework must still be translated into formal class definitions, relation constraints, logical axioms, instance data, and reasoning tests. Machine-readable implementation should maintain explicit boundaries among classes, relations, and constraints and should control semantic drift through version governance, logical consistency testing, and data-shape validation. OWL 2 and SHACL can respectively support formal semantic expression and validation of data graphs \[11,12\].

## 14. Relationship to Existing Systems

MUFO’s value should not be established by dismissing existing systems. Those systems already provide important foundations within their respective scopes.

### 14.1 International Classification of Functioning, Disability and Health

The International Classification of Functioning, Disability and Health (ICF) is the World Health Organization’s international classification and terminology framework for describing functioning, disability, and health in context, including environmental factors \[1\]. MUFO should map to ICF but should not attempt to rewrite ICF as MUFO. MUFO further organizes human function at the whole-person level, internal and external demands, realization through structures and processes, and functional engagement within one cross-scale semantic framework centered on the same person.

### 14.2 Whole Person Physiome

The Whole Person Physiome Program (WPP) aims to digitally integrate multiorgan, multiscale physiological processes and interactions across the whole person \[2\]. The molecular, cellular, tissue, organ, organ-system, physiological-process, and cross-organ content targeted by WPP is directly relevant to the realization mechanisms of human function at the whole-person level in MUFO.

MUFO should neither reduce WPP to a “middle physiological layer” nor divide the ultimate scopes of the two programs into mutually exclusive territories. MUFO’s unifying line is to connect multiscale mechanisms to human functions at the whole-person level, internal and external demands, and functional engagement.

### 14.3 Gene Ontology and Human Phenotype Ontology

