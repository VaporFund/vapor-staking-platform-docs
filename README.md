# VaporFund Staking Platform Documentation

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/vaporfund/vaporfund-staking-platform)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-active-success.svg)]()

> **Comprehensive technical documentation for the VaporFund Staking Platform** - A secure, decentralized multi-token staking application built on Ethereum.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Documentation Structure](#documentation-structure)
- [Quick Start](#quick-start)
- [Core Documents](#core-documents)
- [For Different Audiences](#for-different-audiences)
- [Documentation Standards](#documentation-standards)
- [Contributing](#contributing)
- [Additional Resources](#additional-resources)
- [Version Information](#version-information)
- [Support](#support)

---

## 🎯 Overview

This directory contains comprehensive technical documentation for the VaporFund Staking Platform. The documentation is organized as an Obsidian vault with cross-referenced content for easy navigation and includes:

- Platform architecture and design decisions
- Smart contract specifications
- API documentation
- Partner integration and external APIs
- User referrals and rewards program
- Business model and tokenomics
- Security measures and risk management
- Deployment and infrastructure guides

---

## 📚 Documentation Structure

### Core Documents

| Document                               | Description                                     | Target Audience                         |
| -------------------------------------- | ----------------------------------------------- | --------------------------------------- |
| **[WHITEPAPER.md](WHITEPAPER.md)**     | Platform vision, business model, and tokenomics | Investors, Stakeholders, General Public |
| **[ARCHITECTURE.md](ARCHITECTURE.md)** | Technical architecture and visual diagrams      | Developers, Partners, Technical Teams   |
| **[EARNING.md](EARNING.md)**           | Affiliate and partner earning programs          | Affiliates, Partners, Content Creators  |
| **[ROADMAP.md](ROADMAP.md)**           | Product roadmap and development milestones      | Stakeholders, Investors, Community      |

---

## 🚀 Quick Start

### For Developers

1. Start with **[ARCHITECTURE.md](ARCHITECTURE.md)** for technical implementation details
2. Review the smart contract architecture section
3. Check API specifications and deployment procedures
4. See infrastructure setup for local development

### For Stakeholders & Investors

1. Read **[WHITEPAPER.md](WHITEPAPER.md)** for business vision
2. Review tokenomics and reward distribution model
3. Check **[ROADMAP.md](ROADMAP.md)** for development milestones
4. Understand security architecture and risk management

### For Operations Teams

1. Review **[ARCHITECTURE.md](ARCHITECTURE.md)** deployment procedures
2. Check infrastructure and monitoring guidelines
3. Understand backup and disaster recovery processes
4. See maintenance and update protocols

---

## 👥 For Different Audiences

<details>
<summary><b>🔧 Developers & Engineers</b></summary>

- **Architecture Overview**: [ARCHITECTURE.md](ARCHITECTURE.md) - System design and component interaction
- **Smart Contracts**: Solidity contract specifications and deployment
- **Backend API**: NestJS architecture and endpoint documentation
- **Frontend**: Next.js 14 App Router implementation with Web3 wallet integration
- **User Referrals**: Built-in referral system with rewards and leaderboards
- **Vapor Dashboard**: Next.js 15 partner integration dashboard
- **Admin Dashboard**: React admin management interface
- **Infrastructure**: GKE deployment and Docker configuration

</details>

<details>
<summary><b>💼 Investors & Stakeholders</b></summary>

- **Business Model**: [WHITEPAPER.md](WHITEPAPER.md) - Revenue model and growth strategy
- **Market Opportunity**: TAM/SAM/SOM analysis and competitive landscape
- **Tokenomics**: Reward distribution and staking mechanics
- **Product Roadmap**: [ROADMAP.md](ROADMAP.md) - Development milestones and feature releases
- **Risk Management**: Security measures and mitigation strategies

</details>

<details>
<summary><b>👤 Users & Stakers</b></summary>

- **Getting Started**: [ARCHITECTURE.md](ARCHITECTURE.md) - Simple user journey and staking process
- **Referral Program**: Earn rewards by inviting friends to stake on VaporFund
- **Leaderboards**: Compete with other users for bonus rewards and recognition
- **Supported Tokens**: Multi-token staking (ETH, USDC, USDT, and more)
- **Wallet Integration**: Easy connection with MetaMask, WalletConnect, and popular wallets
- **Security**: Your funds protected by MultiSig wallet and audited smart contracts

</details>

<details>
<summary><b>🤝 Partners & Integrators</b></summary>

- **Earning Programs**: [EARNING.md](EARNING.md) - Affiliate and partner commission structure
- **Vapor Dashboard**: Dedicated dashboard for API keys, affiliate program, and widget management
- **Technology Stack**: [ARCHITECTURE.md](ARCHITECTURE.md) - Technology partners and integrations
- **API Documentation**: REST endpoints and WebSocket support
- **Integration Guide**: How to integrate with VaporFund platform using widgets and APIs
- **Commission Tiers**: 10-40% revenue share with 100% Month 1 bonus
- **Security Standards**: MultiSig, smart contract audits, and compliance

</details>

---

## 📖 Documentation Standards

### Writing Guidelines

| Aspect               | Standard                                                |
| -------------------- | ------------------------------------------------------- |
| **Cross-References** | Use `[[Document Name]]` syntax (Obsidian-style linking) |
| **Headers**          | Clear hierarchical structure (H1 → H2 → H3)             |
| **Code Blocks**      | Include language identifiers for syntax highlighting    |
| **Diagrams**         | Use Mermaid syntax for all visual diagrams              |
| **Style**            | Keep sections focused, concise, and scannable           |

### Update Process

When making changes to documentation:

1. ✅ Update relevant sections in the appropriate document
2. ✅ Maintain version history at document bottom
3. ✅ Keep cross-references synchronized across documents
4. ✅ Follow markdown best practices and conventions
5. ✅ Test Mermaid diagrams in [Mermaid Live Editor](https://mermaid.live)

---

## 🤝 Contributing

We welcome contributions to improve our documentation!

### How to Contribute

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b docs/improve-section`)
3. **Make** your changes following our documentation standards
4. **Test** all Mermaid diagrams render correctly
5. **Submit** a pull request with a clear description

### Contribution Guidelines

- Follow existing document structure and formatting
- Use consistent terminology across all documents
- Add proper cross-references to related sections
- Update this README if adding major new documents
- Ensure all links are working and up-to-date

---

### 🌐 External Documentation

- **Smart Contracts**: [OpenZeppelin](https://docs.openzeppelin.com/) | [Solidity](https://docs.soliditylang.org/)
- **Backend**: [NestJS](https://docs.nestjs.com/) | [TypeORM](https://typeorm.io/)
- **Frontend**: [Next.js 14](https://nextjs.org/docs) | [RainbowKit](https://www.rainbowkit.com/)
- **Vapor Dashboard**: [Next.js 15](https://nextjs.org/docs) | [ShadCN/UI](https://ui.shadcn.com/) | [TanStack Query](https://tanstack.com/query)
- **Infrastructure**: [Kubernetes](https://kubernetes.io/docs/) | [GKE](https://cloud.google.com/kubernetes-engine/docs)

### 🔗 Live Deployments

- **Production Frontend**: [staking.vaporfund.com](https://staking.vaporfund.com)
- **Production API**: [staking-api.vaporfund.com](https://staking-api.vaporfund.com)
- **Staging Environment**: [staking-vaporfund.insitemedia.co.th](https://staking-vaporfund.insitemedia.co.th)
- **Smart Contracts**:
  - Mainnet: `0x089fa7705f6dea9ccc70c912029a0a442b2ced71`
  - Sepolia: `0x508e7698c9fE9214b2aaF3Da5149849CbCBeE009`

---

## 📌 Version Information

| Component           | Version | Last Updated |
| ------------------- | ------- | ------------ |
| **WHITEPAPER.md**   | v1.0    | 2025-10-30   |
| **ARCHITECTURE.md** | v1.0    | 2025-10-30   |
| **EARNING.md**      | v1.0    | 2025-11-12   |
| **ROADMAP.md**      | v1.0    | 2025-11-12   |
| **README.md**       | v1.2    | 2025-11-12   |

---

## 💬 Support

### Get Help

- 📖 **Documentation**: Start with this README and core documents
- 💬 **Discussions**: GitHub Discussions for questions and ideas
- 🐛 **Issues**: GitHub Issues for bug reports and feature requests
- 📧 **Email**: contact@vaporfund.com for general inquiries

### Community

- 🐦 **Twitter**: [@VaporFund](https://twitter.com/vaporfund)
- 💬 **Discord**: Join our [Discord community](https://discord.gg/vaporfund)
- 📱 **Telegram**: [VaporFund Official](https://t.me/vaporfund)

---

<div align="center">

**[⬆ Back to Top](#vaporfund-staking-platform-documentation)**

Made with ❤️ by the VaporFund Team

</div>
