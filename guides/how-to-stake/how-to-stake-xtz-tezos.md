---
description: Everything you need to know to stake your Tezos (aka "Tez") with Chorus One
hidden: true
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/guides/how-to-stake/how-to-stake-xtz-tezos
---

# How to stake XTZ (Tezos)

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-18 at 12.05.12 PM.png" alt=""><figcaption><p>Source: <a href="https://spotlight.tezos.com/how-to-stake/">https://spotlight.tezos.com/how-to-stake/</a></p></figcaption></figure>

## Overview <a href="#h_01hc8bmw88thcadazdzytpfj3f" id="h_01hc8bmw88thcadazdzytpfj3f"></a>

<table data-header-hidden><thead><tr><th width="242"></th><th></th></tr></thead><tbody><tr><td><mark style="color:blue;"><strong>CATEGORY</strong></mark></td><td><mark style="color:blue;"><strong>DETAILS</strong></mark></td></tr><tr><td><strong>Chorus One Validators</strong></td><td><a href="https://tzstats.com/tz1eEnQhbwf6trb8Q8mPb2RaPkNk2rN7BKi8">tz1eEnQhbwf6trb8Q8mPb2RaPkNk2rN7BKi8<br></a><a href="https://tzstats.com/tz1Scdr2HsZiQjc7bHMeBbmDRXYVvdhjJbBh">tz1Scdr2HsZiQjc7bHMeBbmDRXYVvdhjJbBh</a></td></tr><tr><td><strong>Recommended Wallets</strong></td><td> <a href="https://wallet.kukai.app/">Kukai</a>, <a href="https://templewallet.com/">Temple</a>, <a href="https://trustwallet.com/">Trust Wallet</a>, or <a href="https://umamiwallet.com/">Umami Wallet</a>.</td></tr><tr><td><strong>Block Explorers</strong></td><td><a href="https://tzstats.com/">https://tzstats.com/</a> or <a href="https://tzkt.io/">https://tzkt.io/</a></td></tr><tr><td><strong>Staking Rewards</strong></td><td><a href="https://www.stakingrewards.com/asset/tezos">https://www.stakingrewards.com/asset/tezos</a></td></tr><tr><td><strong>Unstaking Period</strong></td><td>4 Cycles (approximately 11 days)</td></tr></tbody></table>

## About Tezos

