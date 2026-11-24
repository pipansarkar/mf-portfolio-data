# Mutual fund portfolio data (India)

Monthly equity holdings and expense ratios of Indian mutual fund schemes, built
automatically from the portfolio and TER disclosures that fund houses publish
on their own websites under SEBI rules. Used by the Portfolio Checkup app.

- `latest/manifest.json`: month, generation time, sha256 and coverage (which fund houses are included)
- `latest/funds.json`: schemes with category, benchmark, TER (direct/regular) and equity holdings by ISIN (% of NAV)
- `archive/YYYY-MM/`: earlier months

Updated by a scheduled job between the 10th and 25th of each month. Data is
provided as-is, may contain parsing errors, and is not investment advice.
Fund houses whose websites don't allow automated access are not included.
