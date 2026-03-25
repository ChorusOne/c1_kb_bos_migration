---
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/api-reference/ethereum-rewards-api
---

# Ethereum Rewards API

## Overview

The Ethereum Rewards API provides reliable access to **staking reward data** on the Ethereum network. It enables institutions, custodians, funds, and applications to retrieve daily rewards, vault information, and exportable reports for compliance and performance tracking.

***

### Purpose

* Retrieve accurate staking rewards for Ethereum addresses
* Access vault-level reward data (Stakewise V3)
* Generate CSV exports for reporting and reconciliation

***

### Authentication

* Uses **Bearer token** authentication
* Header format: `Authorization: Bearer <API_KEY>`

***

### Data Freshness

* Rewards are calculated every day
* Historical backfill available from the date of first stake
