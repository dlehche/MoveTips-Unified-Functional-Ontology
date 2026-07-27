# UOHF V1.0 — Historical English Version

[English](README.md) | [中文](README.zh-CN.md) | [Version archive](../README.md)

> **Historical version notice:** UOHF V1.0 remains part of the formal development history. It is not the current authoritative root definition. For the current framework, see [UOHF Definition 2.1](../../README.md).

## Publication metadata

**Current project title:** *UOHF V1.0: An Auditable Human-Function Inference and Safety-Constrained Decision-Support Framework*  
**Author:** Lei Che, with the MoveTips Research & Engineering Team  
**Affiliation:** MoveTips Technology (Beijing) Co., Ltd.  
**Publication date:** February 6, 2026  
**Version:** 1.0  
**Canonical publication:** [Zenodo record 20711332](https://zenodo.org/records/20711332)  
**DOI:** [10.5281/zenodo.20711332](https://doi.org/10.5281/zenodo.20711332)  
**Copyright:** © 2026 Lei Che and MoveTips Technology (Beijing) Co., Ltd.

## Historical purpose

UOHF V1.0 presented the initial ontology-driven and governance-oriented framework for auditable human-function inference across rehabilitation and movement-training contexts. It addressed functional problems that may exist before or outside a clear disease diagnosis while still producing pain, compensation, reduced performance, unstable tolerance, and elevated risk.

V1.0 emphasized four engineering commitments:

1. a minimal sufficient factorization of human function into eight decision factors;
2. strict separation between observable dimensions and inferred attributions;
3. a hard safety-constraint layer that gates downstream action;
4. deterministic, provenance-bearing reasoning artifacts that can be replayed and audited.

## Historical operational definition

V1.0 used the following operational definition:

> **The capacity to complete a task stably and efficiently under bounded physiological, biomechanical, and cognitive cost within explicit safety constraints.**

This wording belongs to the V1.0 operational framework. It is preserved for historical accuracy. The current UOHF Definition 2.1 uses the authoritative root definition:

> **Human function is the body's capacity to be appropriately engaged to meet internal and external demands.**

## Eight decision factors

V1.0 factorized human function as:

> **Human Function = Task × Movement × Strategy × Capacity × System × Structure × Psychology × Behavior**

The eight-factor set was frozen in V1.0 as a practical decision-complete decomposition intended to support observability, longitudinal updating, intervention planning, and auditable inference.

## Task–Capacity Matching

Task–Capacity Matching (TCM) formed the V1.0 decision spine:

- task conditions define demand;
- the person provides capacity supply;
- the difference between capacity and demand defines functional margin;
- negative margin indicates deficit;
- a small positive margin indicates borderline adequacy;
- a larger positive margin indicates usable reserve.

The basic expression was:

> **M = C − D**

where `C` is the capacity-supply vector, `D` is the task-demand vector, and `M` is the margin vector.

## Minimal Viable State Space

V1.0 introduced an early **MVSS-12** operationalization with twelve normalized dimensions:

1. recovery reserve;
2. sensitization proxy;
3. autonomic-load proxy;
4. motor-control precision;
5. proprioception and sensory quality;
6. protective-strategy intensity;
7. mobility window;
8. stiffness regulation;
9. load-distribution efficiency;
10. task capacity;
11. coordination and rhythm;
12. compensation dependence.

Evidence was mapped into bounded scores through versioned rules and parameters so that the resulting reasoning artifact could be reproduced.

## Observation and inference boundary

V1.0 distinguished:

- **Dimensions:** observable, recordable, and scoreable facts;
- **Attributions:** inferred explanations or hypotheses generated from dimension patterns under task context.

Attributions were not to be stored as factual observations. They were to remain linked to supporting evidence, confidence bounds, model version, and provenance.

## Safety and reasoning artifacts

Safety constraints were treated as hard gates. A reasoning artifact was expected to preserve:

- ontology and parameter versions;
- input snapshots;
- applied constraints and triggered gates;
- calculated margins and risk estimates;
- candidate attributions and evidence links;
- prioritized decision levers;
- allowed action templates;
- provenance required for deterministic replay.

## Relationship to later versions

- **V1.0** established the initial deterministic, task–capacity, safety-gated, and auditable implementation direction.
- **Definition 2.0** moved from a factor-and-score-centered paper toward a broader task-centered ontology architecture, Functional Engagement, continuous write-back, and the UOHF–IHFM–HFWM separation.
- **Definition 2.1** became the current framework definition, restoring the full internal-and-external-demand scope and clarifying the multiscale ontology and world-model trajectory.

V1.0 remains historically important and may still be useful for bounded task–capacity applications. It should not be treated as the complete present-day UOHF ontology architecture.

## Citation

> Che, Lei, and the MoveTips Research & Engineering Team. *UOHF V1.0: An Auditable Human-Function Inference and Safety-Constrained Decision-Support Framework*. Zenodo, 2026. DOI: [10.5281/zenodo.20711332](https://doi.org/10.5281/zenodo.20711332).

## Copyright and reuse

**Copyright © 2026 Lei Che and MoveTips Technology (Beijing) Co., Ltd.**

The canonical Zenodo record governs version-specific access, license, attribution, and reuse terms. Any quotation, translation, implementation, or derivative work should preserve the version number, DOI, authorship, provenance, and the safety and professional-scope limitations of the original publication.
