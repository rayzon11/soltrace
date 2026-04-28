# SolTrace — Solana Wallet Activity Feed

A clean, fast wallet activity explorer for Solana. Enter any wallet address and instantly see categorized transactions, SOL flow stats, and shareable links.

## Live Features
- Real-time transaction fetching via Solana mainnet RPC
- Auto-categorizes txs: Received, Sent, Swaps, NFTs, Program Calls
- SOL in/out stats summary
- Filter by transaction type
- One-click Twitter share
- Links to Solscan for full history
- Works with any valid Solana wallet

## Stack
- Vanilla HTML/CSS/JS (no framework needed)
- Solana JSON-RPC API (mainnet-beta)
- Zero dependencies, loads instantly

## How to Run
Just open index.html in a browser. No build step, no npm install.

Or deploy to any static host (Vercel, Netlify, GitHub Pages).

## Hackathon
Built for Colosseum Frontier Hackathon 2026.
Grant: Superteam Agentic Engineering Grants

---

# Grant Application Text (copy-paste to Superteam Earn form)

**Project name:** SolTrace

**What I want to build:**
A lightweight Solana wallet activity explorer that lets anyone paste a wallet address and instantly see their recent transaction history — categorized, summarized, and shareable. No wallet connection required, no backend, just pure Solana RPC data rendered cleanly.

**How I'll use AI tools:**
I'll use Claude (via Claude Pro) to accelerate the frontend build, help structure the Solana RPC data parsing logic, write clean categorization code for different transaction types (swaps, NFTs, transfers, program calls), and iterate quickly on the UI. The $200 grant covers one month of Claude Pro which is exactly the tool I need to ship this within the Frontier window.

**Solana integration:**
Direct calls to Solana mainnet-beta JSON-RPC — getSignaturesForAddress and getTransactions. No third-party API, no indexer dependency. Pure on-chain data.

**Why it's shippable:**
It's already partially built. The core fetch + render loop is done. Remaining work: deploy to Vercel, add token balance display via getTokenAccountsByOwner, and submit to Colosseum before May 11.

**Timeline:**
- Week 1: Polish UI, add token balances, deploy
- Submit to Colosseum Frontier by May 11
