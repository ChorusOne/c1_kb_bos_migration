---
description: Everything you need to know to stake your NYM with Chorus One.
hidden: true
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/guides/how-to-stake/how-to-stake-nym-nym
---

# ⁉️ How to stake NYM (Nym)

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-03 at 8.37.16 PM.png" alt=""><figcaption><p>Source: <a href="https://nymtech.net/about/mission">https://nymtech.net/about/mission</a></p></figcaption></figure>

## Overview <a href="#h_01hc8bmw88thcadazdzytpfj3f" id="h_01hc8bmw88thcadazdzytpfj3f"></a>

<table data-header-hidden><thead><tr><th width="218"></th><th></th></tr></thead><tbody><tr><td><mark style="color:blue;"><strong>CATEGORY</strong></mark></td><td><mark style="color:blue;"><strong>DETAILS</strong></mark></td></tr><tr><td><strong>Chorus One Validator</strong></td><td><a href="https://www.mintscan.io/nyx/validators/nvaloper15urq2dtp9qce4fyc85m6upwm9xul3049ckp6x4">nvaloper15urq2dtp9qce4fyc85m6upwm9xul3049ckp6x4</a> </td></tr><tr><td><strong>Recommended Wallet</strong></td><td><a href="../../wallets/wallets/getting-started-nym-wallet.md">NYM Wallet</a></td></tr><tr><td><strong>Block Explorers</strong></td><td><a href="https://nym.explorers.guru/">https://nym.explorers.guru/</a> or <a href="https://explorer.nymtech.net/">https://explorer.nymtech.net/</a></td></tr><tr><td><strong>Staking Rewards</strong></td><td><a href="https://www.stakingrewards.com/asset/nym">https://www.stakingrewards.com/asset/nym</a></td></tr><tr><td><strong>Unstaking Period</strong></td><td>______❓</td></tr></tbody></table>

## About Nym

**Nym (NYM)** is a decentralized privacy platform that protects users’ data and metadata across the network and application layers. Its core components include the Nym mixnet, which anonymizes communication by encrypting and mixing data to obfuscate metadata, and Nym credentials, which enable private authentication through zero-knowledge proofs. Together, these tools enhance privacy for users and support applications in the broader blockchain ecosystem.

Nym also introduced the NymVPN which is a decentralized VPN built on the Nym network, designed to eliminate single points of failure and provide strong privacy protections. It offers two modes: a high-speed VPN mode for everyday use and a Mixnet mode for comprehensive metadata protection. Additionally, zk-nym credentials enable private, trace-free payments, ensuring a higher level of online privacy.

***

## How Staking Works on NYM

In the Nym ecosystem, there are two tokens involved with staking — **NYM** and **NYX** which serve different purposes related to staking.

* **NYM** is the primary token and **NYX** functions as a derivative.&#x20;

Anyone with NYM tokens can delegate them to a mix node using either the CLI or the [NYM wallet](../../wallets/wallets/getting-started-nym-wallet.md) to earn a portion of the node’s rewards. Even tokens locked in a vesting contract can be delegated, allowing you to earn rewards while your NYM tokens are still vesting if this is applicable to your situation.&#x20;

{% hint style="info" %}
There is no minimum delegation amount, so you can participate and earn rewards regardless of how much NYM you hold.
{% endhint %}

When you delegate to a mix node, you help boost its reputation, which is based on the node’s total stake. This includes the operator’s bond and all delegated stakes. A higher reputation increases the node’s likelihood of being chosen for rewards and improves its reward rate.

By delegating your stake, you support the node in becoming part of the reward and active sets, thus maximizing its earning potential.

***

### Understanding NYM and NYX

{% tabs %}
{% tab title="NYM (Native Token)" %}
**Purpose:** NYM is the main token of the Nym ecosystem, used for staking, rewards, and paying for network services.

