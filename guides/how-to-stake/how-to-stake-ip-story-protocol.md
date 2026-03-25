---
description: Everything you need to know to stake your IP with Chorus One
hidden: true
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/guides/how-to-stake/how-to-stake-ip-story-protocol
---

# How to stake IP (Story Protocol)

<figure><img src="../../.gitbook/assets/Story x Chorus Banner.jpeg" alt=""><figcaption></figcaption></figure>

## Overview <a href="#h_01hc8bmw88thcadazdzytpfj3f" id="h_01hc8bmw88thcadazdzytpfj3f"></a>

<table data-header-hidden><thead><tr><th width="261.16796875"></th><th></th></tr></thead><tbody><tr><td><mark style="color:blue;"><strong>CATEGORY</strong></mark></td><td><mark style="color:blue;"><strong>DETAILS</strong></mark></td></tr><tr><td><strong>Chorus One Validator</strong></td><td><a href="https://staking.story.foundation/validators/0x785fa3c357e3978c5201d3dcd0795c562687425e">0x785FA3C357E3978C5201d3DCd0795c562687425e</a></td></tr><tr><td><strong>Staking Dashboard</strong></td><td><a href="https://staking.story.foundation/">https://staking.story.foundation/</a></td></tr><tr><td><strong>Block Explorer</strong></td><td><a href="https://story.explorers.guru/">https://story.explorers.guru/</a> or <a href="https://www.storyscan.xyz/">https://www.storyscan.xyz/</a></td></tr><tr><td><strong>Foundation Website</strong></td><td><a href="https://www.story.foundation/">https://www.story.foundation/</a></td></tr><tr><td><strong>Recommended Wallets</strong></td><td><a href="../../wallets/wallets/getting-started-keplr-wallet.md">Kelpr</a>, <a href="../../wallets/wallets/getting-started-okx-wallet.md">OKX</a>, <a href="../../wallets/wallets/getting-started-metamask.md">MetaMask</a>, <a href="../../wallets/wallets/getting-started-phantom-wallet.md">Phantom</a> or other <a href="https://www.story.foundation/wallets">supported wallets</a></td></tr><tr><td><strong>Minimum Stake &#x26; Unstake</strong></td><td>1,024 IP with a 1 IP gas fee to prevent spamming transactions</td></tr><tr><td><strong>Unstaking (Unbonding) Period</strong></td><td>14 Days - Staking rewards are not accrued during unbonding</td></tr></tbody></table>

## About Story Protocol

**Story Protocol (IP)** is a decentralized intellectual property (IP) infrastructure designed to empower creators by allowing them to tokenize, track, and monetize their work in a blockchain-based ecosystem. By leveraging smart contracts, Story Protocol enables provenance tracking of creative assets, ensuring transparent attribution and ownership rights.&#x20;

The protocol facilitates collaborative content creation, allowing multiple contributors to receive automated, programmable royalties based on predefined terms. This makes it particularly useful for industries like publishing, gaming, film, and AI-generated content, where IP management and licensing complexities often create friction.

At its core, Story Protocol aims to revolutionize the way IP is shared and expanded by introducing an open, composable framework for digital storytelling. Creators can register their works on-chain, making them interoperable with various platforms while maintaining control over licensing and derivative works.&#x20;

The system is designed to support modular IP development, meaning that different creators can build upon existing assets while ensuring fair compensation for original contributors. This decentralized approach challenges traditional gatekeepers like studios and publishers, enabling a more transparent and efficient creative economy.

{% hint style="info" %}
For a deeper dive on the staking mechanics, tokenomics, and overview of Story Protocol, please see the official documentation below:

