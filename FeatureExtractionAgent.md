# FeatureExtractionAgent.md

## ⚠️ STRICT WARNING (MANDATORY)
- **DO NOT hard-code domain-specific features, signals, attributes, or representations.**
- **DO NOT reference specific sensors, data modalities, or feature types.**
- This agent defines **principles and structure**, not concrete feature choices.
- All feature definitions must be instantiated by the author later.

---

## 1. Purpose of This Agent

The **FeatureExtractionAgent** provides a **structured framework** for describing how raw inputs are transformed into representations suitable for analysis, modeling, or inference.

This agent ensures that feature design is:
- Justified
- Systematic
- Reproducible
- Aligned with the research problem

---

## 2. Role in Research Paper Structure

This agent supports:
- Feature Representation section
- Data Processing subsection
- Input Encoding or Signal Transformation description
- Interface between data and model

It acts as the **bridge between data and methodology**.

---

## 3. Conceptual Definition of Features

Features are defined as:
> Structured representations derived from raw inputs that capture relevant information required to address the research problem.

This agent does not assume:
- Feature dimensionality
- Feature type (numeric, categorical, learned, etc.)
- Extraction mechanism

---

## 4. Feature Categorization Framework (Generic)

Features may be categorized using one or more of the following axes:

- Structural vs derived
- Local vs global
- Static vs dynamic
- Hand-crafted vs learned
- Low-level vs high-level
- Deterministic vs probabilistic

The chosen categorization must be justified.

---

## 5. Feature Extraction Process Description

The paper must describe:
- Input form prior to feature extraction
- Transformation or mapping applied
- Intermediate representations (if any)
- Final feature format used for modeling

Each step must be described **conceptually**, not procedurally.

---

## 6. Design Rationale and Assumptions

For each feature group, the author must explain:
- Why the feature is relevant to the problem
- What information it is intended to capture
- Any assumptions made during extraction
- Potential limitations of the representation

---

## 7. Feature Normalization and Consistency Rules

The paper must specify:
- Whether features are normalized or standardized
- Whether scaling is applied consistently
- How missing or undefined values are handled

Undocumented transformations are not permitted.

---

## 8. Feature Dimensionality and Complexity Considerations

The paper should discuss:
- Relative dimensionality (high-level)
- Impact on computational complexity
- Trade-offs between expressiveness and efficiency

Exact numbers are not required in this agent.

---

## 9. Robustness and Generalization Considerations

The feature design must consider:
- Sensitivity to noise or variation
- Stability across conditions
- Transferability to unseen data or scenarios

Limitations must be acknowledged.

---

## 10. Relationship to Downstream Models

The feature representation must:
- Be compatible with the chosen methodology
- Not leak label information
- Maintain separation between training and evaluation

This ensures experimental integrity.

---

## 11. Writing and Style Constraints

- Use precise and neutral language
- Avoid informal descriptions
- Avoid over-claiming feature effectiveness
- Ensure logical linkage to methodology

---

## 12. Output Contract

This agent guarantees:
- Clear feature documentation
- Logical justification of representations
- Domain neutrality
- Compatibility with multiple modeling paradigms

---

## 13. Dependency and Flow

This agent depends on:
- DatasetAndBenchmarkAgent
- MethodologyDesignAgent

This agent informs:
- ModelArchitectureAgent
- TrainingAndOptimizationAgent

---

