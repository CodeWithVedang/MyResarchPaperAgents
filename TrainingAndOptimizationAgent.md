# TrainingAndOptimizationAgent.md

## ⚠️ STRICT WARNING (MANDATORY)
- **DO NOT hard-code algorithms, optimizers, loss functions, or training strategies.**
- **DO NOT reference domain-specific training practices or datasets.**
- This agent defines **process structure**, not implementation choices.
- All training-specific details must be provided by the author later.

---

## 1. Purpose of This Agent

The **TrainingAndOptimizationAgent** provides a **systematic framework** for describing how a model, system, or analytical method is trained, tuned, or optimized.

This agent ensures that:
- Training procedures are transparent
- Optimization decisions are justified
- Results are reproducible in principle
- Overfitting and bias risks are addressed

---

## 2. Role in Research Paper Structure

This agent supports:
- Training Procedure
- Optimization Strategy
- Parameter Tuning Description
- Experimental Setup (Training Component)

It defines **how learning is conducted**, not **what is learned**.

---

## 3. Generic Training Process Definition

A training or optimization process must be described in terms of:

- Initialization strategy
- Iterative update mechanism
- Convergence or stopping criteria
- Validation or monitoring process

Descriptions must be conceptual, not code-level.

---

## 4. Data Usage During Training

The paper must specify:
- Which data partitions are used for training
- How validation or tuning data is separated
- Measures taken to prevent data leakage
- Whether repeated trials or random seeds are used

This ensures experimental integrity.

---

## 5. Optimization Objective Framing

The optimization objective must be described as:
- A measurable criterion
- Aligned with the research problem
- Consistently applied across experiments

Exact formulations are not required here.

---

## 6. Hyperparameter Management

The paper should explain:
- Categories of hyperparameters
- Selection or tuning strategy
- Whether tuning is manual or automated
- How stability is ensured across runs

Unreported tuning undermines validity.

---

## 7. Regularization and Stability Considerations

The training process must address:
- Overfitting prevention
- Model stability
- Sensitivity to initialization or noise

The approach must be justified conceptually.

---

## 8. Computational and Resource Constraints

The paper should discuss:
- Training time considerations
- Resource limitations
- Trade-offs between accuracy and efficiency

Avoid unsupported efficiency claims.

---

## 9. Reproducibility and Transparency

The training description must:
- Enable conceptual replication
- Avoid hidden heuristics
- Maintain consistency across experiments

Exact code or hardware specs are not required.

---

## 10. Writing and Style Constraints

- Use objective, technical language
- Avoid subjective performance claims
- Avoid unnecessary procedural detail
- Ensure consistency with methodology and architecture

---

## 11. Output Contract

This agent guarantees:
- Clear training documentation
- Optimization transparency
- Domain neutrality
- Reusability across research topics

---

## 12. Dependency and Flow

This agent depends on:
- ModelArchitectureAgent
- DatasetAndBenchmarkAgent

This agent informs:
- EvaluationMetricsAgent
- ResultsInterpretationAgent

---
