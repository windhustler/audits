## [Aloe](https://audits.sherlock.xyz/contests/120/leaderboard)

### About

I was competing in a team setup under the [roguereddwarf](https://audits.sherlock.xyz/watson/roguereddwarf) handle alongside the Lead Senior Watson [HollaWaldfee](https://twitter.com/HollaWaldfee100).

### Reports

| Risk      | Title                                                                                                                                                                   |
|:----------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 🟥 High   | [Oracle.sol: manipulation via increasing Uniswap V3 pool observationCardinality](https://github.com/sherlock-audit/2023-10-aloe-judging/issues/40)                      |
| 🟥 High   | [Borrower.sol: Health check uses stale liabilities](https://github.com/sherlock-audit/2023-10-aloe-judging/issues/51)                                                   |
| 🟥 High   | [Implied Volatility can be manipulated and takes a long time to recover, which can lead to bad debt](https://github.com/sherlock-audit/2023-10-aloe-judging/issues/109) |
| 🟨 Medium | [Oracle.sol: observe function has overflow risk and should cast to uint256 like Uniswap V3 does](https://github.com/sherlock-audit/2023-10-aloe-judging/issues/85)      |
| 🟨 Medium | [Lender.sol: Incorrect rewards accounting for RESERVE address in _transfer function](https://github.com/sherlock-audit/2023-10-aloe-judging/issues/49)                  |
| 🟨 Medium | [Governor can permanently prevent withdrawals in spite of being restricted](https://github.com/sherlock-audit/2023-10-aloe-judging/issues/35)                           |
| 🟨 Medium | [Couriers can be cheated out of earning fees due to frontrunning](https://github.com/sherlock-audit/2023-10-aloe-judging/issues/37)                                     |
