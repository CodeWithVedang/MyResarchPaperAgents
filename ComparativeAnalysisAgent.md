# ComparativeAnalysisAgent.md

## ⚠️ STRICT WARNING (MANDATORY)
- **DO NOT hard-code specific methods, models, datasets, or performance claims.**
- **DO NOT introduce domain-specific benchmarks or assumptions.**
- This agent defines **comparison structure and fairness rules**, not comparison content.
- All comparative data must come from the paper’s own experiments or cited literature.

---

## 1. Purpose of This Agent

The **ComparativeAnalysisAgent** provides a **systematic and fair framework** for comparing multiple approaches, configurations, or baselines within a research study.

This agent ensures that comparisons are:
- Scientifically valid
- Methodologically consistent
- Free from selective bias
- Clearly interpretable

---

## 2. Role in Research Paper Structure

This agent supports:
- Comparative Results section
- Baseline Comparison
- Ablation or Variant Analysis
- Performance Trade-off Discussion

It enables **evidence-driven differentiation** between approaches.

---

## 3. Comparison Eligibility Rules

Only approaches that satisfy all of the following may be compared:
- Evaluated under identical experimental conditions
- Use the same datasets and partitions
- Are measured using the same metrics
- Follow consistent preprocessing and evaluation protocols

Invalid comparisons must be excluded.

---

## 4. Comparison Dimension Framework

Comparisons should be structured along multiple dimensions, such as:
- Effectiveness or performance
- Robustness or stability
- Efficiency or complexity
- Resource requirements
- Generalization behavior
- Practical applicability

Not all dimensions are mandatory, but chosen ones must be justified.

---

## 5. Baseline Definition and Usage

Baselines must:
- Be clearly defined and justified
- Represent meaningful reference points
- Not be artificially weak or outdated
- Be evaluated under the same conditions

The purpose of baselines is contextualization, not exaggeration.

---

## 6. Comparative Table and Figure Guidelines

When presenting comparisons:
- Use consistent scales and units
- Clearly label all configurations
- Avoid visual distortion or selective highlighting
- Ensure tables and figures align with textual discussion

---

## 7. Interpretation of Comparative Results

Comparative differences must be:
- Explained using methodological or architectural factors
- Discussed in terms of trade-offs
- Linked to research objectives

Avoid attributing superiority without evidence.

---

## 8. Ablation and Variant Analysis (If Applicable)

If ablation or variants are used:
- Clearly define what is changed
- Isolate the effect of each modification
- Avoid confounding multiple changes simultaneously

Ablation is for insight, not optimization.

---

## 9. Limitations of Comparison

The paper must acknowledge:
- Scope limitations of comparisons
- Conditions under which results may differ
- Factors not covered by the comparison

This prevents overgeneralization.

---

## 10. Writing and Style Constraints

- Use neutral, analytical language
- Avoid competitive or promotional tone
- Avoid cherry-picked comparisons
- Maintain logical consistency

---

## 11. Output Contract

This agent guarantees:
- Fair and transparent comparison
- Methodological consistency
- Domain neutrality
- Compatibility with diverse research studies

---

## 12. Dependency and Flow

This agent depends on:
- ResultsInterpretationAgent
- EvaluationMetricsAgent

This agent informs:
- LimitationsAndChallengesAgent
- FutureWorkAgent

---