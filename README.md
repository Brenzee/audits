# Smart Contract Audits and Web3 Developments

Feel free to reach out for Web3 consulting, Web3 development, Smart Contract audits:

- Twitter [@BKWeb3](https://twitter.com/BKWeb3)
- Telegram [@bkweb3](https://t.me/BKWeb3)
- Discord @bk77

### Table of contents

- [Smart Contract Audits and Web3 Developments](#smart-contract-audits-and-web3-developments)
  - [Table of contents](#table-of-contents)
  - [Total issues found](#total-issues-found)
  - [Code4rena Audit Competitions](#code4rena-audit-competitions)
    - [PoolTogether Audit](#pooltogether-audit)
    - [Venus Protocol Audit](#venus-protocol-audit)
    - [Caviar Private Pools Audit](#caviar-private-pools-audit)
    - [Contest 225 Audit](#contest-225-audit)
    - [Asymmetry Audit](#asymmetry-audit)
  - [Sherlock Audit Competitions](#sherlock-audit-competitions)
    - [Blueberry Audit](#blueberry-audit)
    - [JOJO Exchange Audit](#jojo-exchange-audit)
    - [Footium Audit](#footium-audit)
    - [USSD Audit](#ussd-audit)

### Total issues found

8 High impact and 7 Medium impact issues

## Code4rena Audit Competitions

Code4rena profile: [Brenzee](https://code4rena.com/@Brenzee)

### [PoolTogether Audit](https://code4rena.com/contests/2023-07-pooltogether#top)

Found 1H issue
12th place out of 111

Report is not public yet.

### [Venus Protocol Audit](https://code4rena.com/contests/2023-05-venus-protocol-isolated-pools#top)

Found 1H and 1M issues

| Severity | Finding                                                                                                                                                                                  | Notes |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----- |
| High     | [`WhitePaperInterestRateModel.blocksPerYear` is incorrect, which causes the interest rate to be calculated incorrectly](https://github.com/code-423n4/2023-05-venus-findings/issues/260) |       |
| Medium   | [`riskFundBalance` is compared to USD value, which is incorrect](https://github.com/code-423n4/2023-05-venus-findings/issues/263)                                                        |       |

### [Caviar Private Pools Audit](https://code4rena.com/contests/2023-04-caviar-private-pools#top)

Found 2M issues and made QA report

| Severity | Finding                                                                                                                                                | Notes |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ | ----- |
| Medium   | [Pool tokens can be stolen via `PrivatePool.flashLoan` function from previous owner](https://github.com/code-423n4/2023-04-caviar-findings/issues/230) |       |
| Medium   | [`changeFeeQuote` will fail for low decimal ERC20 tokens](https://github.com/code-423n4/2023-04-caviar-findings/issues/858)                            |       |
| QA       | [QA Report](https://github.com/code-423n4/2023-04-caviar-findings/blob/main/data/Brenzee-Q.md)                                                         |

### [Contest 225 Audit](https://code4rena.com/contests/2023-03-contest-225-contest#top)

Found 1M issue

Contest was private and report is not public.

### [Asymmetry Audit](https://code4rena.com/contests/2023-03-asymmetry-contest#top)

Found 1H issue

| Severity | Finding                                                                                                                                          | Notes |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ----- |
| High     | [An attacker can manipulate the preDepositvePrice to steal from other users](https://github.com/code-423n4/2023-03-asymmetry-findings/issues/55) |       |

## Sherlock Audit Competitions

### [Blueberry Audit](https://audits.sherlock.xyz/contests/69)

Found 1M issue

| Severity | Finding                                                                                                                             | Notes |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------- | ----- |
| Medium   | [No checks if Arbitrum sequencer is down in Chainlink feeds](https://github.com/sherlock-audit/2023-04-blueberry-judging/issues/75) |       |

### [JOJO Exchange Audit](https://audits.sherlock.xyz/contests/70)

Found 1M issue

| Severity | Finding                                                                                                                                   | Notes |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ----- |
| Medium   | [Subaccount contract and Subaccount.execute cannot receive ETH tokens](https://github.com/sherlock-audit/2023-04-jojo-judging/issues/160) |       |

### [Footium Audit](https://audits.sherlock.xyz/contests/71)

Found 1H issue

| Severity | Finding                                                                                                                                 | Notes |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------- | ----- |
| High     | [Previous owner of the club can steal tokens that he approved on](https://github.com/sherlock-audit/2023-04-footium-judging/issues/147) |       |

### [USSD Audit](https://audits.sherlock.xyz/contests/82)

Found 4H and 1M issues

| Severity | Finding                                                                                                                                                            | Notes |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----- |
| High     | [`StableOracleDAI` calculates `getPriceUSD` with inverted base/rate tokens for Chainlink price](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/269) |       |
| High     | [Wrong decimals are assumed for `latestRoundData` in `StableOracleDAI` oracle](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/262)                  |       |
| High     | [`USSD.UniV3SwapInput` executes Uniswap V3 swap without slippage protection](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/374)                    |       |
| High     | [Wrong Oracle feed addresses](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/255)                                                                   |       |
| Medium   | [Chainlink's latestRoundData might be stale or incorrect](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/250)                                       |       |
