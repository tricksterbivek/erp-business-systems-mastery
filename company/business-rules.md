# Baseline business rules

These starting assumptions keep future scenarios consistent. They are requirements to investigate and model, not completed accounting solutions.

1. Each order, purchase, invoice, payment, stock movement, and journal identifies its legal entity. Shared services do not merge books or ownership.
2. ABG-AU initially buys China-produced finished goods. ABG-US and ABG-NZ buy group stock through explicit intercompany transactions. EU inventory remains owned by ABG-AU in the initial model.
3. Record contractual title transfer separately from shipment, receipt, and physical custody. Incoterms alone do not establish title. A brief must provide ownership terms before recognising inventory in transit.
4. Shopify and B2B orders route to one seller. Separate order acceptance, cash collection, fulfilment, invoicing, and revenue recognition; specify recognition policy in the revenue module.
5. Customer deposits remain separately identifiable until applied or refunded. Payment authorisation, capture, settlement, fees, and bank receipt are distinct events.
6. Purchase orders, goods receipts, vendor bills, credits, and payments have separate identifiers and lifecycle states. Model discrepancies and approval before payment.
7. Returns need an original-sale link and inspection outcome. A refund, credit, stock receipt, and inventory disposition may happen at different times; prevent duplicate effects.
8. Inventory records separate owner, custodian/location, SKU, lot, expiry, and state. Do not silently sell quarantined or damaged stock, permit negative stock, or change ownership by moving locations.
9. Freight and import costs require an explicit allocation and capitalisation policy. Costing methods and landed-cost rules are deferred to their modules.
10. Tax depends on transaction facts and dated rules. Preserve calculation inputs, outputs, and evidence. Do not embed an unverified global rate.
11. Intercompany partners record linked transactions. Reconcile reciprocal balances, FX differences, inventory movements, and eliminations before consolidation; include unrealised inventory profit when applicable.
12. Integrations preserve source identifiers, timestamps, and auditable transitions. Retries must be idempotent; failed events need visible recovery and reconciliation.
13. Control-sensitive actions require explicit approval rules and an audit trail. Define thresholds and role permissions in the relevant brief rather than choosing arbitrary values now.
14. Use synthetic data only. Specify fiscal calendar, chart of accounts, costing, recognition, FX, rounding, and close policies when first needed; record changes in the shared model.
