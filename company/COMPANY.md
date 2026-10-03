# Aurelia Beauty Group

A fictional beauty group selling skincare through Shopify and B2B wholesale channels. All names, counterparties, identifiers, and operating assumptions in this lab are synthetic.

Australian headquarters owns US and New Zealand subsidiaries. European operations initially run through the Australian entity with a Dutch 3PL and an assumed EU VAT registration; there is no separate EU subsidiary in this starting model. Independent China manufacturers supply finished goods. Legal ownership and physical custody must always be recorded separately.

Goods flow from China through international freight and inventory-in-transit locations to Australian warehouses or US, NZ, and EU 3PL sites. Sales include prepaid B2C orders, B2B credit sales, and customer deposits. Returns can lead to inspection, restocking, write-offs, credits, and refunds. Purchasing includes vendor bills, freight charges, and settlement. Group-owned stock sold between subsidiaries creates intercompany transactions and consolidation requirements.

## Shared model index

- [subsidiaries.md](subsidiaries.md): ownership and accounting entities
- [departments.md](departments.md): responsibilities and control boundaries
- [locations.md](locations.md): custody, warehouses, and transit
- [customers.md](customers.md) and [suppliers.md](suppliers.md): representative counterparties
- [products.md](products.md): starter SKU model
- [currencies.md](currencies.md): currencies and FX conventions
- [tax-jurisdictions.md](tax-jurisdictions.md): tax scope and evidence
- [business-rules.md](business-rules.md): baseline operating assumptions

These are model seeds, not complete master data or solved scenarios. Add transaction datasets and more detailed policies only when a module needs them. Record changes here or in the relevant source file so projects share the same baseline.
