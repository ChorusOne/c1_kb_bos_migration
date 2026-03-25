---
description: Everything you need to know the stake MINA with Chorus One.
hidden: true
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/guides/how-to-stake/how-to-stake-mina-mina-protocol
---

# How to stake MINA (Mina Protocol)

<figure><img src="../../.gitbook/assets/6582f70b3d00eaba66639ab3_How to stake MINA.png" alt=""><figcaption></figcaption></figure>

## Overview <a href="#h_01hc86z3k51fkt90tcfhbwdycq" id="h_01hc86z3k51fkt90tcfhbwdycq"></a>

<table data-header-hidden><thead><tr><th width="280"></th><th></th></tr></thead><tbody><tr><td><mark style="color:blue;"><strong>CATEGORY</strong></mark></td><td><mark style="color:blue;"><strong>DETAILS</strong></mark></td></tr><tr><td><strong>Chorus One Validator Address</strong></td><td><a href="https://minascan.io/mainnet/validator/B62qmFf6UZn2sg3j8bYLGmMinzS2FHX6hDM71nFxAfMhvh4hnGBtkBD/delegations?limit=50&#x26;orderBy=DESC&#x26;page=0&#x26;searchStr=&#x26;sortBy=balance">B62qmFf6UZn2sg3j8bYLGmMinzS2FHX6hDM71nFxAfMhvh4hnGBtkBD</a></td></tr><tr><td><strong>Wallet</strong></td><td><a href="https://www.aurowallet.com/">Auro wallet</a> or <a href="https://clor.io/">Clorio wallet</a></td></tr><tr><td><strong>Block Explorer</strong></td><td><a href="https://minascan.io/mainnet/home">https://minascan.io/mainnet/home</a></td></tr><tr><td><strong>Staking Rewards</strong></td><td><a href="https://www.stakingrewards.com/asset/mina">https://www.stakingrewards.com/asset/mina</a></td></tr></tbody></table>

## About MINA <a href="#h_01hc871mrar5z65205pjcp9q3f" id="h_01hc871mrar5z65205pjcp9q3f"></a>

**Mina Protocol (MINA)** is a lightweight blockchain network designed to keep its entire chain size consistently small, around 22 kilobytes, making it the world’s lightest blockchain.&#x20;

It uses zk-SNARKs (zero-knowledge succinct non-interactive arguments of knowledge) to compress its blockchain, enabling users to quickly and easily verify the network without needing extensive storage or computational power. This unique approach allows Mina to maintain decentralized accessibility, even on resource-constrained devices like smartphones.

The protocol focuses on privacy and scalability, utilizing its zk-SNARK technology to support decentralized applications (DApps) without exposing user data. By leveraging a smaller blockchain, Mina aims to democratize blockchain access, offering faster, more secure transactions and a more inclusive environment for developers and users alike.

***

## How to Stake MINA <a href="#h_01hc871mrar5z65205pjcp9q3f" id="h_01hc871mrar5z65205pjcp9q3f"></a>

### 1. Create a Wallet <a href="#h_01hc871mrawqv6cq019edyahyk" id="h_01hc871mrawqv6cq019edyahyk"></a>

