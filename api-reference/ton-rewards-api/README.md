---
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/api-reference/ton-rewards-api
---

# Ton Rewards API

## Overview

The Ton Rewards API provides reliable access to **staking reward data** on the TON chain. It enables institutions, custodians, funds, and applications to retrieve daily rewards, vault information, and exportable reports for compliance and performance tracking.

***

### Purpose

* Retrieve accurate staking rewards for Ton addresses
* Access Pool-level reward data (Ton Pool)
* Generate CSV exports for reporting and reconciliation

***

### Authentication

* Uses **Bearer token** authentication
* Header format: `Authorization: Bearer <API_KEY>`

***

### Data Freshness

* Rewards are calculated every validation cycle
* Historical backfill available from the date of first stake



### Ton Pool now also available via dApp

{% embed url="https://chorus.one/articles/chorus-one-introduces-ton-pool-dapp" %}
