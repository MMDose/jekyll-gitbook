# Odin Tools API Usage Guide for Partners

This guide explains how partners can use the Odin Tools API for Rank Boost and Volume Bot services. The API is straightforward and does not require technical documentation beyond this README.

## Prerequisites

* **Security Key (secia)**: Partners must obtain a security key (`secia`) before implementation. Contact the Odin Tools team to acquire this key. All API requests require the `secia` key in the request headers for authentication.

## Rank Boost Bot

### Overview

The Rank Boost Bot boosts rankings when a minimum deposit of 0.2 SOL is received in the bot's wallet.

### Steps to Use

1. **Provide Your Fee Wallet Address**: As a partner, provide your fee wallet address where you will receive a percentage of the usage fees.
2. **Make a POST Request**: Send a POST request to `odin.tools/api/rank/create` with your Contract Address (CA) and the `secia` security key in the headers. The bot will respond with its wallet address.
3. **Deposit SOL**: Send at least 0.2 SOL to the bot's wallet address. Once the deposit is detected, the Rank Boost process will start automatically.

### Example POST Request

```bash
curl -X POST https://api.odin.tools/rank/create \
-H "Content-Type: application/json" \
-H "secia: your-security-key" \
-d '{"ca": "your-contract-address"}'
```

**Response**:

* If successful, the bot returns its wallet address.
* If the `secia` key is missing or invalid, the response will be a 404 error with the message: `"Not found"`.

## Volume Bot

### Overview

The Volume Bot operates similarly but requires a higher minimum deposit to activate.

### Steps to Use

1. **Provide Your Fee Wallet Address**: As a partner, provide your fee wallet address to receive a percentage of the usage fees.
2. **Make a POST Request**: Send a POST request to `odin.tools/api/rank/create` with your Contract Address (CA) and the `secia` security key in the headers. The bot will provide its wallet address in response.
3. **Deposit SOL**: Send at least 1 SOL to the bot's wallet address. The Volume Bot will start automatically upon receiving the deposit.

### Example POST Request

```bash
curl -X POST https://api.odin.tools/volume/create \
-H "Content-Type: application/json" \
-H "secia: your-security-key" \
-d '{"ca": "your-contract-address"}'
```

**Response**:

* If successful, the bot returns its wallet address.
* If the `secia` key is missing or invalid, the response will be a 404 error with the message: `"Not found"`.

## Wallet Monitoring

* The bot checks all registered wallet addresses every 24 hours.
* If a wallet has a balance of 0 SOL, it will be removed from tracking.

## Notes

* Ensure your fee wallet address is correct to receive your percentage of usage fees.
* The `secia` security key must be included in the headers of all API requests. Contact the Odin Tools team to obtain this key.
* The minimum deposit requirements are:
  * **Rank Boost Bot**: 0.2 SOL
  * **Volume Bot**: 1 SOL
* No additional technical documentation is available at this time.
