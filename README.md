# Antigravity Skills & Plugins Registry

An organized registry of custom capabilities, specialized workflows, and plugins for **Google Antigravity** and other advanced agentic AI coding assistants. This repository serves as a central compilation of structured instructions, configuration schemas, helper scripts, and domain-specific knowledge bundles that extend the capabilities of AI agents.

---

## 📂 Repository Structure

The repository is structured to support different levels of complexity and modularity for AI agent integrations:

```
.
├── skills/                     # Single-file core capabilities
│   ├── adapt/
│   ├── tdd/
│   └── ...
├── plugins/                    # Domain-specific plugin bundles
│   ├── android-cli-plugin/
│   ├── science/
│   └── ...
└── different_skills/           # Complex, multi-file capabilities
    ├── shadcn/
    └── last30days/
```

- **Core Skills (`skills/`)**: Standalone capabilities defined by a single `SKILL.md` file containing YAML frontmatter and targeted markdown instructions.
- **Plugins (`plugins/`)**: Comprehensive extension packages containing a `plugin.json` descriptor, custom sub-skills, scripts, and local references for dedicated tools or systems.
- **Advanced Skills (`different_skills/`)**: Richer multi-file capability modules that incorporate custom assets, verification scripts, rules, and isolated subagents.

---

## 🔌 Core Plugins

| Plugin | Author/Team | Description |
| :--- | :--- | :--- |
| **`android-cli-plugin`** | Android Developer Tools | Orchestrates Android development tasks (project creation, SDK management, device/emulator diagnostics). |
| **`chrome-devtools-plugin`** | Chrome DevTools Team | Tools and strategies for web inspecting, debugging, and profiling. |
| **`firebase`** | Google | Integration and project management utilities for Google Firebase backend services. |
| **`google-antigravity-sdk`** | Google | Core development resources, API details, and instructions for Google Antigravity SDK. |
| **`modern-web-guidance-plugin`** | Google Chrome | Guidelines, compatibility lists, and optimization best practices for modern web applications. |
| **`ponytail`** | Google | Code auditing and optimization tools to eliminate over-engineering across multiple intensity levels. |
| **`science`** | Google | Integrations for biological and scientific databases (AlphaFold, ChEMBL, dbSNP, Ensembl, GTEx, HPA, InterPro, JASPAR, PDB, PubChem, PubMed, Reactome, STRING, UniProt). |
| **`superpowers`** | Google | Specialized workflows for pair programming (parallel agents, git worktrees, systematic debugging, TDD, code review, plans writing). |

---

## 🛠️ Skill Categories

Skills are categorized below by their primary domain. Each skill contains triggers (`Use when...`) defined in its YAML frontmatter to allow agentic discovery.

