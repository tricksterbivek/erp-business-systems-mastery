# ERP Business Systems Mastery

An engineering lab for learning to become a strong ERP / Business Systems / Forward Deployed Engineer: someone who can understand operations, translate ambiguity into transaction models, implement integrations, reconcile outcomes, and design reliable controls.

This is a progressive 12-month learning environment, built around **Aurelia Beauty Group**, a fictional international beauty business. It is a working lab, not a documentation archive. Its future artifacts will include business and transaction models, accounting logic, realistic datasets, executable code, tests, diagrams, and implementation projects.

## Start here

1. Read [LEARNING_RULES.md](LEARNING_RULES.md) and the [company overview](company/COMPANY.md).
2. Review [ROADMAP.md](ROADMAP.md) and record your starting status in [PROGRESS.md](PROGRESS.md).
3. When you choose to begin a module, request a problem brief and success criteria, then attempt it yourself.
4. Save your model or implementation, validate it, and request feedback. Record evidence and next steps before moving on.

**The foundation is ready for review. Module 1 has not started.** No lessons, exercise answers, or reference implementations are supplied yet.

## How the lab works

Each month focuses on one of the twelve modules in the roadmap. Treat the months as planning windows, not automatic promotions: revisit gaps and advance on evidence. Modules develop concepts; projects apply them across processes and accumulate toward a full ERP capstone. The nine projects are staged through the year, not nine extra months.

Every future module follows:

**Business event → Business process → ERP transaction → Accounting impact → Inventory impact → Reporting impact → Integration impact → Controls → Automation opportunities**

Mark an impact as “none” only with an explanation. Assessments progress through Understand, Explain, Model, Implement, Troubleshoot, and Architect. A finished document or passing test alone does not establish mastery; explain the business outcome and provide reconciliation evidence.

## Working with Codex and ChatGPT

**Codex** is the workspace engineering partner: it can frame problems, inspect your attempts, give staged hints, review code and models, run checks, and help troubleshoot. It should wait for your attempt before supplying complete solutions and follow the learning rules when asked to implement assessed work.

**ChatGPT** is the discussion and reasoning partner: use it to question assumptions, rehearse explanations, explore business concepts, and prepare for stakeholder conversations. Bring useful conclusions back as concise decisions or evidence. Apply the same attempt-first rules when discussing assessments there; ChatGPT does not automatically see or update this repository.

You own the decisions, attempts, and understanding. Neither assistant awards mastery solely because it generated an artifact.

## Repository map

| Path | Purpose |
| --- | --- |
| `company/` | Shared simulation, stable identifiers, and explicit business assumptions |
| `01-accounting/` … `12-erp-architecture/` | Progressive briefs and learner evidence, added only when needed |
| `projects/` | Nine cross-process implementation projects; requirements precede solutions |
| `src/` | Reusable domain and integration code once justified |
| `tests/` | Behavioral checks, reconciliation checks, and failure cases |
| `data/` | Synthetic master data, transactions, and expected reconciliation totals |
| `diagrams/` | Editable business, transaction, and architecture diagrams |
| `scripts/` | Repeatable data generation, validation, and execution tasks |
| `tools/` | Small developer utilities only when needed |

[ROADMAP.md](ROADMAP.md) defines sequencing; [PROGRESS.md](PROGRESS.md) records evidence; [GLOSSARY.md](GLOSSARY.md) holds shared vocabulary. Empty directories contain `.gitkeep` so Git can retain them; replace placeholders when real work arrives.

Keep one source of truth for each concept. Link shared company facts rather than copying them into every module. Add files when they support an active problem. Use simple executable tools and standard libraries first; justify each external dependency. No runtime or framework is selected yet.

The core curriculum is platform-neutral. Later, map established concepts to ERP platforms such as NetSuite without replacing the generic business models with platform-specific behavior.
