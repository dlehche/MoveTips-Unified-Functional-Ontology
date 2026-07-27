# Unification in the MoveTips Unified Functional Ontology

## A Whole-Person Conceptual Framework Centered on Human Function and Functional Engagement

**Lei Che**

MoveTips Technology (Beijing) Co., Ltd.

**Version 1.0 English Academic Preprint**

Conceptual ontology framework and research proposal \| 27 July 2026

**Zenodo DOI:** [10.5281/zenodo.21618293](https://doi.org/10.5281/zenodo.21618293)

## Abstract

Modern medicine, physiology, rehabilitation, exercise science, clinical informatics, and life-science ontologies have developed substantial bodies of knowledge concerning disease, bodily structure, physiological process, body function, activity and participation, clinical phenotype, molecular function, health intervention, and professional action. Each of these systems addresses important questions. Yet when they are brought to bear on the same individual, the functions that already exist as an integrated whole in that person are still often distributed across different scales, professions, and semantic frameworks. What functions the human body has, which functions are required by different internal and external demands, how those functions are realized through bodily structures and processes, and whether they actually operate in real situations have not yet been consistently organized as a continuous semantic representation centered on the same whole person.

Taking **unification** as its central line of argument, this paper proposes a core definition for the MoveTips Unified Functional Ontology (MUFO): **Unification in MUFO means using one coherent semantic system to describe human functions as they exist within an integrated whole person, together with their functional engagement.** Unification does not mean mechanically combining disciplinary knowledge, nor does it mean prescribing how the body ought to operate. It means returning function, demand, engagement, coordination, compensation, boundaries, state, time, and change to the same whole person in whom they actually occur.

MUFO must unify at least six connected domains. First, it must unify what human functions exist and establish completeness rules that continuously expose omissions. Second, it must unify which human functions are required to meet different internal and external demands. Third, it must unify the realization relations between human function, bodily structure, and bodily process. Fourth, it must unify **functional engagement**, a relation internal to the concept of human function: whether the functions required by a demand actually operate when that demand arises. Fifth, it must unify coordination, compensation, boundaries, state, time, and change as dimensions through which functions and their engagement are fully described. Sixth, it must unify these facts in relation to the same person, under specified conditions, across continuous time.

Functional engagement is not a second ontological construction principle parallel to unification. It is an indispensable relation within the concept of human function. Its philosophical definition is: **Functional engagement is whether the human functions required by internal and external demands actually operate when those demands arise.** Its formal definition is: **Functional engagement is the context-specific relation, for a particular person under specified conditions and at a specified time, between a specified demand and each human function required to meet it, according to whether that function actually operates through corresponding bodily structures and bodily processes.** Function describes what capacities the body has; engagement describes whether those capacities actually operate under concrete demands. For each specified demand-function pair, the engagement relation holds when the required function operates and does not hold when it does not.

The paper further distinguishes a **functional-capacity problem** from a **functional-engagement problem**. The former primarily concerns insufficiency, impairment, or loss of the required functional capacity itself. The latter concerns a situation in which relevant functional capacities are supported by evidence as present, but do not actually operate under a specific internal or external demand. The two may coexist, and they must not be forcibly separated when evidence is insufficient. The paper also proposes a shared engagement semantics and a cross-professional framing. Within MUFO, medicine, rehabilitation, and exercise can be interpreted along the common axis of **functional capacity - restoration of appropriate engagement - maintenance and enhancement of human function and expansion of engagement boundaries**. Psychology and nutrition are not positioned as fixed stages parallel to this axis; they are incorporated when indicated by the current primary limiting factor, available evidence, and professional scope. The MUFO core ontology describes the reality of human function itself. Observation, measurement, assessment, and professional judgment belong to the epistemic layer. Medical treatment, rehabilitation, exercise, psychological intervention, nutritional support, environmental modification, and other solutions belong to the application layer.

**Keywords:** human function; MoveTips Unified Functional Ontology; MUFO; unification; functional engagement; internal and external demands; whole person; functional-capacity problem; functional-engagement problem; ontology

## Terminological Note

In this paper, **functional engagement** is the technical English rendering of the Chinese term *diaoyong* (调用). It does **not** mean patient engagement, service engagement, conscious command, voluntary participation, or mere neural activation. It denotes whether the human functions required by a specific internal or external demand actually operate, through bodily structures and bodily processes, in a particular person, under particular conditions, and at a particular time.

The phrase **appropriately engaged** is retained in the formal definition of human function because it conveys the normative meaning of the Chinese expression *zhengchang diaoyong* (正常调用): the required functions operate in a manner appropriate to the present demand, the person’s conditions, and relevant safety boundaries. It does not introduce a separate taxonomy of “normal” and “abnormal” engagement.

## 1. Introduction

A person exists as an integrated living whole. Respiration, circulation, digestion, metabolism, sensation, cognition, movement, defense, repair, recovery, and everyday activity do not occur in different objects; they occur in the same person. Molecules, cells, tissues, organs, organ systems, physiological processes, behavior, environment, and real life are likewise not separate worlds. They are different scales and conditions of the existence and change of the same human being.

Knowledge about the human body, however, has long been organized according to disciplinary objects and professional tasks. Anatomy describes bodily structure. Physiology describes life processes. Medicine identifies disease, injury, and safety risk. Rehabilitation focuses on activity, participation, and functional restoration. Exercise science focuses on capacity, load, adaptation, and performance. Clinical informatics uses terminology and classification to support documentation, exchange, and analysis. Molecular ontologies organize gene products, molecular activities, and biological processes.

This division of labor is necessary, but it does not automatically produce a shared semantics of the whole person. Disease, structural abnormality, physiological change, pain, movement performance, difficulty in everyday life, exercise capacity, and recovery may be recorded in separate systems. Knowledge can continue to accumulate, but if these forms of knowledge cannot consistently refer back to the same human function in the same person, and cannot state whether that function actually operates under concrete internal and external demands, then the “whole person” remains a collection of professional data rather than a common object that can be described, related, and computed over time.

MUFO does not primarily seek to add another disease classification, movement taxonomy, or intervention catalogue. Its central question is:

> **How can one coherent semantic system describe human functions as they exist within an integrated whole person, together with their functional engagement?**

Accordingly, this paper does not treat “unification” and “functional engagement” as two parallel topics at the same conceptual level. The central topic is unification in MUFO. Functional engagement is explained as a key relation within the concept of human function and is incorporated into the unifying framework.

This paper addresses the following questions:

1.  What does “unification” mean in MUFO?

2.  Which realities and relations of human function does MUFO unify?

3.  How can MUFO unify what human functions exist without mistaking a finite list for completeness?

4.  How can relations between internal and external demands and human functions be unified?

5.  How can relations between human function, bodily structure, and bodily process be unified?

6.  Why does functional engagement belong within the concept of human function, and what precisely does it mean?

7.  How can functional-capacity problems and functional-engagement problems be identified and represented within one framework?

8.  How can a shared semantics be established around a medicine-rehabilitation-exercise axis while allowing psychology and nutrition to enter when warranted?

9.  How does MUFO relate to existing classifications, ontologies, and professional systems?

10. What does MUFO unify, and what does it explicitly not unify?

## 2. Aim, Method, and Scope of Argument

### 2.1 Aim

The aim of this paper is to establish a stable, interpretable, and formalisable conceptual framework for unification in MUFO. The framework must satisfy four requirements:

1.  It must state what MUFO directly unifies.

2.  It must cover both internal requirements of life and external demands of real life.

3.  It must connect human function at the whole-person level to multiscale bodily structures, processes, and mechanisms.

4.  It must establish clear boundaries for later machine-readable ontology classes, relations, rules, instance data, and reasoning models.

### 2.2 Method

This paper is a work of conceptual analysis and ontology framework design. It is not a clinical trial, a systematic review, or an externally validated international standard. The methods are:

1.  Boundary analysis of the concepts of human function, unification, demand, functional engagement, structure, process, coordination, compensation, boundary, and state.

2.  Internal consistency review of existing MUFO definitions, relation rules, and working documents.

3.  Comparative analysis of the central objects, scales, relations, and purposes of publicly available systems including ICF, Whole Person Physiome, Gene Ontology, Human Phenotype Ontology, SNOMED CT, Basic Formal Ontology, Relation Ontology, and ICHI.

4.  Proposal of MUFO’s unification target, core relations, completeness rules, and minimum formal framework.

5.  Testing of conceptual adequacy against examples involving internal physiological demands and external real-world tasks.

Ontology is understood here as an explicit specification of the classes, relations, constraints, and semantics of a shared domain \[9\]. Future engineering work should draw on OBO Foundry principles concerning open use, clear scope, collaborative governance, shared relations, and version management \[10\]; use OWL 2 for classes, axioms, and formal semantics \[11\]; and use SHACL to validate RDF data structures and constraints \[12\]. These external methods support ontology engineering quality; they are not sources of MUFO’s core definition of human function.

### 2.3 Scope

This paper addresses the conceptual-ontological basis of MUFO. It does not claim to have completed the full catalogue of human functions, all demand-function relations, all cross-scale mappings, or all machine-readable axioms. It proposes the object boundaries, relation structure, and engineering rules that unification should follow.

The international comparison is based primarily on official materials accessible as of 27 July 2026. It is not a systematic global search. The paper therefore makes no exclusionary claim of global priority and does not assert that existing systems are unrelated to the subject. The systems reviewed cover, respectively, functioning and disability classification, multiscale physiological integration, gene and molecular function, phenotypic abnormality, clinical terminology, upper-level categories, general relations, and health interventions. The proposed organizing center of MUFO is distinct: **the functions of the whole person and their functional engagement under internal and external demands**.

## 3. Ontological Point of Departure: The Whole Person Precedes Disciplinary Division

Ontology first asks what exists in a domain and how those existents are related. MUFO begins not with professional catalogues but with the whole person.

In reality, the human body does not operate according to the boundaries of medicine, rehabilitation, exercise science, physiology, or informatics. When a person climbs stairs, sensation, balance, motor control, force production, joint motion, respiration, circulation, metabolism, and recovery participate together. After a person eats, sensation, mastication, swallowing, gastrointestinal motility, secretion, absorption, metabolism, and regulation occur in continuity. Following infection, injury, or fatigue, defense, protection, repair, and recovery change together in the same body.

Disciplinary categories are divisions in human knowledge and work; they are not divisions in the body’s existence. MUFO must therefore begin from the following commitment:

> **The wholeness of the person precedes disciplinary classification, and the coordination of human functions precedes professional division of labor.**

MUFO is consequently not a database into which existing disciplinary lists are placed side by side. It must re-establish objects and relations from the standpoint of the whole person, so that disease, structure, process, function, demand, engagement, state, and change can all refer to the same individual.

### 3.1 Reality, Epistemic, and Application Layers

To avoid conflating the body itself, judgments about the body, and actions intended to change the body, MUFO must distinguish at least three layers.

The **reality layer** describes what actually exists and occurs in the domain of human function: the person, functions, demands, structures, processes, engagement, coordination, compensation, boundaries, states, time, and change.

The **epistemic layer** describes how these facts are accessed and judged: questioning, observation, measurement, investigation, assessment, evidence, inference, and professional judgment.

The **application layer** describes actions intended to alter reality: medical treatment, rehabilitation, exercise, environmental modification, assistive technology, and other interventions.

The MUFO core ontology primarily describes the reality layer. The epistemic and application layers may be related to it, but an assessment instrument, treatment technique, or exercise plan must not be allowed to define human function itself.

## 4. Core Definition of “Unification” in MUFO

### 4.1 Definition

> **Unification in MUFO means using one coherent semantic system to describe human functions as they exist within an integrated whole person, together with their functional engagement.**

This is the central proposition of the paper.

### 4.2 Unification Is Not the Juxtaposition of Knowledge

Unification is not achieved by placing diseases, organs, movements, scales, assessments, and plans in one system. Even when heterogeneous knowledge is stored in one database, it remains juxtaposed rather than unified if its object boundaries differ, its relations are unclear, and it cannot return to human function in the same person.

Genuine unification must answer:

- Which person is being described?

- Which human function is being described?

- Which internal or external demand does that function serve?

- Through which bodily structures and processes is the function realized?

- Does it actually operate under the specified demand and conditions?

- How does it coordinate with other functions?

- What are its cost, boundaries, state, and change over time?

### 4.3 Unification Is Not the Design of the Body

MUFO does not prescribe an ideal operating procedure for the body. Human functions, internal and external demands, engagement, coordination, compensation, and change already occur in real persons. MUFO identifies these realities, gives them stable definitions, and establishes relations that both humans and machines can understand.

The essence of unification is therefore **the semantic re-articulation of reality**, not **the manufacture of reality**.

### 4.4 Unification Does Not Eliminate Professional Differences

Medicine, rehabilitation, exercise science, physiology, nursing, occupational therapy, speech and language therapy, and other fields retain different aims, methods, evidentiary standards, and scopes of practice. MUFO neither replaces those bodies of knowledge nor requires all professions to use identical methods.

MUFO requires that when different professions discuss the same individual, they can explicitly refer to the same human function, the same demand, and the same engagement fact. Methods may differ, but the human-function object to which they refer must be mutually identifiable and connectable.

### 4.5 Center and Scope of Unification

The center of MUFO’s unification is:

> **the functions of the whole person and their functional engagement.**

Demand, bodily structure, bodily process, coordination, compensation, boundaries, state, time, and change do not compete with human function for conceptual centrality. They are the conditions, mechanisms, and relations required to describe human function and functional engagement completely.

MUFO is therefore not a flat terminology list. It is a relation network organized around human function in the whole person.

## 5. First Domain of Unification: What Human Functions Exist?

### 5.1 Root Definition of Human Function

MUFO adopts the following root definition:

> **Human function is the body’s capacity to be appropriately engaged to meet internal and external demands.**

The term **human function** is not synonymous with the local biological function of a component - what a molecule, cell, tissue, organ, or process is supposed to do in biological or philosophical accounts of function. The center of judgment is the whole person: whether the body has the capacities required to meet the internal requirements of life and the external demands of real life.

The word **appropriately** conveys that functions operate in a manner suited to the current demand, the person’s conditions, and relevant safety boundaries. It does not establish a separate ontology of “normal” and “abnormal” engagement. Functional engagement itself still answers only whether the required functions actually operate in the real situation. Cost, boundaries, and the person’s overall condition are expressed through subsequent state semantics.

Functions at molecular, cellular, tissue, organ, and organ-system levels are realization mechanisms, enabling conditions, or limiting factors of human function at the whole-person level. MUFO must cover and connect these scales, but it must not collapse local biological functions and human function at the whole-person level into the same ontological category.

### 5.2 Human Function Cannot Be Reduced to Movement or Everyday Tasks

Human function includes both the capacities required for external behavior and real-world tasks and the capacities required for internal maintenance, regulation, development, defense, adaptation, repair, and recovery.

Human function therefore cannot be understood solely through walking, stair climbing, grasping, work, or exercise. Even during sleep, rest, or the absence of overt movement, respiration, circulation, metabolism, internal regulation, defense, repair, and recovery continue.

### 5.3 Current Domain Framework of Human Function

The following is a domain-level framework of human function, not a final set of formal ontology classes. Formal modeling must still distinguish, item by item, among functional capacities, bodily processes, states, manifestations, and demands. Ordinary language often uses the same word for different ontological categories, and this ambiguity must not be imported into the ontology.

Within the current scope of MUFO, human function must cover at least the following overlapping domains of capacity:

1.  capacities for sustaining life and regulating the internal environment;

2.  capacities for respiration, gas exchange, circulation, and transport of substances;

3.  capacities for mastication, swallowing, digestion, absorption, metabolism, and energy provision;

4.  capacities for excretion and for regulation of water, electrolytes, and acid-base balance;

5.  capacities for neural, endocrine, autonomic, immune, and biological-rhythm regulation;

6.  capacities for exteroception, interoception, perception, nociception, and pain regulation;

7.  capacities for consciousness, attention, memory, cognition, emotion, and behavioral regulation;

8.  capacities for postural control, balance control, motor control, force production, and mobility;

9.  capacities for grasping, fine manipulation, speech, language, communication, and expression;

10. capacities for protection, defense, hemostasis, immune response, and responses to threat and risk;

11. capacities for growth, development, reproduction, and adaptation across the life course;

12. capacities for learning and adaptation, tissue repair, recovery regulation, fatigue regulation, and sleep-wake regulation;

13. capacities for whole-body coordination and adaptation under complex environments, sustained load, and multiple simultaneous demands.

Self-care, learning tasks, work, family responsibilities, social participation, exercise, and competitive sport are external demands, activities, or tasks. They are not themselves classified as human functions. MUFO must instead specify which human functions are required to meet each of these demands. The domains above are not mutually exclusive compartments. One function may serve many demands, and one demand may depend on several functional domains at once.

### 5.4 Engineering Meaning of Completeness and Non-Omission

Any finite human-generated list may omit something. MUFO cannot claim completeness merely because it contains a list of functions. “Comprehensive” must be translated into continuously auditable rules:

1.  **Demand-coverage rule:** every identified internal or external demand must be linked to the human functions required to meet it.

2.  **Function-traceability rule:** every human function must specify which internal and external demands it serves.

3.  **Realization-link rule:** every human function must be linked to the bodily structures and bodily processes through which it is realized.

4.  **Cross-scale distinction rule:** human function at the whole-person level must be traceable downward to organ, tissue, cellular, and molecular mechanisms, while distinct scales remain ontologically distinct.

5.  **Condition-and-time rule:** functional relations must be able to represent load, environment, time, life stage, and person-specific conditions.

6.  **Semantic-gap rule:** a demand that cannot be classified under existing functions or linked by existing relations must be recorded as a gap for future completion, not treated as nonexistent because it is absent from the catalogue.

7.  **Version-governance rule:** functional catalogues and relations must be revisable, traceable, auditable, and historically versioned.

MUFO’s unification of “what human functions exist” is therefore not a once-and-for-all declaration of an immutable catalogue. It is an engineering mechanism for continuously detecting omissions, filling semantic gaps, and testing completeness.

## 6. Second Domain of Unification: Which Functions Are Required by Which Demands?

### 6.1 Internal and External Demands

A person continuously faces two interconnected classes of demand.

**Internal demands** include requirements for sustaining life, regulating the internal environment, growth and development, defense and protection, adaptation, repair, recovery, sleep-wake regulation, reproduction, and change across the life course.

**External demands** include self-care, maintenance of posture, mobility, manipulation, learning, work, communication, family responsibilities, social participation, exercise, competitive sport, response to the environment, and management of unexpected events.

Internal and external demands are not absolutely separate. Exercise is an external behavioral demand, but it simultaneously generates internal demands for energy provision, thermoregulation, circulation, respiration, and recovery. Infection begins as an internal demand for defense but also affects work, mobility, and social activity.

### 6.2 Demand-Function Relations Are Many-to-Many

Meeting a demand usually requires several human functions to operate together. The same function may also serve many different demands.

Stair climbing requires not only lower-limb force production but also sensation, balance control, motor control, joint mobility, respiration, circulation, energy provision, and recovery regulation. Eating requires not only digestion and absorption but also sensation, mastication, swallowing, secretory regulation, gastrointestinal propulsion, metabolism, and feedback regulation. Recovery after infection may involve immune-response capacity, defensive protection, thermoregulation, circulation, energy provision, tissue repair, sleep-wake regulation, and behavioral regulation.

MUFO must therefore represent:

- which functions are required to meet a given demand;

- what role each function plays in that demand;

- which functions are indispensable and which are supportive;

- how multiple functions coordinate;

- how required functions change when demand load, duration, speed, complexity, or environment changes.

### 6.3 Demand Is Not a Conscious Agent

The phrase “a demand uses functions” may be convenient, but a demand is not a conscious operator. A more rigorous formulation is:

> **Meeting a demand depends on the operation of the relevant human functions.**

This distinction establishes the boundary for the later account of functional engagement. Engagement is not an external agent issuing commands to the body. It concerns whether the functions required by internal and external demands actually operate when those demands arise.

## 7. Third Domain of Unification: Relations Among Function, Bodily Structure, and Bodily Process

Function, bodily structure, and bodily process are different ontological categories.

- **Function** describes what capacity the body has.

- **Bodily structure** provides the bodily basis on which a function exists and can be realized.

- **Bodily process** is the ongoing activity through which a function is realized in real time.

Their relation can be summarized as follows:

> **Meeting a demand requires human functions to operate; human functions depend on bodily structures and are realized through bodily processes.**

Circulatory function, for example, depends on the heart, blood vessels, blood, and associated neural and endocrine regulatory mechanisms, and is realized through myocardial contraction, blood flow, exchange, and regulatory processes. Walking is not the isolated function of a single muscle or joint; it is a whole-person capacity realized through the joint contribution of sensation, neural control, muscular force production, joint motion, balance, circulation, respiration, and metabolism, together with their underlying structures and processes.

This distinction prevents two common errors.

First, bodily structure must not be equated with human function. The presence of a structure or a normal imaging finding does not by itself demonstrate that the corresponding human function can operate in real life.

Second, a local biological process must not be equated with human function at the whole-person level. A normal local process does not guarantee that all functions required by a real demand can operate together in the whole person. Conversely, a local abnormality does not imply that every human function at the whole-person level is necessarily absent.

MUFO need not choose structure, process, or function as the sole explanation. It must state what each is and establish cross-scale, traceable realization relations among them.

## 8. Fourth Domain of Unification: Functional Engagement Within the Concept of Human Function

### 8.1 Position of Functional Engagement in MUFO

Functional engagement is not an ontological construction principle parallel to unification. Unification answers what MUFO returns to the same whole person for description. Functional engagement answers whether human functions actually operate when internal and external demands arise.

Functional engagement therefore belongs within the concept of human function. It is the key relation connecting **the capacities the body has** with **whether those capacities operate in real life**.

### 8.2 Philosophical Definition

> **Functional engagement is whether the human functions required by internal and external demands actually operate when those demands arise.**

This definition does not require complete prior observation of all microscopic processes in the body. It identifies the decisive real-world fact: a function must not merely exist as a capacity; it must actually operate when required.

### 8.3 Formal Definition

> **Functional engagement is the context-specific relation, for a particular person under specified conditions and at a specified time, between a specified internal or external demand and each human function required to meet it, according to whether that function actually operates through corresponding bodily structures and bodily processes.**

Function describes what capacities the body has. Engagement describes whether those capacities actually operate under a concrete demand.

For each specified demand-function pair, engagement holds when the specified required function actually operates and does not hold when it does not. These are two factual outcomes of one engagement concept, not additional concepts. When a demand requires several functions, each pair must be evaluated separately; operation of one function does not establish operation of the others. Whether operation is sufficient, stable, safe, sustainable, or costly is expressed through coordination, boundaries, and state.

“Actually operate” includes not only transition from lower to higher activity, but also continued maintenance, appropriate increase, inhibition, switching, regulation, and recovery. For continuously active functions such as respiration, circulation, and internal regulation, engagement does not imply that the function was previously absent. It asks whether the function can be maintained or appropriately adjusted to the current demand.

### 8.4 Who Engages the Body?

Strictly speaking, there is no commander outside the body that engages it. Internal and external demands are the real conditions under which engagement occurs, and the person is the integrated living whole in which functions actually operate.

Consciousness may participate in task selection, allocation of attention, recognition of risk, strategic adjustment, and decisions to stop. It does not issue item-by-item commands to heart rate, perfusion, gastrointestinal motility, immune response, thermoregulation, muscle recruitment, or tissue repair. A large proportion of engagement is realized through sensory feedback, neural control, endocrine regulation, autonomic regulation, immune response, metabolic regulation, and recovery processes.

The formal formulation is therefore:

> **No external agent commands the body into engagement; when internal or external demands arise, the required human functions operate through bodily structures and processes.**

“Life continually calls upon the body” may be retained as a philosophical communication phrase. It means that the requirements of life maintenance and real life continually place demands on the body. It does not imply that “life” is a volitional physiological controller.

### 8.5 What Is Engaged? The Object and Unified Semantics of Engagement

The object of engagement is human function.

Bodily structures and bodily processes are not second objects of engagement parallel to human function. They are the basis and mode through which human functions actually operate. Everyday language may speak of “engaging the muscles,” “engaging the joints,” or “engaging the cardiopulmonary system.” At MUFO’s highest relational level, the more precise statement is that an internal or external demand requires particular human functions to operate, and those functions are realized through muscles, bones, joints, the heart, lungs, nerves, blood vessels, endocrine and immune systems, and relevant bodily processes.

This distinction establishes a unified semantics for the question “what is engaged?”

1.  **An engagement item must be stated as a human function, not as a bodily structure or bodily process.** Force-production, balance-control, sensory, motor-control, circulatory-regulation, gas-exchange, metabolic energy-provision, digestive-absorptive, defense and protection, tissue-repair, recovery-regulation, cognitive, emotional-regulation, behavioral-regulation, communication, expression, and swallowing functions may be engagement items. The quadriceps, knee joint, heart, and lungs are structural or realization anchors. Specific occurrences of contraction, exchange, secretion, repair, and recovery are realization processes.

2.  **An engagement item is not a disease name.** Osteoarthritis, stroke, diabetes, or depressive disorder may explain background, mechanisms, risk, and limitations, but they are not the human functions being engaged.

3.  **An engagement item is not an action, task, or particular life process.** Stair climbing, eating, work, and running are external behaviors or tasks. A particular episode of sleep, tissue repair, or recovery is a life process. Sleep-wake regulation, tissue-repair function, and recovery-regulation function are the corresponding functions that may be engaged. MUFO must answer which human functions are required to meet these demands or complete these tasks.

4.  **An engagement item is not a technique.** Manual therapy, medication, an exercise movement, a psychological technique, or a nutritional plan belongs to the application layer, not to human function itself.

5.  **One demand usually requires several functions.** The function that is currently decisive should be distinguished from supportive functions, but a whole demand must not be reduced to one anatomical site or one capacity.

6.  **One function may serve several demands.** Circulation, energy provision, and regulation contribute to internal maintenance as well as mobility, work, and exercise. Sensory feedback contributes to posture and movement, visceral regulation, and risk recognition.

7.  **Engagement semantics must be downwardly traceable.** Every engaged function should be linkable to its structural basis, bodily processes, and evidence, without losing human function at the whole-person level as the upper-level object.

Different professions should therefore answer “what is engaged?” through the same basic formulation:

> **Under the current internal or external demand, which human functions are required to operate?**

Medicine may add disease and biological mechanism. Rehabilitation may add real-world activity and the path of restoration. Exercise may add load and adaptation. Psychology and nutrition may add psychological-behavioral conditions and material-energy conditions. The core answer to “what is engaged?” must nevertheless remain in the semantics of human function.

### 8.6 How Functional Engagement Occurs: From Demand to Actual Operation

Functional engagement is not the simple addition of components, nor is it the isolated activation of one structure. The engagement relation is realized through the actual operation of the required human functions, under a concrete internal or external demand, through their corresponding structures and processes.

MUFO may unfold this bodily course of realization into seven connected moments:

1.  **A demand arises or changes.** Internal demands may arise from requirements for oxygen, energy, temperature regulation, immune defense, tissue repair, or recovery. External demands may arise from mobility, eating, communication, work, learning, caregiving, exercise, or environmental change.

2.  **Changes and information associated with the demand become inputs to bodily regulation.** Internal demands may be expressed through changes in the internal environment, energy status, oxygenation, temperature, immune state, or tissue condition. External demands may become relevant to bodily regulation through sensory input, environmental information, task requirements, and conscious intention. This formulation does not posit an independent “recognizer,” nor does it equate engagement with consciousness issuing all commands.

3.  **Required functions become operative or are adjusted.** Relevant functions may begin to operate, remain active, increase or decrease their level of activity, or switch according to the demand. Continuously active functions are usually maintained and regulated rather than restarted from a state of complete inactivity.

4.  **Structures and processes realize the functions.** Functions are realized through organs, tissues, cells, molecules, and bodily processes. Structures provide the enabling basis; processes make the functions occur in real time.

5.  **Multiple functions operate in a coordinated organization.** Functions work together in relation to timing, intensity, spatial distribution, priority, resource allocation, and feedback. Engagement is not the sum of isolated local functions; it depends on a coordinated functional organization.

6.  **Operation is continually adjusted through feedback.** On the basis of external outcomes and internal changes - including pain, fatigue, blood pressure, blood glucose, oxygenation, balance, emotion, and other feedback - the body may amplify, reduce, redirect, or stop relevant functions in order to adapt to changing demands and avoid exceeding current boundaries.

7.  **The demand ends, changes, or gives way to recovery.** When a demand ends, relevant functions may decrease, stop, switch to another task, or the body may shift toward repair, regulation, and recovery. When a demand persists, engagement must be maintained and continuously adjusted.

These moments do not imply that every real situation follows one rigid temporal sequence, nor that all microscopic mechanisms must be visible before engagement can be judged. They provide a unified process semantics through which different professions can add the structures, processes, and evidence available to them while still describing the same engagement fact.

In practice, the bodily realization of engagement is often not directly or completely observable. MUFO therefore permits evidence to be built progressively from performance under a demand, bodily responses, objective measurements, post-demand changes, and time series. When evidence is limited, the only legitimate judgment is whether current evidence supports the statement that the required functions actually operated. If it does not, uncertainty must be retained; insufficient evidence must not be rewritten as proof that the engagement relation did not hold. As evidence increases, the engagement fact can be linked downward to specific structures, processes, coordination relations, and conditions. This prevents engagement from becoming an unusable black box while also preventing unsupported invention of internal bodily processes.

## 9. Fifth Domain of Unification: Coordination, Compensation, Boundaries, State, Time, and Change

Human functions and their engagement are neither isolated terms nor one-time static outcomes. MUFO can describe real human beings only by unifying coordination, compensation, boundaries, state, time, and change in the same person. **Cost**, although not named separately in the title of this section, runs through compensation, boundaries, and state. It is essential to understanding how human function is maintained, constrained, and changed.

### 9.1 Coordination: Human Function Is Not the Sum of Local Capacities

An internal or external demand usually requires several human functions to operate together. Coordination describes how those functions form a relation under a concrete demand, including:

- which functions enter first and which remain continuously active;

- which functions are dominant and which provide support;

- how information, matter, energy, and control pass among functions;

- how functions are aligned in time, intensity, space, and rhythm;

- how an existing organization changes when the demand changes;

- how change in one function affects others.

The actual operation of human function is therefore organized as a coordination network around a concrete internal or external demand, rather than as a set of isolated points. A normal local structure does not guarantee that whole-person coordination is present. A change in one local structure does not necessarily eliminate all human function at the whole-person level. MUFO must represent not merely the quantity of isolated local facts, but how those facts form the person’s current functional organization.

### 9.2 Compensation: Reorganization of Function Under Constraint

Compensation occurs when existing capacities, an existing pattern of coordination, or current environmental conditions are insufficient for a demand to be met smoothly, and the body changes its functional combination, redistributes contribution, or increases the contribution of other functions so that the relevant functions can continue to operate. External assistance, environmental modification, and task adjustment may help the person meet a demand, but they are support conditions or application-layer actions and must not be conflated with compensation within the body.

Compensation has a dual significance.

On one hand, it is an expression of adaptability. It may protect a constrained region, preserve essential activities of life, create time for recovery, and enable necessary action before conditions have been fully restored. On the other hand, compensation may increase pain, fatigue, tension, energy expenditure, load transfer, recovery time, or risk. When compensation persists, a pattern that initially maintained function temporarily may further alter functional boundaries and the person’s overall state.

Compensation must therefore not be treated simply as error, nor should every alternative strategy be immediately corrected. MUFO must record why compensation occurred, which functions or structures increased or decreased their contribution, what practical benefit compensation provided, and what costs and long-term changes it produced.

### 9.3 Boundaries: The Conditions and Extent Within Which Function Can Operate

The existence of a human function does not mean that it can operate without limit under any load, duration, or environment. A boundary describes the range within which, under specified internal or external demands, load, environment, time, and recovery conditions, a function can continue to operate, and the conditions beyond which it can no longer operate in the same way.

At least two interconnected aspects must be distinguished:

- **Safety boundary:** formed by disease, injury, red flags, contraindications, recovery stage, medication effects, and other risk conditions. It identifies demands, loads, or tasks that should not be initiated or continued without appropriate clinical judgment.

- **Functional boundary:** formed by current capacity, coordination, cost, duration, and recovery. It identifies how much the person can currently do, for how long, and under which conditions stability begins to be lost or operation can no longer continue.

A boundary is not a permanent number. The same person’s boundaries change with disease, recovery, training, sleep, nutrition, emotion, environment, and accumulated load. The boundary of the same function also differs with the speed, intensity, complexity, duration, and environmental context of the demand.

### 9.4 State: The Person’s Integrated Functional Reality Under Current Conditions

A state is not the name of one human function, and it is not a single symptom, disease, movement, or test result. It is an integrated expression of the person’s human functions, engagement, coordination, compensation, cost, boundaries, risk, and recovery under a specified demand, set of real conditions, and time.

The four states of **normal**, **compensatory**, **critical**, and **functional incapacity** do not exhaust the full complexity of the person. They are basic consolidations of the person’s present overall functional reality:

- **Normal state:** under the current demand, the required functions operate with relative stability, while cost and risk remain within an acceptable range.

- **Compensatory state:** the required functions still operate, but their organization has changed, additional cost has increased, or boundaries have narrowed.

- **Critical state:** the required functions operate only marginally, partially, or briefly, and a small increase in demand is likely to exceed the current boundary.

- **Functional incapacity state:** under the current demand and conditions, the required functions can no longer produce the integrated effect needed to meet the relevant requirements of life or everyday living.

The purpose of state semantics is to consolidate distributed functional facts into the person’s overall condition at a given time. State cannot be determined by one indicator and must not become a fixed label detached from demand and context.

### 9.5 Time: Functional Facts Must Be Situated in Continuous Processes

Human function has multiple timescales:

- whether a function operates at a particular moment;

- how long a demand persists;

- the sequence of functional operation at the beginning, continuation, change, termination, and recovery of a demand;

- recovery over the following hours, the next day, or longer;

- the stage of disease, injury, medical treatment, rehabilitation, or exercise adaptation;

- growth, development, adulthood, and aging across the life course;

- cumulative effects produced by long-term lifestyle and repeated engagement.

Without time, one performance, long-term capacity, and stage-related change in the same person are collapsed into a static fact. MUFO must allow every function, engagement fact, compensation, boundary, and state to refer to a specific time point, duration, and before-after relation.

### 9.6 Change: Human Function Can Develop, Decline, Be Rebuilt, and Expand

Human functions and their engagement change with disease, injury, treatment, rehabilitation, exercise, learning, adaptation, development, aging, environment, psychology, nutrition, sleep, medication, and social conditions.

Change is not limited to improvement or deterioration. It includes:

- increase, decrease, loss, or reappearance of a functional capacity;

- transition of a required function from not operating to operating under a specific demand, or the reverse;

- reorganization of coordination among several functions;

- emergence, reduction, stabilization, or transfer of compensation;

- expansion or contraction of safety and functional boundaries;

- transition among normal, compensatory, critical, and functional incapacity states;

- change in the primary limiting factor across stages of the same problem.

Unification must therefore include not only what a person has now, but why change occurs, when it occurs, what preceded and followed it, and which conditions promoted or obstructed it. Only then can MUFO support longitudinal recording, causal reasoning, reassessment, and a long-term model of human function.

## 10. Sixth Domain of Unification: The Same Person, Specified Conditions, and Continuous Time

If function, demand, structure, process, and engagement cannot consistently refer to the same person, unification remains no more than the juxtaposition of knowledge.

The capacity associated with the same type of human function may differ between persons and within the same person across time and conditions. The ability to walk 100 meters does not imply the ability to walk 5 kilometers. Stable walking on level ground does not imply stable walking on an uneven surface. Completion of one exercise session does not imply sustained recoverability over time.

Every functional fact in MUFO should therefore, in principle, answer:

- To whom does it belong?

- When does it occur?

- Which internal or external demand is present?

- Under which environment, load, and conditions?

- Which functions are required to operate?

- Which structures and processes realize them?

- Do the required functions actually operate?

- What are the associated cost, boundaries, and state?

- How is the fact related to previous and subsequent change?

The **same person** is not merely another data field in MUFO. The person is the enduring subject through whom all facts of human function are unified.

## 11. Unified Identification and Representation of Human-Function Facts

The purpose of unification is not merely to connect knowledge. It is to enable different professions, when facing the same person, to identify and represent the same kind of human-function fact. What is unified here is the factual object, the order of judgment, and the evidentiary boundary - not the professional explanation, which may legitimately differ.

### 11.1 Minimum Unit for Identifying a Human-Function Fact

A human-function fact cannot be represented by a function name alone. At minimum, it must specify:

- the person;

- the internal or external demand;

- the environment, load, stage, and time;

- the human functions required to operate;

- whether those functions actually operate;

- the manifestations, measurements, and temporal changes that constitute evidence;

- the related bodily structures, bodily processes, and influencing conditions;

- the current cost, boundaries, and state.

This set of information transforms human function from an abstract label into a situated real-world fact that can be observed, tested, communicated, and continuously updated.

### 11.2 Functional-Capacity Problem

> **A functional-capacity problem is insufficiency, impairment, or loss of the functional capacity required to meet an internal or external demand that is appropriate to the person and context.**

The qualification concerning an appropriate demand is essential. An ordinary person’s inability to meet an extreme requirement far beyond normal physiological capacity does not itself establish a functional-capacity problem. The judgment requires evidence that the capacity itself has declined, been lost, or been impaired.

### 11.3 Functional-Engagement Problem

> **A functional-engagement problem exists when evidence supports the presence of the relevant functional capacities, but those functions do not actually operate, or do not operate together with the other required functions, under a concrete internal or external demand.**

For example, an isolated test may support the presence of basic force-production capacity, yet during stair climbing that capacity may not operate together with balance, motor control, respiration, and circulation. In another case, routine investigations may reveal no clear abnormality sufficient to explain a persistent postprandial pattern. Ongoing manifestations and temporal change may nevertheless suggest that digestive, regulatory, or recovery functions are not operating adequately under that demand. Further verification is still required; a functional-engagement problem must not be inferred directly from negative test results.

Identifying an engagement problem is not equivalent to saying vaguely that “the body does not know how to use itself.” It requires continued localization along unified relations:

1.  Has the current demand been defined accurately?

2.  Have all required functions been identified?

3.  Is there evidence that the relevant functional capacities are present?

4.  Do those functions actually operate under the present environment, load, and time?

5.  Do the required functions form the necessary coordination?

6.  Do structure, process, feedback, resources, or external conditions obstruct operation?

7.  Does the problem occur only under certain conditions, or does it change with time and recovery?

Only when the engagement problem is localized to testable relations and conditions can subsequent solutions avoid degenerating into vague language of “activation,” “correction,” or technique chosen primarily by experience.

### 11.4 Functional-Capacity and Functional-Engagement Problems May Coexist

Insufficient functional capacity may directly prevent engagement. Functional capacity may also remain present but fail to operate under a concrete demand because of coordination, conditions, environment, load, time, feedback, or behavioral factors. Repeated inappropriate engagement over time may increase cost, narrow boundaries, and eventually alter functional capacity itself.

The same person may therefore have both a functional-capacity problem and a functional-engagement problem. When evidence is insufficient, no symptom, single failed movement, or negative investigation should be forced into one causal category. The most defensible procedure is to record the established human-function facts first and then specify which explanations remain to be tested.

### 11.5 Disease and Human-Function Facts

Disease may damage the biological basis of human function and may also affect engagement, but disease is not a necessary precondition for a human-function problem.

The absence of a clearly identified disease does not establish that human function is normal. If the required functions do not actually operate under appropriate internal or external demands, a human-function fact remains to be described and verified.

Conversely, a negative investigation does not prove that the problem is necessarily one of engagement. MUFO unifies objects, relations, and judgment boundaries. The specific cause still requires evidence and professional judgment.

### 11.6 Evidentiary Boundaries of Unified Representation

Representation of a human-function fact must distinguish:

- **observed facts:** symptoms, manifestations, task outcomes, measurements, and temporal changes;

- **supported relations:** which functions are affected and which structures or processes are related;

- **explanations still requiring verification:** why a function did not operate and where the primary limitation lies;

- **conclusions not licensed by current evidence:** a negative investigation must not be rewritten as absence of a problem, and a single abnormal event must not be rewritten as permanent loss of function.

A shared language does not conceal uncertainty. It enables different professions to agree on what is known, what remains unknown, and what should be tested next.

## 12. Shared Language: Common Semantics for the Medicine-Rehabilitation-Exercise Axis and the Supporting Roles of Psychology and Nutrition

Once MUFO has unified the object of human function, it must provide a language that different professions can use together. A shared language does not merge professional aims into one system and does not place all professions as equivalent stages. It enables professions to hand over and connect their work around the same person’s internal and external demands, human functions, engagement facts, evidence, boundaries, states, and change.

### 12.1 What the Shared Semantics Unify

The shared semantics must unify at least:

1.  **The same person:** all facts, judgments, and actions must refer to one specific person.

2.  **The current demand:** the internal requirement or external real-world task, including load, environment, time, and life stage.

3.  **The required functions:** the human functions that must operate to meet the current demand.

4.  **The engagement fact:** whether those functions actually operate under the current demand.

5.  **Facts and evidence:** the distinction among observed facts, supported relations, and explanations still requiring verification.

6.  **Realization relations:** the links from function to structures, processes, and coordination among several functions.

7.  **Integrated judgment:** compensation, cost, boundaries, state, risk, recovery, and temporal change.

8.  **Professional position:** the layer in which the current primary limiting factor lies, and which profession should next add evidence or take action.

The shared semantics can be compressed into one sentence:

> **What is the current internal or external demand; which human functions are required; do they actually operate; what is the evidence; what are the boundaries and state; and who should address what next within which professional scope?**

### 12.2 Core Axis of Medicine, Rehabilitation, and Exercise

This paper proposes that, within MUFO’s human-function framework, medicine, rehabilitation, and exercise can be interpreted through the following common axis. The statements describe the primary aim of each field; they are not an externally established professional standard and do not define exclusive scopes of practice.

> **Medicine primarily addresses functional capacities, their biological basis, and safety boundaries.**
>
> **Rehabilitation primarily addresses the return of functional capacities to real-world tasks - that is, the restoration of appropriate engagement.**
>
> **Exercise, through sustained, appropriately dosed, and progressive engagement, maintains and enhances human function and expands its engagement boundaries.**

The core logic is:

> **functional capacity - restoration of appropriate engagement - maintenance and enhancement of human function and expansion of engagement boundaries.**

“Restoration of appropriate engagement” retains the normative meaning of the root definition of human function: functions operate under demands that are appropriate to the person, current conditions, and safety boundaries. It does not turn engagement itself into the four-state taxonomy of normal, compensatory, critical, and functional incapacity states.

This division concerns primary aims, not absolute professional exclusion. Medicine may directly improve engagement; rehabilitation and exercise may rebuild or enhance particular functional capacities; and real practice necessarily overlaps. The common axis must nevertheless remain explicit. Without it, medicine, rehabilitation, and exercise risk being represented as parallel services with similar content and indistinct responsibilities.

In plain language:

> **Medicine helps the body have the capacities it needs. Rehabilitation helps the body use them again. Exercise keeps the body usable over time and enables it to do more.**

### 12.3 Primary Position of Medicine

Medicine commonly enters through disease, injury, physiological abnormality, and safety risk. It asks:

- Is there a disease, injury, or biological abnormality affecting functional capacity?

- What biological basis supports the current functional capacities, and which parts of that basis are impaired?

- Are there contraindications, red flags, acute risks, or clinical problems that require priority management?

- Which internal or external demands should not currently be entered, and which loads or tasks must not be exceeded?

- After medical management, which functional capacities and safety conditions does the person have?

Medicine is not concerned only with disease names. Diagnosis, investigation, medication, surgery, and other clinical actions ultimately need to explain how they affect functional capacities and safety boundaries.

### 12.4 Primary Position of Rehabilitation

Rehabilitation primarily addresses how functional capacities that remain, are recovering, or have been rebuilt can return to real life and real-world tasks. It asks:

- Why do capacities fail to operate appropriately in mobility, self-care, swallowing, communication, learning, work, and social participation?

- Which functions must operate together for the real-world task, and under which conditions or at which link is their connection failing?

- How can coordination among functions be restored and unnecessary compensation that obstructs real-world engagement be reduced?

- How can graded tasks, environmental conditions, assistive technology, and repeated practice return functions to real-world tasks?

- How can engagement progress from low-demand conditions to stable operation across a wider range of real conditions?

The center of rehabilitation is not simply increasing one test score or “improving function” in the abstract. It is restoring the appropriate engagement of functional capacities in real-world tasks.

### 12.5 Primary Position of Exercise

Through sustained, appropriately dosed, and progressive engagement, exercise maintains and enhances human function and expands its engagement boundaries. It asks:

- How can appropriate loading maintain existing function and prevent decline from prolonged underuse?

- How can force production, endurance, control, balance, energy provision, recovery, and other capacities be enhanced?

- How can existing functions operate stably at greater intensity, for longer duration, in more complex environments, and across more tasks?

- How can dose, frequency, progression, regression, and recovery planning expand engagement boundaries?

- How can the body remain usable over the long term and gain greater scope for life, exercise, and performance?

Exercise must proceed within clear safety boundaries. It must not evaluate only movement completion or training performance while ignoring cost, recovery, and long-term boundaries.

### 12.6 Conditional Incorporation of Psychology

Psychology is not positioned as a fixed stage parallel to the medicine-rehabilitation-exercise axis. It is incorporated when cognitive, emotional, behavioral, or psychosocial factors become the primary limiting factor or an important condition affecting function and engagement.

Common indications include:

- pain vigilance, catastrophizing, fear avoidance, or excessive protection affecting real-world engagement;

- stress, anxiety, depression, trauma response, or emotional dysregulation affecting sleep, recovery, behavior, and everyday tasks;

- problems of attention, understanding, motivation, learning, or execution preventing rehabilitation or exercise plans from entering real life;

- apparent “non-adherence” that in fact arises from task demands, feedback design, behavioral environment, or psychological resources rather than simple unwillingness;

- mental-health disorders or risks requiring assessment, treatment, or referral by appropriately qualified professionals.

Cognition, emotion, and behavior are themselves components of human function at the whole-person level. The question of when psychology should enter, however, must be determined by the current primary limiting factor and evidence. Unexplained problems must not be assigned to psychology by default.

### 12.7 Conditional Incorporation of Nutrition

Nutrition is likewise not a fixed stage parallel to the medicine-rehabilitation-exercise axis. It is incorporated when energy availability, material supply, body mass and composition, or nutritional status becomes an important condition of functional capacity, engagement, repair, recovery, or adaptation.

Common indications include:

- inadequate energy intake or chronic energy imbalance affecting work, exercise, or recovery;

- insufficient protein or other nutritional conditions affecting tissue repair, maintenance of muscle mass, or training adaptation;

- malnutrition, low body mass, excessive mass-related load, or change in body composition affecting functional capacity and real-world tasks;

- clinical nutritional risk caused by disease, surgery, swallowing difficulty, impaired digestion or absorption, or metabolic disturbance;

- stalled progression in training or rehabilitation that requires testing whether nutritional and energy conditions are limiting factors.

Nutrition is an important enabling condition of human function, but a single nutritional explanation must not replace an integrated account of disease, structure, process, engagement, psychology, environment, and load.

### 12.8 Principles of Professional Handover

Multiprofessional collaboration does not mean dividing one person equally among several professions. Priority is determined by the current primary limiting factor, evidence, and boundaries:

- when safety boundaries and biological basis are unclear, medical judgment has priority;

- when functional capacities must return to real-world tasks, rehabilitation has the primary position;

- when safety boundaries are clear and long-term maintenance, enhancement, and boundary expansion are required, exercise has the primary position;

- when psychological and behavioral factors become the primary limitation, psychology is incorporated;

- when energy, nutrition, repair, and recovery conditions become the primary limitation, nutrition is incorporated.

A shared handover language should specify:

1.  the human-function facts already established;

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

Gene Ontology (GO) organizes knowledge concerning molecular function, cellular component, and biological process associated with genes and gene products \[3\]. Human Phenotype Ontology (HPO) provides standardized terms for phenotypic abnormalities associated with human disease \[4\]. GO and HPO can respectively support links from MUFO to microscopic mechanisms and abnormal manifestations, but neither directly substitutes for human function at the whole-person level and its engagement.

### 14.4 SNOMED CT

SNOMED CT supports consistent clinical semantic representation through concepts, descriptions, relationships, logical definitions, and concept models \[5\]. MUFO may learn from its concept governance, relation constraints, version management, and machine-readable rules. MUFO’s domain center, however, remains human function at the whole-person level, internal and external demands, and functional engagement.

### 14.5 Basic Formal Ontology and Relation Ontology

Basic Formal Ontology (BFO) provides upper-level categories for scientific information integration \[6\], while Relation Ontology (RO) provides standardized relations across biomedical ontologies \[7\]. MUFO may reuse mature upper-level categories and general relations, but domain relations such as demand-human function-engagement must be defined within the human-function ontology and subjected to logical audit.

### 14.6 International Classification of Health Interventions

The International Classification of Health Interventions (ICHI) supports the recording, reporting, and analysis of health interventions and organizes interventions through the axes of Target, Action, and Means \[8\]. It demonstrates that intervention targets, actions, and means can be modeled independently. MUFO may relate to ICHI, but treatment, rehabilitation, and exercise methods must not be inserted into the core ontology of human function.

### 14.7 Comparative Conclusion

Existing systems provide, among other things, classifications of functioning and disability, whole-person physiological integration, molecular functions and biological processes, abnormal phenotypes, clinical terminology, upper ontological categories, standardized relations, and intervention classification.

MUFO’s proposed contribution is to organize this knowledge around the human functions of the same whole person and their functional engagement so that the following questions can be answered within one framework:

> What human functions does the body have? Which functions are required by which internal and external demands? Through which bodily structures and processes are those functions realized? Do those functions actually operate when required? How do these facts change in the same person across continuous time?

## 15. What MUFO Does Not Unify

Defining what MUFO does not unify is as important as defining what it does.

MUFO does not:

1.  merge distinct disciplines into one discipline;

2.  abolish the boundaries, authority, or scope of medicine, rehabilitation, exercise, or other professions;

3.  require all professions to use one assessment, treatment, or exercise method;

4.  place all diseases, structures, movements, scales, and plans into an unbounded vocabulary;

5.  replace all biological, clinical, and social knowledge with one theory;

6.  mistake a humanly designed account of how the body ought to operate for an account of how the body actually exists;

7.  conflate the epistemic and application layers with the reality of human function itself.

MUFO unifies the whole-person human-function objects and relations to which professional knowledge refers. It does not turn different professions into the same work.

## 16. Core Propositions

This paper advances the following propositions:

1.  A person exists as an integrated living whole, and human functions are not divided by disciplinary classification.

2.  Unification in MUFO means using one coherent semantic system to describe human functions as they exist within an integrated whole person, together with their functional engagement.

3.  Human function is the body’s capacity to be appropriately engaged to meet internal and external demands.

4.  Human function addresses both internal requirements of life and external demands of real life.

5.  Local biological functions at different scales are realization mechanisms, enabling conditions, or limiting factors of human function at the whole-person level; they are not identical to human function at that level.

6.  Meeting one demand usually requires several human functions to operate together, and the same function may serve several demands.

7.  Human functions depend on bodily structures and are realized through bodily processes.

8.  Functional engagement belongs within the concept of human function and is not an ontological construction principle parallel to unification.

9.  Functional engagement is whether the human functions required by internal and external demands actually operate when those demands arise.

10. The object of engagement is human function; bodily structures and bodily processes are its basis and mode of realization.

11. No external agent commands the body into engagement; internal and external demands are the real conditions under which engagement occurs.

12. The realization of engagement may include regulatory inputs arising from demand-related changes and information, the operation or adjustment of required functions, realization through structures and processes, coordination among several functions, feedback-based adjustment, and termination, switching, or recovery.

13. Coordination, compensation, boundaries, state, time, and change are required to describe human functions and their engagement completely.

14. A functional-capacity problem concerns insufficiency, impairment, or loss of the capacity itself.

15. A functional-engagement problem concerns a capacity that is supported by evidence as present but does not actually operate under a concrete demand.

16. Functional-capacity and functional-engagement problems may coexist, and they must not be forcibly separated when evidence is insufficient.

17. The same person, specified conditions, and continuous time are necessary for genuine unification of human-function facts.

18. Within MUFO, functional capacity - restoration of appropriate engagement - maintenance and enhancement of human function and expansion of engagement boundaries can serve as a common interpretive axis for medicine, rehabilitation, and exercise; psychology and nutrition are incorporated when indicated by the current primary limiting factor, evidence, and professional scope.

19. Assessment, diagnosis, and solutions may be linked to MUFO but do not belong to the core ontology of human function itself.

## 17. Final Meaning of “Unification”

MUFO does not unify disciplines, all professional techniques, or every way of working.

It unifies the human functions of the same whole person and their functional engagement by:

1.  unifying what human functions exist and establishing completeness rules that continuously expose omissions;

2.  unifying which functions are required by different internal and external demands;

3.  unifying the realization relations between human function, bodily structure, and bodily process;

4.  unifying the engagement relation through which human functions do or do not actually operate in real situations;

5.  unifying coordination, compensation, boundaries, state, time, and change in functions and engagement;

6.  unifying these facts in the same person, under specified conditions, across continuous time;

7.  unifying the human-function objects and framing used in cross-professional judgment, interpreting medicine, rehabilitation, and exercise through the proposed axis of functional capacity - restoration of appropriate engagement - maintenance and enhancement of human function and expansion of engagement boundaries, while incorporating psychology and nutrition when the current primary limitation and evidence warrant their involvement.

The complete logic can be stated as follows:

> A person has functional capacities through which the body meets the requirements of life and real living. When internal or external demands arise, the corresponding functions are required to operate. Human functions depend on bodily structures and are realized through bodily processes; several functions may coordinate within the same person. Function describes what capacities the body has. Functional engagement describes whether those capacities actually operate in real situations. Coordination, compensation, boundaries, state, and change further explain how functions operate, what costs arise, how long operation can be maintained, and how function changes over time. MUFO reorganizes these realities, which already belong to the same person, through one coherent semantic system.

The final definition therefore remains:

> **Unification in MUFO means using one coherent semantic system to describe human functions as they exist within an integrated whole person, together with their functional engagement.**

## 18. Limitations and Future Work

This paper presents an English conceptual account and ontological framework for unification in MUFO. It has several limitations:

1.  The current domain framework of human function has not undergone systematic multidisciplinary expert review and cannot be claimed to exhaust all human functions.

2.  Demand-function relations require item-by-item validation across large sets of internal demands, everyday tasks, and clinical situations.

3.  The distinction between functional-capacity and functional-engagement problems requires evidentiary rules and case-consistency studies.

4.  The unified semantics, process relations, and evidentiary rules of engagement must be translated into computable classes, relations, axioms, and instance constraints.

5.  Formal representation of coordination, compensation, boundaries, state, and temporal change requires further development.

6.  The proposed medicine-rehabilitation-exercise axis and the conditional incorporation of psychology and nutrition require cross-professional review and case validation.

7.  Formal mappings to ICF, Whole Person Physiome, GO, HPO, SNOMED CT, BFO, RO, and ICHI have not been completed in this paper.

8.  The international comparison is a scoped conceptual comparison, not a systematic review.

9.  Whether MUFO can become a general standard will depend on open governance, machine-readable implementation, cross-professional validation, and long-term testing against data.

Future work should include:

- publication of versioned catalogues of human functions and internal and external demands;

- demand-function, function-structure, function-process, and engagement relation matrices;

- formal rules for engagement semantics, the bodily processes through which engagement is realized, coordination, compensation, boundaries, state, and temporal change;

- publication of a machine-readable ontology, relation constraints, and example data;

- a public registry and governance process for semantic gaps;

- completeness testing in representative domains including digestion, sleep, immunity, mobility, work, and exercise;

- inter-rater semantic annotation, logical consistency, and reasoning tests for the proposed medicine-rehabilitation-exercise axis and conditional incorporation of psychology and nutrition;

- sustained public revision of both Chinese and English conceptual versions.

## 19. Conclusion

A person exists as an integrated whole, yet knowledge of the body has long been organized separately around disease, structure, physiological process, functioning classifications, activity, task, and professional method. Fragmented knowledge does not imply a fragmented person, and professional differences should not deprive human function in the same person of a common representation.

Unification in MUFO is not the mechanical combination of heterogeneous knowledge. It re-establishes a common center: the human functions of the same whole person and their functional engagement. Around this center, MUFO must unify what human functions exist, which functions are required by internal and external demands, the structures and processes through which functions are realized, whether functions actually operate under real demands, and how coordination, compensation, boundaries, state, and change unfold in the same person across continuous time.

Functional engagement belongs within the concept of human function. Function describes what capacities the body has; engagement describes whether those capacities actually operate in real situations. The object of engagement is human function, while bodily structures and processes provide the basis and mode of realization. Within the MUFO framework, medicine can primarily address functional capacities, their biological basis, and safety boundaries; rehabilitation can primarily address the return of functional capacities to real-world tasks and the restoration of appropriate engagement; and exercise can maintain and enhance human function and expand engagement boundaries through sustained, appropriately dosed, and progressive engagement. Psychology and nutrition enter when indicated by the current primary limiting factor and evidence.

The meaning of unification in MUFO can therefore be reduced to one proposition:

> **Use one coherent semantic system to describe human functions as they exist within an integrated whole person, together with their functional engagement.**

## 20. Declarations

### 20.1 Nature of the Paper

This paper is a conceptual ontology framework and research proposal. It has not undergone peer review and does not constitute a clinical guideline, diagnostic conclusion, treatment recommendation, or internationally accepted standard.

### 20.2 Competing Interests

Lei Che is the founder of MoveTips Technology (Beijing) Co., Ltd. MUFO and related research, software, products, and services may be associated with the company’s research, development, and commercial activities.

### 20.3 Funding

This work was completed internally at MoveTips Technology (Beijing) Co., Ltd. and received no external project-specific funding.

### 20.4 Data and Code Availability

This paper reports no newly generated clinical data, experimental data, or personal health data. Machine-readable ontology resources, relation rules, constraint files, and example data are planned for versioned release through a corresponding GitHub repository. Until those resources are publicly released, this paper does not claim that a complete reproducible machine implementation is available.

### 20.5 Ethics Statement

This work is conceptual ontology research and involved no human participants, animal experiments, or personal health data. Ethics approval was therefore not applicable.

### 20.6 License

This work is made available under the Creative Commons Attribution 4.0 International License (CC BY 4.0). License information should remain consistent across Zenodo and GitHub releases.

## References

1.  World Health Organization. *International Classification of Functioning, Disability and Health: ICF.* Geneva: World Health Organization; 2001. https://www.who.int/standards/classifications/international-classification-of-functioning-disability-and-health. Accessed 27 July 2026.

2.  Stanford Medicine, Snyder Lab. *Whole Person Physiome Program.* https://med.stanford.edu/snyderlab/news/whole-person-physiome-program.html. Accessed 27 July 2026.

3.  Gene Ontology Consortium. The Gene Ontology knowledgebase in 2023. *Genetics.* 2023;224(1):iyad031. https://doi.org/10.1093/genetics/iyad031.

4.  Gargano MA, Matentzoglu N, Coleman B, et al. The Human Phenotype Ontology in 2024: phenotypes around the world. *Nucleic Acids Research.* 2024;52(D1):D1333-D1346. https://doi.org/10.1093/nar/gkad1005.

5.  SNOMED International. *What is SNOMED CT?* https://www.snomed.org/what-is-snomed-ct. Accessed 27 July 2026.

6.  International Organization for Standardization. *ISO/IEC 21838-2:2021 Information technology - Top-level ontologies (TLO) - Part 2: Basic Formal Ontology (BFO).* Geneva: ISO; 2021. https://www.iso.org/standard/74572.html.

7.  OBO Relation Ontology. *OBO Relation Ontology: Documentation and User Guide.* https://oborel.github.io/. Accessed 27 July 2026.

8.  World Health Organization. *International Classification of Health Interventions (ICHI).* https://www.who.int/standards/classifications/international-classification-of-health-interventions. Accessed 27 July 2026.

9.  Gruber TR. A translation approach to portable ontology specifications. *Knowledge Acquisition.* 1993;5(2):199-220. https://doi.org/10.1006/knac.1993.1008.

10. Smith B, Ashburner M, Rosse C, et al. The OBO Foundry: coordinated evolution of ontologies to support biomedical data integration. *Nature Biotechnology.* 2007;25(11):1251-1255. https://doi.org/10.1038/nbt1346.

11. W3C OWL Working Group. *OWL 2 Web Ontology Language Document Overview (Second Edition).* W3C Recommendation; 11 December 2012. https://www.w3.org/TR/2012/REC-owl2-overview-20121211/.

12. W3C RDF Data Shapes Working Group. *Shapes Constraint Language (SHACL).* W3C Recommendation; 20 July 2017. https://www.w3.org/TR/shacl/.
