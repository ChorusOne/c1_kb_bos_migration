---
description: Everything you need to know the stake Avalanche (AVAX)
hidden: true
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/guides/how-to-stake/how-to-stake-avax-avalanche
---

# How to stake AVAX (Avalanche)

## Overview <a href="#h_01hc844cgep9se65w3skh56298" id="h_01hc844cgep9se65w3skh56298"></a>

<table data-header-hidden><thead><tr><th width="279"></th><th></th></tr></thead><tbody><tr><td><mark style="color:blue;"><strong>CATEGORY</strong></mark></td><td><mark style="color:blue;"><strong>DETAILS</strong></mark></td></tr><tr><td><strong>Delegation Addresses</strong></td><td><p><a href="https://avascan.info/staking/validator/NodeID-LkDLSLrAW1E7Sga1zng17L1AqrtkyWTGg">NodeID-LkDLSLrAW1E7Sga1zng17L1AqrtkyWTGg</a></p><p><a href="https://avascan.info/staking/validator/NodeID-4Ubqsj2vfwdGUUYNg1jtYpkYNNLugNBQ9">NodeID-4Ubqsj2vfwdGUUYNg1jtYpkYNNLugNBQ9</a></p><p><a href="https://avascan.info/staking/validator/NodeID-MTEbgxTNBdL6GWh8SdQMfMXvEU1jC9aws">NodeID-MTEbgxTNBdL6GWh8SdQMfMXvEU1jC9aws</a></p><p><a href="https://avascan.info/staking/validator/NodeID-N4zuaXKz9tpBax2YVqAXoducH1SugH4ZF">NodeID-N4zuaXKz9tpBax2YVqAXoducH1SugH4ZF</a></p></td></tr><tr><td><strong>Wallet</strong></td><td><a href="https://core.app/">https://core.app/</a></td></tr><tr><td><strong>Block Explorers</strong></td><td><a href="https://avascan.info/">https://avascan.info/</a> or <a href="https://subnets.avax.network/">https://subnets.avax.network/</a></td></tr><tr><td><strong>Staking Rewards</strong></td><td><a href="https://www.stakingrewards.com/earn/avalanche/">https://www.stakingrewards.com/earn/avalanche/</a></td></tr><tr><td><strong>Unbonding Period</strong></td><td>The minimum staking duration is two weeks.</td></tr></tbody></table>

## What is Avalanche?&#x20;

**Avalanche** is a decentralized, open-source proof of stake blockchain with smart contract functionality.&#x20;

**AVAX** is the native cryptocurrency of the platform. It was designed to provide scalable and efficient blockchain solutions for decentralized applications (dApps), custom blockchain networks, and DeFi (decentralized finance).&#x20;

The Avalanche network is built around three interoperable blockchains:&#x20;

1. The Exchange Chain (X-Chain)
2. The Platform Chain (P-Chain)
3. The Contract Chain (C-Chain)

Each serves a different purpose: the X-Chain is for creating and exchanging assets, the P-Chain handles the creation of subnets and manages staking, and the C-Chain is for smart contracts.&#x20;

Subnets on Avalanche allow developers to create their own customizable blockchains, enhancing scalability and flexibility. It operates on a consensus protocol called Avalanche Consensus, which enables it to achieve high throughput and low latency while maintaining security and decentralization.&#x20;

Avalanche supports the Ethereum Virtual Machine (EVM), allowing developers to deploy Ethereum-based dApps seamlessly on its platform with lower transaction fees.

***

## About Staking on Avalanche

Avalanche is a nuanced network to stake with, so if you'd like to read all the details before proceeding, please check out the tab menu below.

<details>

<summary>Avalanche Staking Details</summary>

**Validating Rights**: The weight of validators is determined by the amount of staking tokens bonded as collateral.

