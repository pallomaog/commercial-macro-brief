# Commercial & Macro Brief

A B2B revenue dashboard with a U.S. macro layer: pipeline, bookings vs. target, conversion, coverage and a next-quarter scenario, read against tariffs, import prices, interest rates and the dollar.

**Live page:** https://pallomaog.github.io/commercial-macro-brief/

## What it shows
- **Finding first:** bookings vs. year-to-date target and next-quarter coverage, filterable by segment.
- **Funnel:** monthly pipeline created, bookings and quarterly targets.
- **Conversion:** win rate by source, median sales cycle by segment.
- **U.S. macro (real data, FRED):** federal customs duties, import prices, federal funds rate, real broad dollar, each with what an analyst should watch.
- **Scenario:** expected next-quarter bookings from open pipeline, win rate and slippage.

## Data
| Layer | Source |
|---|---|
| Company | Synthetic. "Harbor Ledger" is a fictional U.S. vendor of customs-compliance software; deals are generated in the page with a fixed seed (see the script in `index.html`). No employer data is used. |
| Macro | FRED, retrieved 24 Nov 2026: B235RC1Q027SBEA (BEA), IR (BLS), FEDFUNDS, RBUSBIS (BIS) |

No causal link between the macro series and the fictional company's numbers is claimed.

## Definitions
- Win rate = won ÷ (won + lost)
- Target = 110% of the same quarter's bookings a year earlier
- Coverage = open pipeline with expected close in the next quarter ÷ that quarter's target


## Author
Palloma Gitahy — Data & Business Intelligence · [LinkedIn](https://linkedin.com/in/pallomagitahy)
