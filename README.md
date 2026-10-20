# 🌌 Antigravity Skills & Plugins Registry

An organized registry of custom capabilities, specialized workflows, and plugins for **Google Antigravity** and other advanced agentic AI coding assistants. This repository serves as a central compilation of structured instructions, configuration schemas, helper scripts, and domain-specific knowledge bundles that extend the capabilities of AI agents.

[![Built for Google Antigravity](https://img.shields.io/badge/Agent-Google_Antigravity-blue?style=flat-square&logo=google)](https://github.com/google/antigravity)
[![License-MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)

---

## 📂 Repository Structure

The repository is structured to support different levels of complexity and modularity for AI agent integrations:

```
.
├── skills/                     # Standalone core capabilities
│   ├── create-readme/
│   ├── frontend-design/
│   └── impeccable/
├── plugins/                    # Domain-specific plugin bundles
│   ├── android-cli-plugin/
│   ├── engineering/
│   ├── ponytail/
│   ├── productivity/
│   ├── pstack/
│   └── science/
└── different_skills/           # Complex, multi-file capabilities
    ├── last30days/
    ├── shadcn/
    ├── vercel-react-best-practices/
    └── web-design-guidelines/
```

* **Core Skills (`skills/`)**: Standalone capabilities defined by a single `SKILL.md` file containing YAML frontmatter and targeted markdown instructions.
* **Plugins (`plugins/`)**: Comprehensive extension packages containing a `plugin.json` descriptor, custom sub-skills, scripts, and local references for dedicated tools or systems.
* **Advanced Skills (`different_skills/`)**: Richer multi-file capability modules that incorporate custom assets, verification scripts, rules, and isolated subagents.

---

## 🔌 Core Plugins

| Plugin | Author/Team | Description |
| :--- | :--- | :--- |
| **`android-cli-plugin`** | Android Developer Tools | Orchestrates Android development tasks (project creation, SDK management, device/emulator diagnostics). |
| **`chrome-devtools-plugin`** | Chrome DevTools Team | Tools and strategies for web inspecting, debugging, and profiling. |
| **`engineering`** | Google Engineering | Deep developer workflows, triage machines, codebase design heuristics, and wayfinding strategies. |
| **`firebase`** | Google Firebase | Integration and project management utilities for Google Firebase backend services. |
| **`google-antigravity-sdk`** | Google SDK Team | Core development resources, API details, and instructions for Google Antigravity SDK. |
| **`modern-web-guidance-plugin`** | Google Chrome | Guidelines, compatibility lists, and optimization best practices for modern web applications. |
| **`ponytail`** | Google Systems | Code auditing and optimization tools to eliminate over-engineering across multiple intensity levels. |
| **`productivity`** | Google | Hand-off, teaching, and writing assistance tools to optimize human-agent alignment. |
| **`pstack`** | Lauren Tan (@poteto) | Rigorous depth-first agent workflows, engineering principles, verification, and high-quality parallelism. |
| **`science`** | Google Science | Integrations for biological and scientific databases (AlphaFold, ChEMBL, dbSNP, Ensembl, GTEx, HPA, InterPro, JASPAR, PDB, PubChem, PubMed, Reactome, STRING, UniProt). |

---

## 🛠️ Skill Categories

Skills are categorized below by their primary domain. Each skill contains trigger conditions defined in its YAML frontmatter to allow agentic discovery.

### 🎨 UI/UX & Frontend Aesthetics
* [create-readme](file:///C:/repositories/skills-record/skills/create-readme/SKILL.md) - Author comprehensive and well-structured project README files.
* [frontend-design](file:///C:/repositories/skills-record/skills/frontend-design/SKILL.md) - Guidance for distinctive, intentional visual design when building new UI or reshaping an existing one.
* [impeccable](file:///C:/repositories/skills-record/skills/impeccable/SKILL.md) - Distill, harden, optimize, adapt, animate, colorize, or improve a frontend interface.
* [shadcn](file:///C:/repositories/skills-record/different_skills/shadcn/SKILL.md) - Specialized guidelines for utilizing the Shadcn components suite in modern React applications.
* [web-design-guidelines](file:///C:/repositories/skills-record/different_skills/web-design-guidelines/SKILL.md) - Design guidelines and UI/UX patterns to produce premium, state-of-the-art websites.
* [vercel-react-best-practices](file:///C:/repositories/skills-record/different_skills/vercel-react-best-practices/SKILL.md) - Architectural patterns and optimization blueprints for Vercel and React environments.

### 💻 Development, QA & Testing
* [ask-matt](file:///C:/repositories/skills-record/plugins/engineering/skills/ask-matt/SKILL.md) - A router tool that suggests the correct skill or flow for the developer's scenario.
* [code-review](file:///C:/repositories/skills-record/plugins/engineering/skills/code-review/SKILL.md) - Run parallel spec-matching and coding-standard reviews on changes.
* [codebase-design](file:///C:/repositories/skills-record/plugins/engineering/skills/codebase-design/SKILL.md) - Shared vocabulary and principles for designing deep software modules.
* [diagnosing-bugs](file:///C:/repositories/skills-record/plugins/engineering/skills/diagnosing-bugs/SKILL.md) - Disciplined diagnostic loops for debugging complex systems and performance regressions.
* [domain-modeling](file:///C:/repositories/skills-record/plugins/engineering/skills/domain-modeling/SKILL.md) - Formulate, record, and maintain a project's ubiquitous domain model.
* [implement](file:///C:/repositories/skills-record/plugins/engineering/skills/implement/SKILL.md) - Standard workflows for implementing code based on tickets or specs.
* [improve-codebase-architecture](file:///C:/repositories/skills-record/plugins/engineering/skills/improve-codebase-architecture/SKILL.md) - Scan codebases for architecture improvements and generate depth analysis reports.
* [prototype](file:///C:/repositories/skills-record/plugins/engineering/skills/prototype/SKILL.md) - Build rapid throwaway prototypes to validate logic and design assumptions.
* [resolving-merge-conflicts](file:///C:/repositories/skills-record/plugins/engineering/skills/resolving-merge-conflicts/SKILL.md) - Guidance on resolving in-progress git merge or rebase conflicts safely.
* [setup-matt-pocock-skills](file:///C:/repositories/skills-record/plugins/engineering/skills/setup-matt-pocock-skills/SKILL.md) - Configure local environments with issue trackers, labels, and docs layouts.
* [tdd](file:///C:/repositories/skills-record/plugins/engineering/skills/tdd/SKILL.md) - Execute Test-Driven Development (Red-Green-Refactor) loops.
* [to-spec](file:///C:/repositories/skills-record/plugins/engineering/skills/to-spec/SKILL.md) - Synthesize conversations into feature specs and publish them to issue trackers.
* [to-tickets](file:///C:/repositories/skills-record/plugins/engineering/skills/to-tickets/SKILL.md) - Break complex plans down into manageable issue tickets with blocking edges.
* [triage](file:///C:/repositories/skills-record/plugins/engineering/skills/triage/SKILL.md) - Move issues and external pull requests through a standardized triage pipeline.
* [wayfinder](file:///C:/repositories/skills-record/plugins/engineering/skills/wayfinder/SKILL.md) - Long-term planning tool to map and resolve decision trees.
* [wizard](file:///C:/repositories/skills-record/plugins/engineering/skills/wizard/SKILL.md) - Generate interactive terminal-based setup or provisioning scripts.

### 🤖 Agent Operations & Alignment
* [grill-me](file:///C:/repositories/skills-record/plugins/productivity/skills/grill-me/SKILL.md) - Challenge plans and implementation directions through an interactive interview.
* [grill-with-docs](file:///C:/repositories/skills-record/plugins/engineering/skills/grill-with-docs/SKILL.md) - A systematic interview that updates architectural decision records (ADRs) inline.
* [grilling](file:///C:/repositories/skills-record/plugins/productivity/skills/grilling/SKILL.md) - Relentless plan stress-testing workflow.
* [handoff](file:///C:/repositories/skills-record/plugins/productivity/skills/handoff/SKILL.md) - Compact current session history into high-density state handoffs for next runs.
* [teach](file:///C:/repositories/skills-record/plugins/productivity/skills/teach/SKILL.md) - Enable agents to teach developers new skills or domain concepts.
* [to-questionnaire](file:///C:/repositories/skills-record/plugins/productivity/skills/to-questionnaire/SKILL.md) - Distill complex decisions into structured questionnaires for human alignment.
* [wait-what](file:///C:/repositories/skills-record/plugins/productivity/skills/wait-what/SKILL.md) - Stop, pivot, and re-frame the last proposed action or direction.
* [writing-for-agents](file:///C:/repositories/skills-record/plugins/productivity/skills/writing-for-agents/SKILL.md) - Protocols for authoring documents, instructions, and rules optimized for AI agents.

### 🔬 Scientific Research & Analysis
* [alphafold-database-fetch-and-analyze](file:///C:/repositories/skills-record/plugins/science/skills/alphafold_database_fetch_and_analyze/SKILL.md) - Query AlphaFold predicted 3D structures and extract confidence metrics (pLDDT).
* [alphagenome-single-variant-analysis](file:///C:/repositories/skills-record/plugins/science/skills/alphagenome_single_variant_analysis/SKILL.md) - Predict genomic variant effects on gene expression, chromatin, and splicing.
* [clinical-trials-database](file:///C:/repositories/skills-record/plugins/science/skills/clinical_trials_database/SKILL.md) - Search and retrieve trial details from ClinicalTrials.gov by condition or drug.
* [clinvar-database](file:///C:/repositories/skills-record/plugins/science/skills/clinvar_database/SKILL.md) - Fetch genomic variant pathogenicity classifications and evidence details.
* [dbsnp-database](file:///C:/repositories/skills-record/plugins/science/skills/dbsnp_database/SKILL.md) - Map and fetch SNPs and short genetic variants from NCBI dbSNP.
* [embl-ebi-ols](file:///C:/repositories/skills-record/plugins/science/skills/embl_ebi_ols/SKILL.md) - Search and resolve ontology terms within EMBL-EBI Ontology Lookup Service.
* [encode-ccres-database](file:///C:/repositories/skills-record/plugins/science/skills/encode_ccres_database/SKILL.md) - Query cis-Regulatory Elements and ENCODE experimental data.
* [ensembl-database](file:///C:/repositories/skills-record/plugins/science/skills/ensembl_database/SKILL.md) - Primary ID translator and sequence retrieval interface for Ensembl.
* [foldseek-structural-search](file:///C:/repositories/skills-record/plugins/science/skills/foldseek_structural_search/SKILL.md) - Search similar 3D structures using protein coordinate files.
* [gnomad-database](file:///C:/repositories/skills-record/plugins/science/skills/gnomad_database/SKILL.md) - Lookup allele frequency and loss-of-function metrics in gnomAD.
* [gtex-database](file:///C:/repositories/skills-record/plugins/science/skills/gtex_database/SKILL.md) - Retrieve quantitative RNA expression data and eQTL resources across human tissues.
* [human-protein-atlas-database](file:///C:/repositories/skills-record/plugins/science/skills/human_protein_atlas_database/SKILL.md) - Extract spatial localization and protein expression markers.
* [interpro-database](file:///C:/repositories/skills-record/plugins/science/skills/interpro_database/SKILL.md) - Annotate and search protein families, domains, and signatures.
* [jaspar-database](file:///C:/repositories/skills-record/plugins/science/skills/jaspar_database/SKILL.md) - Retrieve transcription factor binding profiles and position matrices.
* [literature-search-arxiv](file:///C:/repositories/skills-record/plugins/science/skills/literature_search_arxiv/SKILL.md) - Search, retrieve metadata, and read papers from arXiv.
* [literature-search-biorxiv](file:///C:/repositories/skills-record/plugins/science/skills/literature_search_biorxiv/SKILL.md) - Retrieve life sciences and medical preprints from bioRxiv/medRxiv.
* [literature-search-europepmc](file:///C:/repositories/skills-record/plugins/science/skills/literature_search_europepmc/SKILL.md) - Search open-access articles and download full text XML/PDF.
* [literature-search-openalex](file:///C:/repositories/skills-record/plugins/science/skills/literature_search_openalex/SKILL.md) - Broad bibliometric analysis, paper lookups, and citation graphs.
* [ncbi-sequence-fetch](file:///C:/repositories/skills-record/plugins/science/skills/ncbi_sequence_fetch/SKILL.md) - Fetch protein and nucleotide sequences by accession or locus.
* [openfda-database](file:///C:/repositories/skills-record/plugins/science/skills/openfda_database/SKILL.md) - Query FDA labeling, adverse events, recalls, and device clearances.
* [opentargets-database](file:///C:/repositories/skills-record/plugins/science/skills/opentargets_database/SKILL.md) - Identify drug targets, disease associations, and safety factors.
* [pdb-database](file:///C:/repositories/skills-record/plugins/science/skills/pdb_database/SKILL.md) - Fetch experimentally resolved 3D structures and experiment metadata.
* [protein-sequence-msa](file:///C:/repositories/skills-record/plugins/science/skills/protein_sequence_msa/SKILL.md) - Align multiple sequences with Clustal Omega.
* [protein-sequence-similarity-search](file:///C:/repositories/skills-record/plugins/science/skills/protein_sequence_similarity_search/SKILL.md) - Identify homologous proteins using fast MMseqs2 or BLAST.
* [pubchem-database](file:///C:/repositories/skills-record/plugins/science/skills/pubchem_database/SKILL.md) - Chemical compound searches, SMILES resolving, and bioactivity checks.
* [pubmed-database](file:///C:/repositories/skills-record/plugins/science/skills/pubmed_database/SKILL.md) - Query PubMed literature and index biological annotations.
* [pymol](file:///C:/repositories/skills-record/plugins/science/skills/pymol/SKILL.md) - Command PyMOL to render structures, trace contacts, and highlight sites.
* [quickgo-database](file:///C:/repositories/skills-record/plugins/science/skills/quickgo_database/SKILL.md) - Access biological functions and ontology relationships.
* [reactome-database](file:///C:/repositories/skills-record/plugins/science/skills/reactome_database/SKILL.md) - Map gene lists to metabolic pathways and hierarchical diagrams.
* [string-database](file:///C:/repositories/skills-record/plugins/science/skills/string_database/SKILL.md) - Query protein-protein interaction networks and enrichment scores.
* [ucsc-conservation-and-tfbs](file:///C:/repositories/skills-record/plugins/science/skills/ucsc_conservation_and_tfbs/SKILL.md) - Fetch phyloP evolutionary conservation and binding intervals.
* [unibind-database](file:///C:/repositories/skills-record/plugins/science/skills/unibind_database/SKILL.md) - Access direct experimentally validated transcription factor DNA interactions.
* [uniprot-database](file:///C:/repositories/skills-record/plugins/science/skills/uniprot_database/SKILL.md) - Core functional annotations, classifications, and publications for proteins.
* [workflow-skill-creator](file:///C:/repositories/skills-record/plugins/science/skills/workflow_skill_creator/SKILL.md) - Re-package completed science workflows into reusable skill templates.

### 🧹 Code Auditing & Optimisation (Ponytail)
* [ponytail](file:///C:/repositories/skills-record/plugins/ponytail/skills/ponytail/SKILL.md) - Switch ponytail auditing level (lite, full, ultra, off).
* [ponytail-audit](file:///C:/repositories/skills-record/plugins/ponytail/skills/ponytail-audit/SKILL.md) - Audit the entire codebase for over-engineering and dead code.
* [ponytail-debt](file:///C:/repositories/skills-record/plugins/ponytail/skills/ponytail-debt/SKILL.md) - Trace and measure accumulated architectural debt.
* [ponytail-gain](file:///C:/repositories/skills-record/plugins/ponytail/skills/ponytail-gain/SKILL.md) - Displays measured gains (less code, faster execution, lower cost).
* [ponytail-help](file:///C:/repositories/skills-record/plugins/ponytail/skills/ponytail-help/SKILL.md) - Command reference and auditing intensity descriptions.
* [ponytail-review](file:///C:/repositories/skills-record/plugins/ponytail/skills/ponytail-review/SKILL.md) - Run PR audits to keep code additions clean and minimal.

### 🥔 Depth-First & High-Quality Engineering (pstack)
* [architect](file:///C:/repositories/skills-record/plugins/pstack/skills/architect/SKILL.md) - Sketch types, signatures, and module boundaries before implementation.
* [blast-radius](file:///C:/repositories/skills-record/plugins/pstack/skills/blast-radius/SKILL.md) - Quantify and mitigate the reach and regression risk of proposed changes.
* [create-formal-verification-skill](file:///C:/repositories/skills-record/plugins/pstack/skills/create-formal-verification-skill/SKILL.md) - Generate a project-local skill that formally verifies invariants and race conditions.
* [figure-it-out](file:///C:/repositories/skills-record/plugins/pstack/skills/figure-it-out/SKILL.md) - Autonomous debugging workflow for resolving tricky issues systematically.
* [how](file:///C:/repositories/skills-record/plugins/pstack/skills/how/SKILL.md) - Subsystem architecture, runtime flow walkthroughs, and ownership questions.
* [maintain-formal-verification-skill](file:///C:/repositories/skills-record/plugins/pstack/skills/maintain-formal-verification-skill/SKILL.md) - Bring formal verification models back in sync after code changes.
* [no-comments](file:///C:/repositories/skills-record/plugins/pstack/skills/no-comments/SKILL.md) - Clean up trivial, redundant, or explanatory code comments before review.
* [technical-writing](file:///C:/repositories/skills-record/plugins/pstack/skills/technical-writing/SKILL.md) - Diátaxis structure, Google developer style, and simplified technical english rules.
* [typescript-best-practices](file:///C:/repositories/skills-record/plugins/pstack/skills/typescript-best-practices/SKILL.md) - Rigorous TypeScript idioms and strict typing guidelines.
* [unslop](file:///C:/repositories/skills-record/plugins/pstack/skills/unslop/SKILL.md) - Strip out AI-generated slop, over-engineering, unnecessary abstractions, and boilerplate.
* [why](file:///C:/repositories/skills-record/plugins/pstack/skills/why/SKILL.md) - Query multi-source evidence to explain design decisions and tradeoffs.

---

## ✍️ Authoring New Capabilities

To contribute a new skill or plugin to this registry, follow the standardized authoring workflows:

### Directory Layout
For single-file skills, place them in `skills/`. If the capability contains helper scripts, assets, or reference files, bundle them in a folder under `skills/` or `plugins/`:

```
skills/new-skill/
├── SKILL.md           # Core instructions and triggers (required)
├── REFERENCE.md       # Detailed technical reference (optional)
└── scripts/           # Executable utility scripts (optional)
```

### Frontmatter Requirements
Every `SKILL.md` must start with a YAML frontmatter block declaring its identifier and trigger heuristics:

```yaml
---
name: new-skill
description: 'Identify custom patterns. Use when [trigger rules].'
---
```

> [!IMPORTANT]
> The YAML `description` is the primary metadata parsed by agentic discovery layers. It should state clearly and in the third person exactly when the agent should activate the capability.

> [!TIP]
> Prefer placing deterministic, heavy tasks (like linting, REST validation, or complex regex scraping) into executable scripts within the skill's `scripts/` directory rather than relying on LLM reasoning. This reduces agent token consumption and ensures consistent execution.