[Token distribution](https://messari.io/asset/avalanche/profile/launch-and-initial-token-distribution) model and inflation rate of \~9.2%.

**Staking details:**

* The minimum amount that a validator must stake is 2,000 AVAX
* The minimum amount that a delegator must delegate is 25 AVAX
* The minimum amount of time one can stake funds for validation is 2 weeks
* The maximum amount of time one can stake funds for validation is 1 year
* The minimum amount of time one can stake funds for delegation is 2 weeks
* The maximum amount of time one can stake funds for delegation is 1 year
* The minimum delegation fee rate is 2%
* 50% of AVAX tokens allocated to staking rewards

**Reward Rate:** Rewards are paid out at the expiration of the validation contract provided the validator uptime as seen by the network is above 80%.

**Chorus One Commission:** 2%

**Staking Limits:** The maximum weight of a validator (their own stake + stake delegated to them) is the maximum of 3 million AVAX and 5 times the amount the validator staked. For example, if you staked 2,000 AVAX to become a validator, only 8000 AVAX can be delegated to your node total (not per delegator)

**Slashing:** No slashing. A validator will receive a staking reward if they are online and respond for more than 80% of their validation period, as measured by a majority of validators, weighted by stake. You should aim for your validator be online and responsive 100% of the time.

**Re-Staking:** You need to withdraw rewards and re-stake them with some frequency if you want to make use of compounding returns hence, additional delegation is needed for compounding.

**Staking Guide:** To read a step-by-step guide on how to stake AVAX, click [here](https://twitter.com/ChorusOne/status/1540348016028069888?s=20\&t=Js9ud5qrcw8p6cJSBX_iOg)

</details>

## How to Stake AVAX

### 1. Create an Core Wallet <a href="#h_01hc8b9m56hh4n2jnsckvpbe68" id="h_01hc8b9m56hh4n2jnsckvpbe68"></a>

While there are wallet options to stake AVAX, [Core wallet](https://core.app/) is one of the best options and the one we will be focusing on for this guide. It is [recommended by the Avalanche Network](https://support.avax.network/en/articles/6088395-how-do-i-stake-avax-on-avalanche) themselves as the best wallet to use.

As you may know, Avalanche is comprised of 3 different chains, and as such, this means staking on Avalanche works a bit differently.&#x20;

First, you will need an Avalanche wallet. You can create one through the [Core wallet extension](https://core.app/) or connect your Ledger via the Core wallet browser extension.&#x20;

* Their website can be found here: [https://core.app/](https://core.app/)
* The direct browser extension download can be [found here](https://chromewebstore.google.com/detail/core-crypto-wallet-nft-ex/agoakfejjabomempkjlepdflaleeobhb).

> Make sure you're on the right URL. Don't fall prey to phishing attacks by sites that look like the official wallet

On the Core wallet website, select 'Connect Wallet' in the upper-right hand corner of the page. Then choose the Core browser extension.

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-19 at 6.51.49 PM.png" alt="" width="375"><figcaption><p>The wallet selection screen on Core.app</p></figcaption></figure>

{% hint style="info" %}
If you don't already have the Core wallet browser extension installed, go ahead and follow the steps to install it.&#x20;

Once you've done so, you'll see a screenshot like the one below.&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-19 at 7.06.34 PM.png" alt="" width="375"><figcaption><p>Example of creating a new Core browser extension wallet.</p></figcaption></figure>

{% hint style="warning" %}
You can create a wallet associated with you Google or Apple mail, however, _**this is not recommended.**_
{% endhint %}

It is more secure to create a new wallet (if you don't have one) and store the 24-word seed phrase securely.&#x20;

* If you are using a Ledger or other compatible hardware wallet, you can select 'Access Existing Wallet' and connect following the instructions.&#x20;

**If you choose to create a new wallet you will be shown 24 words as your mnemonic seed phrase.**&#x20;

{% hint style="danger" %}
**Please be sure to back up your mnemonic seed securely.**&#x20;

* It is recommended to store it physically, not in a digital format or as a screenshot.

**Never share this seed phrase with anyone, as they will have access to your funds.**&#x20;

* A lost mnemonic seed phrase cannot be recovered.
* Anyone with your mnemonic seed phrase can take control of your assets.
{% endhint %}

Next, you will be asked to verify three random words that follow in you seed phrase.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-19 at 7.13.39 PM.png" alt="" width="364"><figcaption></figcaption></figure>

This is to make sure you remember the mnemonic and confirm that you wrote it down correctly.

* After you've done this, click 'Save'.&#x20;

Next you will be prompted to name your wallet and set a password. This password will only be saved to this local installation of your wallet. It is your 24-word seed phrase that matters to recover your wallet in the future or on another device.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-19 at 7.16.21 PM.png" alt="" width="371"><figcaption><p>Example of setting a wallet name and password.</p></figcaption></figure>

You might be prompted to opt in to Airdrops for your wallet. It's completely up to you if this is something you wish to do. Opting in or not will not have any bearing on your ability to stake.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-19 at 7.17.34 PM.png" alt="" width="419"><figcaption><p>Airdrop opt in option.</p></figcaption></figure>

{% hint style="success" %}
You're all set! You've created your new Core wallet that can support AVAX!&#x20;
{% endhint %}

You'll be brought to a home screen similar to the screenshot below. It is recommended to pin the browser extention wallet to your taskbar if you have not already (as prompted by the website).

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-19 at 7.19.07 PM.png" alt=""><figcaption><p>Example of the new wallet creation landing page.</p></figcaption></figure>

### 2. Purchase or Acquire some AVAX <a href="#h_01hc8b9m56wb3rgh3dt4q72ft4" id="h_01hc8b9m56wb3rgh3dt4q72ft4"></a>

Once you've accessed your wallet, you will need some AVAX to begin staking.&#x20;

{% hint style="warning" %}
**Two important things to note for staking AVAX:**

You will need P-Chain AVAX to stake (more on this below).

You will need a minimum of 25 AVAX to stake.
{% endhint %}

* **Please note:** You will want to be sure you get **P-Chain AVAX** for staking.&#x20;
* If you do not have access to P-Chain AVAX, please see the next section: [Cross Chain Transfers](how-to-stake-avax-avalanche.md#h_01hc8b9m56c5h03zzstkad2vd6)
* All transactions use AVAX for gas fees, however, leaving a small amount of AVAX on the X, C, or P chains respectively is not a bad idea to ensure you always has gas for future transactions.&#x20;

### 3. Cross Chain Transfers <a href="#h_01hc8b9m56c5h03zzstkad2vd6" id="h_01hc8b9m56c5h03zzstkad2vd6"></a>

If you bought your AVAX on an exchange, you might not have the option to transfer it out on the P-Chain.&#x20;

* However, if that option is not available, you can send it to your Core wallet on either the X-Chain or C-Chain and then cross-chain transfer it to the P-Chain.&#x20;

You can access the cross-chain transfer function in Core by going to the 'Staking' tab on the left and then selecting 'Cross-Chain Transfer'.

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-19 at 7.25.39 PM.png" alt=""><figcaption><p>Example of using the cross-chain transfer feature.</p></figcaption></figure>

Once you've selected how much you wish to transfer, follow the prompts in the Core wallet to complete the transaction and move your AVAX to the P-Chain.&#x20;

### 4. Staking your AVAX <a href="#h_01hc8b9m56c5h03zzstkad2vd6" id="h_01hc8b9m56c5h03zzstkad2vd6"></a>

You should now have some AVAX on the P-chain and are now ready to stake!

{% hint style="info" %}
Please note: AVAX requires a minimum delegation (stake) of 25 AVAX.&#x20;
{% endhint %}

Click on 'Stake' on the left hand side of the Core wallet app and you will see buttons to delegate as shown in the screenshot below.

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-19 at 7.40.45 PM.png" alt=""><figcaption></figcaption></figure>

Next, enter how much AVAX you wish to delegate.&#x20;

{% hint style="info" %}
**Note:** If you have previously delegated or locked AVAX, the available balance may likely be smaller than the total balance shown.&#x20;

You can hover over the tooltip icon for more information.

![](<../../.gitbook/assets/image (41).png>)
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-19 at 7.42.59 PM.png" alt=""><figcaption><p>Example of the delegation screen.</p></figcaption></figure>

After entering the amount and proceeding, you will be prompted to choose which node to delegate to.&#x20;

<figure><img src="../../.gitbook/assets/image (40).png" alt=""><figcaption><p>Example of the node selection screen. </p></figcaption></figure>

### 4. Select Chorus One Node(s) <a href="#h_01hc8b9m564hzswj85dy94p9zs" id="h_01hc8b9m564hzswj85dy94p9zs"></a>

Now you will be prompted to select the node to delegate to.&#x20;

In order to delegate to a Chorus One node, copy one of the following Node IDs:

> [NodeID-LkDLSLrAW1E7Sga1zng17L1AqrtkyWTGg](https://avascan.info/staking/validator/NodeID-LkDLSLrAW1E7Sga1zng17L1AqrtkyWTGg)
>
> [NodeID-4Ubqsj2vfwdGUUYNg1jtYpkYNNLugNBQ9](https://avascan.info/staking/validator/NodeID-4Ubqsj2vfwdGUUYNg1jtYpkYNNLugNBQ9)
>
> [NodeID-MTEbgxTNBdL6GWh8SdQMfMXvEU1jC9aws](https://avascan.info/staking/validator/NodeID-MTEbgxTNBdL6GWh8SdQMfMXvEU1jC9aws)
>
> [NodeID-N4zuaXKz9tpBax2YVqAXoducH1SugH4ZF](https://avascan.info/staking/validator/NodeID-N4zuaXKz9tpBax2YVqAXoducH1SugH4ZF)

Use the search function to look up one of the chosen Node IDs and paste it there.&#x20;

Click the node and you're almost there!

{% hint style="info" %}
Sometimes you might see the message that the node is oversubscribed.&#x20;

Try using the other node IDs if you see this message.&#x20;

In case you see this message for all the nodes, feel free to email at support@chorus.one
{% endhint %}

### 5. Confirm your Delegation <a href="#h_01hc8b9m56yccbwyvnqv7r11zx" id="h_01hc8b9m56yccbwyvnqv7r11zx"></a>

Select the end date for your stake, the amount for staking and click on Confirm.&#x20;

After selecting a delegation duration, you will be prompted to choose the address the rewards will be delivered to.&#x20;

* You can choose between the currently connected P-Chain wallet address, or enter a custom address.

<figure><img src="../../.gitbook/assets/image (42).png" alt=""><figcaption><p>Example of choosing an AVAX rewards address after delegating. </p></figcaption></figure>

Next, you will see a final review screen of your delegation. If all looks good, go ahead and confirm the transaction.&#x20;

{% hint style="success" %}
That's it, congratulations!&#x20;

Your AVAX will now start earning rewards and you've just made the network more secure.&#x20;
{% endhint %}

> The minimum staking duration is two weeks. A delegator will receive a higher percentage of rewards if they decide to stake for longer amounts (up to a year), thus incentivizing longer stake lengths.

W‍hen your delegation period ends your AVAX will become liquid again.

You can navigate to your Portfolio page and view your P-Chain activity to see your staked AVAX balance and other related information.&#x20;

***

## A Note to Institutional Investors

If you are an institutional investor looking to stake Avalanche (AVAX) with Chorus One, please reach out to us via our [staking request form](https://shorturl.at/znows).&#x20;

{% include "../../.gitbook/includes/about-c1-dropdown.md" %}
