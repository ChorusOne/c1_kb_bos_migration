---
hidden: true
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/getting-started/staking-concepts/what-is-liquid-staking/eigenlayer-wip
---

# EigenLayer WIP

## What is EigenLayer? <a href="#what-is-eigenlayer" id="what-is-eigenlayer"></a>

EigenLayer is a protocol built on top of Ethereum designed to enhance the economic utility of staked ETH by allowing users to leverage their existing Ethereum stakes to secure additional protocols and applications without requiring additional collateral.

By doing so, EigenLayer aims to create a marketplace of decentralized trust connecting restakers, operators and builders. This initiative offers additional advantages to ETH holders, aiming to make the blockchain landscape more interconnected and efficient, thereby enriching the overall Ethereum experience.

## Is EigenLayer supported by Chorus One? <a href="#is-eigenlayer-supported-by-kiln" id="is-eigenlayer-supported-by-kiln"></a>

Yes! The [OPUS Pool Dashboard](https://opus.chorus.one/pool/dashboard/) supports ETH restaking in any quantity which can also be used to mint an LST such as osETH and this can be restaked to EigenLayer.&#x20;

You can also bring in other supported LSTs to from your self-custodial wallet to restake to EigenLayer.&#x20;

### How can I restake my ETH? <a href="#how-can-i-restake-my-eth" id="how-can-i-restake-my-eth"></a>

There are two ways to restake your ETH:

PICTURE

1. Direct restaking: deploy and Eigenlayer Pod contract and deposit validators through it. In this case the withdrawal credentials of the validator will be the eigenpod address. This can be done from the Kiln dashboard directly (see demo below)
2. Liquid restaking: deposit of liquid staking tokens to EigenLayer token pools is supported in the Kiln dApp, [Kiln Ledger Live dApp](https://docs.kiln.fi/v1/integrations/wallets/stake-from-ledger-live/using-kiln-dapp) and [Kiln Safe dApp](https://docs.kiln.fi/v1/integrations/wallets/stake-from-safe-wallet).

EMBED VIDEO

#### Why would I restake my ETH/LSTs prior to the launch of AVSs? <a href="#why-would-i-restake-my-eth-lsts-prior-to-the-launch-of-avss" id="why-would-i-restake-my-eth-lsts-prior-to-the-launch-of-avss"></a>

There are three main reasons users currently choose to Native restake or Liquid restake:

* Signal public support to the Eigenlayer protocol.
* Collect[ Eigenlayer Restaked Points](https://docs.eigenlayer.xyz/restaking-guides/restaking-user-guide/restaked-points)
* (only Native Restaking) - Already have Validators running with the withdrawal credentials pointing to an Eigenpod to be first in line when AVSs launch, without having to unstake + restake which would be subject to queues

#### What happens to my ETH when I restake? <a href="#what-happens-to-my-eth-when-i-restake" id="what-happens-to-my-eth-when-i-restake"></a>

Restaked ETH, whether direct or liquid, earns the same rewards as standard staking. However, with the next mainnet phase scheduled for launch in Q2, restakers will have the option to delegate their restaked ETH to Eigenlayer Operators such as Kiln, which operate various protocols for Eigenlayer.

These protocols, known as Actively Validated Services (AVS), derive economic security from the contributions of restaked ETH. In exchange, AVS rewards restakers according to their specific tokenomics.

By delegating to an operator that runs multiple AVSs, a restaker can anticipate multiple sources of rewards from ETH staking and from each AVS, which usually pays with its own token.

#### What are the benefits of restaking? <a href="#what-are-the-benefits-of-restaking" id="what-are-the-benefits-of-restaking"></a>

The main benefit to restaking is the increase in economic utility of your staked position. Your ETH is used to secure other applications, chains and services that require a form of consensus. This helps strengthen the ecosystem while increasing your rewards you earn by locking your coins.

#### What are the risks associated with restaking? <a href="#what-are-the-risks-associated-with-restaking" id="what-are-the-risks-associated-with-restaking"></a>

When restaking, a validator is exposed to both Ethereum and EigenLayer penalties. If it behaves against one network’s consensus rules, it will face slashing. While restaking generates additional rewards, it also implies additional risks that need to be taken into account.

Additionally, your validator’s withdrawal credentials is set to an eigenpod smart contract which is upgradeable by Eigenlayer.

#### If I restake will I still earn ETH rewards? <a href="#if-i-restake-will-i-still-earn-eth-rewards" id="if-i-restake-will-i-still-earn-eth-rewards"></a>

Yes, your ETH is still used to secure the Ethereum chain and will continue to earn native staking rewards.

#### How do I access my ETH rewards when I restake? <a href="#how-do-i-access-my-eth-rewards-when-i-restake" id="how-do-i-access-my-eth-rewards-when-i-restake"></a>

For direct restaking, EL rewards are accrued to the fee recipient address set by the validator and CL rewards by claiming your EigenPod balance.

#### How can I unstake my validator when I restake? <a href="#how-can-i-unstake-my-validator-when-i-restake" id="how-can-i-unstake-my-validator-when-i-restake"></a>

The process of unstaking is similar to the standard procedure for exiting an Ethereum validator. However, the unstaked amount will be sent to the Eigenpod address and must be claimed by the staker (Eigenpod owner) once available. A validator can be exited at any time, but there is a 7 days locking period once the validator is fully exited. So the delay after an exit request is:

* Exit Queue delay (see “Exit queue length” [here](https://www.rated.network/overview?network=mainnet\&timeWindow=1d\&rewardsMetric=average\&geoDistType=all\&hostDistType=all\&soloProDist=stake))
* Skimming delay (see “Withdrawal queue length” [here](https://www.rated.network/overview?network=mainnet\&timeWindow=1d\&rewardsMetric=average\&geoDistType=all\&hostDistType=all\&soloProDist=stake))
* \+ an extra 7 days of locking delay

#### What are the risks associated with EigenLayer restaking? <a href="#what-are-the-risks-associated-with-eigenlayer-restaking" id="what-are-the-risks-associated-with-eigenlayer-restaking"></a>

Risks are highlighted by EigenLayer [here](https://docs.eigenlayer.xyz/risk/risk-faq), it is important to know that your funds will go through the EigenLayer smart contracts and can be impacted in case of a hack or malicious upgrade on the contracts.

EigenLayer also details its security [here](https://docs.eigenlayer.xyz/security/multisig-governance), additional information are:

1. **Audits**

EigenLayer Smart Contracts have been audited by 2 different auditors:

* [Consensys Diligence](https://consensys.io/diligence/audits/2023/03/eigenlabs-eigenlayer/): 1 medium, 6 medium, 6 informational
* [Sigma Prime](https://github.com/Layr-Labs/eigenlayer-contracts/blob/master/audits/Sigma_Prime_Eigen_Layer_Phase_2_Security_Assessment_Report_v2_1.pdf): 1 high, 1 low, 4 informational

Important issues have been fixed and reviewed properly.

A [$2m bug bounty](https://immunefi.com/bounty/eigenlayer/) is also live since December 2023, there have not been communication if there was any findings and if they were addressed properly.

1. **Testing**

<details>

<summary>Unit test - coverage is > 95% on main contracts</summary>

```
```

</details>

<details>

<summary>Integration tests - covering the main user series of interactions with Eigen contracts with fuzzing</summary>

*
*
*
*
*
*
*

</details>

<details>

<summary>Formal verification - using certora</summary>



</details>

1. **Governance**

Splitted between 3 multisigs:

* operations multisig: can do upgrades and pause / timelock: 3 of 5 multisig controlled by Eigenlayer
* pauser multisig: pauser role (1 of 9 multisig) for emergency reaction, cannot unpause
*   community multisig: 9 of 13 can perform upgrades and replace the operations multisig

    Copy

    ```
    Tim Beiko - Ethereum Foundation
    Viktor Bunin - Coinbase
    Uma Roy - Succinct
    Brian Retford - RISC Zero
    Pramod Viswanath - Witness Chain
    Swapnil Raj - Nethermind
    Dimitry Ukhanov - P2P
    Tarun Chitra - Robot Ventures
    Anna Rose - ZK Validator
    Curtis Spencer - Electric Capital
    Yuan Han Li - Blockchain Capital
    Ben Rodriguez - Coinbase Cloud
    Rob Pellecchia - Figment Capital
    ```

INSERT PICTURE

## Questions?

Please contact us for general support via email at [support@chorus.one](mailto:support@chorus.one) or via your dedicated Slack or Telegram channel.&#x20;

