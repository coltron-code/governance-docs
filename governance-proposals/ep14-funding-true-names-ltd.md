---
Description: A proposal to fund TNL for continuing development and improvement of the ENS system.
---

# [Executable] Funding True Names Ltd

| **Status**            | Executed                                                                                                                                      |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| **Discussion Thread** | [Discuss](https://discuss.ens.domains/t/...)                                                                                                |
| **Votes**             | [Onchain](https://www.tally.xyz/governance/eip155:1:0x323A76393544d5ecca80cd6ef2A560C6a395b7E3/proposal/112764562576314516994943312429834673309292069549953740415731020720942627228986)                                                                                                                                     |

# Abstract

  True Names Ltd (“TNL”) developed the Ethereum Name Service (“ENS”) protocol, continues to manage the development of the ENS Protocol and solely focuses on this project. Incubated at the Ethereum Foundation in 2017, TNL spun out in 2018 with the charge of designing and deploying THE next generation naming service. TNL is now a growing team of web3 enthusiasts from across the globe working together to support the ENS Ecosystem that now has a passionate community that has registered over 1 million ENS names and uses more than 500 integrations. 

In 2021, TNL initiated the creation of the ENS DAO with the goal of 1) furthering the development of the ENS Protocol and 2) funding public goods projects.

 
In consideration of the work completed thus far this calendar year and the work in the months and years to come, per Article III of the ENS Constitution, True Names Ltd respectfully requests an evergreen grant stream that will allow the organization to continue the development and improvement of the ENS Protocol. For Calendar Year 2022, this request will amount to $4,197,500 USDC which is equivalent to a daily stream of $11,500 USDC. In Q1 of each year, TNL or the ENS Dao may make requests to alter and/or terminate this evergreen grant stream.

# Specification
We request that the ENS DAO approve a daily grant of $11,500 USDC to True Names Ltd, backdated to January 1st, 2022.

This will be accomplished by approving a dedicated token streaming contract at `0xB1377e4f32e6746444970823D5506F98f5A04201` to spend USDC on behalf of the DAO.

# Transactions
<!-- The transactions section describes all the calls that should be encoded in the onchain version of this proposal. Use the table below as a starting point. -->
<table>
    <tr>
        <th>Address</th>
        <th>Value</th>
        <th>Function</th>
        <th>Argument</th>
        <th>Value</th>
    </tr>
    <tr>
        <td rowspan=2>0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48</td>
        <td rowspan=2>0</td>
        <td rowspan=2>approve</td>
        <td>spender</td>
        <td>0xB1377e4f32e6746444970823D5506F98f5A04201</td>
    </tr>
    <tr>
        <td>value</td>
        <td>0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff</td>
    </tr>
</table>
