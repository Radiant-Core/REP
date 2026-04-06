# Radiant Enhancement Proposals (REPs)

Radiant Enhancement Proposals (REPs) are design documents providing information to the Radiant community, or describing a new feature for Radiant or its processes or environment. REPs are the primary mechanism for proposing major new features, collecting community input on issues, and documenting design decisions.

## REP Summary

| REP | Title | Author | Status | Type |
|-----|-------|--------|--------|------|
| **[1](REP-0001.md)** | DNS Seeder Infrastructure for Network Discovery | Radiant Core Contributors | ✅ Final | Standard |
| **[2](REP-0002.md)** | PSRT Client-Side Order Expiration | Radiant Core Contributors | 📝 Draft | Standard |
| **[3](REP-0003.md)** | Asynchronous JSON-RPC Server | Radiant Core Contributors | 📝 Draft | Standard |
| **[4](REP-0004.md)** | P2P Encryption (BIP324) Implementation | Radiant Core Contributors | 📝 Draft | Standard |
| **[5](REP-0005.md)** | OP_CHECKTEMPLATEVERIFY (CTV) Implementation | Radiant Core Contributors | 📝 Draft | Standard |
| **[6](REP-0006.md)** | Post-Quantum Cryptography Upgrade Path | Radiant Community | 📝 Draft | Standard |
| **[1001](REP-1001.md)** | Radiant Architecture Overview | Radiant Core Contributors | 📝 Draft | Informational |
| **[1002](REP-1002.md)** | Radiant Security Best Practices | Radiant Core Contributors | 📝 Draft | Informational |
| **[2001](REP-2001.md)** | REP Process Definition | Radiant Core Contributors | 🔄 Active | Process |
| **[2002](REP-2002.md)** | Radiant Developer Tools Ecosystem | Radiant Core Contributors | 📝 Draft | Process |
| **[3001](REP-3001.md)** | Glyph Protocol v2 (Core) | C. Donnachie | 📝 Draft | Application |
| **[3002](REP-3002.md)** | Glyph v2 Envelopes | C. Donnachie | 📝 Draft | Application |
| **[3003](REP-3003.md)** | Glyph v2 Test Vectors | C. Donnachie | 📝 Draft | Application |
| **[3004](REP-3004.md)** | Glyph v2 Indexer Guide | C. Donnachie | 📝 Draft | Application |
| **[3005](REP-3005.md)** | Game Item Profile (game_item_v1) | C. Donnachie | 📝 Draft | Application |
| **[3006](REP-3006.md)** | Encrypted Content Extension | C. Donnachie | 📝 Draft | Application |
| **[3007](REP-3007.md)** | Encrypted Content Test Vectors | C. Donnachie | 📝 Draft | Application |
| **[3008](REP-3008.md)** | Recipient Key Wrapping | C. Donnachie | 📝 Draft | Application |
| **[3009](REP-3009.md)** | Timelock / Reveal Mechanisms | C. Donnachie | 📝 Draft | Application |
| **[3010](REP-3010.md)** | Glyph Mining Enhancement: Multi-Algorithm POW & Dynamic Difficulty | Radiant Core Contributors | ✅ Final | Application |
| **[3011](REP-3011.md)** | WAVE: P2P Radiant Blockchain Name System | Radiant Community | ✅ Final | Application |
| **[3012](REP-3012.md)** | Glyph On-Chain Royalties | Radiant Community | 📝 Draft | Application |
| **[3013](REP-3013.md)** | Glyph Containers and Collections | Radiant Community | ✅ Final | Application |
| **[3014](REP-3014.md)** | Glyph Burn Mechanism | Radiant Community | ✅ Final | Application |
| **[3015](REP-3015.md)** | Glyph Authority Tokens | Radiant Community | ✅ Final | Application |
| **[3016](REP-3016.md)** | Induction Proofs for Code Continuity | Radiant Community | ✅ Final | Application |

*Legend: 📝 Draft | 🔄 Active | ✅ Final | ❌ Rejected | 🚫 Withdrawn*

## Quick Start

- **[REP-2001](REP-2001.md)** - REP Process Definition (start here)
- **[REP Template](rep-template.md)** - Template for creating new REPs
- **[Active REPs](active/)** - Currently under consideration
- **[Final REPs](final/)** - Accepted and implemented
- **[All REPs](README.md)** - Complete list by category

