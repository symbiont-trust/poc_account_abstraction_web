# Proof of Concept: Account Abstraction (Social + Wallet Login)

This project demonstrates how to implement account abstraction via **social login (Google, GitHub, etc.)** and **MetaMask** wallet connection using [wagmi](https://wagmi.sh/), [viem](https://viem.sh/), and `@web3modal/wagmi`.


## 1. Project Setup

> Run this only if starting from scratch

npm create vite@latest poc_account_abstraction_web --template react-ts
cd poc_account_abstraction_web

## 2. Install Dependencies

npm install @web3modal/wagmi wagmi viem @tanstack/react-query

## 3. Start Development Server

npm run dev

## 4. Test Login Functionality
A. Social Login (Google, GitHub, etc.)

    Open the app in your browser

    Click the Connect button

    In the modal, choose a social login provider (e.g. Google)

    Complete the login flow

B. MetaMask Wallet Connection

    Install the MetaMask browser extension:
    https://chromewebstore.google.com/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn

    Refresh the app

    Click Connect → Choose MetaMask

    Authorize the connection

After Login

Once logged in (via social or MetaMask), you will see the Ethereum address associated with your wallet or account abstraction session.