---
description: >-
  A full overview of all you need to know to bridge DYDX from Ethereum to the
  DYDX Mainnet.
hidden: true
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/guides/how-to-stake/dydx-bridging-and-staking
---

# DYDX Bridging and Staking

## Why do I need to bridge?

Current DYDX holders have their tokens on Ethereum. As dYdX transitions into being launched as a Cosmos SDK chain, the original DYDX token holders will only be able to access the benefits of the Cosmos SDK chain (staking, governance etc.) after they move their tokens from Ethereum to dYdX chain.&#x20;

To move these tokens dYdX has provided with a bridge contract that makes it easy for anyone to send their tokens from Ethereum to dYdX chain.

If you hit any snags, please see the [#troubleshooting](dydx-bridging-and-staking.md#troubleshooting "mention") section below.&#x20;

## How does DYDX bridging work?

1. Users will send their Ethereum-based DYDX tokens to the [open sourced dYdX bridge contract](https://github.com/dydxfoundation/dydx-token-migration-documentation/blob/en/migration-of-dydx-from-ethereum-to-dydx-chain/wethdydx-smart-contract.md). The contract receives and permanently locks the Ethereum-based DYDX tokens.
2. The bridge then sends a wrapped version of the Ethereum-based DYDX token (**“wethDYDX”**) to the user on a 1-1 proportional basis on Ethereum
3. As the last part, dYdX Chain validators can also read and ingest the information in the Ethereum Smart Contract such that corresponding DYDX can be distributed to users by validators on the dYdX v4 Chain once there is confirmation that Step 1 above is complete and the Ethereum-based DYDX is permanently locked in the Ethereum Smart Contract.

## Do I need ETH to bridge DYDX?

Yes, you will require a small amount of ETH to pay for the transaction fees.

A useful tool for checking current ETH gas fees is: [https://beaconcha.in/gasnow](https://beaconcha.in/gasnow)

## Can I stake at the same time as I bridge?

Yes, Chorus One’s bridging UI enables you to bridge and stake in one go.&#x20;

Our UI allows you to sign the strake transaction as well, so that the whole process happens in one go.&#x20;

As the bridging process takes 48 hours the staking transaction will automatically be broadcasted and processed once the bridging process is complete.

#### Here's how you can do this:

After you sign your bridging transaction, we provide you with an option to “pre-sign” your staking transaction. At this point, the staking hasn’t begun. We only broadcast the “pre-signed” transaction when your bridged funds actually arrive in your account, making it a seamless process for you.

#### <mark style="color:red;">However, there is one caveat:</mark>

{% hint style="danger" %}
When using out in-built the functionality to let you pre-sign your staking transaction, that transaction gets broadcasted automatically when the bridged funds arrive on the dYdX chain.&#x20;

However, if you perform any DYDX mainnet transaction in the meantime [while the funds are transferring](https://app.gitbook.com/o/pEq7DqIRRV63MeJ6sKVS/s/yuw4Rsarhx3nMuCdobop/~/changes/1/group-opus-sdk/getting-started/dydx-bridging-and-staking#how-long-does-it-take-for-my-tokens-to-arrive), the pre-signed transaction is rendered invalid and it will fail.
{% endhint %}

## Is there a block explorer where I can check the status of my bridging/staking?&#x20;

On the Ethereum side you can use [https://etherscan.io/](https://etherscan.io/address/0xdea70595ae2b6748c94ebd2c095687f182fb2a54) and on the Cosmos side you can use [mintscan.io](http://mintscan.io/).

## Do I need to add DYDX chain to Keplr in order to connect with the UI?

Yes, you will need to have DYDX chain added to Keplr.&#x20;

In case, you do not have that, you may go to [https://chains.keplr.app/](https://chains.keplr.app/), search for DYDX and add it.

***

## Bridging FAQs

<details>

<summary>What wallets do I need to bridge?</summary>

You need an Ethereum wallet (e.g. MetaMask) that holds your DYDX tokens and Keplr on the cosmos side to bridge the tokens over. On the Cosmos side, other than Keplr we do not support any other wallet as of now.

</details>

<details>

<summary>Who has built the bridging contract?</summary>

DYDX foundation has built this the [open sourced dYdX bridge contract](https://github.com/dydxfoundation/dydx-token-migration-documentation/blob/en/migration-of-dydx-from-ethereum-to-dydx-chain/wethdydx-smart-contract.md). Chorus One is just using it in their UI.

</details>

<details>

<summary>Has the bridging contract been audited?</summary>

Yes, the wethDYDX Smart Contract, the GovernanceStrategyV2 Smart Contract, and the TreasuryBridge Smart Contract (collectively, the **“Migration Smart Contracts”**) have been [audited by Peckshield](https://github.com/dydxfoundation/governance-contracts/blob/master/audits/PeckShield-Audit-Report-dYdX-Bridge-v1.1.pdf) and are being released under an open-source license (AGPL V3).

</details>

<details>

<summary>How long does it take for my tokens to arrive? </summary>

It takes 40+ hours for your bridged tokens to reflect in your dYdX chain account. This is a parameter set by the DYDX foundation and is not decided by Chorus One’s UI.

</details>

<details>

<summary>What is the minimum amount I can bridge?</summary>

The minimum amount required to bridge is 1 DYDX. Please note, that we also require you to stake a minimum of 1 DYDX as part of the process.

</details>

<details>

<summary>Can I bridge multiple times?</summary>

Yes, you may bridge and stake a portion of your DYDX holdings and come back another time to bridge the remaining portion of your DYDX tokens. Please note that every time you bridge, it will take 40+ hours for the bridging to be complete.

</details>

<details>

<summary>I entered different amounts for Bridging and Staking? What happens to the rest of my tokens?</summary>

The remaining tokens stay liquid in your wallet. You can stake those with us using Keplr.

</details>

## Staking Fundamentals

<details>

<summary>Will I be able to stake my tokens as part of the bridging process?</summary>

Yes. To make the process simple, Chorus One allows users to signed the strake transaction as well, so that the whole process happens in one go. As the bridging process takes 48 hours the staking transaction will automatically be broadcasted and processed once the bridging process is complete.

</details>

<details>

<summary>What is the maximum amount I can stake in one go?</summary>

You can only stake as many tokens as you just bridged. [We also have a ](#user-content-fn-1)[^1] if you want to utilize Keplr to stake with us.

</details>

<details>

<summary>Will I get an email when my DYDX have been staked?</summary>

After you stake, we present you with an option to submit your email ID. If you do that, we will shoot an email to you as soon as your DYDX has been staked.&#x20;

If you forgot to submit your email ID, simply [submit a request](https://support.chorus.one/hc/en-us/requests/new) mentioning your dYdX chain address (on the cosmos side). We will get in touch!

</details>

## Troubleshooting

<details>

<summary>My internet connection got disrupted. What do I do?</summary>

The bridging and staking process need to happen in one go. If you lose connection, hit back or refresh the page you will be required to start from the beginning.&#x20;

In case you are unsure of what to do, you can [submit a request](https://support.chorus.one/hc/en-us/requests/new) and we will get back to you.

</details>

<details>

<summary>I use Leap wallet for cosmos chains, can I connect with the Bridge UI using that?</summary>

Unfortunately, we only support Keplr wallet for now to connect with dYdX chain (on the cosmos side).

</details>

***

## A Note to Institutional Investors

If you are an institutional investor looking to stake DYDX with Chorus One, please reach out to us via our [staking request form](https://shorturl.at/znows).&#x20;

{% include "../../.gitbook/includes/about-c1-dropdown.md" %}

[^1]: Currently links to blog. Will need to update link when the Keplr guide is live in Gitbook.&#x20;
