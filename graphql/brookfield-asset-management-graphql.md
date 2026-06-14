# Brookfield Asset Management GraphQL

## Title
Brookfield Asset Management GraphQL API

## Description
Brookfield Asset Management (NYSE: BAM, TSX: BAM) is a leading global alternative asset manager with over $1 trillion in assets under management across five investment verticals: Renewable Power and Transition, Infrastructure, Real Estate, Private Equity, and Credit.

BAM does not publish a public GraphQL API or any public developer API program. Institutional Limited Partners, financial intermediaries, and distribution platforms interact with the firm through private, authentication-gated investor portals, PDF reporting (10-K, supplemental, letters to shareholders), and data feeds from fund administrators.

## Endpoint
No public GraphQL endpoint is available.

## Documentation URL
https://bam.brookfield.com

## Notes on GraphQL Support

Brookfield Asset Management has no documented GraphQL API surface. The following schema is a conceptual data model representing the core domain entities of an alternative asset manager of BAM's type, derived from:

- BAM's publicly disclosed fund structures, investment verticals, and reporting taxonomy
- Standard private markets data conventions used by fund administrators, placement agents, and LP portals (e.g., Allvue, iLEVEL, Cobalt)
- SEC EDGAR filings (Form 10-K, 10-Q) disclosing AUM, fee-bearing capital, fund vintages, IRR, and distribution metrics
- BAM Investor Relations site: bam.brookfield.com
- BAM Supplemental Information packages (quarterly)

This conceptual schema would be appropriate for an internal LP portal, fund-data integration layer, or alternative-assets data platform that aggregates Brookfield's fund and investment data alongside comparable manager data. It covers the full private-markets data lifecycle from fund formation through commitment, drawdown, investment, valuation, return calculation, and distribution to limited partners.

## Schema Types (25)

- Fund
- AssetClass
- Investment
- Portfolio
- Property
- Infrastructure
- PrivateEquity
- Credit
- Renewable
- REIT
- LP (LimitedPartner)
- NAV (Net Asset Value)
- Commitment
- Drawdown
- Distribution
- Return
- IRR (Internal Rate of Return)
- MOIC (Multiple on Invested Capital)
- Vintage
- Strategy
- Sector
- Geography
- LimitedPartner
- GeneralPartner
- FundPerformance
