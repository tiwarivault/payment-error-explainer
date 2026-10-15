# AI PSP Error Code Assistant

A single-file, client-side tool to look up 50+ payment error codes across cards, UPI, netbanking, wallets and EMI — whose side the issue is on and the likely fix — with an optional AI explanation.

**Live:** https://tiwarivault.github.io/payment-error-explainer/

## What it does
- Instant search across 50+ error codes, with category filters (Card / UPI / Netbanking / Wallet / EMI-BNPL / Integration / Provisioning / Risk / General)
- Each entry: what it means, whose side it's on (customer / merchant-integration / bank-PSP) and the likely fix
- **Optional AI mode** (bring your own Claude API key) for a deeper, context-aware explanation of any code

## Knowledge base vs AI mode
The 50+ codes are a curated, deterministic **knowledge base** — fast and offline. **AI mode is optional** and adds a deeper, free-text explanation for anything not covered or when you want more detail.

## Privacy
Runs entirely in your browser. AI mode sends only the code/message you look up to Anthropic with your own key.

## Note
Generic, public payments knowledge only — no proprietary data. Portfolio project by Prashant Tiwari (payments support → AI).
