# Tuna Transshipment and Reefer Plug

Web app that estimates Pacific International, Inc.'s cost of transshipment over the dock in Majuro, Marshall Islands, as two separate operations:

- **Transshipment operation** — fully burdened labor (expat and local crew, from the PII Shipping rate sheet), depreciation of the dock, reach stacker, Starloader and other assets, and other daily costs. Costed per MT, with monthly and yearly break-even tonnage.
- **Reefer plug operation** — MEC power for reefers held at the set point (default −25°C), including the higher draw while the cargo is pulled down, plus plug assets and other costs. Costed per container per plug-day.

Tabs, grouped Estimate → Actual → Setup: Dashboard, Transshipment, Reefer Plug, Pricing, Billing History (separate transshipment, reefer plug and others reports; PII transshipment invoices May 2019 – Nov 2026 by fiscal year, customer, tonnage and containers; fiscal year ends 30 September), Historical Cost (monthly and yearly cost at the MEC commercial rate and minimum wage in force), Customers (customer analysis), then Considerations (all assumptions editable) and Saved (saved computations). Light mode by default, dark mode by toggle.

`index.html` is a single self-contained page. It is published as a claude.ai artifact, which provides the shared storage used by the Saved tab; opened elsewhere, saved computations fall back to the browser.