### 🎨 UI/UX & Frontend Aesthetics
- [adapt](file:///C:/repositories/skills-record/skills/adapt/SKILL.md) - Adapt designs to work across screen sizes, devices, contexts, or platforms.
- [animate](file:///C:/repositories/skills-record/skills/animate/SKILL.md) - Enhance features with animations, micro-interactions, and motion effects.
- [arrange](file:///C:/repositories/skills-record/skills/arrange/SKILL.md) - Improve layout, spacing, and visual rhythm.
- [bolder](file:///C:/repositories/skills-record/skills/bolder/SKILL.md) - Amplify safe or boring designs to make them visually interesting.
- [colorize](file:///C:/repositories/skills-record/skills/colorize/SKILL.md) - Add strategic color to monochromatic or low-contrast interfaces.
- [critique](file:///C:/repositories/skills-record/skills/critique/SKILL.md) - Evaluate design from a UX perspective with persona-based testing.
- [delight](file:///C:/repositories/skills-record/skills/delight/SKILL.md) - Add moments of joy, personality, and unexpected interactive touches.
- [distill](file:///C:/repositories/skills-record/skills/distill/SKILL.md) - Strip designs to their essence by removing unnecessary clutter.
- [frontend-design](file:///C:/repositories/skills-record/skills/frontend-design/SKILL.md) - Create distinctive, production-grade frontend interfaces.
- [harden](file:///C:/repositories/skills-record/skills/harden/SKILL.md) - Improve interface resilience, error handling, overflow, and i18n.
- [normalize](file:///C:/repositories/skills-record/skills/normalize/SKILL.md) - Realignment of UI elements to match design system standards.
- [optimize](file:///C:/repositories/skills-record/skills/optimize/SKILL.md) - Diagnose and fix UI performance, loading speed, rendering, and bundle size.
- [overdrive](file:///C:/repositories/skills-record/skills/overdrive/SKILL.md) - Push interfaces past limits with shaders, spring physics, and reveals.
- [polish](file:///C:/repositories/skills-record/skills/polish/SKILL.md) - Apply final pass fixes to spacing, alignment, and microscopic details.
- [quieter](file:///C:/repositories/skills-record/skills/quieter/SKILL.md) - Tone down visually aggressive or overstimulating layouts.
- [typeset](file:///C:/repositories/skills-record/skills/typeset/SKILL.md) - Refine typography hierarchy, font choice, readability, and weights.

### 💻 Development, QA & Testing
- [code-review](file:///C:/repositories/skills-record/skills/code-review/SKILL.md) / [review](file:///C:/repositories/skills-record/skills/review/SKILL.md) - Run parallel spec and coding standard checks against git targets.
- [diagnose](file:///C:/repositories/skills-record/skills/diagnose/SKILL.md) - Disciplined diagnostic loop (reproduce, minimize, fix, test) for hard bugs.
- [migrate-to-shoehorn](file:///C:/repositories/skills-record/skills/migrate-to-shoehorn/SKILL.md) - Migrate test files from `as` type assertions to `@total-typescript/shoehorn`.
- [qa](file:///C:/repositories/skills-record/skills/qa/SKILL.md) - Start interactive QA sessions and conversational GitHub issue filing.
- [request-refactor-plan](file:///C:/repositories/skills-record/skills/request-refactor-plan/SKILL.md) - Generate incremental, safe refactoring RFCs via user interviews.
- [scaffold-exercises](file:///C:/repositories/skills-record/skills/scaffold-exercises/SKILL.md) - Create lint-passing exercise directories and solution stubs.
- [setup-pre-commit](file:///C:/repositories/skills-record/skills/setup-pre-commit/SKILL.md) - Configure Husky, lint-staged, formatting, and pre-commit test runs.
- [tdd](file:///C:/repositories/skills-record/skills/tdd/SKILL.md) - Execute Test-Driven Development (Red-Green-Refactor) loops.

### 📝 Editorial & Content Creation
- [create-readme](file:///C:/repositories/skills-record/skills/create-readme/SKILL.md) - Author comprehensive and well-structured project README files.
- [edit-article](file:///C:/repositories/skills-record/skills/edit-article/SKILL.md) - Restructure article drafts to improve flow, prose, and clarity.
- [writing-beats](file:///C:/repositories/skills-record/skills/writing-beats/SKILL.md) - Shape articles interactively as a narrative journey of beats.
- [writing-fragments](file:///C:/repositories/skills-record/skills/writing-fragments/SKILL.md) - Mine ideas, vignettes, and raw claims into structured notes.
- [writing-shape](file:///C:/repositories/skills-record/skills/writing-shape/SKILL.md) - Conversationally shape raw notes into publication-ready articles.

### 🤖 Agent Operations & Planning
- [find-skills](file:///C:/repositories/skills-record/skills/find-skills/SKILL.md) - Discover and install new agent skills.
- [grill-me](file:///C:/repositories/skills-record/skills/grill-me/SKILL.md) / [grilling](file:///C:/repositories/skills-record/skills/grilling/SKILL.md) - Stress-test plans through interactive interviews.
- [grill-with-docs](file:///C:/repositories/skills-record/skills/grill-with-docs/SKILL.md) - Challenge plans against domain models and update ADRs inline.
- [handoff](file:///C:/repositories/skills-record/skills/handoff/SKILL.md) - Pack the current conversation history into a handoff document.
- [research](file:///C:/repositories/skills-record/skills/research/SKILL.md) - Perform detailed background research against primary sources.
- [write-a-skill](file:///C:/repositories/skills-record/skills/write-a-skill/SKILL.md) - Guidelines for creating new agent skills.
- [zoom-out](file:///C:/repositories/skills-record/skills/zoom-out/SKILL.md) - Ask the agent to step back and explain the higher-level architecture.

---

## ✍️ Authoring New Skills

To add a new skill to the registry, follow these guidelines from the [write-a-skill](file:///C:/repositories/skills-record/skills/write-a-skill/SKILL.md) module:

### Directory Layout
For basic single-file skills, place them in `skills/`. If the skill requires assets, configuration, or utility scripts, create a folder under `skills/` or `plugins/`:
```
skills/skill-name/
├── SKILL.md           # Core instructions and triggers (required)
├── REFERENCE.md       # Detailed documentation (optional)
└── scripts/           # Deterministic utility scripts (optional)
```

### Frontmatter Metadata
Every `SKILL.md` must start with standard YAML frontmatter:
```yaml
---
name: skill-name
description: A clear explanation of capability. Use when [trigger conditions].
---
```

> [!IMPORTANT]
> **Why the description matters:**
> The YAML `description` is the only part of the skill the AI agent sees when deciding which skill to load. It must be concise, written in the third person, and clearly specify the trigger conditions (e.g., specific file extensions, commands, or user intents).

> [!TIP]
> **When to write helper scripts:**
> If a skill requires deterministic actions (such as validation checks, formatting, or API lookups), implement them as executable scripts in the `scripts/` folder rather than relying on LLM generation. This saves context tokens and ensures consistent execution.
