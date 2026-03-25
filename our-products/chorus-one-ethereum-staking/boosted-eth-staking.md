---
description: How to maximize your ETH rewards with StakeWise Boost.
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/our-products/chorus-one-ethereum-staking/boosted-eth-staking
---

# Boosted ETH Staking

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-25 at 7.58.20 PM.png" alt=""><figcaption><p>Source: <a href="https://stakewise.medium.com/maximize-your-rewards-with-stakewise-boost-8799ae1e5731">https://stakewise.medium.com/maximize-your-rewards-with-stakewise-boost-8799ae1e5731</a></p></figcaption></figure>

## What is StakeWise Boost?

## Overview

StakeWise Boost is an advanced staking strategy that amplifies your ETH staking rewards by leveraging osETH (a [Liquid Staking Token](../../getting-started/staking-concepts/what-is-liquid-staking/) mintable via [Chorus One Staking](./)) as collateral to borrow additional ETH.&#x20;

This enables an automatic looped staking process powered by StakeWise that increases your stake power via [looping](boosted-eth-staking.md#how-it-works-the-looping-mechanism) up to a maximum of 14 times via automated borrowing and lending utilizing Aave, thus enhancing your rewards with minimal liquidation risks.

Chorus One is pleased to provide this opportunity for our customers staking ETH and this guide below will cover step by step how to take part in the process so you can maximize your ETH staking rewards with this new innovation from StakeWise while understanding the risks and mechanics behind Boosted ETH staking.

***

### Key Benefits of StakeWise Boost

* 📈 Higher Staking Rewards: Achieve up to 3x the usual ETH staking APY.
* :white\_check\_mark: Simple and User-Friendly: Deposit and withdraw assets easily via the StakeWise UI.
* 🔒 Risk Mitigation: No liquidations from osETH price fluctuations; built-in de-risking mechanisms adjust positions as needed.
* 💰 No Performance Fees: Unlike some competitors, StakeWise Boost doesn’t charge fees on your earnings.

***

### How it Works: The Looping Mechanism

{% hint style="success" %}
Looped staking allows users to reinvest their staked ETH (ETH that is already earning rewards) to generate additional staking yield.&#x20;

This mechanism takes advantage of lending protocols and allows for recursive staking.

All of this happens behind the scenes via StakeWise, but feel free to learn more below.&#x20;
{% endhint %}

<details>

<summary>How Looped Staking Works Behind the Scenes</summary>

1\. Deposit ETH into a Vault – First stake your ETH into [OPUS Pool](outdated-staking-ethereum.md) or a StakeWise v3 vault. This ETH gets staked with Ethereum validators.

2\. You'll receive osETH (a [Liquid Staking Token also known as an LST](../../getting-started/staking-concepts/what-is-liquid-staking/)) representing your staked ETH position.

3\. The osETH is used as collateral to borrow more ETH on lending protocols such as Aave.

4\. Stake the Borrowed ETH Again – The borrowed ETH is then redeposited into the StakeWise vault, creating a recursive loop.

5\. Repeat the Process – This cycle can be repeated multiple times, compounding the staking rewards up to a maximum of 14 times.&#x20;

</details>

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-26 at 8.32.43 PM.png" alt=""><figcaption><p>Source: <a href="https://stakewise.medium.com/maximize-your-rewards-with-stakewise-boost-8799ae1e5731">https://stakewise.medium.com/maximize-your-rewards-with-stakewise-boost-8799ae1e5731</a></p></figcaption></figure>

{% hint style="info" %}
APY varies based on market conditions, typically ranging between 4-7%.

Additional incentives from partners (SSV, Obol, SWISE, osETH) may further increase rewards.

* Vaults with 90% LTV → 6x staking loops.
  * This means your initial ETH stake could be looped and boosted up to 6 times.
* Vaults with 100% LTV → 14x staking loops.
  * This means your initial ETH stake could be looped and boosted up the a maximum of 14 times.
{% endhint %}

{% hint style="success" %}
Remember, all this happens automatically when using a [StakeWise Boosted ETH vault](https://app.stakewise.io/).&#x20;

For example, this can be done via [Chorus One's MEV Max vault](https://app.stakewise.io/vault/mainnet/0xe6d8d8ac54461b1c5ed15740eee322043f696c08).&#x20;
{% endhint %}

***

### Benefits, Risks, & Audits

{% tabs %}
{% tab title="Benefits of Boosted ETH Staking" %}
* No Performance Fees: 100% of staking rewards go to you.
* No Liquidation from osETH Fluctuations: Aave uses a stable native rate feed.
* Increased Staking Yield – By restaking borrowed ETH, users effectively amplify their exposure to staking rewards.
* More Efficient Capital Usage – Instead of holding staked ETH passively, users can leverage it to generate additional rewards.
* Higher APY – Compared to simple staking, looped staking can increase the effective staking APY, depending on how many times the process is repeated.
{% endtab %}

{% tab title="Risk Considerations" %}
* Boost APY fluctuates based on Aave borrowing rates.
  * Borrowing costs can fluctuate, potentially offsetting the additional staking rewards.
* Monitor Boost APY regularly and exit if it remains negative for 7+ days.
* Liquidation risk is low but possible if Boost APY remains negative for an extended period.
* This mechanism relies on multiple smart contracts interacting, which increases exposure to potential exploits.

For a more detailed analysis of key risks around using Boost, please check out [this article](https://stakewise.medium.com/how-stakewise-boost-keeps-your-rewards-juicy-your-stake-safe-8839764a5a7d).
{% endtab %}

{% tab title="Audits" %}
* StakeWise Boost has been audited.
  * The contracts for Boost have been audited by [Sigma Prime](https://github.com/stakewise/v3-core/blob/main/audits/2024-09-Sigma-Prime.pdf) and [Hexens](https://github.com/stakewise/v3-periphery/blob/main/audits/2024-09-Hexens.pdf), and Aave has been audited [multiple times as well](https://github.com/aave-dao/aave-v3-origin/tree/main/audits).

For a more detailed analysis of key risks around using Boost, please check out [this article](https://stakewise.medium.com/how-stakewise-boost-keeps-your-rewards-juicy-your-stake-safe-8839764a5a7d).
{% endtab %}
{% endtabs %}

***

## Step-by-Step Guide to Using StakeWise Boost

{% stepper %}
{% step %}
### Accessing StakeWise Boost

You can access the StakeWise Boost page at: [https://app.stakewise.io/](https://app.stakewise.io/)

Boosted Staking is available in [Vaults upgraded to version 3.0](https://stakewise.medium.com/vaults-v3-0-optional-upgrade-now-available-c26cefd8be0b).

This includes **Chorus One's MEV Max Vault**, accessible via [OPUS Pool](./) and on StakeWise's interface [here](https://app.stakewise.io/vault/mainnet/0xe6d8d8ac54461b1c5ed15740eee322043f696c08).&#x20;

* You can also use the [Stake page](https://app.stakewise.io/) to access the interface or the [Vaults](https://app.stakewise.io/vaults) tab.&#x20;

{% hint style="info" %}
Once you're on the StakeWise Boost page or Vaults page, please ensure that the Ethereum Network is selected and connect your wallet.&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-24 at 5.53.33 PM.png" alt="" width="563"><figcaption><p>Ensure Ethereum is selected then connect your compatible wallet.</p></figcaption></figure>

There are quite a few wallets to choose from. You can connect directly with Ledger, or use MetaMask, OKX, WalletConnect among others.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-24 at 5.55.26 PM.png" alt="" width="375"><figcaption><p>Wallet options for StakeWise Boost.</p></figcaption></figure>

{% hint style="info" %}
For this guide, we will be demonstrating with a Ledger connected via MetaMask.
{% endhint %}

{% hint style="danger" %}
**It should be noted that if you are using Rabby Wallet, you may see a warning like the screenshot below.**&#x20;

Rest assured this is expected behavior.

Shown below, this address `(0x57...)` is created during the transaction for all boosting with Aave operations.&#x20;

This is individual for each user and once the transaction is sent it deploys a contract there.

This warning appears because when a user sends an approval and this address is empty Rabby wallet perceives it as an EOA.
{% endhint %}

<figure><img src="../../.gitbook/assets/Rabby Wallet Notification 2025-02-24 at 9.50.40 PM.jpg" alt="" width="375"><figcaption><p>Rabby Wallet warning example.</p></figcaption></figure>

{% hint style="success" %}
If you are using MetaMask or connecting directly with Ledger or another wallet, it is unlikely you will see this warning.&#x20;
{% endhint %}

Once your wallet is connected, you should see your address appear in the upper-right hand corner of the page. You can then proceed to preview your boosted staking options.&#x20;

{% hint style="warning" %}
If you don't have any osETH, please refer to [outdated-staking-ethereum.md](outdated-staking-ethereum.md "mention") to learn how to mint osETH using OPUS Pool.

Or you can stake ETH via the StakeWise interface to the OPUS Pool Vault as shown below.&#x20;

* Essentially it's two different UIs to interact with the same vault.&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-24 at 5.57.20 PM.png" alt="" width="563"><figcaption><p>Example of the Staking screen with a connected wallet.</p></figcaption></figure>

{% hint style="info" %}
If you have already staked your ETH and minted osETH via OPUS Pool, you can navigate to the StakeWise Vaults page at: [https://app.stakewise.io/vaults](https://app.stakewise.io/vaults)

* Be sure to click on 'Deposits' to see the vaults you are already staking with.&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-26 at 9.27.32 PM.png" alt=""><figcaption><p>Example of <a href="https://app.stakewise.io/vaults">https://app.stakewise.io/vaults</a></p></figcaption></figure>

{% hint style="success" %}
You can click on the vault of your choosing, in this example, the Chorus One MEV Max vault to see more details.&#x20;
{% endhint %}

From there you will see a detailed view of the vault you're staking with.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-26 at 9.24.02 PM.png" alt=""><figcaption><p>Example of the Chorus One MEV Max vault.</p></figcaption></figure>

***
{% endstep %}

{% step %}
### Review the Boost APY & Add to your Boost

Next, you can review the maximum Boost APY available in the Vault.

You can add a boost either from the [Vault page](https://app.stakewise.io/vault/mainnet/0xe6d8d8ac54461b1c5ed15740eee322043f696c08) or from the [Staking interface](https://app.stakewise.io/) page.

{% hint style="success" %}
The highest APY is achieved by depositing all the osETH you can mint into Boost.
{% endhint %}

Below is how you could add an osETH staking Boost to the [Chorus One MEV Max vault](https://app.stakewise.io/vault/mainnet/0xe6d8d8ac54461b1c5ed15740eee322043f696c08).

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-26 at 9.32.30 PM.png" alt="" width="375"><figcaption><p>Click on the + button to add to your Boost.</p></figcaption></figure>

Alternatively, you can perform Boosted ETH staking from the main [Staking interface page](https://app.stakewise.io/).&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-24 at 10.26.13 PM.png" alt="" width="563"><figcaption><p>Example of the Boosted staking interface.</p></figcaption></figure>

{% hint style="info" %}
The Boost mechanism operates seamlessly in the background.

If you're curious, please see: [#how-it-works-the-looping-mechanism](boosted-eth-staking.md#how-it-works-the-looping-mechanism "mention")
{% endhint %}

***
{% endstep %}

{% step %}
### Deposit and Boost your osETH

Once everything looks good, go ahead and submit the transaction and approve it in your wallet.&#x20;

* **Note:** The first time you Boost, you’ll need to approve osETH spending.

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-24 at 10.27.51 PM.png" alt="" width="563"><figcaption><p>Example of a transaction in progress.</p></figcaption></figure>

Once it completes, you can review the transaction on-chain and will be shown how much osETH you boosted!&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-24 at 10.28.06 PM.png" alt="" width="563"><figcaption><p>Example of a successful ETH boost transaction.</p></figcaption></figure>

{% hint style="success" %}
Once your deposit is confirmed, Boost will automatically start generating enhanced staking rewards!
{% endhint %}

***
{% endstep %}

{% step %}
### Reviewing your Boosted ETH & Monitoring your Boost

To see how your Boosted ETH stake is doing, all you need to do is select the 'Balance' tab from the [Staking interface](https://app.stakewise.io/).&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-26 at 8.43.45 PM.png" alt="" width="563"><figcaption><p>Example of the Balance tab to review your Boosted ETH stake.</p></figcaption></figure>

You can also view more statistics overtime by clicking on the 'Statistics' button highlighted above.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-26 at 8.44.36 PM.png" alt="" width="563"><figcaption><p>Here you can see how your Boosted ETH stake has performed over time.</p></figcaption></figure>

Alternatively, you can view and export your staking history and APY from the [Chorus One MEV Max vault](https://app.stakewise.io/vault/mainnet/0xe6d8d8ac54461b1c5ed15740eee322043f696c08) as illustrated in the screenshot below by clicking on 'My stats'.

{% hint style="success" %}
You also have the option to export your historic staking history from the vault via the 'Export' button.&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-26 at 9.36.56 PM.png" alt=""><figcaption><p>Example of the Chorus One MEV Max vault interface.</p></figcaption></figure>

{% hint style="warning" %}
**It is advisable to regularly check your Boost APY in the** [**Vault**](https://app.stakewise.io/vaults) **section.**

* If Boost APY becomes negative for more than 7 days, consider unboosting your position.
* StakeWise provides community updates on optimal entry and exit times via their [Discord](https://discord.gg/stakewise).
{% endhint %}

***
{% endstep %}

{% step %}
### Unboosting & Unstaking your ETH

To unboost your ETH, simply click on the two criss-crossing arrows in the upper-left hand corner to switch to unstaking mode and navigate to the 'Boost' tab.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-26 at 8.45.11 PM.png" alt="" width="563"><figcaption><p>Example of the Unboost screen.</p></figcaption></figure>

Or if interfacing directly with the Vault, click on the "-" button to unboost your stake, or for example, from the [Chorus One MEV Max vault](https://app.stakewise.io/vault/mainnet/0xe6d8d8ac54461b1c5ed15740eee322043f696c08).&#x20;

Select the osETH amount you want to withdraw and confirm.

* This queues your unboost request which can take up to 14 days to process contingent on stake size, however, timelines can also be quite a bit shorter.&#x20;
* Once processed, please be sure to claim your withdrawn assets from the [Vaults](https://app.stakewise.io/vaults) page.

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-26 at 9.32.30 PM.png" alt="" width="375"><figcaption><p>Click on the "-" button to unboost.</p></figcaption></figure>

#### Similar steps also apply to unstake your ETH if you wish to do so.

{% hint style="info" %}
Your osETH can be unstaked regardless of where you minted it from.

However, if you originally staked via OPUS Pool, it's advisable to complete the osETH burning and unstaking process there.

* Please refer to: [unstaking-ethereum.md](unstaking-ethereum.md "mention")
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2025-02-26 at 9.15.15 PM.png" alt="" width="563"><figcaption><p>Example of the Unstaking screen.</p></figcaption></figure>

Please note that unstaking your ETH from a vault will also undergo a withdrawal period up to a maximum of approximately 14 days contingent on stake size. However, it can be less due to network conditions.

* To learn more please consider reviewing [unstaking-ethereum.md](unstaking-ethereum.md "mention")
{% endstep %}
{% endstepper %}

***

{% include "../../.gitbook/includes/questions.md" %}

***

{% include "../../.gitbook/includes/about-c1-dropdown.md" %}