**Tezos (XTZ)** is a [self-amending](https://www.opentezos.com/tezos-basics/governance-on-chain/#what-is-self-amendment), Proof-of-Stake (PoS) blockchain launched in 2018 that allows stakeholders to vote on upgrades without hard forks. This self-governing mechanism helps Tezos remain adaptive and reduces disruption by implementing upgrades directly through the protocol.&#x20;

* It supports smart contracts and dApps, with XTZ as its native token used for staking, governance, and fees.

Tezos uses a Liquid Proof-of-Stake (LPoS) model, where holders can stake or delegate to a baker. The network puts a focus on security, on-chain governance, and efficiency which is enhanced by regular upgrades, like the [Paris upgrade](https://chorus.one/articles/tezos-a-guide-to-the-paris-upgrade-and-important-changes-to-their-pos-model), which improved scalability and reduced gas fees.

***

### The Paris Upgrade

On June 4th 2024, the Tezos blockchain successfully activated the Paris upgrade proposal at block 5,726,209.&#x20;

* This marked a new era for the network, with significant effects on its consensus model in three key areas: Faster Finality, Higher Scalability, Stronger LPoS.
* Tezos continues to use a Liquid Proof-of-Stake (LPoS) model, where token holders can either directly stake their XTZ tokens or delegate their XTZ to a baker without losing custody, however, new features and dynamics were added.

{% tabs %}
{% tab title="Before the Paris upgrade" %}
Before the Paris upgrade, delegating was the primary option for most users, as the previous form of staking (baking) required at least 6,000 XTZ.&#x20;

{% hint style="success" %}
However, with the introduction of [adaptive issuance](https://research-development.nomadic-labs.com/adaptive-issuance-paris.html) after the Paris upgrade, direct staking allows users to **earn significantly higher rewards compared to delegating**.&#x20;

Users can now choose to delegate, direct stake, or create a baker (validator).
{% endhint %}

This added direct staking incentives have made staking more attractive and accessible than before, whereas previously there was little difference in rewards between staking and delegating.
{% endtab %}

{% tab title="After the Paris Upgrade" %}
Post-Paris upgrade, staked funds are earned directly into the user’s account, while for delegations, rewards are first sent to the baker, who must distribute them to the delegators.&#x20;

This adds to the appeal of staking for users, as it simplifies reward distribution and ensures immediate access to rewards.

{% hint style="warning" %}
However, reward start and stop times differ between staking and delegating after the Paris upgrade.&#x20;
{% endhint %}

* Notably, direct staking XTZ now involves a lockup period of approximately 11 days (4 cycles) when a user wishes to unstake, after which the funds can be manually reclaimed.
* While users can still create a baker, they can now stake any amount of XTZ using the [Tezos staking app](https://stake.tezos.com/) to a supported baker without the 6,000 token threshold that applies to becoming a baker.

With the adjusted the reward structure favoring direct staking to bakers, the goal was to promote decentralization of the Tezos network by encouraging more individuals to stake and participate actively in validating transactions rather than relying on a smaller set of bakers.
{% endtab %}

{% tab title="Key Takeaways for Users" %}
* The general Tezos user can still delegate their coins to a baker and be a delegator.
* Additionally they can stake their coins and become a staker if the baker accepts staking.
* You can stake any amount in your spendable balance, but you should reserve some funds for staking, unstaking and finalization fees.
* You can stake more or unstake at any time, but changes take 2 cycles to affect baking rights and hence any rewards.
* Unstaked funds are still frozen. The unstaking needs to be finalized after 4 cycles.
* The user’s wallet receives any baking rewards due to the staking directly from the Tezos protocol. The baker is not involved in this process. The rewards are automatically staked.
* The user’s stake is subject to slashing should the baker misbehave.
* You can liquidate your stake by unstaking everything, waiting 4 cycles, and then by issuing the finalization command.
{% endtab %}
{% endtabs %}

{% hint style="info" %}
For a deep dive on the Paris upgrade, please see:&#x20;

[Tezos: a guide to the Paris upgrade and important changes to their PoS model](https://chorus.one/articles/tezos-a-guide-to-the-paris-upgrade-and-important-changes-to-their-pos-model)
{% endhint %}

***

## Delegating vs Staking

Tezos offers multiple ways for users to earn rewards by participating in securing the network via the Liquid Proof-of-Stake (LPoS) model either via delegating, staking to a baker, or running a baker.

<details>

<summary>Baking &#x26; Staking Explained</summary>

Briefly put, [**baking**](https://docs.tezos.com/architecture/baking) means running a machine that is part of securing the Tezos network. Bakers produce blocks, maintain consensus, and vote on governance questions. To obtain the rights to do so, bakers must stake funds, which are frozen by the protocol and subject to economic penalties, _slashing_, if the baker misbehaves. For the work and risk involved, bakers receive rewards in proportion to their stake.

Others can also participate in **staking** and receive rewards directly from the protocol, which is done by choosing a baker and letting your funds count towards that baker’s stake. The funds remain in your account but are frozen by the protocol and subject to slashing, just like the baker’s funds.

For a more detailed tutorial for bakers, please see [this guide](https://news.tezoscommons.org/quick-start-guide-for-adaptive-issuance-3dcae6bef5a4) by Tezos Commons.&#x20;

* **Source:** [Nomadic Labs: How to Stake Tezos](https://research-development.nomadic-labs.com/how-to-stake.html)

</details>

<details>

<summary>Delegating Explained</summary>

An alternative to staking is **delegation**, which lets you contribute to a baker’s stake without the funds being frozen or subject to slashing.&#x20;

However, delegated funds carry only half the weight for receiving baking rights (and hence rewards), and when voting in governance.&#x20;

Also, rewards coming from delegated funds are paid out to the baker, not to the delegator. It is then up to the baker to decide whether and how they are redistributed.

In short, staked funds are incentivized more because they contribute more to network security by being actually _at stake_.

**Source:** [Nomadic Labs: How to Stake Tezos](https://research-development.nomadic-labs.com/how-to-stake.html)

</details>

#### Visual Chart of Staking vs Delegation

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-22 at 5.40.20 PM.png" alt=""><figcaption><p>Source: <a href="https://research-development.nomadic-labs.com/how-to-stake.html">https://research-development.nomadic-labs.com/how-to-stake.html</a></p></figcaption></figure>

***

## How to Bake, Stake or Delegate XTZ

Whether you have 6,000 or more XTZ to become a baker or not, there's now more ways you can participate in network security and be rewarded for doing so!&#x20;

{% hint style="warning" %}
**In light of the Paris upgrade mentioned above, staking XTZ is now more profitable!**&#x20;

If you had previously been delegating your XTZ to a baker and now wish to stake, it is advisable to do so in order to increase your staking rewards.
{% endhint %}

<figure><img src="../../.gitbook/assets/XTZ chart.png" alt=""><figcaption><p>Source: <a href="https://spotlight.tezos.com/how-to-stake/">https://spotlight.tezos.com/how-to-stake/</a></p></figcaption></figure>

While the chart above highlights some key differences, to learn all about the staking or delegating Tezos post Paris upgrade, please check out the comprehensive guide below.

**It covers:** Delegating XTZ, staking XTZ, creating a baker, or changing your previous delegation to a stake via the the [Tezos staking app interface](https://stake.tezos.com/). &#x20;

{% embed url="https://spotlight.tezos.com/how-to-stake/" %}
Source: [https://spotlight.tezos.com/how-to-stake/](https://spotlight.tezos.com/how-to-stake/)
{% endembed %}

***

## A Note to Institutional Investors

If you are an institutional investor looking to stake Tezos (XTZ) with Chorus One, please reach out to us via our [staking request form](https://shorturl.at/znows).&#x20;

{% include "../../.gitbook/includes/about-c1-dropdown.md" %}
