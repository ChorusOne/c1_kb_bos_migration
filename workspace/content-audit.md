# C1 KB → BOS Content Audit
**Date:** March 25, 2026 | **Audited by:** Claude (Cowork)
**Total Files:** 133 | **Goal:** BOS rebrand + overhaul for new website

---

## Quick Summary

| Status | Count | What it means |
|--------|-------|---------------|
| **KEEP** | 89 | Good — just needs rebrand (company name, links, contacts) |
| **UPDATE** | 3 | Mostly good, needs factual/content refresh |
| **ARCHIVE** | 36 | Duplicates, empty shells, placeholders, test files — remove |
| **MERGE** | 2 | Consolidate with another page |
| **REWRITE** | 0 | Nothing needs a full rewrite yet (Attestant ETH content will be net-new) |

---

## Directory Breakdown

### chorus-one-offerings (3 files)
| File | Status | Notes | Effort |
|------|--------|-------|--------|
| `README.md` | KEEP | Core product overview. Just needs rebrand. | LOW |
| `option-2-wl-overview-wip.md` | ARCHIVE | Marked WIP + hidden. Duplicate of staking-options page. | LOW |
| `staking-options-white-label-vs-public-node.md` | KEEP | Good comparison table. Update names only. | LOW |

### our-products (11 files)
| File | Status | Notes | Effort |
|------|--------|-------|--------|
| `chorus-one-rewards.md` | UPDATE | Says "20+ networks" but lists only 14. Verify/update count. | MEDIUM |
| `chorus-one-ethereum-staking/README.md` | KEEP | Excellent ETH guide (Stakewise v3, MEV). Minor rebrand. | LOW |
| `chorus-one-ethereum-staking/staking-to-eth-vaults.md` | KEEP | Current step-by-step with screenshots. | LOW |
| `chorus-one-ethereum-staking/unstaking-ethereum.md` | KEEP | Clear unstaking guide, current specs. | LOW |
| `chorus-one-ethereum-staking/how-do-i-see-my-rewards.md` | KEEP | Dashboard guide, current. | LOW |
| `chorus-one-ethereum-staking/boosted-eth-staking.md` | KEEP | Strong institutional content. Updated Feb 2025. | LOW |
| `chorus-one-ethereum-staking/outdated-staking-ethereum.md` | ARCHIVE | Explicitly marked [OUTDATED] and hidden. Superseded. | LOW |
| `chorus-one-ethereum-staking/using-fireblocks-with-chorus-one-staking.md` | KEEP | Fireblocks integration guide. Current Aug 2024. | LOW |
| `chorus-one-ethereum-native-staking/README.md` | KEEP | Native staking API overview. Points to external docs. | LOW |
| `chorus-one-ethereum-native-staking/api-integration-guide.md` | KEEP | Detailed API integration. Code examples are current. | LOW |
| `chorus-one-widget/README.md` | KEEP | Widget product overview with supported networks. | LOW |
| `chorus-one-widget/customize-and-deploy.md` | KEEP | Iframe deployment guide. Current. | LOW |

### getting-started (7 files)
| File | Status | Notes | Effort |
|------|--------|-------|--------|
| `staking-overview.md` | KEEP | Good PoS/validator conceptual content. | LOW |
| `staking-concepts/README.md` | KEEP | Good taxonomy (DPoS, SaaS, slashing, etc.). | LOW |
| `staking-concepts/what-is-mev.md` | KEEP | MEV explanation with Adagio case study (4.75% additional rewards). | LOW |
| `staking-concepts/what-is-liquid-staking/README.md` | KEEP | Strong LST/LSD/restaking overview. | LOW |
| `staking-concepts/what-is-liquid-staking/stakewise-v3.md` | KEEP | Excellent Stakewise V3 deep-dive. Recent (Feb 2025). | LOW |
| `staking-concepts/what-is-liquid-staking/eigenlayer-wip.md` | ARCHIVE | Hidden + WIP. Has placeholder text (INSERT PICTURE, etc.). Complete or cut. | MEDIUM |
| `staking-concepts/what-is-liquid-staking/symbiotic-wip.md` | ARCHIVE | Hidden. Completely empty — only frontmatter. | LOW |

### network-faqs (4 files)
| File | Status | Notes | Effort |
|------|--------|-------|--------|
| `networks/README.md` | UPDATE | Only 3 of 60+ networks listed. Needs expansion or honest scope note. | MEDIUM |
| `networks/cosmos-atom.md` | KEEP | Comprehensive: validator address, mechanics table, FAQs, slashing. Current. | LOW |
| `networks/celestia-tia.md` | KEEP | Same strong structure as Cosmos. Current. | LOW |
| `networks/axelar-axl.md` | KEEP | Same strong structure as Cosmos. Current. | LOW |

### guides/how-to-stake (73 files)
**Active guides (~47 files) — Status: KEEP**
All current with wallet steps and screenshots. Networks include: AKT, APT, ARCH, AVAX, AXL, BAND, BERA, BLD, BTC (Babylon), CELO, DYM, EIGEN, INJ, JUNO, KAVA, KYVE, LAVA, MINA, NEAR, NYM, OSMO, POL, REGEN, SEI, SKL, SOL, STARS, STRD, STRK, STX, SUI, TIA, TON, XPRT, XTZ, and more.

