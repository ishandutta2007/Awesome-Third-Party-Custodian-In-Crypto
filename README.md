# Awesome-Third-Party-Custodian-In-Crypto

# Awesome-Third-Party-Custodian-In-Crypto

# Top Third-Party Custodian in Crypto Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Institutional Digital Asset Safekeeping, Key Management & Collateral Settlement*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Third-Party Crypto Custodians**. These platforms provide regulated, institutional-grade safekeeping of digital assets — separating asset ownership from key control through MPC, multi-signature wallets, HSMs, and qualified custody structures that protect clients from counterparty failure.

**Examples** include Tether, BitGo, Fireblocks, Anchorage Digital, Coinbase Custody, Copper, Fidelity Digital Assets, Komainu, Zodia Custody, and Hex Trust (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom key management, and transparent custody infrastructure — ideal for institutions prioritizing key sovereignty, developers building wallet infrastructure, and organizations that want verifiable custody without relying on opaque proprietary systems.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Tether](https://tether.io/)**  
  Stablecoin issuer and reserve custodian holding $181B+ in reserves including $135B in U.S. Treasuries, $12.9B in gold, and $9.9B in bitcoin. Q1-Q3 2025 profit surpassed $10B with $6.8B excess reserves. Not a traditional crypto custody provider for third-party assets, but the largest custodian of stablecoin reserves globally.

- **[BitGo](https://www.bitgo.com/)**  
  The only qualified private custodian with a spotless record of never losing client funds to a breach. Safeguards $100B+ in assets under custody. Offers Go Accounts (active management, off-chain settlement) and Segregated Custody Wallets (cold storage, up to 24-hour withdrawal). $250M insurance coverage, multi-sig and MPC wallets, and regulated trust bank status. Pioneered multi-signature wallets now used industry-wide.

- **[Fireblocks](https://www.fireblocks.com/)**  
  Institutional digital asset infrastructure securing $14T+ in digital assets across 70K+ supported assets and 2,400+ institutional counterparties. Unified platform combining MPC-secured custody, Policy Engine (velocity limits, address whitelists, M-of-N quorum), settlement via Fireblocks Network, and audit-ready financial reporting. Policy enforced before key material is touched. Self-custody infrastructure available with API Co-Signer.

- **[Anchorage Digital](https://www.anchorage.com/)**  
  The only federally chartered digital asset bank in the U.S., operating under OCC supervision. Valuation $4.2B, backed by Andreessen Horowitz, GIC, Goldman Sachs, KKR, and Visa. Qualified custodian offering segregated, bankruptcy-remote accounts, tri-party agreements (Lombard LBTC structure), and integrated options execution. Also holds BitLicense (NY) and MAS license (Singapore).

- **[Coinbase Custody](https://www.coinbase.com/)**  
  12+ years safeguarding digital assets at scale, securing 12% of total crypto market cap. MPC key management with geographically distributed key shares, Cross Domain Solution (CDS) systems (NSA/NCSC-endorsed), air-gapped cold storage, and SOC 1/SOC 2 audits. Open-sourced its MPC cryptography library in March 2025. Supports 40+ blockchains and Prime Onchain Wallet for DeFi participation.

- **[Copper](https://copper.co/)**  
  MPC-based institutional custody and collateral management platform founded 2018. ClearLoop enables off-exchange settlement across Coinbase International, OKX, Bybit, Deribit, Kraken MTF, and more — processing ~$121B monthly. Multi-custodial workflows with BitGo and Komainu. $500M insurance via Aon/Lloyd's, SOC 2 Type 2, ISO 27001.

- **[Fidelity Digital Assets](https://clearingcustody.fidelity.com/)**  
  National trust bank subsidiary of Fidelity Investments offering custody and trading of digital assets. Fidelity Crypto for Wealth Managers integrates custody and execution with the Wealthscape platform for RIAs and advisors.

- **[Komainu](https://komainu.com/)**  
  Joint venture between Nomura, Ledger, and CoinShares founded 2018. Raised $75M from Blockstream Capital Partners (first-ever bitcoin fundraising). Komainu Connect off-exchange margining uses Blockstream Liquid Network for 2-minute settlement finality vs. hours. Qualified custodian with government contracts requiring rigorous background screening. Establishing own bitcoin treasury.

- **[Zodia Custody](https://zodia-custody.com/)**  
  Institutional digital asset operating platform deploying entirely within the institution's own environment. Zodia Solutions is KMS-agnostic with three-gate instruction validation before any key material is invoked. Four functional layers: Hold (custody), Earn (staking/RWA), Trade & Settle (off-venue settlement via Interchange), and Issue. Key management sits in institution's own infrastructure — they hold the keys and remain the custodian.

- **[Hex Trust](https://www.hextrust.com/)**  
  Institutional-grade platform with Hex Safe for digital asset management. Air-gapped cold wallets with 24/7 withdrawals, 2-hour SLA for cold wallets, near-instant for warm wallets. Securosys Primus X200 HSM (FIPS Level 3). WalletConnect integration for access to 17,000+ dApps. Configurable transaction policies, multi-enterprise account structure, and iOS/Android approval app. Can generate 70,000 wallets per minute.

## Open-Source GitHub Projects

- **[TransparenKey](https://xplorestaging.ieee.org/document/11264666)**  
  TPM 2.0-backed open-source custody wallet framework enabling independent verification of key operations. Generates tamper-evident records for key generation, transaction signing, and key deletion via Remote Attestation — allowing end users, auditors, and regulators to confirm system integrity without relying on internal disclosures. Replaces institutional trust with publicly verifiable cryptographic evidence. Presented at IEEE conference October 2025.

- **[Safeheron/multi-party-sig-cpp](https://github.com/Safeheron/multi-party-sig-cpp)**  
  C++ implementation of {t,n}-Threshold Signature Scheme for MPC wallets. 104+ GitHub stars. Production-grade threshold cryptography library for building custodial wallet infrastructure without a single point of key compromise.

- **[fystack/mpcium](https://github.com/fystack/mpcium)**  
  Go-based toolkit for launching distributed crypto wallets with MPC technology in minutes. 35+ GitHub stars, actively maintained. Simplifies MPC wallet deployment for developers building custodial services.

- **[kms-secp256k1-api](https://hub.docker.com/r/interchouette/kms-secp256k1-api)**  
  Rust-based API service acting as a custodial wallet for blockchain apps. Enables cryptographic transactions (generation, signing, listing, deletion) via AWS KMS using secp256k1 elliptic curve — private keys never leave AWS infrastructure. Multi-chain support for Casper, Ethereum, and Cosmos. Endpoints include `/createKey`, `/signTransaction`, `/signTransactionHash`, `/verifySignature`, `/listKeys`, `/deleteKey`. Swagger UI available, security-sensitive routes can be disabled at runtime. Ideal for enterprise blockchain systems, DeFi platforms, and NFT marketplaces with regulatory requirements.

### Additional Strong Open-Source Options

- **Fireblocks Self-Custody Infrastructure** — API Co-Signer for automated transaction approval and signing while maintaining custody. MPC technology with key shares in isolated environments (never brought together), secure hardware enclaves, and key backups. Suitable for building custodial services on top of Fireblocks' security infrastructure.
- **MPC Wallet Libraries** — Safeheron and fystack provide foundational MPC primitives for custom custody solutions.
- **HSM-Based Key Management** — AWS KMS, Azure Key Vault, and Google Cloud KMS for secp256k1 key operations without local key storage.

**Frameworks for building custom systems**: Combine **TransparenKey** for auditable TPM-backed custody, **Safeheron/multi-party-sig-cpp** or **fystack/mpcium** for MPC threshold signing, **kms-secp256k1-api** for AWS KMS-backed key management with multi-chain support, and **Fireblocks Self-Custody Infrastructure** for policy-governed transaction automation to build a complete open-source custodial infrastructure stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Third-party custodians must comply with financial regulations (MiCA, DORA, FCA CASS, MAS PSN02, VASP frameworks), anti-money laundering requirements, and applicable securities laws. Custody of digital assets involves significant risk including loss of keys, regulatory changes, and counterparty failure.
- Self-hosted open-source solutions require proper security hardening, HSM/TPM infrastructure, and independent security audits before use with production assets.

---

**Made for institutional investors, digital asset operations teams, custody engineers, and developers building secure custody infrastructure.**  
Let's make third-party crypto custody more open, auditable, and institutionally accessible.
