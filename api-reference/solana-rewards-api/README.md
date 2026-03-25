---
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/api-reference/solana-rewards-api
---

# Solana Rewards API

<figure><img src="../../.gitbook/assets/image (58).png" alt=""><figcaption></figcaption></figure>

## Overview

The Solana Rewards API provides reliable access to **staking reward data** on the Solana network. It enables institutions, custodians, funds, and applications to retrieve daily and epoch-based rewards, validator information, and exportable reports for compliance and performance tracking.

***

### Purpose

* Retrieve accurate staking rewards for Solana addresses
* Access validator-level reward data
* Generate CSV exports for reporting and reconciliation

***

### Authentication

* Uses **Bearer token** authentication
* Header format: `Authorization: Bearer <API_KEY>`

***

### Data Freshness

* Rewards are calculated and aligned with Solana epochs
* Historical backfill available from the date of first stake
