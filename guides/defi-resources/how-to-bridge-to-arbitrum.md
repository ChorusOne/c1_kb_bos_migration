---
description: Everything you need to know to bridge your assets to Arbitrum
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/guides/defi-resources/how-to-bridge-to-arbitrum
---

# How to bridge to Arbitrum

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-10 at 5.54.48 PM.png" alt="" width="563"><figcaption></figcaption></figure>

## What is Arbitrum?&#x20;

Arbitrum is a Layer 2 scaling solution for Ethereum that enhances transaction speed and reduces costs by processing transactions off-chain, while still leveraging the security of Ethereum's blockchain.&#x20;

It uses a technology called Optimistic Rollups, which bundles multiple transactions together and submits them as a single batch to the Ethereum mainnet. This allows users to enjoy faster and cheaper transactions for decentralized applications (dApps), without sacrificing the decentralized security provided by Ethereum.

## What is Bridging?

Bridging to Arbitrum involves transferring assets from a Layer 1 blockchain, like Ethereum, to Arbitrum, a Layer 2 scaling solution. The process requires users to interact with a bridge interface where they connect their wallet (such as MetaMask), select the token they wish to transfer, and approve the transaction. The tokens are then locked on the Layer 1 chain and represented as wrapped tokens on Arbitrum.&#x20;

{% hint style="info" %}
This process can take some time, and it's important to be aware of gas fees on both chains and potential delays when bridging back to Ethereum.

* For example, if you bridge an ERC20 token to Arbitrum, make sure you also bridge ETH in order to have gas to transact on Arbitrum.&#x20;
{% endhint %}

***

## How to Bridge to Arbitrum

### 1.) Navigate to the Arbitrum Bridge

First, navigate to the Arbitrum bridge website found here:

* [https://bridge.arbitrum.io/](https://bridge.arbitrum.io/?destinationChain=arbitrum-one\&sourceChain=ethereum)

{% hint style="info" %}
**Note:** While there are many bridging protocols available, for the sake of this guide we will be using the official Arbitrum bridge. If you choose to use other bridging protocols, it is advisable to always do you due diligence to ensure the bridge is safe.&#x20;
{% endhint %}

Once you have navigated to the Arbitrum bridging website, you can connect a compatible wallet.&#x20;

For this guide, we will be using [MetaMask](https://metamask.io/download/).

* If you don't yet have a MetaMask wallet, please follow the official guide from MetaMask to get started and set up your new wallet: [Getting Started with MetaMask](https://support.metamask.io/getting-started/getting-started-with-metamask/)
* While MetaMask is compatible with many browsers, Chromium based browsers such as Google Chrome or Brave tend to have the best compatibility across various dApps.&#x20;

### 2.) Connect your Wallet

Once your MetaMask or other compatible wallet is ready, connect to the Arbitrum bridge when prompted, or click on the green button in the upper-right hand corner that reads 'Connect Wallet'.

* If you are prompted, or need help connecting your MetaMask wallet to the Arbitrum network, please see the following section: [Connecting to the Arbitrum Network](how-to-bridge-to-arbitrum.md#id-6.-connecting-to-the-arbitrum-network)

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-10 at 6.02.30 PM.png" alt="" width="563"><figcaption><p>Example of the wallet connection prompt.</p></figcaption></figure>

After connecting your wallet, the bridge page will default to the Ethereum (ETH) asset.

* It is advisable to first bridge some ETH to Arbitrum if you don't have any already, as it will be needed to pay for all gas fees on the Arbitrum network.&#x20;
* After this, you can bridge over any other compatible tokens you wish.&#x20;

### 3.) Bridging your assets to Arbitrum

You'll see a screen similar to the screenshot below. This illustrates an example of bridging over some ETH to Arbitrum.&#x20;

You can enter an amount of your choosing and see how much you will receive on Arbitrum as well as the expected gas fees involved with the transaction.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-10 at 5.43.55 PM.png" alt="" width="507"><figcaption><p>Example of bridging ETH to Arbitrum.</p></figcaption></figure>

Go ahead and proceed once you have selected how much ETH you wish to bridge.&#x20;

You will be prompted to sign the transaction via your MetaMask wallet (and Ledger) if you are using a hardware wallet.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-10 at 5.44.20 PM.png" alt=""><figcaption><p>Example of a MetaMask approval transaction. </p></figcaption></figure>

{% hint style="success" %}
Finalize your transaction and you're all set! You've now bridged your ETH to Arbitrum!&#x20;
{% endhint %}

### 4.) Bridging other tokens to Arbitrum

In addition to ETH, it is possible to bridge many other ERC20 tokens to Arbitrum.&#x20;

You can select from the list to find what you want to bridge. In the example below, we will be using USDC.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-10 at 5.45.49 PM.png" alt="" width="480"><figcaption><p>Example of a USDC bridging screen.</p></figcaption></figure>

Go ahead and approve the transaction in a similar fashion as you did for your ETH.&#x20;

{% hint style="info" %}
However, for ERC20 tokens, you may be prompted to first approve a spending limit for the token before you can interact with the smart contract to bridge you asset.&#x20;

* This will incur an ETH gas fee to approve.
* You can set the approval limit to only what you wish to move, or higher if you plan to bridge more of the same token in the future.&#x20;
{% endhint %}

For some tokens, USDC being a great example of this, you will get to choose what version of the token you wish to receive on Arbitrum.&#x20;

* For USDC, you can choose to bridge native USDC via the Arbitrum bridge or a third party bridge
* Alternatively, you can choose Wrapped USDC, known as USDC.e

Any of the options are fine, however, be sure to read the fine print on what the differences are between native and wrapped versions of your ERC20 tokens, as depending on your planned use case on Arbitrum, this differentiation may matter!&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-10 at 5.46.50 PM.png" alt=""><figcaption><p>Example of choosing the type of USDC to receive on Arbitrum.</p></figcaption></figure>

### 5.) Checking on the status of your bridged assets

After you've initiated some bridging transactions, you will likely be prompted to view your transaction history.&#x20;

* It's worth noting that bridging assets to Arbitrum can take a few minutes depending on network conditions and the type of assets you are bridging.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-10 at 5.48.51 PM.png" alt=""><figcaption><p>Example of pending bridge transactions of ETH and USDC.</p></figcaption></figure>

{% hint style="info" %}
You can also find your asset transaction history by clicking on your wallet address in the upper-right corner of the bridge screen and then selecting 'Transactions'.&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-10 at 6.17.18 PM.png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
And that's it, you'e all set! You've successfully bridged your assets to Arbitrum.&#x20;
{% endhint %}

### 6.) Connecting to the Arbitrum Network

If you haven't already added Arbitrum as a network to your MetaMask wallet, you will need to in order to interact with your Arbitrum assets.&#x20;

The wallet may prompt you automatically, and if so, go ahead and proceed with those prompts.&#x20;

If you are not prompted, you can add the Arbitrum Network to MetaMask via the following steps.

* Open your MetaMask browser wallet and click the network selection button.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-10 at 5.49.23 PM.png" alt=""><figcaption></figcaption></figure>

Next, select Arbitrum if it appears in the list. If it does not, you can search for it via the search bar or click 'Add network' to manually enter the network information.&#x20;

* Go ahead and follow the prompts to switch to and connect to the Arbitrum Network.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-10 at 5.50.09 PM.png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
You're all set! You've now connected to the Arbitrum network and you should see any bridged assets appearing in your wallet if the trsansactions have completed.&#x20;
{% endhint %}
