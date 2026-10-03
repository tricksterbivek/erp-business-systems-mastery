# Learning roadmap

Twelve planning months, one primary domain each. No calendar start date is assigned. Begin only when requested; advancement depends on evidence, not elapsed time. Each month can contain a brief, an independent attempt, feedback, a revised artifact, and an assessment. Create these only as work begins.

| Month / directory | Focus and intended evidence | Project progression |
| --- | --- | --- |
| 1 — `01-accounting` | Model accounts, balanced postings, accruals, deposits, and reconciliations | Establish posting foundations for later projects |
| 2 — `02-order-to-cash` | Trace B2B/B2C orders, fulfilment, invoices, collections, returns, and refunds | 01 Order-to-Cash |
| 3 — `03-procure-to-pay` | Trace purchase orders, receipts, vendor bills, matching, and payment | 02 Procure-to-Pay |
| 4 — `04-inventory` | Model stock states, ownership, movements, valuation, and costing | 03 Inventory Lifecycle; 04 Inventory Costing |
| 5 — `05-supply-chain` | Model planning, China sourcing, lead times, international freight, and inventory in transit | 05 High Seas: ownership and landed cost during ocean freight |
| 6 — `06-revenue` | Distinguish orders, cash, deposits, fulfilment, invoices, and revenue recognition | Extend 01 with recognition and reversal cases |
| 7 — `07-tax` | Model AU GST, NZ GST, US sales tax, EU VAT, and evidence requirements | 07 Tax Engine |
| 8 — `08-ecommerce` | Model Shopify orders, discounts, payments, refunds, settlements, and integration recovery | 06 Shopify–ERP, using tax and transaction foundations |
| 9 — `09-logistics` | Model warehouse/3PL events, delivery, returns, and freight exceptions | Extend 03 and 05 with fulfilment and recovery |
| 10 — `10-financial-reporting` | Reconcile subledgers, close periods, translate balances, and explain reports | Prepare reporting requirements for 09 Full ERP |
| 11 — `11-intercompany` | Model cross-entity sales, balances, FX, eliminations, and consolidation | 08 Intercompany |
| 12 — `12-erp-architecture` | Define boundaries, data ownership, controls, integration contracts, and operational recovery | 09 Full ERP capstone |

Project numbering identifies folders, not strict execution order. Reuse earlier models and extend evidence instead of duplicating implementations. Later topics may revisit earlier assumptions with documented changes.

## Shared assessment ladder

| Level | Demonstration | Evidence |
| --- | --- | --- |
| 1 — Understand | Identify the event, participants, vocabulary, and outcome | Correct classification and stated assumptions |
| 2 — Explain | Explain why the process and impacts occur in your own words | Walkthrough across the nine-step mental model |
| 3 — Model | Specify states, relationships, postings, boundaries, and controls | Transaction/data model, diagram, and reconciliation design |
| 4 — Implement | Build behavior that satisfies agreed business requirements | Executable artifact, realistic data, meaningful tests |
| 5 — Troubleshoot | Diagnose and repair inconsistent, failed, or duplicated events | Root cause, recovery evidence, and regression protection |
| 6 — Architect | Defend system boundaries and tradeoffs across entities and processes | Architecture decisions, control design, and operational plan |

Start at Levels 1–2, then progress through models and implementation toward troubleshooting and architecture. Record the highest demonstrated level per domain; do not demand Level 6 in Month 1. Later projects can raise earlier domains' levels. Assessment briefs should specify target level and acceptance criteria before the attempt.

Use statuses **Not started**, **In progress**, **Needs revision**, and **Demonstrated** for each target. Require correct business reasoning, traceable evidence, reconciled accounting/inventory where applicable, and explicit exception handling. When a target is missed, give focused feedback and a new attempt; do not silently lower criteria or reveal the answer.
