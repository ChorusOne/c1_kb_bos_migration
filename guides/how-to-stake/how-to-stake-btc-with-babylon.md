---
description: >-
  Everything you need to know about staking BTC with Babylon and information on
  how the greater network functions.
hidden: true
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/guides/how-to-stake/how-to-stake-btc-with-babylon
---

# How to stake BTC with Babylon

<figure><img src="../../.gitbook/assets/New header.png" alt=""><figcaption></figcaption></figure>

## Overview

<table data-header-hidden><thead><tr><th width="241"></th><th></th></tr></thead><tbody><tr><td><mark style="color:blue;"><strong>CATEGORY</strong></mark></td><td><mark style="color:blue;"><strong>DETAILS</strong></mark></td></tr><tr><td><strong>Chorus One Validator</strong></td><td><a href="https://btcstaking.babylonlabs.io/?ref=chorus.one">Babylon Labs Staking Dashboard</a> or use<br><a href="https://www.stakingrewards.com/stake-app?input=bitcoin&#x26;type=babylon-staking&#x26;provider=chorus-one&#x26;locked=true">Staking Rewards: Babylon Staking Dashboard</a></td></tr><tr><td><strong>Recommended Wallets</strong></td><td><a href="https://chromewebstore.google.com/detail/okx-wallet/mcohilncbfahbmgdjkbpemcciiolgcge?hl=en">OKX browser extension wallet</a></td></tr><tr><td><strong>Block Explorer</strong></td><td><a href="https://www.oklink.com/btc">OKLink</a> or <a href="https://mempool.space/">Mempool</a></td></tr><tr><td><strong>Track Your Stake</strong></td><td><a href="https://www.stakingrewards.com/terminal">https://www.stakingrewards.com/terminal</a></td></tr><tr><td><strong>Activation Period</strong></td><td>10 BTC blocks for the stake to activate</td></tr><tr><td><strong>Unstaking Period</strong></td><td>7 days to unbond or a maximum stake duration of 65 weeks</td></tr></tbody></table>

{% hint style="warning" %}
**When setting up your wallet please follow these guidelines:**

1. Avoid using hardware wallets like Ledger unless Keystone QR code support is enabled.
2. Do not use wallets holding Bitcoin Inscriptions/Ordinals.
3. Use **Native SegWit** or **Taproot** address formats.
{% endhint %}

***

## What is Babylon?

Babylon allows Bitcoin holders to stake their BTC for PoS blockchains without relying on third-party custody, bridges, or wrapping. Traditionally, Bitcoin has been seen as a store of value, but Babylon expands its utility by enabling Bitcoin to play an active role in securing various PoS ecosystems.&#x20;

This is achieved through a trust-minimized protocol that connects Bitcoin holders with the demand for network security across multiple blockchain systems, including PoS chains.&#x20;

