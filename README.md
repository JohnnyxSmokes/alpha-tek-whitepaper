<!--
  PUBLIC ecosystem whitepaper synopsis (2026 refresh).
  Condenses platform + AAI + multi-product stack without private code or ops IP.
-->

<p align="center">
  <a href="https://www.alphatek.app">
    <img src="assets/alpha-tek-lockup-nav.png" alt="AlphaTek" width="720" />
  </a>
</p>

<div align="center">

  <h1>Alpha Tek · Epic Alpha</h1>
  <h3>Ecosystem Whitepaper Synopsis</h3>

  <p>
    <strong>Crypto intelligence at one view. Subscriptions, AAI, and Alpha Trench keep the stack sustainable.</strong>
  </p>

  <p>
    <em>Public synopsis · Version 2026.10.21 · Living document</em>
  </p>
  <p>
    Dual papers, current working copies:
    <a href="ALPHA_TEK_PLATFORM_WHITEPAPER.md">Alpha Tek Platform White Paper</a>
    ·
    <a href="AAI_TOKEN_WHITEPAPER.md">AAI Token White Paper</a>
    (version 2.1, October 18, 2026).
    The official issuance is published on alphatek.app at TGE.
  </p>

  <p>
    <a href="https://www.alphatek.app">
      <img src="https://img.shields.io/badge/Portal-AlphaTek.App-a855f7?style=for-the-badge&labelColor=0A0A0A" alt="Portal" />
    </a>
    &nbsp;
    <a href="https://discord.gg/sPW3tJk">
      <img src="https://img.shields.io/badge/Discord-Epic%20Alpha-5865F2?style=for-the-badge&labelColor=0A0A0A&logo=discord&logoColor=white" alt="Discord" />
    </a>
    &nbsp;
    <a href="https://www.alphatek.app/changelog">
      <img src="https://img.shields.io/badge/Build%20Journey-Public-00D4FF?style=for-the-badge&labelColor=0A0A0A" alt="Build Journey" />
    </a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Scope-Ecosystem%20Synopsis-a855f7?style=flat-square&labelColor=0A0A0A" alt="Synopsis" />
    <img src="https://img.shields.io/badge/Code-Private%20Core-f59e0b?style=flat-square&labelColor=0A0A0A" alt="Private core" />
    <img src="https://img.shields.io/badge/AAI-Devnet%20Proven-22c55e?style=flat-square&labelColor=0A0A0A" alt="AAI devnet" />
  </p>

</div>

---

## 1. Abstract

**Alpha Tek** is a production **crypto intelligence ecosystem**:

1. **Epic Alpha Discord** — community home and Discord Tek Stack (200+ channels, hundreds of commands)  
2. **AlphaTek.App** — live multi-surface web portal (Explorer, Discover, News Hub, Market Intel, Watchlist, Alpha Spy, TG Arena, KOL, Guard, Academy, AAI Hub, API library)
3. **Alpha Trench** — browser trench client. Linked sessions feed the live leaderboard and weekly trade contests  
4. **AAI (AlphaAi)** — Solana utility token design with **devnet-proven** programs and a revenue-linked buyback flywheel  

For more than three years, Epic Alpha offered free tools, alpha, and intel to people who got wrecked, refuse to get wrecked again, or only have a little capital. That chapter is morphing into an ecosystem. The operating model is three rails: **subscriptions and Discord licensing**, **AAI utility**, and the **Alpha Trench extension**.

This document is a **public synopsis**. Implementation monorepos remain private by default. Working product surfaces are public.

---

## 2. Problem

| Failure mode | Result |
|--------------|--------|
| Tab hell | Eight terminals, zero shared session memory |
| No revenue rail | The product stops when one builder funds the whole stack |
| Token-first vapor | Dec without product |
| Discord noise | Channel spam with no operator structure |
| Vendor cosplay | User interfaces advertising someone else’s brand |

---

## 3. Solution — Product Planes

```text
┌──────────────────────────────────────────────────────────────┐
│                     ALPHA TEK ECOSYSTEM                        │
├────────────────┬─────────────────────┬───────────────────────┤
│  EPIC ALPHA    │  ALPHATEK.APP       │  ALPHA TRENCH         │
│  Discord       │  Web portal         │  Browser extension    │
│  Community     │  Full intelligence  │  Pair-page client     │
│  + licensing   │  + AAI Hub          │  Guard · Journal      │
└───────┬────────┴──────────┬──────────┴───────────┬───────────┘
        │                   │                      │
        └───────────────────┼──────────────────────┘
                            ▼
              REVENUE + AAI UTILITY FLYWHEEL
     subs · Discord licensing · stake / spend · buybacks
```

