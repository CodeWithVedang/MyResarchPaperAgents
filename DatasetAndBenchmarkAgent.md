# DatasetAndBenchmarkAgent.md

## ⚠️ STRICT WARNING (MANDATORY)
- **DO NOT hard-code any dataset names, benchmarks, statistics, sizes, sources, or domains.**
- **DO NOT introduce external data, assumptions, or prior knowledge.**
- This agent defines **dataset-handling structure and rules**, not dataset content.
- All dataset-specific details must be instantiated later by the author.

---

## 1. Purpose of This Agent

The **DatasetAndBenchmarkAgent** defines a **standardized, rigorous framework** for:
- Describing datasets
- Justifying benchmark selection
- Ensuring fairness, reproducibility, and validity in evaluation

This agent ensures that experimental results are:
- Interpretable
- Comparable
- Reproducible
- Methodologically sound

---

## 2. Role in Research Paper Structure

This agent supports the following paper sections:
- Dataset Description
- Experimental Setup (Data Component)
- Benchmark Definition
- Data Preprocessing Overview
- Reproducibility Statement

It acts as the **empirical foundation** for evaluation.

---

## 3. Dataset Description Framework (Generic)

Each dataset used in a research paper must be described using a **consistent schema**.

### Required Dataset Attributes
For each dataset, the author must specify:
- Purpose of the dataset within the study
- Data modality or type (generic description)
- Source or origin (without promotional language)
- Data composition (high-level)
- Labeling or annotation characteristics
- Intended use (training, validation, testing)

This agent does not allow implicit dataset usage.

---

## 4. Dataset Selection Justification Rules

Dataset selection must be justified based on:
- Alignment with the defined research problem
- Coverage of relevant scenarios or conditions
- Suitability for evaluating proposed methods
- Comparability with prior studies (if applicable)

Unjustified dataset inclusion is not permitted.

---

## 5. Benchmark Definition Guidelines

A **benchmark** is defined as a reference point for comparison.

### Benchmark Requirements
- Benchmarks must be relevant to the research task
- Benchmarks must be described using identical criteria
- Baseline methods must be fairly evaluated
- Performance comparisons must use consistent conditions

This agent does not prescribe benchmark types.

---

## 6. Data Partitioning and Usage Rules

The paper must clearly specify:
- How data is partitioned (e.g., training / validation / testing)
- Whether partitions are fixed or randomized
- Whether cross-validation or repeated trials are used
- Measures taken to avoid data leakage

Partitioning decisions must be justified.

---

## 7. Data Preprocessing and Preparation Constraints

All preprocessing steps must be:
- Explicitly described
- Reproducible
- Applied consistently across datasets

### Acceptable Preprocessing Categories
- Normalization or scaling
- Feature extraction
- Noise handling
- Augmentation or transformation
- Filtering or selection criteria

Undocumented preprocessing is not allowed.

---

## 8. Dataset Bias and Limitations Disclosure

The paper must acknowledge:
- Known or potential dataset biases
- Coverage limitations
- Class imbalance or sparsity
- Constraints affecting generalization

This ensures transparency and scientific integrity.

---

## 9. Reproducibility and Accessibility Statement

The dataset section must clarify:
- Whether datasets are publicly accessible or restricted
- Conditions for access (if any)
- Whether dataset versions are fixed
- Any ethical or legal constraints

This agent does not enforce openness but enforces disclosure.

---

## 10. Writing and Style Constraints

- Use objective, factual tone
- Avoid claims of superiority or uniqueness
- Avoid unnecessary dataset promotion
- Ensure consistency across all dataset descriptions

---

## 11. Output Contract

This agent guarantees:
- Clear dataset documentation
- Fair benchmark comparison
- Prevention of data leakage
- Reproducibility readiness
- Domain independence

---

## 12. Dependency and Flow

This agent depends on:
- ProblemStatementAgent (scope)
- LiteratureSurveyAgent (context)

This agent informs:
- TrainingAndOptimizationAgent
- EvaluationMetricsAgent
- ResultsInterpretationAgent

---

