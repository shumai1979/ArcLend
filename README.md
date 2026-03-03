# ArcLend

A DeFi lending protocol built on Circle's Arc Testnet.

## What it does

ArcLend lets users deposit USDC or EURC as collateral and borrow against it. Depositors earn interest, borrowers pay interest. No intermediaries — everything runs on a smart contract deployed directly on Arc Testnet.

## Live Contract
```
0x3A2Aa26B62cD5d5E71f1466B4c3b847532d2b3F2
```
[View on Arc Explorer →](https://testnet.arcscan.app/address/0x3A2Aa26B62cD5d5E71f1466B4c3b847532d2b3F2)

## Network

| Parameter | Value |
|-----------|-------|
| Network | Arc Testnet |
| Chain ID | 5042002 |
| Gas Token | USDC |
| RPC | https://arc-testnet.drpc.org |
| Explorer | https://testnet.arcscan.app |

## Token Addresses

| Token | Address |
|-------|---------|
| USDC | `0x3600000000000000000000000000000000000000` |
| EURC | `0x89B50855Aa3bE2F677cD6303Cec089B5F319D72a` |

## Features

- Supply USDC or EURC to earn interest
- Borrow up to 80% LTV against supplied collateral
- Real-time health factor monitoring
- Liquidation protection warnings
- Full MetaMask integration — all transactions are real on-chain

## How to use

1. Add Arc Testnet to MetaMask (Chain ID 5042002, gas token USDC)
2. Get testnet USDC from the [Circle Faucet](https://faucet.circle.com)
3. Open the app and connect your wallet
4. Supply USDC → Approve → Supply
5. Borrow against your collateral if needed

## Stack

- Solidity 0.8.20 — smart contract
- Vanilla HTML/CSS/JS — frontend, no frameworks
- MetaMask provider API — wallet + transaction handling
- Deployed via ethers.js v6

## Disclaimer

Testnet only. No real funds involved.
