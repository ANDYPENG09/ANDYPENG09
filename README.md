# Y. Peng

**AI for Materials & Science (AI4M/S) | Materials R&D | Scientific Computing & Automation**

Materials Science · Electrocatalysis · Electrochemistry · Functional Membranes  
Materials Informatics · Scientific Software · DoE · Bayesian Optimization · Research Agents

I am an industrial materials R&D engineer with hands-on experience in **electrocatalysts, functional membranes, materials characterization, electrochemical evaluation, experimental design, and process scale-up**.

My current focus is **AI for Materials (AI4M) and AI for Science (AI4S)**: connecting domain expertise, experimental data, scientific computing, and AI-assisted workflows to accelerate materials discovery and development.

This portfolio brings together scientific software, data-driven experimental optimization, research agents, and practical engineering tools. Many projects originate from real materials R&D problems. I am building toward reproducible, evidence-grounded, closed-loop research workflows that connect computational recommendations with experimental validation.

---

## 🧭 Applications & Quality Tools

### Membrane & Gas Separation Support

A bilingual, offline workbench for mixed-gas membrane tests: humid and sweep-gas conditions, GC composition, apparent permeance, separation factors, and structured technical-support reports. Demonstration records are synthetic.

→ [Open the workbench](https://andypeng09.github.io/PEMFC-Electrocatalyst-Activity-Analyzer/membrane-gas-support/) · [Source and methods](https://github.com/ANDYPENG09/membrane-gas-separation-support)

### Technical Support & Quality Workbench

An offline, bilingual prototype for reviewing catalyst test results, checking test conditions and user-defined specifications, documenting troubleshooting hypotheses, and preparing a traceable report. The demonstration uses synthetic scenarios and an anonymized electrochemistry example.

→ [Open the workbench](https://andypeng09.github.io/PEMFC-Electrocatalyst-Activity-Analyzer/technical-support/) · [Source and documentation](https://github.com/ANDYPENG09/PEMFC-Electrocatalyst-Activity-Analyzer/tree/main/technical-support)

---

## 🔬 Featured AI4M/S & Scientific Computing Projects

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

## 🔁 AI4M/S Research Workflow

My longer-term goal is to connect these tools into a practical closed-loop materials-development workflow, using electrocatalysis as an initial application domain:

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

Rather than treating modeling as a separate activity, I am interested in integrating scientific computation, AI-assisted literature analysis, and experimental feedback into the research workflow. The complete closed loop remains a development goal.

---

## 🎯 Research Interests

- AI for Materials & AI for Science (AI4M/S)
- Materials informatics and scientific data workflows
- Scientific software, research agents and reproducible research automation
- Experimental design, active learning and closed-loop materials development
- Functional membranes and materials characterization
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

These projects complement my experimental materials background and support the same objective: **reducing repetitive work, making scientific reasoning traceable, and shortening the path from a research question to a testable result.**

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

My foundation is **industrial materials R&D**, and my developing focus is **AI4M/S, scientific computing and research automation**.

I use programming, statistics, and AI-assisted development to solve experimental and engineering problems. I am actively strengthening independent Python development, machine learning, and materials informatics skills.

Current direction:

**scientific question → evidence → experiment → characterization → data → model → next experiment**

---

*Y. Peng · AI4M/S · Materials R&D · Scientific Computing · Data-Driven Experimentation*
