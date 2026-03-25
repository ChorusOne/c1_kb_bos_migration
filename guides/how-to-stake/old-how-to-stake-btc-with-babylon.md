---
description: Everything you need to know about staking BTC and how Babylon works
hidden: true
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/guides/how-to-stake/old-how-to-stake-btc-with-babylon
---

# (old) How to stake BTC with Babylon

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-09 at 8.52.37 PM.png" alt=""><figcaption></figcaption></figure>

## What is Babylon?

Babylon allows Bitcoin holders to stake their BTC for PoS blockchains without relying on third-party custody, bridges, or wrapping. Traditionally, Bitcoin has been seen as a store of value, but Babylon expands its utility by enabling Bitcoin to play an active role in securing various PoS ecosystems. This is achieved through a trust-minimized protocol that connects Bitcoin holders with the demand for network security across multiple blockchain systems, including PoS chains.&#x20;

* If you're interested, you can read our comprehensive overview of Babylon [here](https://chorus.one/articles/unlocking-bitcoins-potential-with-babylon).
* To do right into the staking guide, head to [How to Stake BTC with Babylon](old-how-to-stake-btc-with-babylon.md).

### Babylon vs Babylon Chain

Babylon is a Bitcoin Staking Protocol that provides shared security for PoS systems and allows Bitcoin holders to delegate their BTC to Finality Providers, who can then provide Bitcoin security to a consumer PoS chain or DA layer.

Babylon chain, on the other hand, is built on Cosmos SDK, which receives security from the Babylon Bitcoin Staking Protocol and acts as the first chain that Finality Providers can support. However, Babylon plans to support different PoS systems from various blockchain ecosystems and provide them access to shared security collateral with BTC.

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

## How to Stake BTC with Babylon

