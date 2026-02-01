# ProblemStatementAgent.md

## ⚠️ STRICT WARNING (MANDATORY)
- **DO NOT inject domain-specific facts, datasets, metrics, claims, or assumptions inside this agent.**
- **DO NOT use external sources, web data, or prior knowledge.**
- This agent defines **structure and intent**, not subject-matter conclusions.
- All topic-specific instantiation must occur in downstream agents or during paper writing.

---

## 1. Purpose of This Agent

The **ProblemStatementAgent** is responsible for establishing a **clear, rigorous, and academically valid problem definition** for a research paper.

This agent does **not** solve the problem.  
It **frames** the problem in a way that enables:
- Consistent methodology design
- Logical literature review
- Coherent evaluation and discussion
- IEEE / ACM / Springer–compliant academic writing

This agent must remain **domain-agnostic** so it can be reused across disciplines.

---

## 2. Role in Research Paper Structure

This agent directly supports the following paper sections:

- Introduction (Problem Motivation)
- Problem Definition
- Research Context
- Scope and Boundaries
- Objective Framing

It provides the **conceptual foundation** upon which all other sections depend.

---

## 3. Generic Research Context Definition

Every research problem exists within a broader academic or applied context.  
This agent establishes that context **without assuming a specific field**.

### Contextual Framing Guidelines
When writing the paper:
- Identify a **broad domain or area of study**
- Describe the **general evolution or importance** of the problem area
- Emphasize why **automated, systematic, or scientific investigation** is necessary
- Avoid premature mention of methods, datasets, or results

This ensures the problem statement remains neutral and adaptable.

---

## 4. Core Problem Statement Template

The core problem must be expressed as a **research challenge**, not a solution.

### Generic Problem Definition Template
> The central problem addressed in this research is the difficulty of accurately, reliably, and efficiently addressing a well-defined challenge within a given domain, due to limitations in existing approaches, methodologies, or assumptions.

This formulation allows substitution of:
- Domain
- Task
- Constraints  
without changing logical structure.

---

## 5. Identification of Research Gaps (Generic)

A valid research problem must be justified by **gaps or limitations** in existing work.

This agent defines **how gaps should be framed**, not what they are.

### Acceptable Gap Categories
- Conceptual limitations
- Methodological weaknesses
- Scalability or efficiency issues
- Generalization or robustness concerns
- Evaluation or benchmarking inconsistencies
- Interpretability or explainability gaps

The actual gap content is supplied later by the Literature Survey.

---

## 6. Scope and Boundary Definition

This agent enforces **explicit scope control**, which prevents research drift.

### Scope Definition Rules
A valid scope must:
- Clearly state what the research **addresses**
- Clearly state what it **does not address**
- Avoid expanding beyond what can be empirically supported

### Boundary Examples (Generic)
- In-scope: specific data types, problem formulations, or evaluation settings  
- Out-of-scope: unrelated tasks, auxiliary domains, or unsupported assumptions

No domain names should be hard-coded here.

---

## 7. Research Objectives (Reusable Template)

⚠️ **This section is intentionally generic.**

```text
The objectives of this research are:
1. To examine and contextualize existing work relevant to the defined research problem.
2. To evaluate current approaches with respect to their effectiveness, limitations, or assumptions.
3. To identify gaps, inefficiencies, or unresolved challenges in existing solutions.
4. To propose a structured approach, framework, or analysis aligned with the research findings.
5. To discuss constraints, challenges, and potential directions for future research.
