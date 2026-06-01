# Personal Financial Planning AI Assistant
### Udacity Course Assignment 1: Prompting for LLM Reasoning and Financial Services

This repository contains a complete, end-to-end implementation of a domain-specific **Personal Financial Planning AI Assistant**. The project demonstrates advanced techniques in System Prompt Engineering, Persona Design, Context Injection, and Output Guardrails using the OpenAI API framework (`gpt-4o-mini`).

---

## Project Overview

The objective of this assignment is to study the baseline output variances of Large Language Models when presented with complex, unstructured personal financial scenarios and programmatically engineer high-fidelity, deterministic, and fiduciary-grade financial advice.

### Key Objectives:
1. **Iterative Persona Design:** Moving from generic plain instructions to specialized, expert configurations.
2. **Dynamic Context Extension:** Writing algorithmic parsing filters (`extend_profile`) to dynamically scale static data baselines with runtime scenario variances (Family Growth, Multi-tier Liabilities, Retirement adjustments).
3. **Behavioral Guardrailing:** Mitigating common LLM alignment vulnerabilities, such as stripping UI-breaking LaTeX blocks and forcing vertical programming notations.
4. **Multi-Scenario Stress Testing:** Evaluating structural model changes across distinct personal financial disciplines.

---

## Repository Structure

* **`Assignment1_Financial_Advisory_AI_system.ipynb`**: The complete production notebook containing all cell-by-cell Markdown documentations, helper scripts, advanced prompt iterations, and execution pipeline records.
* **`README.md`**: Project blueprint, execution guide, and performance documentation.

---

## Prompting Framework Architecture

The framework evaluates the AI's structural maturity across **Four Development Tiers**:

```
[Plain Prompt Baseline] 
       │
       ▼
[Certified Financial Planner Role Definition]
       │
       ▼
[Domain Specialization & Fiduciary Injections (CFP Board Guide)]
       │
       ▼
[Style Refinement, Priority Tiering, & UI Flat-Text Constraints]
```

### Prompt Evolution Details:
* **Baseline (`cfp_system_prompt`):** Basic identifier configuration providing high-level, unstructured checklists.
* **Expert Layer (`expertise_system_prompt`):** Injects core financial execution standards (Debt Avalanche/Snowball comparisons, tax-advantaged scaling via 401k/IRA/HSA/529, and cash flow management models).
* **Refined Engine (`expertise_system_prompt_with_styling`):** The final production prompt setting tone parameters, forced execution lists, timeline math parameters, and rigorous string-level formatting constraints (banning math formatting tokens to optimize terminal parsing).

---

## Stress-Testing Case Studies

The pipeline programmatically validates persona consistency against three real-world customer lifecycles:
1. **Scenario 1 (Retirement Planning Strategy):** Analyzing the feasibility of altering target retirement age metrics from 65 to 62 while modeling compound return assumptions and early mortgage payoffs versus investment yields.
2. **Scenario 2 (Household Growth & Priority Balance):** Modeling financial adjustments during 3 months of unpaid leave, accounting for immediate operational variables (daycare, diapers, healthcare), calculating term life insurance scaling targets, and balancing real-estate milestones.
3. **Scenario 3 (Complex Balance Sheet Debt Optimization):** Handling high-utilization revolving credit, auto loans, liquid asset tiers (HYSA), and structural data conflicts to evaluate the model's factual reconciliation capabilities.

---

## Evaluation & Key Findings

### 1. Most Effective Persona Strategy
The **Communication Style Refinement Approach** with strict layout constraints proved to be the most effective strategy. While knowledge blocks ensure semantic validity, an advisor tool requires explicit operational structures to protect users from choice overload.

### 2. Key Success Factors (5 Critical Pillars)
1. **Enforced Priority Tiers:** Maps tasks from absolute dependencies (Priority 1) to deferred operations (Priority 5) to remove analysis paralysis.
2. **Concrete Variable Math:** Eliminates generic descriptions with explicit, auto-calculated dollar amounts and vertical runouts.
3. **Fiduciary Transparency:** Forces step-by-step reasoning behind mathematical trade-offs to build user confidence.
4. **Token Isolation Constraints:** Explicitly strips LaTeX tags to ensure multi-platform legibility.
5. **Algorithmic Context Control:** Using regular expressions to handle profile merges ensures prompt clarity without adding clutter.

### 3. Critical Elements for Personal Finance AI
1. **Cash Flow and Budget Auditing**
2. **Mathematical Liability Acceleration Strategies (Avalanche vs. Snowball)**
3. **Tax-Advantaged Portfolio Optimization**
4. **Liquid Capital Protection Planning (Risk Management & Emergency Buffers)**
5. **Behavioral Trade-off Analysis**

---

## ⚙️ Execution Instructions

### Prerequisites
* Python 3.8+
* An active OpenAI API account / Sandbox Gateway token.

### Colab Environment Launch Setup
1. Upload the `.ipynb` file directly into your **Google Colab Workspace**.
2. Navigate to Colab **Secrets (the Key Icon 🔑)** in the left sidebar menu.
3. Add a new secret entry named exactly: `Udacity_Vocareum_OpenAI_Key`.
4. Paste your secret authentication token inside the Value block and grant notebook access privileges.
5. *(Optional)* If you are executing via an academic sandbox or internal hub, locate the second code cell and update the `base_url` value to match your gateway string.
6. Click **Runtime -> Run All** to execute the production testing pipeline.

---
*Developed as part of the Udacity Prompt Engineering Curriculum.*
