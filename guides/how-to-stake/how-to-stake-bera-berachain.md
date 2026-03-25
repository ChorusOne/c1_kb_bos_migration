---
description: Everything you need to know to stake BERA with Chorus One.
hidden: true
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/guides/how-to-stake/how-to-stake-bera-berachain
---

# How to stake BERA (Berachain)

<figure><img src="../../.gitbook/assets/Screenshot 2024-11-18 at 4.19.59 PM.png" alt=""><figcaption></figcaption></figure>

***

{% hint style="success" %}
Chorus One is excited to announce that BERA staking is now possible using Chorus One validators via Bitgo. Regardless of if you're holding liquid of unvested BERA tokens, you can create your own White Label (WL) validator.&#x20;

Please reach out to us via our [staking request form](https://chorusone.my.salesforce-sites.com/WebToLead) to get started!
{% endhint %}

## Chorus One & BeraBoost

Chorus One has pioneered the [BeraBoost Algorithm](how-to-stake-bera-berachain.md#the-beraboost-algorithm) to maximize BGT rewards for stakers.&#x20;

With Berachain’s unique emission mechanics, delegators need a sophisticated strategy to maximize returns. This is where **BeraBoost** comes in—an automated allocation algorithm developed by Chorus One Research that dynamically optimizes BGT distribution to maximize rewards.

* To learn more, please see: [BeraBoost: Maximizing Chorus One Delegator Rewards](https://chorus.one/reports-research/beraboost-maximizing-chorus-one-delegator-rewards)
* Or see: [Stake BERA with Chorus One: A comprehensive overview of Berachain, Proof-of-Liquidity](https://chorus.one/articles/stake-bera-with-chorus-one-a-comprehensive-overview-of-berachain-proof-of-liquidity)

## Overview <a href="#h_01hc8bmw88thcadazdzytpfj3f" id="h_01hc8bmw88thcadazdzytpfj3f"></a>

***

<table data-header-hidden><thead><tr><th width="211"></th><th></th></tr></thead><tbody><tr><td><mark style="color:blue;"><strong>CATEGORY</strong></mark></td><td><mark style="color:blue;"><strong>DETAILS</strong></mark></td></tr><tr><td><strong>Chorus One Validator</strong></td><td><a href="https://hub.berachain.com/validators/0xab98ea73f3afab04154829f8d12a537cbf31a8b08f7f8e3870f4902001f0011234ed8f9218b40b4ed732d11d889f609d/">0xF2048c29ef806ed003dEE1ae703F00ef7340AC84</a> (Bera Hub) <br><a href="https://berascan.com/address/0xf2048c29ef806ed003dee1ae703f00ef7340ac84">0xF2048c29ef806ed003dEE1ae703F00ef7340AC84</a> (Berascan)</td></tr><tr><td><strong>Recommended Wallet</strong></td><td><a href="https://metamask.io/download/">MetaMask</a></td></tr><tr><td><strong>Block Explorer</strong></td><td><a href="https://berascan.com/">https://berascan.com/</a></td></tr><tr><td><strong>Stake with Chorus One</strong></td><td><a href="https://chorus.one/crypto-staking-networks/berachain">https://chorus.one/crypto-staking-networks/berachain</a></td></tr><tr><td><strong>Connecting to Testnet</strong></td><td><a href="https://docs.berachain.com/developers/network-configurations">https://docs.berachain.com/developers/network-configurations</a></td></tr></tbody></table>

{% hint style="warning" %}
[Bera Hub](https://hub.berachain.com/) is the central dashboard to interact with the Berachain ecosystem. Unfortunately it will not be accessible for users coming from a US-based IP address.

[https://hub.berachain.com/](https://hub.berachain.com/)
{% endhint %}

## About Berachain

**Berachain (BERA)** is revolutionizing how DeFi users interact with liquidity, optimizing applications, and enhancing flexibility within the digital economy. Built using the Cosmos SDK, Berachain introduces its novel Proof-of-Liquidity (PoL) consensus mechanism and its modular execution framework, BeaconKit, which ensures full compatibility with unmodified Ethereum Virtual Machine (EVM) execution clients.

Through the Proof-of-Liquidity (PoL) consensus mechanism, Berachain redefines traditional staking by integrating liquidity provisioning into network security and governance. Instead of requiring users to lock assets in traditional staking contracts, PoL encourages liquidity contributions to the ecosystem. This model operates with a dual-token system:

* **BERA** – The native gas token used for transaction fees and network security.&#x20;
  * Validators stake BERA to participate in securing the chain.
* **BGT** (Bera Governance Token) – A non-transferable, governance-focused token distributed to users who contribute liquidity.&#x20;
  * Users can delegate BGT to validators, influencing their rewards and emissions.

This structure aligns incentives between validators, liquidity providers, and decentralized applications (dApps) and users who supply liquidity to Berachain receive LP tokens, which can be staked to earn BGT.&#x20;

The more BGT a validator receives in delegation, the higher their emissions, reinforcing an economic model that prioritizes liquidity depth and network engagement.

{% hint style="info" %}
Chorus One has pioneered the BeraBoost Algorithm to maximize BGT rewards for stakers.&#x20;

To learn more, please see: [**BeraBoost: Maximizing Chorus One Delegator Rewards**](https://chorus.one/reports-research/beraboost-maximizing-chorus-one-delegator-rewards)
{% endhint %}

By integrating BeaconKit as its execution layer, Berachain maintains full EVM compatibility while leveraging the modular flexibility of the Cosmos SDK. This combination enhances interoperability, scalability, and the overall efficiency of DeFi applications built on the network.

Ultimately, Berachain’s approach not only addresses liquidity fragmentation but also creates a sustainable, incentive-driven model for securing and growing the DeFi ecosystem.

***

### **What is Proof of Liquidity (PoL)?**

To support the PoL model, Berachain utilizes a tri-token model comprising the Bera Governance Token (BGT), the native gas token (BERA), and Honey (HONEY).&#x20;

Each token serves a specific role:&#x20;

* **BGT** is central to governance and staking, granting holders voting rights for protocol decisions and access to rewards through whitelisted liquidity pools.
* **BERA** powers transactions within the network.&#x20;
* **HONEY** facilitates lending, borrowing, and liquidity provision, driving ecosystem activity.&#x20;

{% hint style="info" %}
BGT plays a central role in the staking process on Berachain. It grants holders governance rights, enabling them to vote on proposals that shape protocol upgrades.&#x20;
{% endhint %}

* Users can only earn BGT by participating in PoL.
* For PoL participants, BGT rewards are distributed through vaults tied to particular liquidity pools, which must first be approved and whitelisted through a governance approval process.&#x20;
  * Once a pool is whitelisted, users can contribute liquidity to these vaults and receive BGT rewards in return.

Together, this tri-token model creates a robust and dynamic economic framework that aligns network security, liquidity, and governance.&#x20;

***

## Chorus One and BeraBoost

Chorus One has been involved with the ongoing developments of Berachain and their new PoL model and is offered day one support for the mainnet launch. Alongside this, we have created a special algorithm called BeraBoost to maximize BGT rewards for PoL participants allowing Chorus One to provide infrastructure that maximizes the performance of the PoL system, ensuring that liquidity is efficiently managed while securing the network through the use of our in-house algorithm.

### The BeraBoost Algorithm:&#x20;

Chorus One optimizes rewards distribution for liquidity providers and validators on Berachain. This approach maximizes returns for BGT delegators by tracking LP positions and directs incentives to the most relevant reward vaults.

BeraBoost maximizes delegator income by strategically distributing BGT emissions to their reward vault positions. This is a sophisticated approach that takes into account nuances like vault turnover and varying incentive liquidity.&#x20;

Chorus One's BeraBoost operates on a public dashboard, providing transparent, optimized incentive capture for delegators. BeraBoost maximizes incentives taking into account delegator reward vault positions and Chorus One will continue to improve BeraBoost as the chain matures.

### How BeraBoost Works

Validators on Berachain play a crucial role in emission allocation. Delegators who stake with a validator benefit from the validator’s strategy for directing emissions to Reward Vaults.&#x20;

BeraBoost takes this a step further by:

* Algorithmically distributing emissions to maximize delegator rewards on their reward vault positions.
* Transparently directing liquidity where it is most needed.
* Reducing the complexity of staking for delegators by automating the yield-maximization process.

This mirrors how traditional DeFi yield farming strategies work but integrates them directly at the consensus level.&#x20;

As Camila Ramos highlighted in [this thread](https://x.com/camiinthisthang/status/1826692027679211689), Berachain’s PoL effectively allows users to **outsource their farming strategies to validators**, providing an avenue for both sophisticated and unsophisticated users to optimize their returns without active management.

{% hint style="info" %}
Learn more about Chorus One's BeraBoost [here](https://chorus.one/reports-research/beraboost-maximizing-chorus-one-delegator-rewards).
{% endhint %}

<figure><img src="../../.gitbook/assets/beraboost.png" alt=""><figcaption><p>Source: <a href="https://x.com/camiinthisthang/status/1826692027679211689">https://x.com/camiinthisthang/status/1826692027679211689</a></p></figcaption></figure>

***

## How to stake BERA & BGT

{% hint style="info" %}
To stake BERA, please reach out to us directly via our [staking request form](https://chorusone.my.salesforce-sites.com/WebToLead) to get started or at staking@chorus.one
{% endhint %}

To stake BGT to the [Chorus One Validator](https://hub.berachain.com/validators/0xab98ea73f3afab04154829f8d12a537cbf31a8b08f7f8e3870f4902001f0011234ed8f9218b40b4ed732d11d889f609d/), please navigate to: [https://hub.berachain.com/validators/0xab98ea73f3afab04154829f8d12a537cbf31a8b08f7f8e3870f4902001f0011234ed8f9218b40b4ed732d11d889f609d/](https://hub.berachain.com/validators/0xab98ea73f3afab04154829f8d12a537cbf31a8b08f7f8e3870f4902001f0011234ed8f9218b40b4ed732d11d889f609d/)&#x20;

* Next connect with MetaMask or another supported wallet of your choosing.&#x20;
* You will be prompted to add the Berachain Mainnet if this is your first time connecting with MetaMask.

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-10 at 12.03.32 PM.png" alt="" width="263"><figcaption></figcaption></figure>



Click on '**Boost**' to delegate BGT to the Chorus One Validator and boost it further.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-10 at 12.08.19 PM.png" alt=""><figcaption></figcaption></figure>

Follow the prompts in your wallet to complete the transaction and submit your BGT delegation to the Chorus One Validator.&#x20;

***

## How to use Bera Hub

### Swapping Tokens

Once you've acquired some BERA tokens, you can use [Bera Hub Swap](https://hub.berachain.com/swap/) to swap your BERA into different tokens you wish to provide liquidity for.  For example, let's say you wanted to provide liquidity to the BERA/HONEY pool.

First, navigate to [https://hub.berachain.com/swap/](https://hub.berachain.com/swap/) and select how much BERA you wish to swap for HONEY.&#x20;

{% hint style="info" %}
Note: When providing liquidity, you will need to provide a roughly 50/50 distribution in value of each token. For example, $100 worth of BERA and $100 worth of HONEY.&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-11-18 at 4.52.13 PM.png" alt="" width="399"><figcaption></figcaption></figure>

You will see a preview of your swap, go ahead and complete the steps by approving the transaction in your wallet.&#x20;

### Providing Liquidity to Pools

Once you have the tokens you want to provide liquidity for, navigate to '**Pools**' on Bera Hub ([https://hub.berachain.com/pools/](https://hub.berachain.com/pools/)) and provide liquidity of the token pair of your choosing.&#x20;

{% hint style="info" %}
In this example, we are using the **WBERA | HONEY** pool.&#x20;

* **Note:** When you deposit your BERA to a pool, it will become WBERA.&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-10 at 12.13.20 PM.png" alt=""><figcaption><p>Source: <a href="https://hub.berachain.com/pools/">https://hub.berachain.com/pools/</a></p></figcaption></figure>

Select the pool of your choosing and select how much liquidity to provide.&#x20;

Complete the transaction in your wallet as prompted and you will receive the LP receipt token for your pool contribution.&#x20;

### Using Vaults

Once you have an LP token from your provided liquidity pair, you can deposit it into a vault to begin earning BGT.&#x20;

First, navigate to '**Vaults**' on Bera Hub ([https://hub.berachain.com/vaults/](https://hub.berachain.com/vaults/)) to select the vault you wish to interact with.&#x20;

{% hint style="info" %}
In this case, we will be demonstrating with the WBERA | HONEY vault.&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-10 at 12.16.46 PM.png" alt=""><figcaption><p>Source: <a href="https://hub.berachain.com/vaults/">https://hub.berachain.com/vaults/</a></p></figcaption></figure>

Complete the transaction in your wallet as prompted and you will have successfully staked your LP tokens to the vault.&#x20;

This will make you eligible to start earning BGT.&#x20;

{% hint style="success" %}
And now you've successfully participated in PoL! Your receipt tokens will begin earning BGT rewards that you can claim and then stake with the [Chorus One Validator](https://hub.berachain.com/validators/0xab98ea73f3afab04154829f8d12a537cbf31a8b08f7f8e3870f4902001f0011234ed8f9218b40b4ed732d11d889f609d/).&#x20;

See: [#how-to-stake-bera-and-bgt](how-to-stake-bera-berachain.md#how-to-stake-bera-and-bgt "mention")
{% endhint %}

You can view and claim your accrued BGT from the '**Vaults**' tab on [Bera Hub](https://hub.berachain.com/vaults/).&#x20;

Please note that BGT will not be instantly earned for your LP vault token deposit, however, you will begin earning BGT from your stake in that rewards vault and can come back and claim it as it accrues.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-10 at 12.21.10 PM.png" alt="" width="534"><figcaption><p>Source: <a href="https://hub.berachain.com/vaults/">https://hub.berachain.com/vaults/</a></p></figcaption></figure>

***

### Using BGT & Converting it to BERA

As you accrue BGT rewards you can either delegate them to a validator to boost it further (Please see: [#how-to-stake-bera-and-bgt](how-to-stake-bera-berachain.md#how-to-stake-bera-and-bgt "mention")) or you can convert your BGT rewards to BERA in a 1:1 ratio.&#x20;

With that newly converted BERA you can freely hold, send, swap, or participate in PoL with it.&#x20;

{% hint style="warning" %}
Please note that BGT cannot be transferred to another wallet. It is soul bound to your wallet.&#x20;

BGT can be delegated to a validator or it can also be converted one way in a 1:1 ratio to BERA.&#x20;

Please note it is not possible to convert BERA back to BGT. This is a one way swap only.&#x20;
{% endhint %}

***

## A Note to Institutional Investors

If you are an institutional investor looking to stake Berachain (BERA) with Chorus One, please reach out to us via our [staking request form](https://shorturl.at/znows) or via email to staking@chorus.one

{% include "../../.gitbook/includes/about-c1-dropdown.md" %}
