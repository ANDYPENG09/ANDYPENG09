# Y. Peng

**Electrocatalysis R&D | Data-Driven Catalyst Development**

PEMFC · PEMWE · Pt / PtCo · IrOx · ORR / OER  
Electrochemistry · XRD · DoE · Bayesian Optimization · Research Automation

I work on **electrocatalyst development for PEM fuel cells and water electrolysis**, with experience spanning catalyst synthesis, characterization, electrochemical evaluation, and process scale-up.

My current focus is on connecting **experimental design, catalyst characterization, and data-driven optimization** to better understand synthesis–structure–activity relationships and make catalyst R&D more efficient.

Many of the tools below originated from practical problems encountered during catalyst development rather than from software development alone.

---

## 🧭 Applications & Quality Tools

### Technical Support & Quality Workbench

An offline, bilingual prototype for reviewing catalyst test results, checking test conditions and user-defined specifications, documenting troubleshooting hypotheses, and preparing a traceable report. The demonstration uses synthetic scenarios and an anonymized electrochemistry example.

→ [Open the workbench](https://andypeng09.github.io/PEMFC-Electrocatalyst-Activity-Analyzer/technical-support/) · [Source and documentation](https://github.com/ANDYPENG09/PEMFC-Electrocatalyst-Activity-Analyzer/tree/main/technical-support)

---

## 🔬 Featured Research Projects

### 01 · Bayesian Optimization for Electrocatalyst R&D

**Closed-loop experimental optimization for catalyst development**

A Gaussian-process-based workflow for recommending the next experiment from existing catalyst datasets.

**Methods**
- Gaussian Process surrogate modeling
- Matérn 5/2 + ARD kernel
- EI / PI / UCB acquisition functions
- Constraints on stability, cost, particle size, etc.
- Batch experiment recommendation
- Multi-objective optimization
- Uncertainty reporting and experiment traceability

**Example applications**
- PtCo L1₀ ordering optimization
- IrOx OER catalyst optimization
- synthesis–structure–activity exploration

→ [bayesian-optimization-electrocatalyst](https://github.com/ANDYPENG09/bayesian-optimization-electrocatalyst)

---

### 02 · PEMFC Electrocatalyst Activity Analyzer

**Offline electrochemical analysis for PEMFC catalyst evaluation**

A browser-based tool for calculating:

- ECSA from H-upd
- ORR mass activity
- ORR specific activity
- N₂ background correction
- kinetic current using the Koutecký–Levich equation

Also includes utilities for processing **Autolab `.paax`** and **Origin `.opju`** data.

The goal is to make routine catalyst evaluation more reproducible and reduce repetitive manual processing.

→ [PEMFC-Electrocatalyst-Activity-Analyzer](https://github.com/ANDYPENG09/PEMFC-Electrocatalyst-Activity-Analyzer)

---

### 03 · PtCo L1₀ XRD Ordering Analysis

**XRD analysis for PtCo intermetallic ordering**

Offline tool for estimating PtCo L1₀ chemical ordering from characteristic XRD reflections.

Methods include:

- SNIP background subtraction
- Gaussian peak fitting
- Levenberg–Marquardt optimization
- overlapping peak deconvolution
- characteristic superlattice/fundamental peak analysis

Developed from practical PtCo catalyst characterization work and currently focused on PtCo/Pt-based catalyst systems.

→ [XRD-PtCoOrdering](https://github.com/ANDYPENG09/XRD-PtCoOrdering)

---

### 04 · XRD Crystallite Size Analysis

Tools for estimating catalyst crystallite size using:

- Scherrer analysis
- Williamson–Hall analysis
- integral-breadth approaches
- Pt / PtCo-specific diffraction workflows

→ [XRD-Scherrer](https://github.com/ANDYPENG09/XRD-Scherrer)

---

## 🧪 Catalyst Research Tools

| Project | Purpose |
|---|---|
| **XRD File Converter** | Convert diffraction files from Rigaku, Bruker, Jade/MDI and generic text formats |
| **Catalyst Search Skill** | Structured literature search for catalysis and electrocatalysis |
| **Catalyst Design Skill** | Literature-grounded catalyst design workflow for HER / OER / ORR / PEMWE |
| **XRD Toolkit** | Collection and integration point for diffraction-analysis tools |

---

## 🔁 Research Workflow

My longer-term goal is to connect these tools into a practical closed-loop catalyst-development workflow:

```text
Synthesis Variables
        ↓
Design of Experiments
        ↓
Catalyst Synthesis
        ↓
Characterization
XRD · Electrochemistry · Particle Size
        ↓
Structure–Activity Dataset
        ↓
Statistics / Gaussian Process
        ↓
Bayesian Optimization
        ↓
Next Experiment
```

Rather than treating modeling as a separate activity, I am interested in using computational methods directly inside the experimental workflow.

---

## 🎯 Research Interests

- Electrocatalyst synthesis and scale-up
- PEM fuel-cell catalysts
- PEM water-electrolysis catalysts
- Pt and Pt-alloy ORR catalysts
- Ir-based OER catalysts
- synthesis–structure–activity relationships
- catalyst benchmarking and measurement uncertainty
- Design of Experiments
- Bayesian optimization and active learning
- data-driven experimental planning

---

## 🤖 Research AI & Automation

I also build small tools and integrations to improve scientific and technical workflows.

### AI Skills

- **catalyst-search-skill** — Literature retrieval and structured evidence synthesis for catalysis research.
- **catalyst-design-skill** — Traceable catalyst-design reasoning with literature sources, confidence levels, and validation paths.
- **opencode-responses-bridge-skill** — Local compatibility bridge between Chat Completions and Responses-style APIs.

### Scientific Productivity

- Zotero integrations
- literature/RAG workflows
- Hermes Agent extensions
- research automation utilities

These projects are secondary to my catalyst work but support the same objective: **reducing repetitive work and shortening the path from an experimental question to a testable result.**

---

## 🛠 Selected Engineering Projects

| Project | Description |
|---|---|
| **hermes-cache-hit-rate** | Token-cache analytics for Hermes Agent |
| **hermes-gpt-light-theme** | Lightweight dashboard/interface customization |
| **zotero-ima-sync** | Zotero-to-knowledge-base literature synchronization |
| **hermes-multi-task-concurrency-solution** | Diagnosis and workaround for concurrent-session failures |

---

## About

My background is primarily in **industrial electrocatalyst R&D**.

I use programming, statistics, and AI-assisted development mainly as tools for solving experimental and engineering problems rather than as ends in themselves.

Current direction:

**experiment → characterization → data → model → next experiment**

---

*Y. Peng · Electrocatalysis R&D · Research Tools · Data-Driven Experimentation*