This guide will show you how to stake your Bitcoin (BTC) to the Babylon protocol via Chorus One’s Finality Provider using [Staking Rewards](https://www.stakingrewards.com/stake-app?input=bitcoin\&type=babylon-staking\&provider=chorus-one\&locked=true).

{% hint style="warning" %}
**The initial staking cap for Babylon’s Phase 1 was 1,000 BTC. This cap filled up very quickly  and currently no more BTC delegations are live at this time.**&#x20;

**Future BTC delegations are expected in Phase 2.**

* **You can read more about Babylon's planned phases** [**here**](https://chorus.one/articles/top-10-things-to-know-about-the-babylon-bitcoin-staking-mainnet-launch)**.**
{% endhint %}

Bitcoin (BTC) staking on Babylon was activated at BTC block height 857909.&#x20;

The cap will be raised in Phase 2, which is expected to begin 4 weeks after Phase 1 ends.

### **1.) Set up your OKX Bitcoin wallet**

Currently the [Stake App](https://www.stakingrewards.com/stake-app?input=bitcoin\&type=babylon-staking\&provider=chorus-one\&locked=true) will only support BTC staking via the [OKX wallet](https://www.okx.com/web3).&#x20;

Begin by installing the [OKX wallet browser extension](https://www.okx.com/web3) and deposit your BTC before proceeding to the next step.

{% hint style="info" %}
**Note:** When setting up and funding your OKX wallet, it is important to:

* **Not use** a hardware a wallet (such as Ledger), aside from a Keystone QR code either directly or through other software wallets.
* **Not use** a wallet that holds any Bitcoin Inscriptions.
* Be sure to choose either **Native Segwit** or **Taproot** address formats.
{% endhint %}

### **2.) Start staking BTC**

Navigate to the Chorus One’s BTC Staking Interface:

* [https://www.stakingrewards.com/stake-app?input=bitcoin\&type=babylon-staking\&provider=chorus-one\&locked=true](https://www.stakingrewards.com/stake-app?input=bitcoin\&type=babylon-staking\&provider=chorus-one\&locked=true)

<figure><img src="https://cdn.prod.website-files.com/63fdf8c863bcf00d7ffdff91/66c71c1e5a7cd3783d13875f_AD_4nXcZFOgkzp17m6KVKQPpvB94f4_065jk6Z8xDraPxNCJT6W2uBIbckzwx6XaqW4-jC9X-bXAEcBUP3rsDE3fJ7N9dJYv8zIEPJIexU5jby8jq45ziYZ31M1psxpnWEGeMfE0kKEYBKJzh4CPNnxu39Xl1S0O.png" alt=""><figcaption><p>Example of the BTC stakng interface.</p></figcaption></figure>

### ‍3.) **Connect your Bitcoin wallet**

Connect your wallet by clicking on the blue button in the center of the screen. If you’re visiting the website for the first time, you will need to sign the signature request to have your wallet connected.<br>

<figure><img src="https://cdn.prod.website-files.com/63fdf8c863bcf00d7ffdff91/66c71c1d68163a5f8b6bb125_AD_4nXd4CETJnGOnis-crN2PEQb20_xIus_Yc4055rq1SoZgIpHg3ab9QYx9yM1dYO6IVi7Jl93PKpvAdWEln2aFzyiWQ_R47ecxZGNgKwlJPjvgTYLlEPJyvzMx6MWXkroD25MSj7o6K6vcxoeknKfCTT5pd7Pv.png" alt=""><figcaption><p>Example of selecting your wallet to connect with. OKX is recommended for this guide.</p></figcaption></figure>

### **4.) Enter your BTC amount to stake**

Input the amount of BTC you want to stake. During Babylon Phase 1, it was only possible to stake between 0.005 and 0.05 BTC per transaction.

* In Phase 2, it is likely these caps will be raised.

Next, please be sure to select or switch to the correct address format in your wallet. You can see this in the screenshot below where it shows `BTC (Taproot)`.&#x20;

<figure><img src="https://cdn.prod.website-files.com/63fdf8c863bcf00d7ffdff91/66c71c1d51821ed5a6f31cf8_AD_4nXexB0VzU26FXohzUyOLYNzj8hr80qInX6vhEbRqfGCl-xD9HU1UCVIUVsQWEWOvmbsbJh-9TY7cW6ylNn6v9w7SF-Q9s48evkqPJWUaZnUE4VcyK0K0cta_wy557dV3wV2qSlQk4A1TB1_odDkfa3TLABAC.png" alt=""><figcaption><p>Example of the staking interface and ensuring the right address format is selected.</p></figcaption></figure>

### **5.) Determine the transaction fee to stake**

Next you can choose to keep the current network fee or prioritize your delegation by increasing the transaction fee. Choosing a higher transaction fee can help ensure your BTC is picked up sooner and will be added to the next BTC block.&#x20;

If a cap is active for any future Babylon staking phases and it gets filled before your BTC is accepted, it will be in the “overflow” status and you will need to unbond and withdraw your BTC.

<figure><img src="https://cdn.prod.website-files.com/63fdf8c863bcf00d7ffdff91/66c71c1eb7d300ad1b04b6eb_AD_4nXfXKWn26jNUIoEDYDgLhTJ8R0MdMgiLj6JZS8ZYsnSBw9vK7ML_S_CnTMnQnziElWDALMABTvR3bo3whZ2bC4x9_qgCyJBBM5dVzseqbkr9S5pz5Ne_Qo2RYMKJDB7rR3Tv9V6EJRpMoL4RJRPeRbNmFiLu.png" alt=""><figcaption><p>Example of choosing your BTC transaction fee rate.</p></figcaption></figure>

### **6.) Stake your BTC**

Finalize the staking process by clicking the '**Stake**' button and confirm the transaction in your wallet.

<figure><img src="https://cdn.prod.website-files.com/63fdf8c863bcf00d7ffdff91/66c71c1e80a7016917cc5358_AD_4nXc-QDyiuYhtPG4t1Dy9VCeAFHbvsGVJAz0-cwbxUuWKbviH7GatnJCzBQOhmObv6XSrmc-TNn9feIsMF7g-5-VP2hwh7IGgKwf-l6iVMxEJGVdJy_S0jggvFuxYvTSYUddjAbuQ66uYzNIZfSDV9wfYacyc.png" alt=""><figcaption><p>Example of the OKX wallet transaction confirmation screen.</p></figcaption></figure>

### **7.) Complete the staking process**

{% hint style="success" %}
Congratulations you have successfully staked your BTC to Babylon via Chorus One’s Finality Provider!

* You can now track your staked position via the [Staking Terminal](https://www.stakingrewards.com/terminal).
{% endhint %}

<figure><img src="https://cdn.prod.website-files.com/63fdf8c863bcf00d7ffdff91/66c71c1dd9f6e1572882d190_AD_4nXfTxWo0Y4iAggHzvqPc7pyRAhQr2r6Zw_H5dQSj7PRv1acvCzTNWIwMGjWntbbXl07jayRzqBqirxmfRndyXsMM_SjYjlnx75kMykWzH53602Yexgd0_dGSfWU_QLIadnRSvSfzWafHTLR4ycpCElvsAiPo.png" alt=""><figcaption><p>Example of a successful BTC staking transaction.</p></figcaption></figure>

***

## **How to Unstake Your BTC**

You can unstake your BTC and withdraw it via the [Staking Terminal](https://www.stakingrewards.com/terminal).&#x20;

There are two steps required to withdraw your BTC,

1. Submit an unbonding transaction, to enable your BTC to be withdrawn. The unbonding period takes roughly 7 days (or exactly 1,008 Bitcoin blocks as defined by the unbonding script).
2. Once unbonded you will be able to withdraw your BTC.

{% hint style="info" %}
**Note: Your BTC stake will automatically unbond after 65 weeks.**

* #### To begin the process of unstaking your BTC before this point, follow the the steps below.‍
{% endhint %}

### **1.) Go to the Staking Terminal**

Visit the [Staking Terminal](https://www.stakingrewards.com/terminal) to view your staking positions.

### **2.) Connect your Bitcoin wallet**

Connect the wallet you staked with previously. If you've been following this guide, it would have been the [OKX wallet](https://www.okx.com/web3).&#x20;

### **3.) Manage your delegations**

Navigate to the '**My Hodlings**' tab to view your staked positions.

<figure><img src="https://cdn.prod.website-files.com/63fdf8c863bcf00d7ffdff91/66c71c1e7536852548948982_AD_4nXfWvzgotyYhyTJ9sP5VKQXyZ9Fpt_jrDRfzY1DcPNo8mBOoJy0kLSexe9t0f8bZL5jQx7P3gaGBmdUS1Crl1xWT1PCvdXA5NpHVRfl7HjP4sXiwmBzOKUn6JgnYhguujK3x4cHGLzf9pCzyDck5HmhmHv4.png" alt=""><figcaption><p>Example of the Staking Terminal "My Hodlings" tab.</p></figcaption></figure>

### **4.) Unbond your BTC**

Click on position details and select '**Unbond**'.&#x20;

Next, confirm the transaction in your wallet.

<figure><img src="https://cdn.prod.website-files.com/63fdf8c863bcf00d7ffdff91/66c71c1d42d9501563416ae4_AD_4nXcvn3KFaBB1AiTgrLsnQYayG6uikUMFCPYwcdtyILGryJW4K9MpTFgu2GPWKnp19jsJMJMT6muVMXWjgRj-GaOB1GU-uqaFJ-WlTqo649aS_zQbOVdj6T_iIjwtJ2LYbCQGiNBhIEO5y6DAjlIMIGkzFhJO.png" alt=""><figcaption><p>Example of an unbonding transaction of BTC on Babylon.</p></figcaption></figure>

### **5.) Withdraw your BTC**

You can monitor your unbonded BTC via the '**Unbonding**' tab as shown below.&#x20;

Once your unbonding period of 7 days ends, you will be able to withdraw your BTC.

<figure><img src="https://cdn.prod.website-files.com/63fdf8c863bcf00d7ffdff91/66c71c1d1bebba33c771885a_AD_4nXfRWHBcnMXhXdecfec3gbnxQtXLxoHUnuLBCDQDLR6nt-wt33y_VRZ_a7Gq2g92_9NPaESSqlAAAe5onPSbEOOp9zLPxJOjF3HPEofATtIxmlNOGXbZGBKgJj4TFk-z8YsXHRzC5VB9wRS23ZPhSfBmHbZE.png" alt=""><figcaption><p>Example of a BTC unbonding transaction in progress.</p></figcaption></figure>