Product footprints (docs only, no private source):

| Plane | Public repo |
|-------|-------------|
| Portal | [alpha-tek-portal](https://github.com/JohnnyxSmokes/alpha-tek-portal) |
| Discord (community) | [epic-alpha-discord](https://github.com/JohnnyxSmokes/epic-alpha-discord) |
| Discord **licensing** | [discord-licensing](https://github.com/JohnnyxSmokes/discord-licensing) |
| Extension | [alpha-trench](https://github.com/JohnnyxSmokes/alpha-trench) |
| **AAI Hub** | [aai-hub](https://github.com/JohnnyxSmokes/aai-hub) |
| Founder | [JohnnyxSmokes](https://github.com/JohnnyxSmokes/JohnnyxSmokes) |

---

## 4. Mission & Origin

**Mission:** multi-chain alpha that is accessible, fast, and usable. Subscriptions, AAI utility, and Alpha Trench are how the stack sustains itself.

**Origin:** For more than three years, Epic Alpha Discord offered free tools, alpha, and intel. That chapter is morphing into an ecosystem: **subscriptions, Discord licensing, AAI utility, and the Alpha Trench extension**.

**Founder:** JohnnyxSmokes (EpicAlpha · AlphaTek), Tampa FL — **14+ year crypto veteran** (trader · developer · multiproject operator since the **2012 BTC era**). Extensive public forum history from the **Bitcointalk** era with verifiable long-horizon participation; earlier free education (e.g. Bitcoin Homework brand) and multiple cycle-crossing products before Alpha Tek. Daily product shipping discipline (Cursor Day **600** era and ongoing). Shipping heat visible on GitHub contribution graphs — largely private repos by design.

---

## 5. Web Portal (AlphaTek App)

Live: **[https://www.alphatek.app](https://www.alphatek.app)**

| Surface | User outcome |
|---------|--------------|
| Explorer | Multi-chain market / token context |
| Discover | Narrative and pool heat discovery |
| News Hub | Merged headlines from exchange news, CryptoRank, CoinGecko Buzz, and Bitcoin.com |
| Market Intel | Global metrics, ETF flow, derivatives, cycle indicators, click-through chart |
| Watchlist | Saved coins with price, market cap, volume, and 24h direction |
| Alpha Spy | Entity and connection context |
| Launch / Pump rails | Solana new-pair lifecycle context |
| Wallet views | Portfolio + enrichment where connected |
| Quant | Social trading / calls / flex culture |
| TG Arena | Telegram-call operator views |
| KOL Scope | Social influencer heat, carefully framed |
| Alpha Guard | Host / domain / mint / approval awareness |
| Alpha Terminal | Research coin pages |
| Trench Replay | Cast, Forecast, Market Replay, Wallet Replay |
| Alpha Trench | Extension plus live leaderboard and weekly trade contests |
| Alpha Academy | Interactive education |
| AAI Hub | Utility rails (stake / claim / activity) and the referral ladder |
| API library | 1,500+ platform endpoints. Agent MCP (`@alphatekapp/mcp`) is reserved on npm and ships after QA and auditor approval |
| Alpha Brain / MLM | Queryable memory for calls, heat, and replay, keyed by mint |
| Build Journey | Public changelog of real shipping |

**Security principles (product-level):**

- API secrets never shipped to browsers
- Privy wallet login, Stripe payments, JWT sessions
- Alpha-branded safety language instead of scattered vendor widgets
- Alpha Trench release zips ship with a SHA-256 and a VirusTotal report for that exact file. The published 0.9.540 Windows and Safari builds scanned 0 malicious and 0 suspicious. That evidence is for those hashes.  

---

## 6. Discord Tek Stack (Epic Alpha)

Join: **[https://discord.gg/sPW3tJk](https://discord.gg/sPW3tJk)**

Discord is not a support ticket booth. It is a **production intelligence server**:

- **HQ** onboarding, multi-chain call and trade rooms, analysis lounges  
- **Pump.fun + Solana radars** for launch velocity  
- **KOL / Dev monitors** and rank boards  
- **Multichain trending radars**  
- **News / macro central** and curated **X / KOL trackers**  
- **Alpha Tools** (sentiment, whales, Polymarket suite, DEX tools)  
- **Call bots + monitor health** lanes for operational visibility  
- Daily **Morning Brief** and market report style products  

Scale narrative: **200+** specialized Tek channels, **hundreds** of commands, multi-year embed delivery with reliability culture. Bot source and bridge workers stay private; the community experiences the product live.

Licensing Discord Tek packs is a commercial pillar for other servers / operators.

---

## 7. Alpha Trench (Browser Client)

Chrome MV3 trench client: Instant Trade shell, honesty ladder (paper / practice first), Alpha Guard on social hosts, mint context, journal / replay path, optional portal link.

On the ecosystem flywheel, the **Alpha Trench Extension** is the entry node. Traders land there, practice, then move into AlphaTek App, subscriptions, and AAI.

**Why a separate product footprint:** extensions must be **inspectable**. Core platform need **not** be open for that trust to exist.

Repo: [alpha-trench](https://github.com/JohnnyxSmokes/alpha-trench)  
Portal pairing: [alphatek.app](https://www.alphatek.app)

---

## 8. Data & Partner Footprint (Public Language)

Alpha Tek is the product. The live site reads many upstreams. They do different jobs. No single name is the stack. The public library is **1,500+ platform endpoints**.

**Markets and listings:** Binance, CoinMarketCap, CoinGecko, MEXC, CoinEx.

**Pools and pairs:** DexScreener, GeckoTerminal, PancakeSwap, Jupiter, Raydium, FluxBeam, Birdeye, Solscan.

**Launches and terminals:** Pump.fun, GMGN, Axiom, Padre.

**Headlines:** CryptoRank, Bitcoin.com.

**Wallets, maps, and perps:** Arkham, Bubblemaps, Hyperliquid.

**Charts:** TradingView.

**Account:** Privy, Stripe, Telegram.

Moralis remains for a few chain reads. It is not the spine. **Cielo is retired.**

Interfaces stay Alpha Tek. Exact rate limits and private routes stay off this page.

---

## 9. AAI Utility & AAI Hub

**AAI (AlphaAi)** is a Solana SPL **utility** token design powering access, stake, referral, and spend rails for Alpha Tek.

**Micro-footprint (product page):** [aai-hub](https://github.com/JohnnyxSmokes/aai-hub)  
**Live hub:** [alphatek.app/dashboard/aai](https://www.alphatek.app/dashboard/aai)

### 9.1 Hub surfaces

| Surface | Job |
|---------|-----|
| Stake / claim / unstake | On-chain utility flows (devnet proof path) |
| Activity feed | Economy / session visibility |
| XP · leaderboards · lottery V1 | Engagement rails on a real product |
| Access narrative | How hold / stake maps to platform depth |

### 9.2 Utility systems (design)

| System | Design |
|--------|--------|
| **Wallet access tiers** | Hold thresholds (e.g. 1k / 5k / 50k class) gate platform depth |
| **On-chain staking** | Tiered APY design (e.g. 15–30% class by tier); multi-position model — **not a guarantee** |
| **Referral ladder** | Bronze → Platinum style commissions on paid referrals |
| **Credits / energy** | Spend path for premium AI / agent actions |

### 9.3 Revenue → buyback flywheel (policy)

```text
Subscriptions + Discord licensing revenue
        │
        ▼
   25% → buybacks
        │
        ├── 50% burn (deflation)
        ├── 30% staking pool
        └── 20% treasury / reinvestment
```

### 9.4 Honest status (critical)

| Item | Status |
|------|--------|
| Platform / Discord / portal / AAI Hub UI | **Live** |
| On-chain programs | **Devnet proven** (mint, staking, buyback, referral designs) |
| Mainnet mint / public sale | **TBD** — external audit required first |
| Utility marketing | Utility token — **not** an investment solicitation |

Devnet proof exists for deliberate readers; mainnet remains gated.

---

## 10. Discord Licensing (Commercial Micro-Footprint)

Epic Alpha is the **community flagship**. Discord **licensing** is how other servers buy **Tek stack product** without cloning private ops IP.

**Micro-footprint:** [discord-licensing](https://github.com/JohnnyxSmokes/discord-licensing)  
**Flagship product map:** [epic-alpha-discord](https://github.com/JohnnyxSmokes/epic-alpha-discord)  
**Community server:** [discord.gg/sPW3tJk](https://discord.gg/sPW3tJk)

### 10.1 Monthly tiers

| Tier | Price | Fit |
|------|------:|-----|
| **Starter** | **$299** | Small communities · core pack |
| **Professional** | **$799** | Mid-size servers · deeper radar / monitor footprint |
| **Enterprise** | **$1,999** | Large / white-label · priority relationship |

Pack composition is **agreement-scoped**. Tiers communicate ladder and economics, not a free dump of proprietary channel trees.

### 10.2 Why it exists

- Licensing funds the flagship community and feeds the same buyback policy as subscriptions  
- B2B licensing sells **replication cost** (years of channel + command + reliability culture)  
- Revenue participates in the same **25% buyback policy** design as subscriptions  

### 10.3 Flagship vs licensed

| | Epic Alpha | Licensed |
|--|------------|----------|
| Join | Free | Commercial |
| Role | Mission home and community intelligence | Operator stacks inside other communities |
| IP | Alpha Tek operated | Rights under license |

---

## 11. Economic Stack

| Stream | Role | Public footprint |
|--------|------|------------------|
| **Subscriptions** | Portal depth ($29 / $79 / $199 design ladder) | [alpha-tek-portal](https://github.com/JohnnyxSmokes/alpha-tek-portal) |
| **Discord licensing** | Tek packs for other communities | [discord-licensing](https://github.com/JohnnyxSmokes/discord-licensing) |
| **AAI utility** | Retention + spend + stake alignment | [aai-hub](https://github.com/JohnnyxSmokes/aai-hub) |
| **Alpha Trench** | Practice floor: Instant Trade, paper books, portal distribution | [alpha-trench](https://github.com/JohnnyxSmokes/alpha-trench) |
| **Community flagship** | Epic Alpha Discord, the home for calls and learning | [epic-alpha-discord](https://github.com/JohnnyxSmokes/epic-alpha-discord) |

The sustainability rails are subscriptions and Discord licensing, AAI utility, and the Alpha Trench extension. Traders enter through Trench, then subscriptions, tipping, and licensing fund buybacks.

---

## 12. Competitive Thesis — Replication Cost

Alpha Tek is hard to clone as a **weekend fork** because the value is:

1. **14+ year founder track** — trader / developer / multiproject history since BTC 2012, not a single-cycle story  
2. **Years** of production shipping on the current stack (not Figma decks)  
3. **Discord Tek Stack** channel architecture and ops culture  
4. **Multi-surface** product (portal + Discord + extension + Hub)  
5. **Commercial dual rail** — consumer subs + B2B Discord licensing  
6. **Alpha brand** integrity (one label, many feeds)  
7. **Build Journey** public accountability at alphatek.app/changelog  
8. **Private core** until release slices are intentional  

Investors and rivals can clone a logo. They cannot cheaply clone multi-cycle operational trenches.

---

## 13. Public Proof Surfaces

| Proof | URL |
|-------|-----|
| Live portal | https://www.alphatek.app |
| AAI Hub | https://www.alphatek.app/dashboard/aai |
| Build Journey / changelog | https://www.alphatek.app/changelog |
| Discord | https://discord.gg/sPW3tJk |
| Founder GitHub heat | https://github.com/JohnnyxSmokes |
| Profile story | https://github.com/JohnnyxSmokes/JohnnyxSmokes |
| Product footprints | portal · discord · licensing · trench · aai-hub · whitepaper |

Contribution graphs include private repository activity when the founder enables that setting — **greens without free clones**.

---

## 14. Roadmap Themes (Non-binding)

Chain parity, the multi-chain menu, usability polish, and the current data surfaces are shipped. They are the floor.

1. **Mainnet and AAI.** Launch the token so the platform can be used for what it was built for.
2. **Community.** Learn together, stay social, make call-outs, look up KOLs, and follow traders worth copying. The community is how the ecosystem fills in.
3. **Alpha Trench first.** Paper books and the extension are how someone learns trading before risking real capital.
4. **One clean desk.** Accurate, checkable information in one place, so the community is not fed psyops and rumor hops.
5. **Tokenized participation.** AAI is how people learn, post, and take part. Devnet programs are proven. Mainnet is the gate.  

---

## 15. Risks & Disclaimers

- Crypto markets are high risk; intel tools **do not** remove loss likelihood  
- Automated feeds can be wrong, delayed, or gamed — verify  
- Token utility designs can change; devnet ≠ mainnet; APY is design not guarantee  
- Licensing scope and pricing can evolve commercial terms  
- This synopsis is **information**, not an offer of securities or investment advice  
- Always DYOR  

---

## 16. Contact

| | |
|--|--|
| Email | contact@alphatek.app |
| Portal | https://www.alphatek.app |
| AAI Hub | https://www.alphatek.app/dashboard/aai |
| Discord | https://discord.gg/sPW3tJk |
| Licensing footprint | https://github.com/JohnnyxSmokes/discord-licensing |
| AAI footprint | https://github.com/JohnnyxSmokes/aai-hub |
| X | https://x.com/BitcoinHomework · https://x.com/AlphaTekBot |
| GitHub | https://github.com/JohnnyxSmokes |

---

<div align="center">

  <p>
    <img src="assets/alphatek-mark-clear.png" alt="AlphaTek" width="180" />
  </p>

  <sub>
    Alpha Tek · Epic Alpha — Public Ecosystem Whitepaper Synopsis · 2026<br />
    Built with passion since BTC 2012 · Core private · Product public
  </sub>

</div>