[Story Documentation: Staking Design](https://docs.story.foundation/docs/tokenomics-staking)
{% endhint %}

***

## Key Staking Mechanics

{% hint style="warning" %}
Before diving into how to stake Story Protocol (IP), it's important to understand a few unique key mechanics of how staking on the network functions.

**Note:** Story Protocol requires a minimum stake and unstake value of 1,024 IP.&#x20;

All stake, unstake, and redelegate transactions require 1 IP to prevent spam transactions.

If you specify a token amount that has more than 9 decimal places, the actual amount will be rounded down to 9th decimal place, and, if staking, the remainder will be refunded to your wallet.
{% endhint %}

<details>

<summary><code>Staking Periods</code></summary>

### A**ll users can select how long they wish to stake for.**&#x20;

By default, for both **locked** and **unlocked** IP tokens, delegators can stake and then unstake immediately and get their token back after the 14 day unbonding time.

{% hint style="success" %}
**However, for unlocked tokens only, a few more fixed staking periods are supported:**&#x20;

* 90 days, 360 days, and 540 days.&#x20;

In this case, users can only unstake _after_ the staking period is mature.&#x20;

Any call earlier than the mature day will be discarded.&#x20;

**Note:** Unstaking from a mature staking period is still subject to the unbonding process, meaning users will get their staked tokens back after 14 days of unbonding time in addition to their elected staking period.&#x20;
{% endhint %}

***

### **Why use fixed periods for staking IP tokens?**&#x20;

Staking in these fixed staking periods earns more rewards. The longer the period, the bigger the reward weight multiplier.&#x20;

Below are the reward multiplier rates for different periods:

* **Locked** flexible period - **0.5x**
* **Unlocked** flexible period - **1.0x**
* 90 days - **1.1x**
* 360 days - **1.5**
* 540 days - **2**

{% hint style="warning" %}
**For locked tokens, only flexible staking is allowed and the reward multiplier is 0.5x.**&#x20;

If a user delegates their locked tokens to a staking period, it will be automatically converted into a flexible staking delegation.
{% endhint %}

### What happens when a staking period ends?&#x20;

After the staking period ends, users can choose not to unstake.&#x20;

In this case, they will continue earning the same reward rate based on the reward rate of the corresponding staking period until they unstake manually.&#x20;

* **Note:** This means that a staking period does not automatically unstake your tokens.

{% hint style="info" %}
For example, if the 1-year staking period’s boosted reward rate is 0.02% per block, after staking for 1 year, the user can still the earn the bonus 0.02% until they unstake.

As mentioned above, this only applies for **unlocked tokens.**&#x20;
{% endhint %}

</details>

<details>

<summary><code>Delegation IDs</code></summary>

#### If a Staking Period is selected, you will receive a Delegation ID.&#x20;

{% hint style="warning" %}
Please be sure to keep track of this Delegation ID as it will be needed to unstake your IP tokens later when your Staking Period has passed.&#x20;

* If flexible staking is chosen, or a Staking Period is selected with **locked** IP tokens, then the returned Delegation ID will be 0.
{% endhint %}

{% hint style="info" %}
Remember, only **unlocked** IP tokens can choose a Staking Period.&#x20;
{% endhint %}

If a fixed Staking Period is selected, the Delegation ID will be returned to the staker.

Stakers must use this Delegation ID to unstake tokens from from their Staking Period once it reaches maturity.&#x20;

</details>

<details>

<summary><code>Staking Functions &#x26; The Singularity Period at Network Genesis</code></summary>

#### These are all of the possible staking related functions on Story Protocol. \[[source](https://docs.story.foundation/docs/tokenomics-staking#staking)]

{% hint style="info" %}
**Note:** Some of these are validator specific and go beyond the scope of staking as an individual.&#x20;

For individuals staking Story, the most relevant functions will be Stake, Unstake,  and Redelegate.
{% endhint %}

You can find out [more information here](https://docs.story.foundation/docs/tokenomics-staking#staking-contract) about the Story Protocol Staking Contract.&#x20;

***

* `Create validator`
* `Update validator commission`
* `Stake`
* `Stake on behalf`
* `Unstake`
* `Unstake on behalf`
* `Redelegate`
* `Redelegate on behalf`
* `Set withdraw address`
* `Set reward address`
* `Unjail`
* `Unjail on behalf`

***

### The Singularity

{% hint style="success" %}
**Note:** The Singularity has now passed and is no longer in effect. :white\_check\_mark:
{% endhint %}

#### What was the Singularity?&#x20;

The first 1,580,851 blocks after Story Protocol's network genesis was called the Singularity, during which time everyone could create a validator and stake tokens, however, the active validator set only contained genesis validators.&#x20;

{% hint style="info" %}
During this time, there were no new token emissions and thus no staking rewards.&#x20;

Unstaking, redelegating, slashing, and jailing were not yet active during the Singularity. \[[source](https://docs.story.foundation/docs/tokenomics-staking#singularity)]
{% endhint %}

The Genesis validator set consisted of 8 validators, setup by the foundation and trusted staking institutions.&#x20;

* 4 of the genesis validators support locked tokens and the other 4 support unlocked tokens.&#x20;

Each of the genesis validators had an initial stake of 0.001 IP and each validator could set its own commission rate.&#x20;

During the Singularity, the genesis validators needed to self delegate at least 1,024 IP to perform validator operations like editing validator commission rates.

After Singularity passed, the top 64 validators with the highest stakes were selected to participate in network consensus and receive rewards.

</details>

<details>

<summary><code>Rewards &#x26; Withdrawal Addresses</code></summary>

After the Singularity (see the section above) passed and rewards began on Story Protocol, you can now opt to select a specific withdrawal and rewards address to collect staking rewards automatically.&#x20;

{% hint style="info" %}
**Note:** Rewards earned are unlocked by default, even for those earned from **locked** IP tokens.&#x20;

However, for **locked** tokens, rewards can accrue but can’t be unbonded until the lock period ends.&#x20;
{% endhint %}

You can call the staking contract to set a withdrawal and rewards address of your choosing if you wish.&#x20;

* When you unstake, the tokens will be sent to this withdrawal address.&#x20;
* Similarly, for the rewards address all reward distributions will be sent to this address.

A fee of 1 IP will be charged for updating either the withdrawal address or the rewards address to prevent spamming and this fee will be burnt by the staking contract.

When doing so, the withdrawal or rewards address change will take effect in the next block.

* For further reading, please see the Story Protocol documentation [here](https://docs.story.foundation/docs/tokenomics-staking#set-withdrawalreward-address).

</details>

***

## How to Stake Story Protocol (IP) with Chorus One

{% hint style="info" %}
For institutional investors we can assist with questions regarding Qualified Custodians (QCs), White Label (WL) or VaaS setups for Story Protocol.

Please contact us via our [staking request form](https://shorturl.at/znows) or see: [#a-note-to-institutional-investors](how-to-stake-ip-story-protocol.md#a-note-to-institutional-investors "mention")
{% endhint %}

First, navigate to the Staking Dashboard found at: [https://staking.story.foundation/](https://staking.story.foundation/) or navigate [directly to the Chorus One Validator](https://staking.story.foundation/validators/0x785fa3c357e3978c5201d3dcd0795c562687425e).&#x20;

#### **Be sure to you have a compatible wallet installed.**&#x20;

* Some recommended options are Keplr, OKX, MetaMask, and Phantom.&#x20;

For this guide, we will be demonstrating the steps with Keplr, however, the staking steps will be similar with each compatible wallet.&#x20;

{% hint style="warning" %}
If you'd like instructions on setting up any of the above wallets, please see:

* [getting-started-keplr-wallet.md](../../wallets/wallets/getting-started-keplr-wallet.md "mention"), [getting-started-okx-wallet.md](../../wallets/wallets/getting-started-okx-wallet.md "mention"), [getting-started-metamask.md](../../wallets/wallets/getting-started-metamask.md "mention"), or [getting-started-phantom-wallet.md](../../wallets/wallets/getting-started-phantom-wallet.md "mention")
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2025-03-10 at 11.54.32 PM.png" alt="" width="563"><figcaption><p>Source: <a href="https://staking.story.foundation/">https://staking.story.foundation/</a></p></figcaption></figure>

From the [Staking Dashboard](https://staking.story.foundation/), click on Connect Wallet in the upper-right hand corner of the page, or follow similar steps to connect your wallet interface if navigating directly to the [Chorus One Validator](https://staking.story.foundation/validators/0x785fa3c357e3978c5201d3dcd0795c562687425e).&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-03-11 at 12.04.18 AM.png" alt=""><figcaption><p>Example of the Story Protocol staking dashboard: <a href="https://staking.story.foundation/">https://staking.story.foundation/</a></p></figcaption></figure>

When you connect, your Keplr wallet or other compatible wallet may prompt you to connect to the Ethereum Network. Go ahead and accept the connection.&#x20;

#### If you connected via the [Staking Dashboard](https://staking.story.foundation/), next click on Stake Now then scroll through the list to find **Chorus One**.

Or you can find Chorus One via the list below.

<figure><img src="../../.gitbook/assets/Screenshot 2025-03-11 at 12.17.05 AM.png" alt=""><figcaption><p>Example of the active validator list.</p></figcaption></figure>

Once you've clicked on Stake Now you will be able to scroll through the list to find **Chorus One**.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-03-11 at 12.07.31 AM.png" alt="" width="563"><figcaption><p>Example of staking to Chorus One via the <a href="https://staking.story.foundation/">Staking Dashboard</a></p></figcaption></figure>

#### If you navigated directly either via the list or [direct link](https://staking.story.foundation/validators/0x785fa3c357e3978c5201d3dcd0795c562687425e) you'll see a screen similar to what's shown below.&#x20;

In the screenshot below you can see the **Stake** and **Unstake** buttons highlighted.&#x20;

{% hint style="info" %}
It can be useful to [bookmark the link](https://staking.story.foundation/validators/0x785fa3c357e3978c5201d3dcd0795c562687425e) for easy access later.&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2025-03-11 at 12.22.51 AM.png" alt=""><figcaption><p>Example of the <a href="https://staking.story.foundation/validators/0x785fa3c357e3978c5201d3dcd0795c562687425e">Chorus One Validator Dashboard</a>.</p></figcaption></figure>

Simply click on the Stake button in the right hand side of the screen to begin.

Here you will see a similar stake screen as you saw before as if you were accessing staking from the main dashboard, however, you no longer have to select a validator.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-03-11 at 12.26.50 AM.png" alt="" width="563"><figcaption><p>Example of the IP staking screen.</p></figcaption></figure>

### Selecting a Staking Period

You can click the dropdown menu to explore a Staking Period and see how the period corresponds to additional rewards.

* For a refresher on Staking Periods and their mechanics, please see: [#staking-periods](how-to-stake-ip-story-protocol.md#staking-periods "mention")

{% hint style="warning" %}
**Note:** Only **unlocked** IP tokens are able to use staking periods.&#x20;

If a staking period is selected with **locked** IP tokens, it will default back to flexible staking at the 0.5x rewards rate.&#x20;

Both unlocked and locked IP tokens are subject to the minimum 1,024 staking, unstaking, and redelegation minimum.&#x20;

If you select a Staking Period with **unlocked** IP tokens, be sure to retain your Delegation ID.&#x20;

* More can be found on this here: [#delegation-ids](how-to-stake-ip-story-protocol.md#delegation-ids "mention")
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2025-03-11 at 12.27.00 AM.png" alt=""><figcaption><p>Example of the staking period selection available for unlocked tokens. </p></figcaption></figure>

Once you have selected how much IP to stake and for how long, go ahead and finalize the transaction in your wallet.&#x20;

You can then click on the button to view your transaction on-chain to verify it.

It may be needed to refresh the validator page or the staking dashboard to see your updated staked balance reflected.

{% hint style="success" %}
And that's it! You're all set, you've now staked your IP!&#x20;
{% endhint %}

***

## Unstaking your IP

Similar to the steps above, navigate back to the Staking Dashboard or directly to the Chorus One Validator from the links below:

* [https://staking.story.foundation/](https://staking.story.foundation/)
* [https://staking.story.foundation/validators/0x785fa3c357e3978c5201d3dcd0795c562687425e](https://staking.story.foundation/validators/0x785fa3c357e3978c5201d3dcd0795c562687425e)

Select the Chorus One Validator by finding it in the list or [navigating directly to it](https://staking.story.foundation/validators/0x785fa3c357e3978c5201d3dcd0795c562687425e).

Click on **Unstake** and select the amount of IP to unstake (minimum of 1,024 IP).

<figure><img src="../../.gitbook/assets/Screenshot 2025-03-11 at 12.39.56 AM.png" alt="" width="520"><figcaption><p>Example of the Stake &#x26; Unstake buttons.</p></figcaption></figure>

{% hint style="info" %}
Unstaking IP requires a minimum of 1,024 IP tokens and a 1 IP fee that will be burnt by the staking contract.

Once initiated, the unbonding period will last for 14 days before the tokens will become liquid in your wallet again.
{% endhint %}

Similar to staking, once you've selected the amount of IP you wish to unstake, submit and finalize the transaction in your wallet.&#x20;

You can then click on the button to view your transaction on-chain to verify it.

It may be needed to refresh the validator page or the staking dashboard to see your updated staked and unstaking (unbonding) balances reflected.

***

## Redelegating your IP

As an alternative to unstaking you can also redelegate your existing staked IP.&#x20;

The redelegate operation allows a delegator to move their staked IP from one validator to another.

This can be useful if you were already staking your IP to another validator and wish to move it to Chorus One.&#x20;

When you redelegate, your IP tokens will be redelegated to the new validator immediately and start earning rewards.&#x20;

However, the redelegated IP is still subject to the unbonding process if the originating validator is in the active validator set or currently unbonding from the active validator set. This means you will not be able to redelegate your stake again until the 14 day unbonding period has passed.&#x20;

* During this 14 day unbonding time, your IP can be subject to slashing if the original validator gets slashed.
* A fee of 1 IP will be also charged for redelegation to prevent spamming transactions and this fee will be burnt by the staking contract.

{% hint style="warning" %}
Similarly to unstaking, if the redelegation amount chosen is larger than the total staked tokens at the originating validator, the entire amount of IP will be redelegated.&#x20;

If the remaining balance after redelegation is less than 1,024 IP, then all remaining tokens will be redelegated together in one move to the new chosen validator.&#x20;

**Note:** The Delegation ID (if applicable) will remain the same after the redelegation.
{% endhint %}

{% hint style="info" %}
**Other Important Redelegation Considerations:**

You can choose to redelegate your IP tokens to another active validator even if the unlocked IP tokens are still in an immature staking period.&#x20;

* Your staking period maturation date and reward rate will stay the same.
* Redelegation can only be triggered when the source and destination validators support the same token type.

If you specify to redelegate a token amount that has more than 9 decimal units, the actual redelegated amount of IP tokens will be rounded down to the 9th decimal place.
{% endhint %}

***

## Staking Rewards Distribution

Rewards from staking your IP are accumulated on a per block basis and can be distributed every block from the validator you delegate to, however, they must reach a certain threshold. Staking rewards cannot be manually withdrawn by design.&#x20;

* Rewards will only be automatically distributed to your account when the sum of the rewards reach a  defined threshold.&#x20;
* The default and also minimal threshold is 8 IP, which means that only when you have accrued >8 IP tokens in staking rewards will these be sent to your address.&#x20;

When this happens, your reward distribution will go into a rewards distribution queue which only processes a fixed amount of 32 reward distribution requests per block.&#x20;

{% hint style="success" %}
**Since the Singularity phase has passed, staking rewards are now live and earned on Story Protocol.** :white\_check\_mark:

* To learn more, please reference: [#staking-functions-and-the-singularity](how-to-stake-ip-story-protocol.md#staking-functions-and-the-singularity "mention")
* Also please see: [#rewards-and-withdrawal-addresses](how-to-stake-ip-story-protocol.md#rewards-and-withdrawal-addresses "mention")
{% endhint %}

***

{% include "../../.gitbook/includes/questions.md" %}

## A Note to Institutional Investors

If you are an institutional investor looking to stake Story Protocol (IP) with Chorus One, please reach out to us via our [staking request form](https://shorturl.at/znows).&#x20;

***

{% include "../../.gitbook/includes/about-c1-dropdown.md" %}
