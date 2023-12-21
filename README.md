# Smart Contract Audits and Web3 Developments

Feel free to reach out for Web3 consulting, Web3 development, Smart Contract audits:

- Twitter [@BKWeb3](https://twitter.com/BKWeb3)
- Telegram [@bkweb3](https://t.me/BKWeb3)
- Discord @bk77
- Website [bkweb3.com](https://bkweb3.com/)

### Table of contents

- [Smart Contract Audits and Web3 Developments](#smart-contract-audits-and-web3-developments)
  - [Table of contents](#table-of-contents)
  - [About me](#about-me)
    - [Audit Contest Profiles](#audit-contest-profiles)
  - [Stats](#stats)
  - [Code4rena Audit Competitions](#code4rena-audit-competitions)
    - [Revolution Protocol Audit](#revolution-protocol-audit)
    - [Venus Prime Audit](#venus-prime-audit)
    - [Dopex Audit](#dopex-audit)
    - [veRWA Audit](#verwa-audit)
    - [Tapioca DAO Audit](#tapioca-dao-audit)
    - [PoolTogether Audit](#pooltogether-audit)
    - [Venus Protocol Audit](#venus-protocol-audit)
    - [Basin Audit](#basin-audit)
    - [Lybra Finance Audit](#lybra-finance-audit)
    - [Caviar Private Pools Audit](#caviar-private-pools-audit)
    - [Contest 225 Audit](#contest-225-audit)
    - [Asymmetry Audit](#asymmetry-audit)
  - [Sherlock Audit Competitions](#sherlock-audit-competitions)
    - [Nouns Builder Audit](#nouns-builder-audit)
    - [Index Update Audit](#index-update-audit)
    - [Index Audit](#index-audit)
    - [Iron Bank Audit](#iron-bank-audit)
    - [USSD Audit](#ussd-audit)
    - [JOJO Exchange Audit](#jojo-exchange-audit)
    - [Footium Audit](#footium-audit)
    - [Blueberry Audit](#blueberry-audit)

## About me

My name is Brendons, people know me as BK. I am a software developer specialized in Web3 for almost 3 years. In my free time I participate in Smart Contract audit competitions.

### Audit Contest Profiles

| Platform  | Profile                                               |
| --------- | ----------------------------------------------------- |
| Code4rena | [Brenzee](https://code4rena.com/@Brenzee)             |
| Sherlock  | [Brenzee](https://audits.sherlock.xyz/watson/Brenzee) |

## Stats

15 High issues reported

15 Medium issues reported

## Code4rena Audit Competitions

### [Revolution Protocol Audit](https://code4rena.com/audits/2023-12-revolution-protocol#top)

Results coming soon.

### [Venus Prime Audit](https://code4rena.com/audits/2023-09-venus-prime#top)

Found 2H issues

**3rd place out of 115**

| Severity | Finding                                                                                                                                                                   | Notes               |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- |
| High     | [Incorrect decimal usage in score calculation leads to reduced user reward earnings](https://github.com/code-423n4/2023-09-venus-findings/issues/122)                     | Selected for report |
| High     | [Users can claim the Prime Token without waiting 90 days after irrevocable token is burned by the admin](https://github.com/code-423n4/2023-09-venus-findings/issues/199) |                     |

### [Dopex Audit](https://code4rena.com/audits/2023-08-dopex#top)

Found 1M issue

| Severity | Finding                                                                                                                                                  | Notes |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- | ----- |
| High     | [Users` votes do not impact/change the Gauge's relative weight and it will always be 0](https://github.com/code-423n4/2023-08-verwa-findings/issues/287) |       |

### [veRWA Audit](https://code4rena.com/audits/2023-08-verwa#top)

Found 1H issue

| Severity | Finding                                                                                                                                                  | Notes |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- | ----- |
| High     | [Users` votes do not impact/change the Gauge's relative weight and it will always be 0](https://github.com/code-423n4/2023-08-verwa-findings/issues/287) |       |

### [Tapioca DAO Audit](https://code4rena.com/audits/2023-07-tapioca-dao#top)

Found 1H issue

| Severity | Finding                                                                                                                                                                           | Notes |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----- |
| High     | [emergencyWithdraw in LidoEthStrategy can be sandwich attacked because the slippage is calculated incorrectly](https://github.com/code-423n4/2023-07-tapioca-findings/issues/539) |       |

### [PoolTogether Audit](https://code4rena.com/contests/2023-07-pooltogether#top)

Found 1H issue

**12th place out of 111**

| Severity | Finding                                                                                                                                                   | Notes                    |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------ |
| High     | [Vault exchange rate may be inflated/deflated if \_yieldVault pauses withdrawals](https://github.com/code-423n4/2023-07-pooltogether-findings/issues/109) | Found only by 2 auditors |

### [Venus Protocol Audit](https://code4rena.com/contests/2023-05-venus-protocol-isolated-pools#top)

Found 1H and 1M issues

| Severity | Finding                                                                                                                                                                                  | Notes |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----- |
| High     | [`WhitePaperInterestRateModel.blocksPerYear` is incorrect, which causes the interest rate to be calculated incorrectly](https://github.com/code-423n4/2023-05-venus-findings/issues/260) |       |
| Medium   | [`riskFundBalance` is compared to USD value, which is incorrect](https://github.com/code-423n4/2023-05-venus-findings/issues/263)                                                        |       |

### [Basin Audit](https://code4rena.com/audits/2023-07-basin#top)

Found 1H issue

| Severity | Finding                                                                                                  | Notes |
| -------- | -------------------------------------------------------------------------------------------------------- | ----- |
| High     | [Pump is not updated in shift function](https://github.com/code-423n4/2023-07-basin-findings/issues/177) |       |

### [Lybra Finance Audit](https://code4rena.com/audits/2023-06-lybra-finance#top)

Found 3M issues

| Severity | Finding                                                                                                                                                     | Notes |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ----- |
| Medium   | [etherInLp and lbrInLp can be manipulated to purchase other people earnings](https://github.com/code-423n4/2023-06-lybra-findings/issues/431)               |       |
| Medium   | [eUSD shares are compared to peUSD balance, which may send unexpected tokens](https://github.com/code-423n4/2023-06-lybra-findings/issues/359)              |       |
| Medium   | [getReward function tries to send more tokens than the contract has, which may cause DoS ](https://github.com/code-423n4/2023-06-lybra-findings/issues/362) |       |

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

### [Nouns Builder Audit](https://audits.sherlock.xyz/contests/111)

Found 1H issue

| Severity | Finding                                                                                                                                                 | Notes |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- | ----- |
| High     | [Specific bid amounts will not allow the auction to be settled and will DoS](https://github.com/sherlock-audit/2023-09-nounsbuilder-judging/issues/206) |       |

### [Index Update Audit](https://audits.sherlock.xyz/contests/91)

Found 1M issue

| Severity | Finding                                                                                                                                               | Notes |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | ----- |
| Medium   | [Price is not calculated correctly according to the documentation in the contract](https://github.com/sherlock-audit/2023-06-Index-judging/issues/36) |       |

### [Index Audit](https://audits.sherlock.xyz/contests/81)

Found 1M issue

| Severity | Finding                                                                                                               | Notes |
| -------- | --------------------------------------------------------------------------------------------------------------------- | ----- |
| Medium   | [Chainlink's latestAnswer function is deprecated](https://github.com/sherlock-audit/2023-05-Index-judging/issues/230) |       |

### [Iron Bank Audit](https://audits.sherlock.xyz/contests/84)

Found 2M issue

| Severity | Finding                                                                                                                        | Notes |
| -------- | ------------------------------------------------------------------------------------------------------------------------------ | ----- |
| Medium   | [Chainlink's latestRoundData is not validated](https://github.com/sherlock-audit/2023-05-ironbank-judging/issues/123)          |       |
| Medium   | [Chainlink's L2 sequencer is not checked if it is down](https://github.com/sherlock-audit/2023-05-ironbank-judging/issues/125) |       |

### [USSD Audit](https://audits.sherlock.xyz/contests/82)

Found 4H and 1M issue

| Severity | Finding                                                                                                                                                            | Notes |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----- |
| High     | [`StableOracleDAI` calculates `getPriceUSD` with inverted base/rate tokens for Chainlink price](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/269) |       |
| High     | [Wrong decimals are assumed for `latestRoundData` in `StableOracleDAI` oracle](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/262)                  |       |
| High     | [`USSD.UniV3SwapInput` executes Uniswap V3 swap without slippage protection](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/374)                    |       |
| High     | [Wrong Oracle feed addresses](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/255)                                                                   |       |
| Medium   | [Chainlink's latestRoundData might be stale or incorrect](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/250)                                       |       |

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

### [Blueberry Audit](https://audits.sherlock.xyz/contests/69)

Found 1M issue

| Severity | Finding                                                                                                                             | Notes |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------- | ----- |
| Medium   | [No checks if Arbitrum sequencer is down in Chainlink feeds](https://github.com/sherlock-audit/2023-04-blueberry-judging/issues/75) |       |
