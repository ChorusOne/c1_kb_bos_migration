---
metaLinks:
  alternates:
    - https://app.gitbook.com/s/KGu77aAU8HQJ5FTwSgOi/api-reference/overview
---

# Overview

### Chorus One Rewards API

The **Chorus One Rewards API** provides comprehensive access to staking rewards data across multiple blockchain networks. **Built for Chorus One clients and partners**, these APIs offer reward tracking with enterprise-grade reliability.

### **Supported Networks**

| Network      | Coverage                      | Key Features                                                           |
| ------------ | ----------------------------- | ---------------------------------------------------------------------- |
| **Solana**   | Validator & Delegator rewards | Voting rewards, transaction fees, Jito MEV tips                        |
| **Ethereum** | StakeWise protocol staking    | Daily rewards, withdrawal tracking, event monitoring                   |
| **TON**      | TON Pool-based staking        | TON pool support, pool level or individual nominators reward reporting |

### **What You Can Track**

* **Daily (epoch) reward earnings** across all supported networks
* **Historical performance** with flexible date range queries
* **Validator/pool performance** metrics and commission structures
* **Staking events** including deposits, withdrawals, and delegation changes

### **Get Started**

1. **Get your API key** from Chorus One
2. **Choose your network** - start with any of our three supported chains
3. **Make your first call** - query rewards for any validator or delegator address

Ready to start tracking staking rewards? Let's get you authenticated and making your first API calls.

### **Authentication** <a href="#undefined" id="undefined"></a>

All API requests require authentication using an API key passed in the request header.

### **API Key Setup**

To access the Chorus One Rewards API, you'll need an API key from our team:

1. **Contact Chorus One** to request API access
2. **Receive your unique API key** via secure communication
3. **Include the key** in all API requests using the `X-API-KEY` header

### **Using Your API Key**

Add your API key to every request header:

```
bashX-API-KEY: your-api-key-here
```

### **Example Requests**

**cURL:**

```bash
curl -H "X-API-KEY: your-api-key-here" \
  "https://api.chorus.one/solana-rewards/v0/delegator_rewards?delegator_address=ADDRESS"
```

**JavaScript:**

```javascript
const headers = {
  'X-API-KEY': 'your-api-key-here',
  'Content-Type': 'application/json'
};

fetch('https://api.chorus.one/ethereum-rewards/v0/delegator_rewards', {
  headers: headers
})
```

**Python:**

```python
import requests

headers = {
    'X-API-KEY': 'your-api-key-here'
}

response = requests.get(
    'https://api.chorus.one/ton-rewards/v0/details',
    headers=headers
)
```

### Modules Overview

#### Supported Networks

* [**Ethereum**](ethereum-rewards-api/)
* [**Solana**](solana-rewards-api/)
* [**TON**](ton-rewards-api/)

### Next Steps

To help you get started with specific blockchain networks, please check out the detailed guides for each supported chain below.

<table data-view="cards"><thead><tr><th></th><th data-type="content-ref"></th><th data-hidden data-card-target data-type="content-ref"></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td><strong>Ethereum</strong></td><td><a href="ethereum-rewards-api/">ethereum-rewards-api</a></td><td><a href="/broken/pages/vDUEVBp0lgtEqg3LyEfY">Broken link</a></td><td><a href="../.gitbook/assets/ethereum.png">ethereum.png</a></td></tr><tr><td><strong>Solana</strong></td><td><a href="solana-rewards-api/">solana-rewards-api</a></td><td><a href="/broken/pages/5YAXVHWHmLO2cGbcof7M">Broken link</a></td><td><a href="../.gitbook/assets/solana.png">solana.png</a></td></tr><tr><td><strong>TON</strong></td><td><a href="ton-rewards-api/">ton-rewards-api</a></td><td><a href="/broken/pages/uGQqpMMbXWkrWspC1B8a">Broken link</a></td><td><a href="../.gitbook/assets/ton.png">ton.png</a></td></tr></tbody></table>