**Outdated/Old — Status: ARCHIVE (remove)**
| File | Notes |
|------|-------|
| `old-how-to-stake-btc-with-babylon.md` | Superseded by current version |
| `old-how-to-stake-nym-nym.md` | Superseded by current version |
| `old-previous-lava-guide.md` | Superseded by current version |
| `old-testnet-of-how-to-stake-bera-berachain.md` | Testnet only, mainnet guide exists |
| `outdated-how-to-stake-sol-solana.md` | Marked [OUTDATED], current version exists |
| `postponed-how-to-stake-dot-polkadot.md` | [POSTPONED] — future |
| `postponed-how-to-stake-hash-provenance.md` | [POSTPONED] — future |
| `postponed-how-to-stake-hnt-helium-network.md` | [POSTPONED] — future |
| `postponed-how-to-stake-ksm-kusama.md` | [POSTPONED] — future |
| `wip-how-to-stake-cfg-centrifuge.md` | WIP, incomplete |
| `wip-how-to-stake-rose-oasis-network.md` | WIP, incomplete |
| `wip-how-to-stake-xtz-tezos.md` | WIP, but final version exists |

**Templates/Duplicates — Status: ARCHIVE**
| File | Notes |
|------|-------|
| `markdown-template-1.md` | Template file, remove from production |
| `copy-of-markdown-template-1.md` | Duplicate template |
| `new-template-based-on-stars-how-to-stake-_____-______.md` | Placeholder template |

### guides/faqs (4 files) — All KEEP
- `README.md`, `what-is-a-seed-phrase.md`, `custodial-versus-self-custodial-wallets.md`, `crypto-security-best-practices.md`
- All solid foundational content. LOW effort rebrand.

### guides/defi-resources (5 files) — All KEEP
- `README.md`, Arbitrum bridge, Base bridge, Osmosis Swap, Drop Protocol
- All current. LOW effort rebrand.

### wallets (12 files) — All KEEP
- MetaMask, Keplr, Leap, Cosmostation, Petra, OKX, NYM, Phantom, Solflare, Ledger Live, Safe{Wallet}
- All current. LOW effort rebrand.

### custodians (6 files)
| File | Status | Notes | Effort |
|------|--------|-------|--------|
| `staking-from-anchorage.md` | KEEP | Contact info/support page. Current. | LOW |
| `staking-from-bitgo.md` | KEEP | Same structure as Anchorage. Current. | LOW |
| `staking-from-fireblocks/README.md` | ARCHIVE | Empty file. No content yet. | LOW |
| `staking-from-fordefi.md` | ARCHIVE | Hidden + empty. | LOW |
| `staking-from-hextrust.md` | ARCHIVE | Hidden + empty. | LOW |
| `test-syncing-page.md` | ARCHIVE | Test file. Remove. | LOW |

### working-with-chorus-one (4 files)
| File | Status | Notes | Effort |
|------|--------|-------|--------|
| `support.md` | KEEP | Support contacts. Update emails/channels for BOS. | LOW |
| `our-mission.md` | ARCHIVE | Hidden + empty. Merge into offerings overview or delete. | LOW |
| `chorus-one-social-platforms/README.md` | KEEP | Official social channels. Update for BOS. | LOW |
| `chorus-one-social-platforms/backup-of-social-links.md` | ARCHIVE | Duplicate of above. Remove. | LOW |

### workspace + root (3 files)
| File | Status | Notes |
|------|--------|-------|
| `workspace/to-do.md` | ARCHIVE | Working doc, not production content. |
| `README.md` | ARCHIVE | Migration meta-doc, not production content. |
| `SUMMARY.md` | KEEP | Navigation TOC — keep as working reference. |

---

## Gaps vs. Goals (Net-New Content Needed)

| Gap | Priority | Source Material |
|-----|----------|----------------|
| Attestant ETH content (Vouch, Dirk) | HIGH | Attestant docs — need to locate |
| EigenLayer deep-dive | HIGH | WIP exists; needs completion |
| Network FAQ pages (only 3 of ~60) | HIGH | Per TO-DO: SOL, ETH, TIA, AXL priority |
| Restaking via restake.app | MEDIUM | Google Slides deck in TO-DO |
| Symbiotic guide | MEDIUM | Empty WIP; start fresh |
| Custodian pages (Fireblocks, Fordefi, HexTrust) | MEDIUM | All empty — need content |
| BOS branding/mission content | HIGH | Need from marketing + BOS website plans |

---

## Recommended Phased Approach

**Phase 1 — Cleanup (Low effort, fast wins)**
1. Archive/delete all 36 ARCHIVE files
2. Fix SUMMARY.md to remove archived pages
3. Strip Chorus One branding → BOS placeholder throughout

**Phase 2 — Content inputs (External)**
1. Connect Slack + Google Drive for network roadmap, BOS website plans
2. Locate Attestant Vouch/Dirk documentation
3. Define final BOS brand voice and naming conventions

**Phase 3 — Expand & Build**
1. Complete EigenLayer + Symbiotic guides
2. Add top network FAQ pages (SOL, ETH, TIA, AXL, ATOM + others per roadmap)
3. Write Restaking/restake.app guide
4. Merge Attestant ETH content
5. Build out custodian pages (Fireblocks, Fordefi, HexTrust)

**Phase 4 — Final Polish**
1. Full rebrand pass with confirmed BOS brand guidelines
2. Update all validator addresses, contact emails, support links
3. Final SUMMARY.md / site structure review
