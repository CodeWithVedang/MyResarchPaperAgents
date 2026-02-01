# EvaluationMetricsAgent.md

## ⚠️ STRICT WARNING (MANDATORY)
- **DO NOT hard-code specific metrics, benchmarks, thresholds, or domain assumptions.**
- **DO NOT introduce external standards or prior knowledge.**
- This agent defines **evaluation structure and principles**, not metric selection.
- All metric choices must be instantiated later by the author.

---

## 1. Purpose of This Agent

The **EvaluationMetricsAgent** provides a **structured framework** for defining, applying, and reporting evaluation criteria in a research paper.

This agent ensures that evaluation is:
- Objective
- Comparable
- Transparent
- Aligned with the research problem

---

## 2. Role in Research Paper Structure

This agent supports:
- Evaluation Methodology
- Performance Metrics Description
- Experimental Results Setup
- Validation Strategy

It defines **how success is measured**, not **what success is**.

---

## 3. Principles of Valid Evaluation

All evaluation metrics must satisfy:
- Relevance to the research objective
- Interpretability
- Consistency across experiments
- Reproducibility

Metrics must be justified, not assumed.

---

## 4. Metric Selection Framework (Generic)

Metrics may be selected based on:
- Task objectives
- Data characteristics
- Error sensitivity
- Practical relevance

Multiple metrics should be used when appropriate to avoid biased conclusions.

---

## 5. Evaluation Protocol Definition

The paper must clearly define:
- Evaluation procedure
- Data partitions used for evaluation
- Number of runs or trials
- Averaging or aggregation strategy

The protocol must be consistent across all comparisons.

---

## 6. Baseline and Reference Comparison Rules

When comparing methods:
- Baselines must be clearly defined
- Comparisons must use identical conditions
- Improvements must be contextualized

Unfair or selective comparison is not acceptable.

---

## 7. Statistical Reliability and Variability

The evaluation should address:
- Variability across runs
- Stability of results
- Sensitivity to parameter changes

Statistical claims must be supported conceptually.

---

## 8. Error Analysis and Failure Cases

Beyond aggregate metrics, the paper should:
- Analyze common failure modes
- Discuss limitations revealed by evaluation
- Avoid hiding poor performance

This improves scientific credibility.

---

## 9. Result Presentation Guidelines

Results should be:
- Clearly labeled
- Logically ordered
- Accompanied by explanatory text
- Free from misleading visual emphasis

Tables and figures must match textual interpretation.

---

## 10. Writing and Style Constraints

- Avoid overstating metric improvements
- Avoid cherry-picking results
- Maintain neutral academic tone
- Ensure alignment with methodology

---

## 11. Output Contract

This agent guarantees:
- Structured evaluation design
- Transparent performance reporting
- Domain neutrality
- Compatibility with diverse research fields

---

## 12. Dependency and Flow

This agent depends on:
- TrainingAndOptimizationAgent
- DatasetAndBenchmarkAgent

This agent informs:
- ResultsInterpretationAgent
- ComparativeAnalysisAgent

---
