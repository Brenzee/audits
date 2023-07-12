# Smart Contract Audits and Web3 Developments

Feel free to reach out for Web3 consulting, Web3 development, Smart Contract audits:

- Twitter [@BKWeb3](https://twitter.com/BKWeb3)
- Telegram [@bkweb3](https://t.me/BKWeb3)
- Discord @bk77

### Table of contents
<!-- TOC -->
* [Smart Contract Audits and Web3 Developments](#smart-contract-audits-and-web3-developments)
    * [Table of contents](#table-of-contents)
    * [Total issues found](#total-issues-found)
  * [Code4rena Audit Competitions](#code4rena-audit-competitions)
    * [Venus Protocol](#venus-protocol)
    * [Caviar Private Pools](#caviar-private-pools)
    * [Contest 225](#contest-225)
    * [Asymmetry](#asymmetry)
  * [Sherlock Audit Competitions](#sherlock-audit-competitions)
    * [Blueberry](#blueberry)
    * [JOJO Exchange](#jojo-exchange)
    * [Footium](#footium)
    * [USSD](#ussd)
<!-- TOC -->

### Total issues found

3 High, 8 Medium

## Code4rena Audit Competitions

Code4rena profile: [Brenzee](https://code4rena.com/@Brenzee)

### [Venus Protocol](https://code4rena.com/contests/2023-05-venus-protocol-isolated-pools#top)

Found 1H and 1M issues

| Severity | Finding                                                                                                               | Notes                    |
|----------|-----------------------------------------------------------------------------------------------------------------------|--------------------------|
| High     | `riskFundBalance` is compared to USD value, which is incorrect                                                        | Report is not public yet |
| Medium   | `WhitePaperInterestRateModel.blocksPerYear` is incorrect, which causes the interest rate to be calculated incorrectly | Report is not public yet |

### [Caviar Private Pools](https://code4rena.com/contests/2023-04-caviar-private-pools#top)

Found 2M issues and made QA report

| Severity | Finding                                                                                                                                                | Notes                                                                                                                                                  |
|----------|--------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
| Medium   | [Pool tokens can be stolen via `PrivatePool.flashLoan` function from previous owner](https://github.com/code-423n4/2023-04-caviar-findings/issues/230) | [Chosen for report](https://code4rena.com/reports/2023-04-caviar#m-15-pool-tokens-can-be-stolen-via-privatepoolflashloan-function-from-previous-owner) |
| Medium   | [`changeFeeQuote` will fail for low decimal ERC20 tokens](https://github.com/code-423n4/2023-04-caviar-findings/issues/858)                            |                                                                                                                                                        |
| QA       | [QA Report](https://github.com/code-423n4/2023-04-caviar-findings/blob/main/data/Brenzee-Q.md)                                                         |                                                                                                                                                        |

### [Contest 225](https://code4rena.com/contests/2023-03-contest-225-contest#top)

Found 1M issue

Contest was private and report is not public.

### [Asymmetry](https://code4rena.com/contests/2023-03-asymmetry-contest#top)

Found 1H issue

Report is not public yet.

## Sherlock Audit Competitions

### [Blueberry](https://audits.sherlock.xyz/contests/69)

Found 1M issue

| Severity | Finding                                                                                                                             | Notes |
|----------|-------------------------------------------------------------------------------------------------------------------------------------|-------|
| Medium   | [No checks if Arbitrum sequencer is down in Chainlink feeds](https://github.com/sherlock-audit/2023-04-blueberry-judging/issues/75) |       |

### [JOJO Exchange](https://audits.sherlock.xyz/contests/70)

Found 1M issue

| Severity | Finding                                                                                                                                   | Notes |
|----------|-------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Medium   | [Subaccount contract and Subaccount.execute cannot receive ETH tokens](https://github.com/sherlock-audit/2023-04-jojo-judging/issues/160) |       |

### [Footium](https://audits.sherlock.xyz/contests/71)

Found 1H issue

| Severity | Finding                                                                                                                                 | Notes |
|----------|-----------------------------------------------------------------------------------------------------------------------------------------|-------|
| High     | [Previous owner of the club can steal tokens that he approved on](https://github.com/sherlock-audit/2023-04-footium-judging/issues/147) |       |

### [USSD](https://audits.sherlock.xyz/contests/82)

Audit is being judged as of now.
