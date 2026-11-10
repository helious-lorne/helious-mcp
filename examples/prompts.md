# Example prompts

Ask in plain words once the server is connected. The tool each prompt usually reaches is in brackets.

## Rates and the curve

- What is the Treasury curve doing today? (`get_rates_and_curve`)
- Show me the whole curve from the 3-month bill to the 30-year bond. (`get_treasury_curve`)
- When did the curve regime last flip, and from what? (`get_curve_history`)
- Why are yields moving today? (`get_market_context`)

## Treasury auctions

- Was the last 10-year auction strong or weak? Give me the tail and the bid-to-cover. (`get_auctions`)
- How did indirect bidders do at the last three 30-year auctions? (`get_auctions`)
- What is the Treasury refunding schedule ahead? (`get_treasury_issuance`)

## Economic data

- What prints this week, and what is forecast? (`get_economic_calendar`)
- How hot was the last CPI against its own history? (`get_series`, `get_inflation`)
- Which sectors drove the last payrolls number? (`get_jobs`)
- Show me the consensus record for nonfarm payrolls over the last year. (`get_economic_calendar` with `event`)

## The Fed

- What are the odds of a Fed cut at the next meeting? (`get_rate_odds`)
- What rate is the market pricing for the end of next year? (`get_rate_path`)
- Who votes on the FOMC this year, and who speaks next? (`get_fed_roster`)
- What did the last FOMC minutes say about the balance sheet? (`get_document_digests`)

## Cross-asset

- Which currencies are strongest against the basket right now? (`get_fx_board`)
- Where does the VIX sit in its one-year range? (`get_vol_board`)
- How correlated are stocks and bonds over the last 60 days? (`get_correlations`)
- What is the imbalance into the close today? (`get_market_imbalance`)
- How many tankers went through the Strait of Hormuz yesterday? (`get_hormuz_transits`)

## Building something

- I want a bot that posts every Treasury auction result to Discord. What should I call, and what will it cost? (`get_build_plan`)
- What can my key read, and how many credits are left this month? (`get_access_info`)