To get started, you will want to choose a wallet. Some recommended wallets are [Auro wallet](https://www.aurowallet.com/) or [Clorio wallet](https://clor.io/). For the entirety of this guide, we we will be demonstrating staking using the Auro wallet.

* If you'd like to use Clorio wallet, we have al alternative guide found [here](https://chorus.one/articles/how-to-stake-mina-mina-protocol).&#x20;

{% hint style="info" %}
If you already have a compatible wallet set up, please feel free to skip ahead to [How to stake MINA](how-to-stake-mina-mina-protocol.md#id-3.-how-to-stake-mina).
{% endhint %}

First, navigate to [https://www.aurowallet.com/](https://www.aurowallet.com/) and download the browser extension for your compatible browser.&#x20;

* While a mobile wallet version is available, this guide will be focusing on staking via the browser extension either as a standalone wallet or via a hardware wallet such as [Ledger](https://docs.minaprotocol.com/using-mina/ledger-hardware-wallet).&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-12 at 5.01.34 PM.png" alt=""><figcaption><p>Example of the Auro wallet browser extension installation page.</p></figcaption></figure>

{% hint style="info" %}
In Chrome and Firefox, you can manage your extensions via the jigsaw icon :jigsaw: and then pin it to your browser for easy access with the pin icon. :pushpin:&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-12 at 5.25.31 PM.png" alt=""><figcaption></figcaption></figure>

When you first interact with the browser extension wallet you will have the option to either create a new wallet or restore an existing wallet.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-12 at 5.04.27 PM.png" alt="" width="546"><figcaption></figcaption></figure>

When you opt to create a new wallet you will be prompted to set a password for your wallet.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-12 at 5.06.12 PM.png" alt="" width="551"><figcaption></figcaption></figure>

Next you will be provided with your wallet's mnemonic phrase.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-12 at 5.06.42 PM.png" alt="" width="551"><figcaption></figcaption></figure>

{% hint style="danger" %}
Please be sure to write this down carefully and securely!&#x20;

Your mnemonic phrase (aka your seed phrase or 12-word phrase) cannot be recovered if lost.

* It should never be shared with anyone as it controls your wallet.
* It is advisable to create a backup copy in a physical format and it should not be stored as a digital file or screenshot.&#x20;
{% endhint %}

To ensure you've written down your wallet's seed phrase correctly you will be prompted to re-enter it again after it is shown to you by ordering the supplied words.

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-12 at 5.25.13 PM.png" alt="" width="531"><figcaption></figcaption></figure>

{% hint style="success" %}
And that's it! You're all set and you've now created your Auro wallet!
{% endhint %}

***

### 2. Funding your wallet or using a Ledger

Now that your wallet is set up, you can receive funds to it by simply clicking on 'Receive' and using that address to send MINA to from an external source.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-12 at 5.28.17 PM.png" alt="" width="278"><figcaption></figcaption></figure>

{% hint style="info" %}
Alternatively, if you wish to use a Ledger to secure your MINA, click on the wallet icon in the upper-right corner of the screen and then select 'Add Account' then select 'Hardware Wallet'
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-12 at 5.29.06 PM.png" alt="" width="278"><figcaption></figcaption></figure>

You'll need to have your Ledger device connected and unlocked with the MINA app open and installed on your device.&#x20;

* For instructions on installing the MINA app, please see [Ledger's guide here](https://support.ledger.com/article/4404685362961-zd) and their other [guide specifically for use with the Auro wallet](https://support.ledger.com/article/5458493215901-zd).&#x20;

Once you have set up your Ledger device to be used with the Auro wallet you can switch between your accounts using the wallet icon highlighted before.&#x20;

* If you're using a Ledger you will now have 2 addresses — One belongs to the base Auro wallet controlled by your 12-word phase, the other is the address controlled by the seed phrase of your Ledger device.&#x20;
* Please be sure you are sending MINA to the intended address you wish to store your funds at!&#x20;

***

### 3. How to stake MINA

Once your wallet has some MINA in it, staking is as simple as clicking on the 'Staking' button when you open and unlock your wallet.&#x20;

{% hint style="info" %}
However, there are a few important nuances to know when staking (delegating) MINA.

When delegating, you can technically stake your entire balance or only a portion, depending on the delegation tool or wallet you’re using.

However, most wallets (such as Auro) will delegate your current balance to the validator at the time of delegation.&#x20;

If you later add more MINA to the wallet, the additional tokens may not be automatically staked unless you re-delegate.
{% endhint %}



<figure><img src="../../.gitbook/assets/Screenshot 2024-12-12 at 5.45.36 PM.png" alt="" width="279"><figcaption></figcaption></figure>

When you first go to stake, you will receive some information about the current epoch and how staking works on MINA Protocol if you'd like to learn more. [Auro Wallet's Staking Guide](https://www.aurowallet.com/mina-staking-guide/)

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-12 at 5.47.26 PM.png" alt="" width="277"><figcaption></figcaption></figure>

Simply click on 'Go to staking' to be taken to the next screen where you can select a validator.&#x20;

You can scroll through the list or type in Chorus One to find the Chorus One validator.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-12 at 5.47.41 PM.png" alt="" width="278"><figcaption></figcaption></figure>

Click on the Chorus One validator and you will see a confirmation screen. Note: A memo will not be needed to stake to a validator. Simply go ahead and click on 'Next' to continue.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-12 at 5.49.48 PM.png" alt="" width="277"><figcaption></figcaption></figure>

You'll be prompted with a confirmation screen, proceed from here and if you are using a Ledger you will need to have your device connected and unlocked to proceed.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-12 at 5.51.04 PM.png" alt="" width="279"><figcaption></figcaption></figure>

If you're using a Ledger, the signing process may take a little bit of time, up to 1-3 minutes.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-12 at 5.52.59 PM.png" alt="" width="273"><figcaption></figcaption></figure>

After that you'll know your delegation is complete when you see the following next to your wallet balance.

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-12 at 6.06.31 PM.png" alt="" width="257"><figcaption></figcaption></figure>

***

### 4. Earning MINA rewards

When you stake MINA, rewards are calculated based on the balance you delegated, but they won’t compound automatically.&#x20;

You will need to manually delegate any newly received staking rewards to earn rewards on those new MINA tokens.

***

### 5. Unstaking your MINA

{% hint style="success" %}
MINA is unique as you do not need to unstake your Mina to send it since the protocol uses a liquid staking model.
{% endhint %}

#### Here's what this means:

* **Tokens Are Not Locked:** When you delegate Mina to a validator, your tokens remain in your wallet and are not locked. You can transfer or trade them at any time.
* **Effect on Delegation:** If you send or spend a portion of your staked Mina, the amount delegated to the validator decreases accordingly. Your staking rewards will be based on the updated delegated balance.

{% hint style="info" %}
**For example:** If you delegate 100 MINA and then send 20 MINA, the validator will only be staking 80 MINA after the transaction.
{% endhint %}

{% hint style="warning" %}
However, redelegation may be required as some wallets or validators may not automatically adjust your delegation if your balance changes.&#x20;

If you frequently send or receive MINA, it’s a good idea to check your staking balance periodically to ensure your delegation reflects your intended amount.
{% endhint %}

***

## A Note to Institutional Investors

If you are an institutional investor looking to stake Mina Protocol (MINA) with Chorus One, please reach out to us via our [staking request form](https://shorturl.at/znows) or via email to staking@chorus.one

{% include "../../.gitbook/includes/about-c1-dropdown.md" %}