* If you're interested, you can read our comprehensive overview of Babylon [here](https://chorus.one/articles/unlocking-bitcoins-potential-with-babylon).
* To dive right into the staking guide, head to: [How to stake BTC with Babylon](how-to-stake-btc-with-babylon.md#how-to-stake-btc-with-babylon) or check our the [latest about Babylon's Phase 3 here](https://chorus.one/articles/babylon-cap-3-is-live-stake-your-bitcoin-btc-with-chorus-one).&#x20;

{% hint style="info" %}
**Note:** Babylon is a developing network and currently the full functionality of Babylon has not been rolled out yet. Please see the [Babylon Timeline](how-to-stake-btc-with-babylon.md#babylon-timeline-and-planned-phases) section below for more info.&#x20;

* For information and staking support for Phase 3, please read on or review the following guide: [Babylon Cap 3 is Live: Stake Your Bitcoin (BTC) with Chorus One](https://chorus.one/articles/babylon-cap-3-is-live-stake-your-bitcoin-btc-with-chorus-one)
* Or see the guide from Staking Rewards: [Bitcoin Staking on Babylon](https://www.stakingrewards.com/journal/guides/how-to-stake-bitcoin-with-babylon)
{% endhint %}

***

### Babylon Timeline & Planned Phases

As the network is participating in a phased rollout, the full scope and functionality of Babylon is not yet live. Babylon’s mainnet launch is divided into three distinct phases, each with specific goals and functionalities:

<details>

<summary><strong>Phase 1: Bitcoin Locking</strong></summary>

This phase initiates the staking process. Bitcoin holders can begin locking their Bitcoin by submitting Bitcoin staking transactions directly to the Bitcoin blockchain.&#x20;

These transactions secure the Bitcoin within a self-custodial staking script, where it is prepared to participate in PoS consensus validation.&#x20;

Stakers also designate a finality provider by specifying the provider's public key, allowing their Bitcoin to be used in the PoS process without actually transferring the Bitcoin to the provider.

</details>

<details>

<summary><strong>Phase 2: Bitcoin Staking Activation</strong></summary>

In this phase, Babylon will launch its PoS chain, which will begin receiving security from the Bitcoin locked in Phase 1.&#x20;

Finality providers who have received adequate delegations from Bitcoin stakers will participate in the consensus of the Babylon PoS chain, helping to determine the finality of its blocks.&#x20;

This phase also introduces the Bitcoin [timestamping protocol](https://docs.babylonchain.io/docs/introduction/btc-timestamping), which ensures cross-chain time synchronization, a crucial aspect of maintaining security across multiple blockchains.

</details>

<details>

<summary><strong>Phase 3: Bitcoin Multi-Staking Activation</strong></summary>

The final phase transforms Babylon into a marketplace for shared security.&#x20;

This allows Bitcoin holders to stake their assets across multiple PoS systems, earning rewards from various sources.&#x20;

The Babylon PoS chain will act as a control plane, facilitating the staking process across different blockchains and ensuring that Bitcoin’s security is effectively leveraged across the ecosystem.

</details>

So far, there have been three openings for users to stake their BTC in a non-custodial manner to participate in the network.&#x20;

As the network continues to develop it is recommended to follow [Chorus One on Twitter/X](https://x.com/ChorusOne), [Babylon Foundation on Twitter/X](https://x.com/babylonlabs_io), as well as the [Chorus One Blog](https://chorus.one/insights-category/blog) for new updates.&#x20;

* Future updates to the network will see the PoS network BabylonChain go live in the near future with further expansion and utility planned from there.&#x20;

{% hint style="info" %}
You can also read more about Babylon's planned phases [here](https://chorus.one/articles/top-10-things-to-know-about-the-babylon-bitcoin-staking-mainnet-launch) and the most recent Phase 3 staking cap that opened on **December 10th, 2024**.&#x20;

* [Babylon Cap 3 is Live: Stake Your Bitcoin (BTC) with Chorus One](https://chorus.one/articles/babylon-cap-3-is-live-stake-your-bitcoin-btc-with-chorus-one)
{% endhint %}

***

### Babylon Cap 3 Information

Babylon BTC staking for Cap 3 went live on December 10, 2024 at **BTC block 874,088** (around 11:00 UTC). With this new cap, Bitcoin holders can now stake their BTC seamlessly and earn rewards while contributing to the evolution of the Bitcoin ecosystem.

Cap 3 introduces new limits and features that make this staking opportunity both exciting and accessible:

* 🌟 **Start Block:** 874,088
* ⏳ **Duration:** 1,000 BTC blocks (\~1 week)
* 🔒 **Minimum Stake Per Transaction:** 0.005 BTC
* 🔓 **Maximum Stake Per Transaction:** 5,000 BTC
* 🏆 **Rewards:**
  * First 300 BTC blocks: 100,000 points per block
  * Remaining 700 BTC blocks: 21,000 points per block

{% hint style="info" %}
You can view your BTC stake by connecting your compatible wallet to the [Staking Terminal](https://www.stakingrewards.com/terminal).

After you submit your stake, it will require 10 additional BTC blocks to pass in order for your stake to transition from _pending_ to _active_, at which point it will begin earning BBN points. &#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-10 at 2.40.46 PM.png" alt=""><figcaption><p>Example of a BTC stake passing the required blocks to become active.</p></figcaption></figure>

***

### Babylon vs BabylonChain

Babylon is a Bitcoin Staking Protocol that provides shared security for PoS systems and allows Bitcoin holders to delegate their BTC to Finality Providers, (_similar to Validators in other contexts_) who can then provide Bitcoin security to a consumer PoS chain or DA (Data Availability) layer.

BabylonChain, on the other hand, is built on the Cosmos SDK which receives security from the Babylon Bitcoin Staking Protocol and acts as the first chain that Finality Providers can support.&#x20;

However, Babylon plans to support different PoS systems from various blockchain ecosystems and provide them access to shared security collateral via staked BTC.

***

### Mechanisms of Babylon&#x20;

{% tabs %}
{% tab title="Overview" %}
The Babylon protocol operates as a modular plug-in compatible with various PoS consensus protocols, serving as a foundational component for building restaking protocols. The core component, the 'control plane' (Babylon Chain), manages several critical functions:

* **Timestamping Service:** Ensures synchronization with the Bitcoin network.
* **Stake Matching:** Matches Bitcoin stakes with PoS chains and tracks staking/validation information.
* **Finality Signature Recording:** Records the finality signatures of PoS chains.
{% endtab %}

{% tab title="Timestamping" %}
Timestamping involves embedding data at a specific point in time. Babylon records PoS chain data onto Bitcoin to leverage Bitcoin’s robust PoW security. Due to Bitcoin’s expensive and limited blockspace, direct timestamping of every PoS chain onto Bitcoin is impractical.&#x20;

Instead, the 'control plane,' implemented as a Cosmos-SDK chain (aka Babylon Chain), aggregates timestamps from all PoS chains via IBC. This ensures a secure and immutable record of PoS data on the Bitcoin blockchain.
{% endtab %}

{% tab title="Staking Process" %}
To stake, a Bitcoin staker (e.g., Alice) sends a special transaction to the Bitcoin blockchain, locking her BTC in a self-custodial vault. This vault, defined by Bitcoin's scripting language, has three transaction types:

* **Unbonding Transaction:** Allows Alice to retrieve her Bitcoin after a predefined period once she initiates the unbonding process.
* **Slashing Transaction:** Sends the Bitcoin to a burn address if Alice violates the PoS protocol.
* **Withdraw Transaction:** Allows withdrawal after the staking period is complete, provided no violations have occurred.

Alice delegates her staking duties to a finality provider on the Babylon chain, who uses their private keys to validate the PoS chain on her behalf. This delegation maintains Alice's control over her Bitcoin while enabling participation in PoS validation.
{% endtab %}

{% tab title="Security Guarantees" %}
Babylon ensures validators are accountable for their actions through cryptographic mechanisms like Extractable One-Time Signatures (EOTS). EOTS allows the network to detect and prove double-signing, exposing the validator's private key. This key, which is already pre-signed by the staker and the finality provider, is used to create a slashing transaction, burning the staked Bitcoin as a penalty. Babylon's protocol guarantees that a block is truly final only when it has received EOTS from at least 2/3 of the staked BTC.

A simplified transaction flow on Babylon would roughly look like this:

<figure><img src="../../.gitbook/assets/babylon security.png" alt="" width="563"><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

***

## How to stake BTC with Babylon

This guide will show you how to stake your Bitcoin (BTC) to Babylon via Chorus One’s Finality Provider using [Babylon Lab's Staking Interface](https://btcstaking.babylonlabs.io/?ref=chorus.one) or you can use the [Chorus One BTC Staking Dashboard](https://www.stakingrewards.com/stake-app?input=bitcoin\&type=babylon-staking\&provider=chorus-one\&locked=true).

Bitcoin (BTC) staking on Babylon was first activated at BTC block height `857909`.&#x20;

{% hint style="info" %}
**The initial staking cap for Babylon’s Phase 1 was 1,000 BTC and is now closed.**&#x20;

**Phase 2 opened in early October 2024. This slot has also now filled.**&#x20;

**Phase 3 opened on December 10th 2024 and will be open for 1,000 BTC blocks (\~1 week)**&#x20;

* Minimum BTC stake per transaction: 0.005 BTC
* Maximum BTC stake per transaction:  5,000 BTC
{% endhint %}

***

### **1.) Set up your Supported Bitcoin Wallet**

Currently the Babylon Foundation recommends using the [OKX wallet](https://www.okx.com/web3), although other wallets are possible. The OKX browser extension can be found [here](https://chromewebstore.google.com/detail/okx-wallet/mcohilncbfahbmgdjkbpemcciiolgcge).

<details>

<summary>Other Supported Wallets</summary>

**Browser Wallets:**

* OKX Wallet
* UniSat
* Leather
* Phantom
* Magic Eden
* Fordefi (select UniSat in the wallet selector)

**Hardware Wallets:**

* OneKey
* Keystone

</details>

{% hint style="warning" %}
Hardware wallets are not supported at this time, _**except**_ for the Keystone wallet via QR code or the OneKey.
{% endhint %}

**A few important warnings:**&#x20;

{% hint style="danger" %}
Using other hardware wallets through any means (such as connection to a software/extension/mobile wallet) can lead to permanent inability to withdraw the stake.

Also, please do not connect or use a Bitcoin wallet holding BRC-20, ARC-20, Runes, or other NFTs or Bitcoin-native assets (other than BTC).&#x20;

Failure to do so could result in the loss of those assets.&#x20;
{% endhint %}

Begin by installing the [OKX wallet browser extension](https://www.okx.com/web3), setting up a seed phrase (which should be stored securely) and then deposit your BTC before proceeding to the next step.

{% hint style="warning" %}
**When setting up and funding your OKX wallet, it is important to remember:**

**Do not use** a hardware a wallet such as Ledger (_exception Keystone via QR code_) either directly or through other software wallets.

**Do not use** a wallet that holds any Bitcoin Inscriptions.

Please be sure to use either **Native Segwit** or **Taproot** address formats.
{% endhint %}

***

### **2.) Connect your Wallet**

Navigate to [Babylon's staking interface via Chorus One](https://btcstaking.babylonlabs.io/?ref=chorus.one) or use the [Chorus One BTC Staking Dashboard](https://www.stakingrewards.com/stake-app?input=bitcoin\&type=babylon-staking\&provider=chorus-one\&locked=true) via Staking Rewards.&#x20;

{% hint style="info" %}
The guide below covers the steps performed via Babylon Labs.

For the steps performed via the Staking Rewards interface, please see [this guide](https://chorus.one/articles/babylon-cap-3-is-live-stake-your-bitcoin-btc-with-chorus-one).&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-08 at 1.14.01 PM.png" alt=""><figcaption><p>Example of the BTC staking interface.</p></figcaption></figure>

Connect your wallet by clicking on the orange button in the bottom-right of the screen.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-08 at 1.13.50 PM.png" alt="" width="375"><figcaption></figcaption></figure>

Next you will be prompted to review and accept the terms then choose the [OKX wallet](https://chromewebstore.google.com/detail/okx-wallet/mcohilncbfahbmgdjkbpemcciiolgcge?hl=en) to connect.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-08 at 1.13.33 PM.png" alt="" width="563"><figcaption><p>Review and accept the terms, then select OKX, then click connect.</p></figcaption></figure>

***

### 3.) Begin staking your BTC

Next you will see your wallet connected to the interface. This will give you a readout of your previous staking history, TVL, time left in the staking window (_if applicable_) and other finality providers to choose from.&#x20;

You will also see a section titled 'Step 2: Set up staking terms'&#x20;

* This will be where you can choose how much BTC with wish to stake&#x20;
* There may be a minimum amount required to stake.

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-08 at 12.53.50 PM.png" alt=""><figcaption><p>Example of the Babylon dashboard after connecting the OKX wallet.</p></figcaption></figure>

Next, you will want to enter how much BTC you wish to stake and which finality provider to use.

{% hint style="info" %}
Note: If you recently received BTC to your OKX wallet, it will need to be confirmed on the network before you can stake it.&#x20;
{% endhint %}

Shown below, you can use the search bar to look for Chorus One.

Simply click on it to select it as your finality provider, then enter the amount of BTC you wish to stake.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-08 at 1.14.54 PM.png" alt=""><figcaption><p>Example of Chorus One selected and preparing to stake 0.005 BTC.</p></figcaption></figure>

To begin your stake, click on 'Preview' which will prompt you to review and sign the transaction.&#x20;

{% hint style="info" %}
**Note:** Network fees can often spike when many users are trying to stake BTC at one.&#x20;

It is advisable to select 'Use Custom' directly about the 'Preview' button to set a custom fee well about the current sat/VB fee rate listed on [Mempool](https://mempool.space/).  (_example shown below_)
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-08 at 1.54.00 PM.png" alt="" width="563"><figcaption><p>Here's where you can see the current fee rate on Mempool. </p></figcaption></figure>

Once you've clicked on 'Preview' to begin submitting the transaction, you will be given a chance to review and approve the transaction.&#x20;

* The maximum staking time is 65 weeks, after which your BTC will be unstaked.
* Once you stake is accepted, you can remove it at any time by initiating a 7 day unbonding period.&#x20;

{% hint style="info" %}
Once your initial BTC staking transaction is confirmed, it will require 10 more BTC blocks to pass before you will start earning BBN points for your stake.&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-08 at 1.15.22 PM.png" alt=""><figcaption><p>Example of the staking confirmation and informational window. </p></figcaption></figure>

After clicking 'Stake' you will be prompted to approve and sign the transaction in your OKX wallet.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-08 at 1.15.37 PM.png" alt="" width="357"><figcaption><p>Example of the transaction approval screen in OKX.</p></figcaption></figure>

{% hint style="success" %}
Simply click 'Confirm' and your transaction will be submitted! &#x20;
{% endhint %}

***

### 4.) Reviewing your staking transaction

Once you've submitted your transaction, you will see the Babylon dashboard again.&#x20;

Under the section titled 'Staking history' you will see your pending stake.&#x20;

{% hint style="info" %}
**Please note that your stake will remain pending until it reaches 10 block confirmations.**&#x20;

This is why it is important that if there is any time window limitation, please set your transaction fees higher than normal to ensure your BTC stake is accepted in time.&#x20;

As long as it reaches 1 confirmation before any applicable staking window closes, you will be good to go!&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-08 at 1.17.20 PM.png" alt=""><figcaption><p>Example of the Babylon dashboard after submitting a BTC staking transaction.</p></figcaption></figure>

Below we can see the staking history in depth.&#x20;

{% hint style="info" %}
Please note that your stake will remain as pending until your transaction reaches 10 BTC block confirmations.&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-08 at 1.17.54 PM.png" alt=""><figcaption><p>Example of a staking transaction still waiting to reach 10 confirmations. </p></figcaption></figure>

After 10 BTC block confirmation have been reached, your stake will change to active, and you will also see the 'Unbond' button become available.&#x20;

This can be used to unstake your BTC and initiate to 7 day unbonding period.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-08 at 3.55.49 PM.png" alt=""><figcaption><p>Example of a successfully accepted BTC staking transaction.</p></figcaption></figure>

***

### 5.) Reviewing your staked balances

You can review your staked balances from the [Babylon dashboard](https://btcstaking.babylonlabs.io/?ref=chorus.one) after connecting your OKX wallet.&#x20;

Alternatively you can use the [Staking Rewards Dashboard](https://www.stakingrewards.com/terminal/dashboard) to review your active BTC staking. (shown below)

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-10 at 3.10.31 PM.png" alt=""><figcaption><p>Example of the Staking Rewards Dashboard to view your stake.</p></figcaption></figure>

Below you can see and example of the Babylon Labs dashboard which shows:

1. Total network metrics along the top row of the dashboard.
2. Your staking summary along the second row of the dashboard.
3. Staking finality providers in the middle.
4. Your staking history towards the bottom of the dashboard.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-08 at 3.55.33 PM.png" alt=""><figcaption><p>Example of the Babylon dashboard with an active BTC stake. </p></figcaption></figure>

***

### 6.) Unstaking your BTC from Babylon

To unstake your BTC from Babylon, simply navigate to your staking history and click on 'Unbond'.&#x20;

You will then be prompted with a message about the details on the unbonding transaction.&#x20;

{% hint style="info" %}
The unbonding period is 1,008 BTC blocks (\~7 days).
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-08 at 4.03.26 PM.png" alt="" width="563"><figcaption><p>Example of the unbonding confirmation screen.</p></figcaption></figure>

If you wish to unstake, click on 'Proceed' and your OKX wallet will prompt you with a transaction to sign, illustrated below.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-08 at 4.03.42 PM.png" alt="" width="351"><figcaption><p>Example of an unstaking approval transaction.</p></figcaption></figure>

To begin your unstaking, approve the transaction. Your BTC will begin the 7 day unbonding process, after which you will be able to withdraw your BTC from the Babylon Labs interface or the Staking Rewards Dashboard.&#x20;

{% hint style="success" %}
And that's it! You've successfully unstaked your BTC from Babylon.
{% endhint %}

***

## A Note to Institutional Investors:

If you are an institutional investor looking to stake BTC through Babylon with Chorus One, please reach out to us via our [staking request form](https://shorturl.at/znows) or at staking@chorus.one

{% include "../../.gitbook/includes/about-c1-dropdown.md" %}
