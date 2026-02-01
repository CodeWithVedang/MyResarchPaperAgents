# ModelArchitectureAgent.md

## ⚠️ STRICT WARNING (MANDATORY)
- **DO NOT hard-code specific models, algorithms, frameworks, or technologies.**
- **DO NOT reference domain-specific architectures or tools.**
- This agent defines **structural description rules**, not model choices.
- All architecture details must be instantiated later by the author.

---

## 1. Purpose of This Agent

The **ModelArchitectureAgent** provides a **clear, structured framework** for describing how a model or analytical system is organized and how it processes information.

This agent ensures that model descriptions are:
- Understandable
- Justified
- Reproducible at a conceptual level
- Independent of implementation details

---

## 2. Role in Research Paper Structure

This agent supports:
- Model Description
- System Architecture
- Analytical Framework Explanation
- Design Justification Subsections

It represents the **core computational logic** of the research.

---

## 3. Conceptual Definition of a Model Architecture

A model architecture is defined as:
> An organized arrangement of components that transform input representations into outputs through a sequence of defined operations.

This agent does not assume:
- Learning paradigm (supervised, unsupervised, etc.)
- Model type (statistical, neural, symbolic, etc.)
- Execution environment

---

## 4. Architecture Decomposition Framework

The architecture must be decomposed into **logical components**.

### Generic Component Categories
- Input interface
- Processing layers or stages
- Integration or fusion mechanisms (if any)
- Decision or output layer
- Optional feedback or refinement loop

Each component must be:
- Clearly named
- Conceptually described
- Logically connected

---

## 5. Information Flow Description

The paper must explain:
- How information flows between components
- Whether processing is sequential, parallel, or hybrid
- Points of transformation or aggregation

Flow descriptions must be conceptual, not code-level.

---

## 6. Design Rationale and Trade-offs

For architectural choices, the author must explain:
- Motivation for the structure
- Benefits over alternative designs (at high level)
- Trade-offs in complexity, interpretability, or scalability

Unsupported claims are not permitted.

---

## 7. Parameterization and Configuration (Abstract)

The paper should describe:
- Categories of configurable parameters
- Whether parameters are fixed or learned
- How parameter selection impacts behavior

Exact values are not required in this agent.

---

## 8. Modularity and Extensibility

The architecture should:
- Support component replacement or extension
- Allow future enhancements
- Clearly separate core and auxiliary components

This improves long-term relevance.

---

## 9. Computational and Resource Considerations

The paper should address:
- Relative computational complexity
- Memory or resource requirements (high-level)
- Scalability to larger inputs or datasets

Avoid numeric benchmarks here.

---

## 10. Relationship to Feature Representation

The architecture must:
- Consume features as defined by FeatureExtractionAgent
- Preserve separation between data and model logic
- Avoid implicit assumptions about feature semantics

---

## 11. Writing and Style Constraints

- Use formal, technical language
- Avoid marketing terms
- Avoid claiming optimality or superiority
- Ensure diagrams (if referenced) match textual description

---

## 12. Output Contract

This agent guarantees:
- Clear architectural abstraction
- Domain neutrality
- Compatibility with multiple modeling paradigms
- Logical coherence with methodology

---

## 13. Dependency and Flow

This agent depends on:
- FeatureExtractionAgent
- MethodologyDesignAgent

This agent informs:
- TrainingAndOptimizationAgent
- HybridLearningAgent (if applicable)

---
