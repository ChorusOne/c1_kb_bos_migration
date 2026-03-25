---
description: Everything you need to know to stake Celestia (TIA) with Chorus One
hidden: true
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/guides/how-to-stake/how-to-stake-tia-celestia
---

# How to stake TIA (Celestia)

## Overview <a href="#h_01hc8bmw88thcadazdzytpfj3f" id="h_01hc8bmw88thcadazdzytpfj3f"></a>

<table data-header-hidden><thead><tr><th width="267"></th><th></th></tr></thead><tbody><tr><td><mark style="color:blue;"><strong>CATEGORY</strong></mark></td><td><mark style="color:blue;"><strong>DETAILS</strong></mark></td></tr><tr><td><strong>Recommended Wallet</strong></td><td><a href="https://www.keplr.app/">Kelpr</a></td></tr><tr><td><strong>Block Explorers</strong></td><td><a href="https://www.mintscan.io/celestia">https://www.mintscan.io/celestia</a></td></tr><tr><td><strong>Staking Rewards</strong></td><td><a href="https://www.stakingrewards.com/asset/celestia">https://www.stakingrewards.com/asset/celestia</a></td></tr><tr><td><strong>Unstaking Period</strong></td><td>21 Days</td></tr></tbody></table>

## About the Celestia Network

**Celestia (TIA)** is a decentralized, modular blockchain built on the Cosmos SDK that focuses on separating consensus from execution, offering a novel approach to blockchain scalability.&#x20;

Unlike traditional blockchains that bundle transaction execution, consensus, and data availability, Celestia divides these tasks into distinct layers, allowing greater flexibility and efficiency. At its core, Celestia uses data availability sampling, which allows light clients to verify large blocks of data without downloading them in full, improving scalability without compromising security.&#x20;

The blockchain's native token, **TIA**, is used for securing the network through staking and paying for services like data availability and transaction validation. By focusing on modularity, Celestia aims to empower developers to create decentralized applications with more freedom, driving innovation and allowing blockchains to scale more effectively.&#x20;

***

## How to Stake TIA <a href="#h_01hcdmyz7c17s7x9rzvke00phe" id="h_01hcdmyz7c17s7x9rzvke00phe"></a>

{% hint style="warning" %}
Similar to many Cosmos ecosystem blockchains, the unstaking period for TIA is 21 days.&#x20;
{% endhint %}

### 1. Install the Keplr Wallet Extension <a href="#h_01hcdmyz7cbe2a0abfyckedy76" id="h_01hcdmyz7cbe2a0abfyckedy76"></a>

