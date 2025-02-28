---
description: >-
  Proposes to reimburse True Names Limited for expenses incurred on behalf of
  ENS and the DAO.
---

# \[EP8] \[Executable] Reimburse True Names for expenses and tax obligations incurred for the DAO

| **Status**            | Executed                                                                                                                                                                                                                                                                                                                                                                                         |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Discussion Thread** | [Discourse](https://discuss.ens.domains/t/ep8-executable-reimburse-true-names-for-expenses-and-tax-obligations-incurred-on-behalf-of-the-dao/10053)                                                                                                                                                                                                                                              |
| **Votes**             | <p><a href="https://snapshot.org/#/ens.eth/proposal/0xdf7e59e58ab0cf5ee0a591bd65369db3ee5091ae3b7ca696a0d31c2eac9959f5">Snapshot</a>, passed March 6th 2022<br><a href="https://www.withtally.com/governance/eip155:1:0x323A76393544d5ecca80cd6ef2A560C6a395b7E3/proposal/82659277767818009782194204088226418907972756681918239480374274857360772298879">Onchain</a>, passed March 30th 2022</p> |

## Abstract

Since ENS started allowing registrations using the annual-fee model, revenue from this has accrued to the ENS root multisig, which is controlled by seven individuals drawn from the Ethereum community. In order to shield them from individual tax liability, True Names Limited, the development company responsible for ENS development, historically identified itself as the beneficial owner of these funds, which obliged True Names to pay tax on any income to the multisig.

In past years True Names has covered this tax bill from its own reserves - primarily out of funds that were collected during the Short Name auction - but in 2021 revenue rose to a level that meant that was no longer sustainable. Accordingly, True Names requested funds from the multisig to cover the anticipated tax, and the multisig agreed.

The calculation used to determine the tax owing used the actual income to October 20th, plus a 1/12th buffer to cover the anticipated income between the launch of the DAO and its potential request for control of the funds from the keyholders. This total came to $2,163,921 USDC.

However, this failed to take into account the enormous uptick in interest that the announcement of the DAO produced, and so falls significantly short of True Names' actual tax obligations for FY 2021. This proposal requests that the DAO sends True Names the remainder of the funds required to cover the multisig's income during the period that True Names was the beneficial owner.

Further, True Names has incurred the following expenses on behalf of the DAO in January 2022:

![Screenshot from 2022-01-28 09-27-45|617x500](upload://1jcGsmCKdHJpl5D0a7CAKr6Bmmd.png)

We additionally request the DAO reimburse True Names for these expenses in the total of $48,637.

### Revenue

Revenue to the multisig came exclusively from ENS name registrations and renewals, and can be calculated from onchain data using [this BigQuery query](https://gist.github.com/Arachnid/dfd374886a3e6b0a0eb17b26703d776a), producing the following results:

| Month     | ETH           | USD             |
| --------- | ------------- | --------------- |
| Jan 2021  | 411.6875      | 498484.22       |
| Feb 2021  | 383.5613      | 643985.05       |
| Mar 2021  | 453.5619      | 776834.28       |
| Apr 2021  | 429.0654      | 955345.36       |
| May 2021  | 243.0624      | 740165.91       |
| Jun 2021  | 422.2419      | 993899.95       |
| Jul 2021  | 384.6863      | 811202.23       |
| Aug 2021  | 849.9890      | 2563121.38      |
| Sep 2021  | 728.7825      | 2490699.18      |
| Oct 2021  | 500.3753      | 1863125.83      |
| Nov 2021  | 1699.4660     | 7643673.03      |
| **Total** | **6506.4793** | **19980536.41** |

### Tax

Singapore's company tax rate is 17%, meaning that the tax owing on $19,980,536 comes to $3,396,691. After deducting the $2,163,921 USDC already sent by the multisig, this leaves a shortfall of $1,232,770.

## Specification

We request that the DAO send $1,281,407 USDC to coldwallet.ens.eth.
