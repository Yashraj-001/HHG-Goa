# HHG-Goa
# 💎 Diamante SDK CLI Tool

A powerful Node.js command-line interface for interacting with the [Diamante Blockchain](https://diamcircle.io) using the official `diamante-sdk-js`.

> 🏆 **Project built for selection in HHG (Hack House Goa)**

---

## 🚀 Features

- 🔐 Create or log into Diamante accounts
- 💰 Set up trustlines and issue custom assets
- 📤 Make native and asset payments
- 📉 Manage decentralized exchange offers (buy/sell)
- 📡 Stream real-time payment events
- ⏳ Handle transaction preconditions
- 🧭 Perform pathfinding for asset routing
- 🔗 Establish and manage Starlight payment channels

---

## 🧑‍💻 Getting Started

### 📦 Prerequisites

- Node.js (v14+)
- npm

### 🛠️ Installation

```bash
git clone https://github.com/Yashraj-001/HHG-Goa.git
cd diamante-sdk-cli
npm install
```

---

## 🧪 Usage

```bash
node index.js
```

Upon launch, you'll be prompted with:

```
Select an action:
1: Create a new account
2: Login to an existing account
Enter your choice:
```

Then, after logging in or creating an account:

```
Select an operation to perform:
1: Set up a trustline
2: Issue an asset
3: Make a payment
4: Manage buy offer
5: Manage sell offer
6: Stream payments
7: Handle preconditions
8: Pathfinding
9: Payment Channel
0: Exit
```

---

## 📁 Project Structure

```
diamante-sdk-cli/
├── index.js         # Main CLI logic
├── package.json     # Dependencies and scripts
└── README.md        # You're here!
```

---

## 📚 Tech Stack

- [`diamante-sdk-js`](https://github.com/diamcircle/diamante-sdk-js)
- [`node-fetch`](https://www.npmjs.com/package/node-fetch)
- [`readline`](https://nodejs.org/api/readline.html)
- [`eventsource`](https://www.npmjs.com/package/eventsource)

---

## 🎯 Motivation

This project was created as part of my submission for **HHG (Hack House Goa)** to demonstrate practical experience in:

- Blockchain SDK integration
- Wallet/account management
- Decentralized finance operations
- Real-time data streaming
- Payment channel implementation

---

## 📸 Preview

<!-- Replace with your actual image or terminal screenshot -->
```
> Account Loaded Successfully!
> Trustline Set Successfully!
> Payment Successful!
```

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
