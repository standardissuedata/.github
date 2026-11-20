# Standard Issue Data

**Automobile data primitives.**

Vehicle identity, safety records, fuel economy, and observed listing history — available through REST and MCP.

[Explore the playground](https://standardissuedata.com/) · [Read the docs](https://standardissuedata.com/docs) · [Get in touch](mailto:hello@standardissuedata.com)

## Open source

Our first open-source project is **Vehicle Profile**: a standalone TypeScript library and CLI for public U.S. vehicle data from NHTSA and EPA/DOE FuelEconomy.gov.

It combines VIN decoding, recall campaigns, owner complaints, crash ratings, and rated fuel economy in versioned JSON, with source URLs and explicit matching scope. When the evidence leaves multiple compatible configurations, it returns those candidates.

**Status:** version 0.1.0 is in release preparation and is not yet published. The code is MIT-licensed and requires Node.js 22 or later.

## How we approach data

- **Make the source visible.** Results should be traceable to the records behind them.
- **Keep scope explicit.** Model-year recall campaigns are distinct from VIN-specific unrepaired-recall checks.
- **Preserve uncertainty.** Missing data and ambiguous configurations should remain visible.

For project questions, feedback, or collaboration, email **[hello@standardissuedata.com](mailto:hello@standardissuedata.com)**.