## REP Categories

### Standard Track (REP-1 to REP-999)
Protocol changes that affect most or all Radiant implementations:
- Consensus rule changes
- P2P network protocol changes
- New opcodes or transaction types
- Block validation changes
- RPC interface changes

### Informational (REP-1001 to REP-1999)
Design issues, guidelines, and informational content:
- Architecture overviews
- Security best practices
- Mining guidelines
- Wallet integration standards

### Process (REP-2000 to REP-2999)
Process changes and governance:
- REP process changes
- Release processes
- Security disclosure processes
- Governance guidelines

### Application Track (REP-3000 to REP-3999)
Application-layer protocols and token standards:
- Glyph token protocol specifications
- NFT and asset standards
- Encryption and privacy extensions
- Application profiles (game items, etc.)

## REP Status Legend

- 📝 **Draft**: Initial proposal, being discussed
- 🔄 **Active**: Under consideration, implementation may begin
- ✅ **Final**: Accepted and implemented
- ❌ **Rejected**: Considered and rejected
- 🚫 **Withdrawn**: Author withdrew the proposal

## Current REPs

### Standard Track REPs (Protocol Changes)

| REP | Title | Author | Status | Description |
|-----|-------|--------|--------|-------------|
| **[1](REP-0001.md)** | DNS Seeder Infrastructure for Network Discovery | Radiant Core Contributors <info@radiantfoundation.org> | ✅ Final | Implemented in Radiant Core 2.2 |
| **[2](REP-0002.md)** | PSRT Client-Side Order Expiration | Radiant Core Contributors <info@radiantfoundation.org> | 📝 Draft | Adds optional max_age filtering to PSRT RPC methods to reduce stale order clutter and improve swap protocol efficiency |
| **[3](REP-0003.md)** | Asynchronous JSON-RPC Server | Radiant Core Contributors <info@radiantfoundation.org> | 📝 Draft | Refactors JSON-RPC server for async processing to improve throughput and enable concurrent request handling |
| **[4](REP-0004.md)** | P2P Encryption (BIP324) Implementation | Radiant Core Contributors <info@radiantfoundation.org> | 📝 Draft | Implements BIP324 encrypted P2P transport to enhance network privacy and security against surveillance |
| **[5](REP-0005.md)** | OP_CHECKTEMPLATEVERIFY (CTV) Implementation | Radiant Core Contributors <info@radiantfoundation.org> | 📝 Draft | Implements BIP119 CTV opcode to enable trustless transaction covenants for vaults, congestion control, and batched payments |
| **[6](REP-0006.md)** | Post-Quantum Cryptography Upgrade Path | Radiant Community | 📝 Draft | Phased migration from ECDSA to post-quantum signatures with upgrade hooks, hybrid schemes, and ecosystem preparation |

### Informational REPs (Guidelines & Overviews)

| REP | Title | Author | Status | Description |
|-----|-------|--------|--------|-------------|
| **[1001](REP-1001.md)** | Radiant Architecture Overview | Radiant Core Contributors <info@radiantfoundation.org> | 📝 Draft | Comprehensive overview of Radiant blockchain architecture, components, and design principles for developers and researchers |
| **[1002](REP-1002.md)** | Radiant Security Best Practices | Radiant Core Contributors <info@radiantfoundation.org> | 📝 Draft | Security guidelines for node operators, developers, and users covering operational security, development practices, and user protection |

### Process REPs (Governance & Procedures)

| REP | Title | Author | Status | Description |
|-----|-------|--------|--------|-------------|
| **[2001](REP-2001.md)** | REP Process Definition | Radiant Core Contributors <info@radiantfoundation.org> | 🔄 Active | Defines the REP process, format, and guidelines for submitting and managing Radiant Enhancement Proposals |
| **[2002](REP-2002.md)** | Radiant Developer Tools Ecosystem | Radiant Core Contributors <info@radiantfoundation.org> | 📝 Draft | Defines the ecosystem of developer tools for Radiant blockchain |

### Application Track REPs (Glyph Protocol v2)

