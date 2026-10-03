# Currency conventions

| Currency | Use |
| --- | --- |
| AUD | AU functional currency and group presentation |
| USD | US functional currency and initial China/freight purchasing |
| NZD | NZ functional currency |
| EUR | European sales and 3PL bills in ABG-AU books |

Store transaction currency independently of entity functional currency and group presentation currency. Future datasets must identify rate date, source, purpose, and precision. Express each rate as **functional-currency units per one transaction-currency unit**, with explicit base and quote currencies. Consolidation rates must similarly name both currencies and their purpose. Do not assume one rate serves posting, settlement, remeasurement, and consolidation. Use decimal monetary arithmetic; select rounding rules in the relevant brief. No live FX service is needed.
