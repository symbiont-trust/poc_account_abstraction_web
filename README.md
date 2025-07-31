# Proof of Concept: Account Abstraction (Social + Wallet Login)

This project demonstrates how to implement account abstraction via **social login (Google, GitHub, etc.)** and wallet connection using [wagmi](https://wagmi.sh/), [viem](https://viem.sh/), and [`@web3modal/wagmi`](https://www.npmjs.com/package/@web3modal/wagmi).

---

## 1. Project Setup

> Run this only if starting from scratch:

```bash
npm create vite@latest poc_account_abstraction_web --template react-ts
cd poc_account_abstraction_web
```

---

## 2. Install Dependencies

```bash
npm install @web3modal/wagmi wagmi viem @tanstack/react-query
```

---

## 3. Start Development Server

```bash
npm run dev
```

---

## 4. Test Login Functionality

### A. Social Login (Google, GitHub, etc.)

1. Open the app in your browser
2. Click the **Connect** button
3. In the modal, choose a social login provider (e.g. Google)
4. Complete the login flow

---

### B. MetaMask Wallet Connection

1. Install the MetaMask browser extension:
   👉 [Install MetaMask](https://chromewebstore.google.com/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn)

2. Refresh the app

3. Click **Connect** → Choose **MetaMask**

4. Authorize the connection

---

## ✅ After Login

Once logged in (via social or MetaMask), you will see the Ethereum address associated with your wallet or account abstraction session.
