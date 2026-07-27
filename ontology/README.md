# Public Machine-Readable Ontology Status

## Current status

This public repository currently provides the conceptual framework, governed architecture, version history, citation records, explanatory documents, and non-normative examples for MUFO.

A reviewed, authoritative machine-readable public release of MUFO in OWL, Turtle, RDF, JSON-LD, or SHACL has **not yet been published**. This is deliberate: an unreviewed formal file should not be mistaken for the production ontology, the frozen relation topology, or a validated interoperability release.

本公共仓库目前提供 MUFO 的概念框架、受治理架构、版本历史、引用信息、说明文档和非规范性示例。

MUFO 尚未发布经过审查、可作为权威版本使用的 OWL、Turtle、RDF、JSON-LD 或 SHACL 机器可读公共本体。这是有意的边界控制：未经审查的形式文件不应被误认为生产本体、已冻结关系拓扑或已经验证的互操作版本。

## Public-release requirements

A future public ontology subset should include, at minimum:

1. a stable public namespace and identifier policy;
2. an explicit release scope and version identity;
3. reviewed class and relation definitions;
4. domain, range, direction, inverse-query, and lifecycle rules where applicable;
5. competency questions and expected answers;
6. mappings to external standards with provenance and scope boundaries;
7. machine-readable constraints, such as SHACL, where appropriate;
8. example instances clearly marked as normative or non-normative;
9. consistency, reasoning, and validation reports;
10. a file-specific license and citation statement.

未来的公共本体子集至少应包含：

1. 稳定的公共命名空间和标识符政策；
2. 明确的发布范围和版本身份；
3. 经过审查的类别与关系定义；
4. 适用情况下的 domain、range、方向、反向查询和生命周期规则；
5. 能力问题及预期答案；
6. 带有来源和范围边界的外部标准映射；
7. 适当的机器可读约束，例如 SHACL；
8. 明确标注规范性或非规范性的实例；
9. 一致性、推理和验证报告；
10. 文件级许可和引用说明。

## What can be inspected now

- [MUFO Definition 2.1](https://doi.org/10.5281/zenodo.21399269)
- [Unification in the MoveTips Unified Functional Ontology](../papers/unification/README.md)
- [Detailed Chinese framework definition](../MUFO_DEFINITION_ZH.md)
- [Minimal task-centered example](../examples/minimal-task-centered-case.json)
- [Version archive](../versions/README.md)
- [Rights and reuse](../RIGHTS_AND_REUSE.md)

## Contribution and review

Proposals concerning namespace design, competency questions, formal class and relation boundaries, mappings, OWL axioms, SHACL constraints, and validation methods are welcome. See [COLLABORATION.md](../COLLABORATION.md).

Until a versioned public ontology release is explicitly published here, no file in this directory should be treated as a complete or authoritative representation of the production MUFO ontology.
