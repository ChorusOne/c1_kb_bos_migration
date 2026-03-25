---
description: Everything you need to know to stake APT with Chorus One.
hidden: true
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/guides/how-to-stake/how-to-stake-apt-aptos-network
---

# How to stake APT (Aptos Network)

## Overview of the Aptos Network

Aptos is a high-performance Layer 1 blockchain designed to deliver scalability, safety, and user experience for decentralized applications. Built by a team of experienced engineers, Aptos leverages the Move programming language to enable parallel transaction execution, robust security, and high throughput.

The network aims to provide an accessible and developer-friendly environment, fostering innovation across Web3, DeFi, and gaming applications.&#x20;

Staking APT is a simple and rewarding way to contribute to the Aptos network. By choosing Chorus One, you are staking with a trusted validator committed to reliability and performance.

{% hint style="info" %}
For a quick review, feel free to jump ahead to our [FAQ Section](how-to-stake-apt-aptos-network.md#faqs).

If you would like to review the Aptos technical docs, please see: [Delegated Staking on the Aptos Blockchain](https://aptos.dev/en/network/blockchain/delegated-staking)
{% endhint %}

***

## How Staking Works on Aptos

Aptos employs an owner-operator-voter model for staking, which divides responsibilities among three distinct roles.&#x20;

Simply put, the owner account holds the funds, while the operator and voter accounts handle management tasks like staking operations and voting.&#x20;

Using this model, the owner does not have to run a validator and this separation allows for secure delegation of responsibilities without risking the safety of the funds. In turn the operator receives rewards for validating the network and these are distributed among delegators, owners, and voters.&#x20;

{% tabs %}
{% tab title="Delegator" %}
**What is a Delegator?**

A delegator is anyone who has stake in the delegation pool.&#x20;

Delegators earn rewards on their stake minus any commissions for the operator. Delegators can perform the following delegator operations:

1. Add stake
2. Unlock stake
3. Reactivate stake
4. Withdraw stake

Delegators can unlock their stake at any time. However, the stake will only become withdrawable after the delegation pool’s lockup period expires.&#x20;

A delegator's unlocked stake will continue earning rewards until the stake becomes withdrawable.
{% endtab %}

{% tab title="Owner" %}
**What is an Owner?**&#x20;

An owner is anyone who creates an account on the Aptos blockchain.&#x20;

Once they do so, they become the owner of that account and the funds it contains. They have the ability to create a pool and once it reaches 1M APT it can then be managed by an operator.&#x20;
{% endtab %}

{% tab title="Operator" %}
**What is an Operator?**

An operator refers to the validator operator.&#x20;

An operator is a user that the owner can delegate the management of their funds to.&#x20;

This allows the owner to assign their address to the operator allowing for the account to participate in validation of the Aptos Network and thus earn rewards.

The operator receives commission that is distributed automatically at the end of each epoch as rewards.
{% endtab %}

{% tab title="Voter" %}
**What is a Voter?**

Voters are users who and owner can designate to participate in governance.&#x20;

The voter will use the voter keys to sign the governance votes. Generally, voter privileges are assigned to the operator.

See [Governance](https://aptos.dev/en/network/blockchain/governance) for how to participate in the Aptos on-chain governance using the owner-voter model.
{% endtab %}
{% endtabs %}

***

<table data-header-hidden><thead><tr><th width="229"></th><th></th></tr></thead><tbody><tr><td><mark style="color:blue;"><strong>Category</strong></mark></td><td><mark style="color:blue;"><strong>Details</strong></mark></td></tr><tr><td><strong>Minimum Stake</strong></td><td>You must delegate a minimum of 11 APT to begin staking</td></tr><tr><td><strong>Lock-Up/Unbonding Period</strong></td><td>Unlocking your APT takes 0 to 30 days. During this period you will still earn staking rewards. </td></tr><tr><td><strong>Rewards Payout</strong></td><td>Rewards accrue over time and auto-compound to your staked balance. </td></tr><tr><td><strong>Recommended Explorer</strong></td><td><a href="https://explorer.aptoslabs.com/?network=mainnet">https://explorer.aptoslabs.com/?network=mainnet</a></td></tr><tr><td><strong>Recommended Wallets</strong></td><td><a href="https://aptosfoundation.org/ecosystem/project/petra">Petra</a>, <a href="https://chromewebstore.google.com/detail/pontem-crypto-wallet-eth/phkbamefinggmakgklpkljjmgibohnba">Pontem</a>, or <a href="https://aptosfoundation.org/ecosystem/project/aptos-connect">Aptos Connect</a> — Full list seen <a href="https://aptosfoundation.org/ecosystem/projects/wallets">here</a></td></tr><tr><td><strong>Chorus One Validator</strong></td><td><a href="https://explorer.aptoslabs.com/validator/0xda418307cff595ced2af5eb471ec11b1ad6a4907ef57d6e2eeb253bdd5bd9d0d?network=mainnet">Validator Address Direct Link</a> or 0xda418307cff595ced2af5eb471ec11b1ad6a4907ef57d6e2eeb253bdd5bd9d0d</td></tr><tr><td><strong>APY</strong></td><td>Refer to <a href="https://www.stakingrewards.com/asset/aptos">Staking Rewards</a> for current rates</td></tr></tbody></table>

***

### Prerequisite Checklist

Before you start staking APT, ensure you have the following:

* **Aptos Wallet**: A compatible wallet that supports staking, such as [Petra](../../wallets/wallets/getting-started-petra-wallet.md).
* **APT Tokens**: Ensure you have APT tokens in your wallet for staking and a small amount for transaction fees.
  * A minimum of 11 APT must be held in your wallet to begin staking.&#x20;
* **Chorus One Validator**: Locate the Chorus One validator address in the Aptos staking interface.
  * Address: 0xda418307cff595ced2af5eb471ec11b1ad6a4907ef57d6e2eeb253bdd5bd9d0d
  * [Direct link to the Chorus One validator](https://explorer.aptoslabs.com/validator/0xda418307cff595ced2af5eb471ec11b1ad6a4907ef57d6e2eeb253bdd5bd9d0d?network=mainnet)

***

## Step-by-Step Guide to Stake your APT

### Step 1: Set Up Your Wallet

1. Download and install a compatible wallet, such as [Petra wallet](https://aptos.web3doc.top/guides/install-petra-wallet-extension/).&#x20;
   1. For this guide we will be demonstrating the process using Petra.&#x20;
   2. A wallet setup guide can be found here: [getting-started-petra-wallet.md](../../wallets/wallets/getting-started-petra-wallet.md "mention")
2. Create or import your wallet and securely store your recovery phrase.
3. Transfer APT tokens to your wallet.

***

### Step 2: Access the Staking Interface

1. Navigate to the [Chorus One Aptos Validator](https://explorer.aptoslabs.com/validator/0xda418307cff595ced2af5eb471ec11b1ad6a4907ef57d6e2eeb253bdd5bd9d0d?network=mainnet) or search for the validator address using [Aptos explorer](https://explorer.aptoslabs.com/?network=mainnet).
   1. `0xda418307cff595ced2af5eb471ec11b1ad6a4907ef57d6e2eeb253bdd5bd9d0d`
2. From the Chorus One validator on the block explorer connect your Petra wallet by clicking on 'Connect' in the upper-right hand corner of the screen.

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-02 at 10.11.33 PM.png" alt=""><figcaption><p>Example of the Chorus One validator page. </p></figcaption></figure>

Once connected with your Petra wallet you will see your address in the upper-right hand corner of the screen.&#x20;

***

### Step 3: Stake your APT to Chorus One

1. Now that you are on the Chorus One validator page, simply click on 'Stake' to begin.
2. Select the amount of APT you wish to stake. (The minimum is 11 APT).
   1. Note: It is advisable to leave a small amount of APT in your wallet to pay for future transactions and gas fees.&#x20;
3. Once you've selected how much APT you wish to stake, finalize and confirm the transaction in your wallet.&#x20;

***

### Step 4: Managing Your Staked APT

As a delegator, you will earn rewards on your stake minus any commissions for the operator and you can perform the following operations:

1. Add stake
2. Unlock stake
3. Reactivate stake
4. Withdraw stake

***

### Step 5. Unstaking your APT

{% hint style="info" %}
As a delegator, you can unlock your stake at any time. However, the stake will only become withdrawable after the delegation pool’s lockup period expires.&#x20;

During this time, your unlocked stake will continue earning rewards until your stake becomes withdrawable.
{% endhint %}

Enter the amount of APT you wish to unlock (unstake).

1. Review the transaction details and approve and finalize the transaction.
2. Confirm the transaction.
3. Wait until the unlock period ends which can range from 0 to 30 days.
   1. During this time you will still earn APT rewards.&#x20;

***

### FAQs

#### 1. What are the staking rewards for APT?

Staking rewards vary based on network parameters, validator performance, and the total staked amount. Please refer to [Staking Rewards](https://www.stakingrewards.com/asset/aptos) for the most up to date APY information.&#x20;

#### 2. Is there a lock-up period for APT staking? How long does it to to unstake?

You can unstake your APT at any time — However, the stake can only be withdrawn after the delegation pool's lockup period expires. This can range from 0 to 30 days.

* Your unlocked stake will continue earning rewards until the stake can be withdrawn.

#### 3. Do my APT rewards auto-compound?&#x20;

Yes, your APT staking rewards are auto-compounded. The commission is paid to the validator when delegators unstake their positions.

#### 4. Is there a slashing on Aptos?&#x20;

No, currently slashing is not enabled on the Aptos Network.&#x20;

#### 5. Can I adjust my APT stake?

Yes, you can increase the amount of APT you have staked or unstake a portion or all of it at any time. It will then undergo the unlocking period that ranges from 0 to 30 days.&#x20;

***

{% include "../../.gitbook/includes/questions.md" %}

***

## A Note to Institutional Investors

If you are an institutional investor looking to stake on the Aptos Network (APT) with Chorus One, please reach out to us via our [staking request form](https://shorturl.at/znows).&#x20;

{% include "../../.gitbook/includes/about-c1-dropdown.md" %}
