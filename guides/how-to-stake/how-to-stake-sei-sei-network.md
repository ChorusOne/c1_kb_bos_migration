---
description: Everything you need to know to stake SEI with Chorus One.
hidden: true
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/guides/how-to-stake/how-to-stake-sei-sei-network
---

# How to stake SEI (Sei Network)

## Overview of the Sei Network

Sei is a high-performance Layer 1 blockchain designed specifically for trading applications. With its innovative parallel order execution and native price oracles, Sei is optimized for decentralized exchanges (DEXs) and other trading-focused dApps.

By staking SEI, you contribute to the security and scalability of this cutting-edge blockchain while earning staking rewards.

{% hint style="info" %}
SEI is also unique in that is has both IBC compatibility and EVM compatibility.&#x20;

This means that each Sei address in Sei V2 has a corresponding EVM / 0x address, and vice versa. When you use Sei V2 for the first time, it is necessary to link these two addresses.

You can link your Sei and EVM / 0x addresses using the Sei app: [https://app.sei.io/](https://app.sei.io/)

:arrow\_forward: **It is recommended to store your SEI on the SEI native address as this is what you will stake from.**&#x20;
{% endhint %}

This means that every account on the Sei Network has a unique public key. In Sei V2, this public key translates into two different types of addresses:

* **EVM Address**: This address starts with `0x` and is used for EVM-based activities.
* **SEI Address**: This address starts with `sei` and is used for Sei-native activities.

{% hint style="warning" %}
**Please note:** You cannot decide which Sei and 0x addresses are linked together. Each Sei account has exactly one specific Sei address, and one specific EVM / 0x address, associated with it. They are like 2 sides of the same coin, and cannot be combined with other addresses.

To learn more, please reference the SEI technical docs: [https://www.docs.sei.io/user-guides/linking-addresses](https://www.docs.sei.io/user-guides/linking-addresses)
{% endhint %}

***

## Staking Summary

<table data-header-hidden><thead><tr><th width="280"></th><th></th></tr></thead><tbody><tr><td><mark style="color:blue;"><strong>Category</strong></mark></td><td><mark style="color:blue;"><strong>Details</strong></mark></td></tr><tr><td><strong>Minimum Stake</strong></td><td>No minimum requirement</td></tr><tr><td><strong>Unbonding Period</strong></td><td>SEI undergoes a 21 day unbonding period</td></tr><tr><td><strong>Rewards Payout</strong></td><td>Rewards are distributed block-by-block and do not auto-compound. They can be claimed and added to your stake.</td></tr><tr><td><strong>Recommended Block Explorer</strong></td><td><a href="https://seistream.app/">https://seistream.app/</a> or <a href="https://www.seiscan.app/">https://www.seiscan.app/</a></td></tr><tr><td><strong>Recommended Wallets</strong></td><td><a href="../../wallets/wallets/getting-started-metamask.md">MetaMask</a>, <a href="https://www.keplr.app/get">Keplr</a>, <a href="../../wallets/wallets/getting-started-cosmostation-wallet.md">Cosmostation</a>, or any wallet in <a href="https://www.docs.sei.io/dev-ecosystem-providers/wallets#recommended-wallets">this list</a></td></tr><tr><td><strong>Chorus One Validator</strong></td><td><a href="https://seistream.app/validators/seivaloper16pj5gljqnqs0ajxakccfjhu05yczp98743ctgy">seivaloper16pj5gljqnqs0ajxakccfjhu05yczp98743ctgy</a></td></tr><tr><td><strong>APY</strong></td><td>Please review <a href="https://www.stakingrewards.com/earn/sei-network">Staking Rewards</a> for current rates</td></tr><tr><td><strong>Managing Your Stake</strong></td><td><a href="https://app.sei.io/">https://app.sei.io/</a></td></tr><tr><td><strong>SEI Technical Docs</strong></td><td><a href="https://www.docs.sei.io/">https://www.docs.sei.io/</a></td></tr></tbody></table>

***

### Prerequisite Checklist

{% hint style="info" %}
Before you start staking SEI, ensure you have the following:

* **Compatible Wallet**: A wallet that supports SEI staking, such as [MetaMask](https://metamask.io/download/), [Keplr](https://www.keplr.app/get), or [Cosmostation](https://www.cosmostation.io/products/cosmostation_extension).
* **SEI Tokens**: Ensure you have SEI tokens in your wallet for staking and transaction fees.
* **Chorus One Validator**: Locate the official [Chorus One Validator Address](https://seistream.app/validators/seivaloper16pj5gljqnqs0ajxakccfjhu05yczp98743ctgy).
* **Block Explorer**: Use [https://seistream.app/](https://seistream.app/)  or to verify transactions and validator details.
* **Staking Rewards Info**: Check [Staking Rewards](https://www.stakingrewards.com/earn/sei-network) for the latest APY rates.
{% endhint %}

#### For more details, please refer to the [FAQs](how-to-stake-sei-sei-network.md#faqs).

***

## Step-by-Step Guide

### Step 1: Set Up Your Wallet

1. Download and install a compatible wallet, MetaMask is recommended.&#x20;

* [MetaMask](https://metamask.io/download/) — [getting-started-metamask.md](../../wallets/wallets/getting-started-metamask.md "mention")
* [Keplr](https://www.keplr.app/get) — [getting-started-keplr-wallet.md](../../wallets/wallets/getting-started-keplr-wallet.md "mention")
* [Cosmostation](https://www.cosmostation.io/products/cosmostation_extension) — [getting-started-cosmostation-wallet.md](../../wallets/wallets/getting-started-cosmostation-wallet.md "mention")

1. Create a new wallet and securely store your recovery phrase.
   1. For additional security information please see [what-is-a-seed-phrase.md](../faqs/what-is-a-seed-phrase.md "mention")and [crypto-security-best-practices.md](../faqs/crypto-security-best-practices.md "mention")
2. [Transfer SEI tokens to your wallet](https://www.docs.sei.io/user-guides/getting-tokens).

***

### Step 2: Access the Staking Interface

1. For this guide we will be demonstrating the process with [MetaMask](https://metamask.io/download/).
2. Navigate to [https://app.sei.io/](https://app.sei.io/) and connect your wallet.&#x20;
   1. For SEI, special instructions on adding the network to MetaMask can be [found here](https://www.docs.sei.io/user-guides/wallet-setup) if needed, however, when you first connect MetaMask to the staking interface it will automatically add the needed network information for you.&#x20;
3. Alternatively, you can navigate to [https://seistream.app/](https://seistream.app/) click on the left-hand column 'Stake' then search for Chorus One.
   1. If you are using [https://seistream.app/](https://seistream.app/) you can search for the Chorus One validator address `seivaloper16pj5gljqnqs0ajxakccfjhu05yczp98743ctgy`
   2. If you are using [https://seistream.app/](https://seistream.app/) please ensure that the SEI mainnet 'pacific-1' is selected in the upper-right hand corner of the screen where you will see your wallet connected.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-02 at 7.25.51 PM.png" alt=""><figcaption><p>Example of <a href="https://seistream.app/">https://seistream.app/</a> locating the Chorus One validator.</p></figcaption></figure>

If you're using [https://app.sei.io/](https://app.sei.io/) you will be prompted to connect with MetaMask. After, you can click the address in the upper-right hand corner to see your EVM (0x) address and your SEI address.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-02 at 8.27.58 PM.png" alt=""><figcaption><p>Example of the staking dashboard on <a href="https://app.sei.io/">https://app.sei.io/</a> highlighting both addresses.</p></figcaption></figure>

***

### Step 3: Select the Chorus One Validator

1. Search for the **Chorus One Validator** using the official [Chorus One Validator Address](https://seistream.app/validators/seivaloper16pj5gljqnqs0ajxakccfjhu05yczp98743ctgy).
   1. `sei16pj5gljqnqs0ajxakccfjhu05yczp987t7f9f5`
   2. If you are using [https://app.sei.io/](https://app.sei.io/) click on 'Stake' in the left side bar and look for Chorus One.
2. Click on the validator to select it.
   1. Example below showing the [https://seistream.app/](https://seistream.app/) delegation screen.

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-02 at 8.51.50 PM.png" alt=""><figcaption><p>Example of the <a href="https://seistream.app/">https://seistream.app/</a> Chorus One delegation screen.</p></figcaption></figure>

***

### Step 4: Delegate Your SEI Tokens

1. Enter the amount of SEI you wish to stake.
2. Review the transaction details, ensuring the validator is set to Chorus One.
3. Confirm the transaction in your wallet.

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-02 at 9.01.01 PM.png" alt="" width="432"><figcaption><p>Example of the delegation confirmation screen.</p></figcaption></figure>

When you're ready, click on 'Delegate' and approve the transaction in MetaMask.

{% hint style="warning" %}
It is recommended to leave a small amount of SEI in your wallet to pay for any future gas fees.&#x20;
{% endhint %}

***

### Step 5: Managing Your Delegation

1. Once the transaction is confirmed, your SEI tokens will be staked, and you will start earning rewards.
2. Check the [Staking Dashboard](https://app.sei.io/) at [https://app.sei.io/](https://app.sei.io/) by connecting your MetaMask wallet to review your staked balances and claim your staking rewards as they accrue.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-02 at 9.07.44 PM.png" alt=""><figcaption><p>Example of the staking dashboard found at <a href="https://app.sei.io/">https://app.sei.io/</a></p></figcaption></figure>

***

### Step 6: Claiming Rewards & Unstaking Your SEI

#### **Claiming Rewards**:&#x20;

* Over time you will accrue rewards from your staked SEI.&#x20;
* Navigate to [https://app.sei.io/stake](https://app.sei.io/stake) and you can view any pending rewards you can claim.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-02 at 9.09.00 PM.png" alt=""><figcaption><p>Example of the rewards claim dashboard found at <a href="https://app.sei.io/stake">https://app.sei.io/stake</a></p></figcaption></figure>

#### **Unstaking**:&#x20;

To unstake your SEI, navigate to the same [staking interface](https://app.sei.io/stake) and click on the three vertical dots next to 'Claim rewards' and from the dropdown menu select 'Unstake'.

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-02 at 9.11.22 PM.png" alt=""><figcaption></figcaption></figure>

Select the amount of SEI you would like to unstake and submit and approve the transaction in your wallet.&#x20;

* You can also redelegate your staked balance to another validator if you wish.&#x20;

{% hint style="warning" %}
Please note: There is a 21 day unbonding period when you unstake your SEI.
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-02 at 9.15.28 PM.png" alt="" width="459"><figcaption><p>Example of the unstaking confirmation screen.</p></figcaption></figure>

Once you've completed your unstaking transaction, you're all set! Your SEI will begin unstaking and will become available after the 21 day unbonding period has passed.&#x20;

You can view your SEI unbonding period in progress from the [staking dashboard](https://app.sei.io/stake).&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-02 at 9.17.54 PM.png" alt=""><figcaption><p>Example of a SEI unbonding transaction in progress.</p></figcaption></figure>

***

### FAQs

#### 1. What are the staking rewards for SEI?

Staking rewards depend on network parameters and validator performance. Check [Staking Rewards](https://www.stakingrewards.com/earn/sei-network) for the latest APY rates.

#### 2. Is there a lock-up period for SEI staking?

Yes, there is a 21-day unbonding period when unstaking SEI tokens.

#### 3. Do staking rewards auto-compound?

No, staking rewards must be manually claimed and can then be added to your staked balance.&#x20;

***

{% include "../../.gitbook/includes/questions.md" %}

***

## A Note to Institutional Investors

If you are an institutional investor looking to stake Sei Network (SEI) with Chorus One, please reach out to us via our [staking request form](https://shorturl.at/znows).&#x20;

{% include "../../.gitbook/includes/about-c1-dropdown.md" %}
