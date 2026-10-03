# Customer model seeds

| ID | Synthetic customer | Channel / market | Selling entity | Currency | Starting terms |
| --- | --- | --- | --- | --- | --- |
| C-AU-001 | Southern Beauty Retail | B2B AU | ABG-AU | AUD | Net 30, approved credit limit |
| C-US-001 | Pacific Wellness Stores | B2B US | ABG-US | USD | Net 30, approved credit limit |
| C-NZ-001 | Aotearoa Beauty Retail | B2B NZ | ABG-NZ | NZD | Net 30, approved credit limit |
| C-EU-001 | Canal Beauty Retail | B2B Netherlands | ABG-AU | EUR | Prepayment initially |

B2C customers are individual synthetic records created with later datasets, not one shared debtor. Shopify storefronts AU, US, NZ, and EU route to the corresponding sellers above. Capture ship-to address, bill-to address, currency, tax evidence where relevant, and payment/refund references. Some B2B orders require deposits; specify those terms per order. Do not infer tax exemption solely from B2B status.
