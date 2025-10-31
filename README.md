# Welcome to Warden Gate

Warden is a cutting-edge protocol built for the Solana x402 Hackathon under the Best Trustless Agent track.

We address the fundamental challenge in the burgeoning AI agent economy: Trust and Identity. In a world where AI agents transact autonomously, our solution enforces a reputation-gated access layer, ensuring that services and premium APIs only engage with verified, trustworthy on-chain identities, not anonymous bots.

## 🛡️ x402 Warden Gate: The Trustless Agent Gateway
Warden is a cutting-edge protocol built for the Solana x402 Hackathon under the Best Trustless Agent track.

We address the fundamental challenge in the burgeoning AI agent economy: Trust and Identity. In a world where AI agents transact autonomously, our solution enforces a reputation-gated access layer, ensuring that services and premium APIs only engage with verified, trustworthy on-chain identities, not anonymous bots.

### How It Works: Combining Trust with Transactions
Warden integrates an immutable Solana Smart Contract with the x402 payment protocol to create a secure, two-step access system:
1. On-Chain Vetting: An agent's wallet must first satisfy a set of predefined reputation requirements (e.g., holding a specific NFT, maintaining a minimum token balance, or having a positive reputation score).
2. Payment-Gated Access: Only upon successful on-chain validation is the agent permitted to proceed to the x402 payment flow, instantly executing a micropayment to gain access to the protected resource.

3. This creates a high-assurance layer where access is earned through verifiable reputation, and payment is seamless through the x402 standard.

### Key Technologies
- Blockchain: Solana (for fast, low-cost on-chain identity and reputation checks)
- Smart Contracts: Anchor / Rust
- Payment Protocol: x402 (HTTP 402 "Payment Required" standard)
- Server: Node.js / Express (for the API middleware/Facilitator)

### Links
- Repo: https://github.com/Warden-Gate/Warden
- Demo: https://warden-demo.vercel.app/
- X: https://x.com/warden_gate
