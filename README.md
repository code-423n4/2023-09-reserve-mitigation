# Reserve - Mitigation Review details
- Total Prize Pool: $17,600 USDC 
- [Warden guidelines for C4 mitigation reviews](https://code4rena.notion.site/Guidelines-for-C4-mitigation-reviews-ed10fc5cfbf640bd8dcec66f38b343c4)
- Submit findings [using the C4 form](https://code4rena.com/contests/2023-09-reserve-mitigation-review/submit)
- Starts TBD XXX XXX XX 20:00 UTC (ex. `Starts March 22, 2023 20:00 UTC`)
- Ends TBD XXX XXX XX 20:00 UTC (ex. `Ends March 30, 2023 20:00 UTC`)

## Important note 

Each warden must submit a mitigation review for *every High and Medium finding* from the parent audit that is listed as in-scope for the mitigation review. **Incomplete mitigation reviews will not be eligible for awards.**

## Findings being mitigated

Mitigations of all High and Medium issues will be considered in-scope and listed here.

- [H-01: CBEthCollateral and AnkrStakedEthCollateral _underlyingRefPerTok is incorrect](https://github.com/code-423n4/2023-07-reserve-findings/issues/23)
- [H-02: CurveVolatileCollateral Collateral status can be manipulated by flashloan attack](https://github.com/code-423n4/2023-07-reserve-findings/issues/22)
- [H-03: ConvexStakingWrapper.sol after shutdown，rewards can be steal](https://github.com/code-423n4/2023-07-reserve-findings/issues/11)
- [M-01: Upgraded Q -> 2 from #26 [1693915911684]](https://github.com/code-423n4/2023-07-reserve-findings/issues/45)
- [M-02: CTokenV3Collateral._underlyingRefPerTok should use the decimals from underlying Comet.](https://github.com/code-423n4/2023-07-reserve-findings/issues/39)
- [M-03: RTokenAsset price estimation accounts for margin of error twice](https://github.com/code-423n4/2023-07-reserve-findings/issues/31)
- [M-04: Possible rounding during the reward calculation](https://github.com/code-423n4/2023-07-reserve-findings/issues/30)
- [M-05: Permanent funds lock in StargateRewardableWrapper](https://github.com/code-423n4/2023-07-reserve-findings/issues/27)
- [M-06: CurveStableMetapoolCollateral.tryPrice returns a huge but valid high price when the price oracle of pairedToken is timeout](https://github.com/code-423n4/2023-07-reserve-findings/issues/25)
- [M-07: The Asset.lotPrice doubles the oracle timeout in the worst case](https://github.com/code-423n4/2023-07-reserve-findings/issues/24)
- [M-08: User can't redeem from RToken based on CurveStableRTokenMetapoolCollateral when any underlying collateral of paired RToken's price oracle is offline(timeout)](https://github.com/code-423n4/2023-07-reserve-findings/issues/21)
- [M-09: RTokenAsset price oracle can return a huge but valid high price when any underlying collateral's price oracle timeout](https://github.com/code-423n4/2023-07-reserve-findings/issues/20)
- [M-10: Asset.lotPrice only uses oracleTimeout to determine if the price is stale.](https://github.com/code-423n4/2023-07-reserve-findings/issues/17)
- [M-11: StaticATokenLM transfer missing _updateRewards](https://github.com/code-423n4/2023-07-reserve-findings/issues/12)
- [M-12: _claimRewardsOnBehalf() User's rewards may be lost](https://github.com/code-423n4/2023-07-reserve-findings/issues/10)
- [M-13: Lack of protection when caling CusdcV3Wrapper._withdraw](https://github.com/code-423n4/2023-07-reserve-findings/issues/8)
- [M-14: Lack of protection when withdrawing Static Atoken](https://github.com/code-423n4/2023-07-reserve-findings/issues/7)
- [M-15: Potential Loss of Rewards During Token Transfers in StaticATokenLM.sol](https://github.com/code-423n4/2023-07-reserve-findings/issues/4)

[ ⭐️ SPONSORS ADD INFO HERE ]

## Overview of changes

Please provide context about the mitigations that were applied if applicable and identify any areas of specific concern.

## Mitigations to be reviewed

### Branch
[ ⭐️ SPONSORS ADD A LINK TO THE BRANCH IN YOUR REPO CONTAINING ALL PRS ]

### Individual PRs
[ ⭐️ SPONSORS ADD ALL RELEVANT PRs TO THE TABLE BELOW:]

Wherever possible, mitigations should be provided in separate pull requests, one per issue. If that is not possible (e.g. because several audit findings stem from the same core problem), then please link the PR to all relevant issues in your findings repo. 

| URL | Mitigation of | Purpose | 
| ----------- | ------------- | ----------- |
| https://github.com/your-repo/sample-contracts/pull/XXX | H-01 | This mitigation does XYZ | 

## Out of Scope

Please list any High and Medium issues that were judged as valid but you have chosen not to fix.
