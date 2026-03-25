---
description: Technical information on the Celestia Network and it's token TIA.
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/network-faqs/networks/celestia-tia
---

# Celestia (TIA)

## Validators

{% tabs %}
{% tab title="Mainnet" %}
<table><thead><tr><th width="154" align="center">Name</th><th align="center">Address</th></tr></thead><tbody><tr><td align="center">Chorus One</td><td align="center"><a href="https://www.mintscan.io/celestia/validators/celestiavaloper15urq2dtp9qce4fyc85m6upwm9xul3049gwdz0x">celestiavaloper15urq2dtp9qce4fyc85m6upwm9xul3049gwdz0x</a></td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

## Staking Mechanics <a href="#overview" id="overview"></a>

| **Stake activation time**                                    | Instant                                                                                                                                                                                                  |
| ------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Stake lock-up time**                                       | 21 days                                                                                                                                                                                                  |
| **Re-delegating activation time**                            | Instant                                                                                                                                                                                                  |
| **Rewards frequency**                                        | <p><strong>First reward:</strong> next block once stake is active.</p><p><strong>Rewards frequency:</strong> Every block. </p><p><strong>Last reward:</strong> Last rewards earned before unstaking.</p> |
| **Auto-compounding**                                         | Yes, available for Whitelabel / VaaS customers.                                                                                                                                                          |
| **Self-bond**                                                | None                                                                                                                                                                                                     |
| **Active set**                                               | Yes (100 validators - list [here](https://www.mintscan.io/celestia/validators))                                                                                                                          |
| **Slashing**                                                 | Yes, delegators' staked tokens can be slashed.                                                                                                                                                           |
| **Relationship between validator stake balance and rewards** | Linear. The more stake balance there is on the validator, the more rewards it will earn.                                                                                                                 |

***

## Staking FAQs <a href="#staking-workflow" id="staking-workflow"></a>

#### How does staking work?

On Cosmos Chains such as the Celestia, token holders choose a validator to delegate a select amount of tokens to.&#x20;

The delegator initiates a delegation transaction, which involves locking their tokens in a smart contract. These tokens are then counted towards the validator's total stake.

#### What is the staking process?

After the delegation has been initiated, your TIA is changed to validator shares for the validator you delegate to.

<details>

<summary><strong>Do my funds move to another wallet?</strong></summary>

Staked TIA is not part of your balance anymore, but they don’t go to another address.

</details>

<details>

<summary><strong>Can I keep staking/unstaking from/to the same wallet?</strong></summary>

Yes, you can increase your staked amount or unstake part of it at anytime.

</details>

<details>

<summary><strong>Can I select how much of my wallet balance I want to stake?</strong></summary>

Yes, you select the amount of TIA you want to stake to earn rewards.

</details>

<details>

<summary><strong>How does auto-compounding work?</strong></summary>

In the Cosmos Ecosystem, auto-compounding is possible through a module called [Authz](https://docs.cosmos.network/v0.46/modules/authz/), that allows granting arbitrary privileges from one account (the granter) to another account (the grantee).&#x20;

Delegators utilizing Chorus One's VaaS services can grant the ability to claim rewards and stake them back to the Chorus One Whitelabel Validator. This grant can be revoked at any time.

</details>

<details>

<summary><strong>How do I unstake?</strong></summary>

You can unstake by unbonding your TIA at any time. After you initiated the process:

• You will stop receiving staking rewards.

• It will take 21 days for the unbonding tokens to be liquid.

• You will be able to cancel the unbonding process anytime, as TIA currently supports this function.

</details>

<details>

<summary><strong>Can I unstake a portion of the staked balance?</strong></summary>

Yes, you can select the amount of tokens you want to unstake, which will take 21 days.&#x20;

</details>

<details>

<summary><strong>How is my balance computed at each epoch for the rewards distribution?</strong></summary>

The balance computed at block for the rewards distribution is the staked balance at each respective block.

</details>

<details>

<summary><strong>What is the slashing risk on the Celestia network?</strong></summary>

**Downtime:** During a block window (10,OOO blocks) if a validator signed less than 5% of the blocks, he will get jailed for 10 min and will incur a 0.01% slashing penalty. No rewards can be earned during that jail time.&#x20;

**Double signing:** When a validator attests to two different blocks, it will face slashing.

Stakers who have delegated to the slashed validator will incur a slashing penalty of 5% and the validator won't ever be able to earn rewards again. Delegators will have to re-delegate to another validator in order for their stake to earn rewards again.

</details>

<details>

<summary><strong>How is commission paid?</strong></summary>

Commissions are paid to the validator at the same frequency as the reward distribution, which is every block.

</details>

***