**Staking:** NYM is staked directly on mix nodes to secure the network and provide privacy services. Stakers earn rewards proportional to their stake and the performance of the mix nodes.

**Utility:** Besides staking, NYM is used for governance and transaction fees within the network.
{% endtab %}

{% tab title="NYX (Liquid Staking Derivative)" %}
**Purpose:** NYX is a liquid staking derivative token issued when you stake NYM. It represents your staked NYM and the rewards it accrues over time.

**Staking Mechanism:** When you stake NYM using a liquid staking mechanism, you receive NYX tokens in return, which can be freely traded or used in DeFi applications while your NYM remains staked.

**Benefits & Flexibility:** NYX allows you to access the value of your staked NYM without waiting for the unstaking period.

**Composability:** You can use NYX in other decentralized finance (DeFi) protocols for additional yield or liquidity options.
{% endtab %}
{% endtabs %}

{% hint style="info" %}
In short, NYM is the token you stake to secure the network, while NYX is a derivative that allows you to retain liquidity and participate in additional financial activities without losing staking rewards.
{% endhint %}

***

### Prerequisite Checklist

Before you start staking NYM, ensure you have the following:

* **Supported Wallet**: [NYM Wallet](../../wallets/wallets/getting-started-nym-wallet.md) will be necessary to use.&#x20;
* **NYM Tokens**: Ensure you have NYM tokens in your wallet for staking and a small amount for transaction fees.
* **Chorus One Validator**: Locate the Chorus One validator address in [https://ping.pub/nyx/staking](https://ping.pub/nyx/staking)
  * Address: nvaloper15urq2dtp9qce4fyc85m6upwm9xul3049ckp6x4
  * [Direct link to the Chorus One validator](https://ping.pub/nyx/staking/nvaloper15urq2dtp9qce4fyc85m6upwm9xul3049ckp6x4)

***

## How to Stake NYM <a href="#h_01hcdmyz7c17s7x9rzvke00phe" id="h_01hcdmyz7c17s7x9rzvke00phe"></a>

### Step 1. Install the NYM Wallet <a href="#h_01hcdmyz7cbe2a0abfyckedy76" id="h_01hcdmyz7cbe2a0abfyckedy76"></a>

For the focus of this guide we recommend using the [official NYM Wallet](https://nymtech.net/download/wallet).&#x20;

If you don't yet have a NYM wallet setup, please see: [getting-started-nym-wallet.md](../../wallets/wallets/getting-started-nym-wallet.md "mention")

If you already have a wallet installed, feel free to skip ahead to [Step 3: Stake your NYM](how-to-stake-nym-nym.md#h_01hc8b1t0xqz8tdapbp8g98nkt)

***

### Step 2. Locate the Chorus One Validator <a href="#h_01hc8b1t0x9e4fj4j73357dgbw" id="h_01hc8b1t0x9e4fj4j73357dgbw"></a>

Navigate to [https://ping.pub/nyx/staking](https://ping.pub/nyx/staking) and either scroll through the list to find Chorus One, or navigate directly to the [Chorus One validator](https://ping.pub/nyx/staking/nvaloper15urq2dtp9qce4fyc85m6upwm9xul3049ckp6x4).&#x20;

Connect your wallet to the PingPub by clicking on wallet icon in the upper-right hand corner of your screen.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-03 at 9.04.33 PM.png" alt=""><figcaption></figcaption></figure>

You will be prompted to connect with a compatible wallet such as Keplr or Leap. Choose whichever wallet you are currently using.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-03 at 9.06.04 PM.png" alt="" width="384"><figcaption><p>PingPub wallet connect screen</p></figcaption></figure>

Once you've connected your wallet, if you haven't added the NYM network to Keplr already, you will be prompted to do so.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-03 at 9.07.51 PM.png" alt="" width="263"><figcaption><p>Keplr Nym/Nyx approval request</p></figcaption></figure>

Go ahead and accept the connection and at this point if you have not done so already, send some NYM to your wallet that you wish to stake.&#x20;

***

### Step 3. Stake your NYM <a href="#h_01hc8b1t0xqz8tdapbp8g98nkt" id="h_01hc8b1t0xqz8tdapbp8g98nkt"></a>

Next, make sure you have the [Chorus One NYM validator](https://ping.pub/nyx/staking/nvaloper15urq2dtp9qce4fyc85m6upwm9xul3049ckp6x4) address from PingPub.

* [https://ping.pub/nyx/staking/nvaloper15urq2dtp9qce4fyc85m6upwm9xul3049ckp6x4](https://ping.pub/nyx/staking/nvaloper15urq2dtp9qce4fyc85m6upwm9xul3049ckp6x4)
* `nvaloper15urq2dtp9qce4fyc85m6upwm9xul3049ckp6x4`

From your NYM wallet, click on 'Delegate'.

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-03 at 10.15.06 PM.png" alt=""><figcaption></figcaption></figure>

Next you will be prompted with some information about delegation.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-03 at 10.17.59 PM.png" alt=""><figcaption></figcaption></figure>

When you click on 'Delegate' you will be prompted with the following and need to supply the required information to stake to Chorus One.&#x20;

* The Node Identity Key
  * Chorus One: `34RqwDf7nGcJQxoNMT83ZrdZNCMsAAztm7sKFcyMXaB4`
* The amount of NYM you wish to stake (10 NYM minimum)

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-03 at 10.19.18 PM.png" alt="" width="469"><figcaption></figcaption></figure>

When staking NYM via the NYM wallet, you must select a mix node to delegate to. The wallet uses the node’s identity key to ensure your delegation is applied to the correct node, (in this case Chorus One) which then earns rewards for your NYM stake.





Simply click on 'Delegate' and you can begin the process to stake your NYM.

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-03 at 9.11.37 PM.png" alt=""><figcaption><p>Chorus One validator staking screen on PingPub</p></figcaption></figure>

### Step 4. Managing your NYM Stake <a href="#h_01hc8b1t0x326w2f4nzezyfjz6" id="h_01hc8b1t0x326w2f4nzezyfjz6"></a>

\>>



{% hint style="info" %}
Please note that there is a \_\_\_\_ day unbonding process (also known as unstaking) for NYM.

During this period your stake no longer earns rewards and cannot be transferred, exchanged, or spent.

However, you can cancel the unstaking process if you wish without penalty.&#x20;
{% endhint %}

***

### Step 5. Claiming NYM Rewards <a href="#h_01hc8b1t0xyhfh6z6pc14htt2d" id="h_01hc8b1t0xyhfh6z6pc14htt2d"></a>

After some time you will see rewards accumulating in your NYM wallet.&#x20;

\>>>



{% hint style="success" %}
You can simply go to the NYM Wallet interface to claim them by selecting 'Claim' and approving the transaction.&#x20;
{% endhint %}

***

### Step 6. Unstaking your NYM

If you wish to unstake your NYM, you can do so from the NYM Wallet that you used to stake.&#x20;

\>>> Further instructions pending

{% hint style="warning" %}
Please note that NYM undergoes a \_\_\_\_ day unbonding period when unstaking.&#x20;
{% endhint %}

To proceed, click on 'Unstake' and follow the prompts to select the amount of NYM you wish to unstake.

Then confirm and sign the transaction in your wallet.&#x20;

{% hint style="success" %}
And that's it! Your NYM will begin unbonding which you can track from your wallet.

After the unbonding period is complete you will be able to transact with your unstaked NYM.&#x20;
{% endhint %}

***

{% include "../../.gitbook/includes/questions.md" %}

***

## A Note to Institutional Investors:

If you are an institutional investor looking to stake Nym (NYM) with Chorus One, please reach out to us via our [staking request form](https://shorturl.at/znows).&#x20;

{% include "../../.gitbook/includes/about-c1-dropdown.md" %}
