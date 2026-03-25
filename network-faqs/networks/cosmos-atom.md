---
description: Technical information on the Cosmos Network and it's token ATOM.
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/network-faqs/networks/cosmos-atom
---

# Cosmos (ATOM)

## Validators

{% tabs %}
{% tab title="Mainnet" %}
<table><thead><tr><th width="154" align="center">Name</th><th align="center">Address</th></tr></thead><tbody><tr><td align="center">Chorus One</td><td align="center"><a href="https://www.mintscan.io/cosmos/validators/cosmosvaloper15urq2dtp9qce4fyc85m6upwm9xul3049e02707">cosmosvaloper15urq2dtp9qce4fyc85m6upwm9xul3049e02707</a></td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

## Guide <a href="#overview" id="overview"></a>

{% content-ref url="../../guides/how-to-stake/how-to-stake-atom-cosmos.md" %}
[how-to-stake-atom-cosmos.md](../../guides/how-to-stake/how-to-stake-atom-cosmos.md)
{% endcontent-ref %}

## Staking Mechanics <a href="#overview" id="overview"></a>

<table data-header-hidden><thead><tr><th width="324"></th><th></th></tr></thead><tbody><tr><td><strong>Stake activation time</strong></td><td>Instant</td></tr><tr><td><strong>Stake lock-up time</strong></td><td>21 days</td></tr><tr><td><strong>Re-delegating activation time</strong></td><td>Instant</td></tr><tr><td><strong>Rewards frequency</strong></td><td><p><strong>First reward:</strong> Next block once stake is active. </p><p><strong>Rewards frequency:</strong> Every block.</p><p><strong>Last reward:</strong> Last rewards earned before unstaking.</p></td></tr><tr><td><strong>Auto-compounding</strong></td><td>Yes, available for Whitelabel / VaaS customers.</td></tr><tr><td><strong>Self-bond</strong></td><td>None</td></tr><tr><td><strong>Active set</strong></td><td>Yes (180 validators - list <a href="https://www.mintscan.io/cosmos/validators">here</a>)</td></tr><tr><td><strong>Slashing</strong></td><td>Yes, delegators' staked tokens can be slashed.</td></tr><tr><td><strong>Relationship between validator stake balance and rewards</strong></td><td>Linear. The more stake balance there is on the validator, the more rewards it will earn.</td></tr></tbody></table>

***

## Staking FAQs <a href="#staking-workflow" id="staking-workflow"></a>

#### How does staking work?

On the Cosmos Hub, ATOM token holders choose a validator to delegate a select amount of tokens to.&#x20;

The delegator initiates a delegation transaction, which involves locking their tokens in a smart contract. These tokens are then counted towards the validator's total stake.

#### What is the staking process?

After the delegation has been initiated, your ATOM is changed to validator shares for the validator you delegate to.

<details>

<summary><strong>Do my funds move to another wallet?</strong></summary>

Staked ATOM is not part of your balance anymore, however they don’t go to another address.

</details>

<details>

<summary><strong>Can I keep staking/unstaking from/to the same wallet?</strong></summary>

Yes, you can increase your staked amount or unstake part of it at anytime.

</details>

<details>

<summary><strong>Can I select how much of my wallet balance I want to stake?</strong></summary>

Yes, you select the amount of ATOM you want to stake to earn rewards.

</details>

<details>

<summary><strong>How does auto-compounding work?</strong></summary>

In the Cosmos Ecosystem, auto-compounding is possible through a module called [Authz](https://docs.cosmos.network/v0.46/modules/authz/), that allows granting arbitrary privileges from one account (the granter) to another account (the grantee).&#x20;

Delegators utilizing Chorus One's VaaS services can grant the ability to claim rewards and stake them back to the Chorus One Whitelabel Validator. This grant can be revoked at any time.

</details>

<details>

<summary><strong>How do I unstake?</strong></summary>

You can unstake by unbonding your ATOM at any time. After you initiated the process:

• You will stop receiving staking rewards.

• It will take 21 days for the unbonding tokens to be liquid.

• You will be able to cancel the unbonding process anytime, as ATOM currently supports this function.

</details>

<details>

<summary><strong>Can I unstake a portion of the staked balance?</strong></summary>

Yes, you can select the amount of tokens you want to unstake. The unstaking process takes 21 days.

</details>

<details>

<summary><strong>How is my balance computed at each epoch for the rewards distribution?</strong></summary>

The balance computed at block for the rewards distribution is the staked balance at each respective block.

</details>

<details>

<summary><strong>What is the slashing risk on the Cosmos network?</strong></summary>

**Downtime:** During a block window (10,OOO blocks) if a validator signed less than 5% of the blocks, he will get jailed for 10 min and will incur a 0.01% slashing penalty. No rewards can be earned during that jail time.&#x20;

**Double signing:** When a validator attests to two different blocks, it will face slashing.

Stakers who have delegated to the slashed validator will incur a slashing penalty of 5% and the validator won't ever be able to earn rewards again. Delegators will have to re-delegate to another validator in order for their stake to earn rewards again.

</details>

<details>

<summary><strong>How is commission paid?</strong></summary>

Commissions are paid to the validator at the same frequency as the reward distribution, which is every block.

</details>

***

## Staking Links <a href="#staking-links" id="staking-links"></a>

#### **How can I get testnet tokens?**

You can join the Cosmos Network discord and request some on the [#test-faucet channel](https://discord.com/channels/669268347736686612/953697793476821092)
