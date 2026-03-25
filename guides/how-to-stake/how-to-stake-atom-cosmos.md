---
description: Everything you need to know to stake your ATOM with Chorus One.
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/guides/how-to-stake/how-to-stake-atom-cosmos
---

# How to stake ATOM (Cosmos)

## Overview <a href="#h_01hc8aygmwstsr0b932yjyhzsx" id="h_01hc8aygmwstsr0b932yjyhzsx"></a>

<table data-header-hidden><thead><tr><th width="236"></th><th></th></tr></thead><tbody><tr><td><mark style="color:blue;"><strong>CATEGORY</strong></mark></td><td><mark style="color:blue;"><strong>DETAILS</strong></mark></td></tr><tr><td><strong>Chorus One Validator Address</strong></td><td><a href="https://www.mintscan.io/cosmos/validators/cosmosvaloper15urq2dtp9qce4fyc85m6upwm9xul3049e02707">cosmosvaloper15urq2dtp9qce4fyc85m6upwm9xul3049e02707</a></td></tr><tr><td><strong>Recommended Wallet</strong></td><td><a href="https://wallet.keplr.app/">Keplr</a> or <a href="https://www.leapwallet.io/">Leap</a></td></tr><tr><td><strong>Block Explorer</strong></td><td><a href="https://www.mintscan.io/cosmos">https://www.mintscan.io/cosmos</a></td></tr><tr><td><strong>Staking Rewards</strong></td><td><a href="https://www.mintscan.io/cosmos">https://www.mintscan.io/cosmos</a></td></tr><tr><td><strong>Unstaking Period</strong></td><td>21 Days</td></tr></tbody></table>

## About Cosmos

**ATOM** is the native cryptocurrency of the Cosmos network, a decentralized ecosystem designed to enable interoperability between different blockchain networks. Cosmos aims to solve the challenges of blockchain scalability, usability, and sovereignty by creating a modular architecture where blockchains, known as zones, can communicate and exchange value through the Inter-Blockchain Communication (IBC) protocol.&#x20;

* ATOM serves a vital role in this ecosystem by acting as a staking token for securing the Cosmos Hub, the central blockchain that facilitates interchain connectivity.&#x20;
* It also grants holders governance rights, allowing them to participate in decision-making processes related to network upgrades and policies.

The Cosmos Hub uses a Proof of Stake (PoS) consensus mechanism, where ATOM holders delegate their tokens to validators to help secure the network and process transactions. In return, delegators and validators earn staking rewards. Unlike some other cryptocurrencies, ATOM does not have a fixed supply; instead, its issuance is governed by a dynamic inflation rate aimed at incentivizing participation in staking.&#x20;

Cosmos’s modular framework and its IBC protocol have made it a cornerstone of cross-chain communication, enabling a more interconnected and scalable blockchain ecosystem.

***

## How to Stake ATOM <a href="#h_01hc8b1t0wcrq7d9kzmt9cspq4" id="h_01hc8b1t0wcrq7d9kzmt9cspq4"></a>

{% hint style="warning" %}
Please note that the unstaking period for ATOM is 21 days.
{% endhint %}

### 1. Install the Keplr Wallet Extension <a href="#h_01hc8b1t0wyk1r9rxq0jc0pqmw" id="h_01hc8b1t0wyk1r9rxq0jc0pqmw"></a>