While there are a few wallets out there that can be used to stake TIA, [Keplr](https://wallet.keplr.app/) or [Leap](https://www.leapwallet.io/) are recommended. For this guide, we will be demonstrating the steps with Keplr.&#x20;

In case you don't have the Keplr extension installed in your browser visit [https://www.keplr.app/](https://www.keplr.app/) and click on 'Install Keplr'.

{% hint style="info" %}
If you already have a compatible wallet installed, feel free to skip ahead to: [Stake your TIA](how-to-stake-tia-celestia.md#h_01hc8b1t0x326w2f4nzezyfjz6)
{% endhint %}

{% include "../../.gitbook/includes/how-to-install-leap-dropdown.md" %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-20 at 5.00.32 PM.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://uploads-ssl.webflow.com/63fdf8c863bcf00d7ffdff91/6419606a2f4ea84e4f721641_image1.png" alt=""><figcaption><p>Example of the installation screen using Brave browser.</p></figcaption></figure>

Click on **Install Keplr for Chrome** if you are using a Chrome browser or **Brave** if you are using the Brave browser and follow the installation instructions.

***

### 2. Create or Import an Account <a href="#h_01hc8b1t0x9e4fj4j73357dgbw" id="h_01hc8b1t0x9e4fj4j73357dgbw"></a>

Click on the extension in the Chrome/Brave toolbar and the following page will open up.

* It is recommended to pin it to your browser toolbar by clicking on the pin :pushpin: icon.

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-20 at 5.05.09 PM.png" alt="" width="375"><figcaption><p>Select to either create a new wallet, import an existing wallet, or connect with a hardware wallet.</p></figcaption></figure>

{% hint style="info" %}
In case you do not have an existing Keplr account you can click '**Create a new wallet**'.&#x20;

If you already have a wallet to use, you can select '**Import an existing wallet**' or you can connect with a compatible hardware wallet, such as a Ledger device.\
\
Alternatively, Keplr now offers the ability to associate your wallet with your Google account, however, this is a less secure way of establishing your wallet.
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-20 at 5.07.19 PM.png" alt=""><figcaption><p>Here you can choose between creating, importing, or associating your wallet with your Google account. </p></figcaption></figure>

**If you choose to create a new wallet you will be shown 12 words as your mnemonic seed.**&#x20;

* You can select the 24 words option for a more secure mnemonic.&#x20;

{% hint style="danger" %}
**Please be sure to back up your mnemonic seed securely.**&#x20;

* It is recommended to store it physically, not in a digital format or as a screenshot.

**Never share this seed phrase with anyone, as they will have access to your funds.**&#x20;

* A lost mnemonic seed phrase cannot be recovered.
* Anyone with your mnemonic seed phrase can take control of your assets.
{% endhint %}

Next, enter an account name and a passphrase to lock and unlock your wallet. You will be asked for the mnemonic again.&#x20;

Enter the 12 or 24 words in order and case sensitive (all lower case).&#x20;

This is to make sure you remember the mnemonic and confirm that you wrote it down correctly.

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-20 at 5.18.45 PM.png" alt="" width="375"><figcaption><p>Example of the screen that will show your recovery phrase.</p></figcaption></figure>

After verifying your 12 or 24 word phrase, you will be prompted to select any other Cosmos Hub networks you'd like to add to your wallet.&#x20;

* **In this case, we will be adding Celestia (TIA), so please be sure to select that from the list or use the search bar to find it.**

{% hint style="info" %}
No need to add any other networks if you don't plan on using them yet. You can always select more networks later. &#x20;

* However, it is advisable to have '**Cosmos Hub**' selected when creating your new wallet.
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-20 at 5.21.13 PM (1).png" alt="" width="563"><figcaption><p>Be sure to search for Celestia in the list in addition to Cosmos Hub.</p></figcaption></figure>

Once you selected the relevant networks you want to use, click '**Save**' and you'll be all set to go.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-20 at 5.23.52 PM.png" alt="" width="563"><figcaption><p>All set!! Your Keplr wallet is good to go!</p></figcaption></figure>

***

### 3. Log in to your Wallet <a href="#h_01hc8b1t0xqz8tdapbp8g98nkt" id="h_01hc8b1t0xqz8tdapbp8g98nkt"></a>

Regardless of whether you already have an wallet or if you just created it, you may now click on the Keplr extension to view your address or visit [https://wallet.keplr.app/?tab=overview](https://wallet.keplr.app/?tab=overview) to see your full Keplr dashboard.

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-20 at 5.25.10 PM.png" alt=""><figcaption><p>Example of the Keplr dashboard.</p></figcaption></figure>

***

### 4. Staking your TIA <a href="#h_01hc8b1t0x326w2f4nzezyfjz6" id="h_01hc8b1t0x326w2f4nzezyfjz6"></a>

{% hint style="info" %}
In addition to regular staking, both TIA and ATOM can be liquid staked via Drop Protocol.&#x20;

To learn more please check out the following sections:

* [what-is-liquid-staking](../../getting-started/staking-concepts/what-is-liquid-staking/ "mention")
* [drop-protocol-cosmos-liquid-staking-and-defi-guide.md](../defi-resources/drop-protocol-cosmos-liquid-staking-and-defi-guide.md "mention")
{% endhint %}

If you don't already have TIA in your wallet, you can fund it with some tokens. You may use an exchange to transfer the tokens to your address or get it from someone who already holds them.

If you want to stake from the browser extension wallet, you can either navigate to the [Keplr dashboard](https://wallet.keplr.app/) (shown below) or scroll down on the wallet screen and select TIA.&#x20;

From there, you will be prompted to stake.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-20 at 5.28.41 PM.png" alt="" width="356"><figcaption><p>How to access the dashboard from the wallet browser extension</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-06 at 4.19.12 PM.png" alt="" width="358"><figcaption><p>Or navigate in the wallet to find TIA and select it.</p></figcaption></figure>

Once you are on the [Keplr dashboard](https://wallet.keplr.app/), to stake click on the 'Stake' tab in the left hand side of the dashboard.

Once there, you will see three steps highlighted in the pink box in the screenshot below.&#x20;

1. **Select Chain**
2. **Select Validator**
3. **Stake**

Scroll or through the list or search for the chain you want (in this case **TIA**).

Then, you can either search or scroll through the list to find Chorus One.

<figure><img src="../../.gitbook/assets/Screenshot 2024-06-14 at 1.08.13 PM.png" alt=""><figcaption></figcaption></figure>

Once you've chosen the Chorus One validator, select how much TIA you wish to stake, then click the '**Stake**' button at the bottom of the screen.

Clicking on Stake will take you to Keplr wallet for approval. Approve the transaction and you will be able to see your stake.

* Note: If you are using a Ledger hardware wallet, you will need to have the wallet connected, unlocked, and approve the transaction there.&#x20;

{% hint style="info" %}
Please note that there is a 21 day unbonding process (also known as unstaking) for TIA during which your stake no longer earns rewards and cannot be transferred, exchanged, or spent.
{% endhint %}

***

### 5. Claiming your Rewards <a href="#h_01hc8b1t0xyhfh6z6pc14htt2d" id="h_01hc8b1t0xyhfh6z6pc14htt2d"></a>

After some time you will see rewards accumulating in your wallet.&#x20;

* This can be easiest to view from the [Keplr dashboard](https://wallet.keplr.app/).&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-08-20 at 5.43.04 PM.png" alt=""><figcaption><p>Example of how available rewards will display from the Keplr dashboard.</p></figcaption></figure>

{% hint style="success" %}
You can simply go to the Keplr extension to claim them by selecting '**Claim**' and approving the transaction.&#x20;

* You will see all rewards available from any networks you are staking to.&#x20;
* You can choose to claim all of them, or select which networks you specifically want to claim rewards for.&#x20;
{% endhint %}

***

### 6. Unstaking your TIA

If you wish to unstake your TIA, you can do so from the same interface in Keplr that you used to stake.&#x20;

Either go to the [Keplr dashboard](https://wallet.keplr.app/) or manage your asset directly from the browser extension window.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-06 at 4.24.18 PM.png" alt=""><figcaption><p>Example of managing your TIA stake from the browser extension.</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-06 at 4.26.23 PM.png" alt=""><figcaption><p>Example of the Keplr dashboard where you can see your active stake and selected validators. </p></figcaption></figure>

Simply click on the validator you wish to unstake from and you will be prompted with the following screen.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-06 at 4.29.05 PM.png" alt="" width="563"><figcaption></figcaption></figure>

{% hint style="warning" %}
Please note that TIA undergoes a 21 day unbonding period when unstaking.&#x20;
{% endhint %}

To proceed, click on 'Unstake' and follow the prompts to select the amount of TIA you wish to unstake and then confirm and sign the transaction in your wallet.&#x20;

And that's it! Your TIA will begin unstaking which you can track from your [Keplr dashboard](https://wallet.keplr.app/) under the Staking tab.

* You can view and manage all ongoing undelegations from your Keplr dashboard and cancel them if you change your mind.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-06 at 4.37.14 PM.png" alt=""><figcaption><p>Example above showing a LAVA unstaking transaction in progress. </p></figcaption></figure>

{% hint style="success" %}
After the unbonding period is complete you will be able to transact with your unstaked TIA again!
{% endhint %}

***

## A Note to Institutional Investors

If you are an institutional investor looking to stake Celestia (TIA) with Chorus One, please reach out to us via our [staking request form](https://shorturl.at/znows) or at staking@chorus.one

{% include "../../.gitbook/includes/about-c1-dropdown.md" %}