| REP | Title | Author | Status | Description |
|-----|-------|--------|--------|-------------|
| **[3001](REP-3001.md)** | Glyph Protocol v2 (Core) | C. Donnachie | 📝 Draft | Core specification for Glyph v2: structured smart assets with typed files, bundles, previews, and mutable state |
| **[3002](REP-3002.md)** | Glyph v2 Envelopes | C. Donnachie | 📝 Draft | Exact script templates for commit/reveal/update envelopes (Style A/B) |
| **[3003](REP-3003.md)** | Glyph v2 Test Vectors | C. Donnachie | 📝 Draft | Deterministic test vectors for CBOR, SHA256, and envelope payloads |
| **[3004](REP-3004.md)** | Glyph v2 Indexer Guide | C. Donnachie | 📝 Draft | Implementation guide for indexers with C++ examples and DB schema |
| **[3005](REP-3005.md)** | Game Item Profile (game_item_v1) | C. Donnachie | 📝 Draft | Application profile for game items with stats, effects, and mutable state |
| **[3006](REP-3006.md)** | Encrypted Content Extension | C. Donnachie | 📝 Draft | Optional encryption for Glyph payloads with AEAD and key delivery |
| **[3007](REP-3007.md)** | Encrypted Content Test Vectors | C. Donnachie | 📝 Draft | Test vectors for AES-256-GCM, ChaCha20-Poly1305, and scrypt |
| **[3008](REP-3008.md)** | Recipient Key Wrapping | C. Donnachie | 📝 Draft | X25519-HKDF-AES256GCM key wrapping for multi-recipient encryption |
| **[3009](REP-3009.md)** | Timelock / Reveal Mechanisms | C. Donnachie | 📝 Draft | Hash-commit and scheduled key reveal for encrypted Glyphs |
| **[3010](REP-3010.md)** | Multi-Algorithm POW & DAA for dMint | Radiant Core Contributors | ✅ Final | V2 hard fork deployed at block 410,000 with OP_BLAKE3, OP_K12, OP_LSHIFT, OP_RSHIFT |
| **[3011](REP-3011.md)** | WAVE: P2P Name System | Radiant Community | ✅ Final | Decentralized naming via Glyph NFTs, implemented in Photonic Wallet |
| **[3012](REP-3012.md)** | Glyph On-Chain Royalties | Radiant Community | 📝 Draft | Script-enforced royalty payments with percentage-based fees |
| **[3013](REP-3013.md)** | Glyph Containers and Collections | Radiant Community | ✅ Final | GLYPH_CONTAINER (protocol ID 7) for hierarchical groupings, implemented in Photonic Wallet |
| **[3014](REP-3014.md)** | Glyph Burn Mechanism | Radiant Community | ✅ Final | GLYPH_BURN (protocol ID 6) with photon recovery, implemented in radiant-mcp-server |
| **[3015](REP-3015.md)** | Glyph Authority Tokens | Radiant Community | ✅ Final | GLYPH_AUTHORITY (protocol ID 10) for transferable project authority |
| **[3016](REP-3016.md)** | Induction Proofs | Radiant Community | ✅ Final | Code continuity verification via tx.state operators, implemented in RadiantScript |

## Submitting a REP

1. **Discuss First**: Talk about your idea on community channels
2. **Use Template**: Copy [rep-template.md](rep-template.md) 
3. **Create PR**: Submit as a pull request to this repository
4. **Community Review**: Participate in the review process
5. **Implementation**: Develop reference implementation (for Standard Track)

## Community

- **Discussions**: [GitHub Discussions](https://github.com/Radiant-Core/REP/discussions)
- **Issues**: [GitHub Issues](https://github.com/Radiant-Core/REP/issues)
- **Core Repository**: [Radiant-Core/Radiant-Core](https://github.com/Radiant-Core/Radiant-Core)

## Repository Structure

```
REP/
├── README.md              # This file
├── REP-2001.md            # REP Process Definition
├── rep-template.md        # Template for new REPs
├── active/                # Active REPs
├── final/                 # Final REPs
├── rejected/              # Rejected REPs
├── withdrawn/             # Withdrawn REPs
└── draft/                 # Draft REPs (PRs)
```

## License

All REPs are licensed under the MIT License unless otherwise specified in the individual REP.

---

*Inspired by Bitcoin Improvement Proposals (BIPs), Ethereum Improvement Proposals (EIPs), and Python Enhancement Proposals (PEPs).*