While there are a few wallets out there that can be used to stake ATOM, [Keplr](https://wallet.keplr.app/) or [Leap](https://www.leapwallet.io/) are recommended. For this guide, we will be demonstrating the steps with Keplr.&#x20;

In case you don't have the Keplr extension installed in your browser visit [https://www.keplr.app/](https://www.keplr.app/) and click on 'Install Keplr'.

{% hint style="info" %}
If you already have a compatible wallet installed, feel free to skip ahead to: [Stake your ATOM](how-to-stake-atom-cosmos.md#h_01hc8b1t0x326w2f4nzezyfjz6)
{% endhint %}

{% include "../../.gitbook/includes/how-to-install-leap-dropdown.md" %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-20 at 5.00.32 PM.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://uploads-ssl.webflow.com/63fdf8c863bcf00d7ffdff91/6419606a2f4ea84e4f721641_image1.png" alt=""><figcaption></figcaption></figure>

Click on **Install Keplr for Chrome** if you are using a Chrome browser or **Brave** if you are using the Brave browser and follow the installation instructions.

***

### 2. Create or Import an Account <a href="#h_01hc8b1t0x9e4fj4j73357dgbw" id="h_01hc8b1t0x9e4fj4j73357dgbw"></a>

Click on the extension in the Chrome/Brave toolbar and the following page will open up.

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-20 at 5.05.09 PM.png" alt="" width="375"><figcaption></figcaption></figure>

{% hint style="info" %}
In case you do not have an existing Keplr account you can click '**Create a new wallet**'.&#x20;

If you already have a wallet to use, you can select '**Import an existing wallet**' or you can connect with a compatible hardware wallet.

Alternatively, Keplr now offers the ability to associate your wallet with your Google account, however, this is a less secure way of establishing your wallet.
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-20 at 5.07.19 PM.png" alt=""><figcaption></figcaption></figure>

**If you choose to create a new wallet you will be shown 12 words as your mnemonic seed (aka your seed phrase or 12-word phrase).**&#x20;

* You can select the 24 word option for a more secure mnemonic.&#x20;

{% hint style="danger" %}
**Please be sure to back up your mnemonic seed securely!**&#x20;

**Never share this seed phrase with** **anyone, as they will have access to your funds.**&#x20;

* A lost mnemonic seed cannot be recovered.
* Anyone with your mnemonic seed can take your assets.
* It is best to store your seed phrase physically, digital copies or photos are not a secure way to store it.&#x20;
{% endhint %}

Next, enter an account name and a password to unlock your wallet. You will be asked for the mnemonic again to ensure it was recorded correctly.&#x20;

* Enter the 12 or 24 words in order and case sensitive (all lower case).&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-20 at 5.18.45 PM.png" alt="" width="375"><figcaption></figcaption></figure>

After verifying your 12 or 24 word phrase, you will be prompted to select any other Cosmos Hub networks you'd like to add to your wallet.&#x20;

* In this case, we will be adding Cosmos Hub for ATOM, so please be sure to select that from the list or use the search bar to find it.

{% hint style="info" %}
No need to add any other networks if you don't plan on using them yet as you can always select more networks later. &#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-20 at 5.21.13 PM.png" alt="" width="375"><figcaption></figcaption></figure>

Once you selected the relevant networks, click '**Save**' and you'll be all set to go.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-20 at 5.23.52 PM.png" alt="" width="563"><figcaption></figcaption></figure>

***

### 3. Log in to your Wallet <a href="#h_01hc8b1t0xqz8tdapbp8g98nkt" id="h_01hc8b1t0xqz8tdapbp8g98nkt"></a>

Regardless of whether you already have an wallet or if you just created it, you may now click on the extension to view your address or visit [https://wallet.keplr.app/?tab=overview](https://wallet.keplr.app/?tab=overview) to see your full Keplr dashboard.

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-20 at 5.25.10 PM.png" alt=""><figcaption><p>Example of the Keplr dashboard.</p></figcaption></figure>

***

### 4. Staking your ATOM <a href="#h_01hc8b1t0x326w2f4nzezyfjz6" id="h_01hc8b1t0x326w2f4nzezyfjz6"></a>

{% hint style="info" %}
In addition to regular staking, both ATOM and TIA can be liquid staked via Drop Protocol.&#x20;

To learn more please check out the following sections:

* [what-is-liquid-staking](../../getting-started/staking-concepts/what-is-liquid-staking/ "mention")
* [drop-protocol-cosmos-liquid-staking-and-defi-guide.md](../defi-resources/drop-protocol-cosmos-liquid-staking-and-defi-guide.md "mention")
{% endhint %}

If you don't already have ATOM in your wallet, you can fund it with some tokens. You may use an exchange to transfer the tokens to your address or get them from a trusted third party who already holds some.

If you want to stake from the browser extension wallet, you can either navigate to the [Keplr dashboard](https://wallet.keplr.app/) (shown below) or scroll down on the Keplr browser extension wallet screen and select ATOM.&#x20;

From there, you will be prompted to stake.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-20 at 5.28.41 PM.png" alt="" width="356"><figcaption><p>How to access the dashboard from the wallet browser extension</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-20 at 5.28.54 PM.png" alt="" width="358"><figcaption><p>You can stake within the wallet by selecting ATOM.</p></figcaption></figure>

Once you are on the Keplr dashboard, to stake click on the '**Stake**' tab in the left hand side of the dashboard.

Once there, you will see three steps highlighted in the pink box in the screenshot below.&#x20;

1. **Select Chain**
2. **Select Validator**
3. **Stake**

Scroll or through the list or search for the chain you want (in this case **ATOM**).

Then, you can once again either search or scroll through the list to find **Chorus One.**

<figure><img src="../../.gitbook/assets/Screenshot 2024-06-14 at 1.08.13 PM.png" alt=""><figcaption></figcaption></figure>

Once you've clicked on the Chorus One validator, select how much ATOM you wish to stake, then click the '**Stake**' button at the bottom of the screen.

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-06 at 7.55.57 PM.png" alt=""><figcaption><p>Example of the staking screen for ATOM.</p></figcaption></figure>

Clicking on Stake will take you to Keplr wallet for approval. Simply approve the transaction and you will be able to see your stake.

***

### 5. Claiming your Rewards <a href="#h_01hc8b1t0xyhfh6z6pc14htt2d" id="h_01hc8b1t0xyhfh6z6pc14htt2d"></a>

After some time you will see rewards accumulating in your wallet.&#x20;

* This can be easiest to view from the [Keplr dashboard](https://wallet.keplr.app/).

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption><p>Example of how available rewards will display from the Keplr dashboard.</p></figcaption></figure>

{% hint style="info" %}
You can simply go to the [Keplr dashboard](https://wallet.keplr.app/) to claim them by selecting 'Claim' and approving the transaction.

* You will see all rewards available from all networks you are staking with.
* You can choose to claim all pending rewards or select which networks you specifically want to claim rewards for.
{% endhint %}

***

### 6. Unstaking your ATOM

You can unstake your ATOM at any time by navigating to the staking dashboard in your Keplr wallet and selecting the Cosmos chain (ATOM).

From here you will see an overview of your staked balances and you can either click unstake, or follow the same steps you took to stake, however, instead this time you will select unstake.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-06 at 7.56.43 PM.png" alt=""><figcaption><p>Example of the ATOM staking dashboard.</p></figcaption></figure>

If you are staking ATOM to multiple validators you can select which one you wish to unstake from.

Alternatively, you can choose to re-delegate your stake to another validator which happens instantly.

Simply click on the validator you wish to unstake from, follow the prompts, and confirm the amount of ATOM you wish to unstake.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-06 at 7.58.58 PM.png" alt="" width="512"><figcaption><p>Example of the ATOM unstaking screen.</p></figcaption></figure>

When you're ready, click on 'Unstake' and confirm the transaction in your wallet.&#x20;

{% hint style="warning" %}
Please note that there is a 21-day unbonding process (also known as unstaking) for ATOM during which the staked ATOM balance does not earn rewards and cannot be transferred, exchanged, or spent.
{% endhint %}

You can view your currently unstaking balances from the staking dashboard and if you change your mind, you can cancel them at any time if you wish to do so.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-06 at 7.59.17 PM.png" alt=""><figcaption><p>Example of ATOM in the unstaking process.</p></figcaption></figure>

{% hint style="success" %}
Once the 21 day unstaking period has passed your ATOM will become liquid again and you're all done!&#x20;
{% endhint %}

***

## A Note to Institutional Investors

If you are an institutional investor looking to stake Cosmos (ATOM) with Chorus One, please reach out to us via our [staking request form](https://shorturl.at/znows) or at staking@chorus.one

{% include "../../.gitbook/includes/about-c1-dropdown.md" %}
