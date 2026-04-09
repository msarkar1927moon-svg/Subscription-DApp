# 🌐 Subscription DApp (Soroban | Stellar)

## 🚀 Project Description

Subscription DApp is a decentralized application built on the Stellar network using Soroban smart contracts. It enables users to create and manage recurring payments in a trustless, transparent, and fully decentralized way.

This project removes the need for intermediaries by allowing users to directly control their subscriptions on-chain.

---

<img width="1918" height="992" alt="Screenshot 2026-04-09 145407" src="https://github.com/user-attachments/assets/d16e81d4-82e3-432f-ac9d-60db4aa6fea9" />

## ⚙️ What it does

* 📌 Allows users to create subscription plans with a fixed payment amount
* ⏱️ Enforces time-based recurring payments
* 🔄 Lets users manually trigger subscription payments
* ❌ Enables users to cancel subscriptions anytime
* 📊 Stores subscription data securely on-chain

---

## ✨ Features

* 🔐 Decentralized subscription management
* ⏳ Time-locked recurring payment system
* 👤 User-controlled subscriptions
* ❌ Instant cancellation support
* 📡 Transparent on-chain records
* ⚡ Built with Soroban smart contracts on Stellar

---

## 🧠 Smart Contract Functions

### `create_subscription`

Creates a new subscription with:

* Subscriber address
* Payment amount
* Payment interval

---

### `pay`

Executes subscription payment:

* Checks if payment interval has passed
* Updates last payment timestamp

---

### `cancel`

Cancels an active subscription and removes it from storage.

---

### `get_subscription`

Fetches subscription details for a specific user.

---

## 🛠️ Tech Stack

* Stellar Network (Soroban Smart Contracts)
* Rust
* Soroban SDK

---

## 🔗 Deployed Smart Contract

**Subscription DApp Contract Address:**
👉 `CCXUTMNLHOUJKN2PMMXI7KZG77NDN2JXLHPONFAPFJ2GACUWEDVVK42N`

---

## 🧪 How to Interact

Using Soroban CLI:

```bash
# Example: Invoke contract function
soroban contract invoke \
  --id CCXUTMNLHOUJKN2PMMXI7KZG77NDN2JXLHPONFAPFJ2GACUWEDVVK42N \
  --fn get_subscription \
  --arg <subscriber_address>
```

---

## 📦 Future Improvements

* 💰 Token-based payments (USDC or custom tokens)
* 🔁 Automated recurring payments (cron/bots)
* 📱 Frontend dashboard for managing subscriptions
* 🔔 Payment reminders & notifications
* 🧾 Payment history tracking

---

## 🧠 Use Cases

* SaaS subscriptions
* Membership platforms
* Content creators / Patreon-like systems
* Utility billing systems
* Web3 service payments

---

## 📜 License

MIT License
