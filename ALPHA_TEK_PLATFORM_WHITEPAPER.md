# Alpha Tek Platform — Whitepaper

**Crypto intelligence at one view. Same depth across every chain.**

*Version 1.3 — October 18, 2026*

---

## 1. Vision & Mission

**Alpha Tek** is a unified **crypto intelligence platform** that gives traders and researchers a single place to see what’s moving across chains: trending tokens, top gainers, new launches, narratives, and wallet activity. We aim to provide **Solana-level depth and usability across the 15 chains Alpha Tek supports**, so Solana, Ethereum, Base, BSC, and the rest of that menu share one terminal.

**Mission:** Make multi-chain alpha accessible, fast, and easy to use — with one menu, one DEX view, and one data refresh model across all supported networks.

---

## 2. Platform Overview

The platform is split into **frontend** (Next.js web app) and **backend** (Express API). All sensitive keys and external API calls stay on the backend; the frontend only consumes our own APIs. This keeps the stack secure and makes it straightforward to add new chains and data sources over time.

### 2.1 Frontend

- **Framework:** Next.js 14+ (React, App Router)
- **Styling:** Tailwind CSS, dark theme, Alpha Tek design tokens
- **Main surfaces (October 2026):**
  - **Explorer** — Multi-chain market and token context
  - **Discover** — Narratives, pools, and heat across feeds
  - **News Hub** — Merged headlines (exchange news, CryptoRank, CoinGecko Buzz, Bitcoin.com)
  - **Market Intel** — Global metrics, ETF net flow, derivatives, cycle indicators, click-through price chart
  - **Watchlist** — Saved coins with price, market cap, volume, and 24h direction
  - **Alpha Spy** — Entity and connection context for mints and wallets
  - **Quant, TG Arena, KOL Scope** — Calls, Telegram structure, influencer heat
  - **Alpha Guard** — Host, domain, mint, and approval awareness
  - **Alpha Terminal** — Research coin pages
  - **Trench Replay Theater and Market Replay** — Cast, Forecast, wallet and chart playback
  - **Alpha Academy** — Courses, quizzes, certificates
  - **AAI Hub** — Stake, claim, and utility (devnet programs proven; mainnet gated)
  - **Alpha Trench extension** — Instant Trade, paper books, Guard, Mint Intel, linked live leaderboard and weekly trade contests
  - **API library** — 1,500+ platform endpoints. Alpha Tek MCP is coming soon
  - **Alpha Brain / MLM** — Queryable memory for calls, search heat, and replay, keyed by mint
  - **Subscribe / Help** — Stripe payments, Privy wallet login, JWT sessions

Navigation is via a **sidebar**: Explorer, Dashboard, Multi-Chain (planned), Pump.fun, Alpha Radar (planned), Subscribe, Help. A **status bar** at the bottom shows connection health and **“Data: Xs ago”** so users see how fresh the DEX data is (5s refresh target).

### 2.2 Backend

- **API:** Express.js, REST. The public library is **1,500+ platform endpoints**. Alpha Tek MCP is coming soon.
- **Data:** Many upstreams, normalized behind Alpha Tek routes. See section 4. No single vendor is the stack.
- **Auth:** JWT. Provider keys stay on the server.
- **Cache:** Short TTL caches on live endpoints so the UI stays fresh without hammering any one feed.

---

## 3. Chains We Cover

The chain menu is **15 networks**: Solana, Ethereum, Base, BSC, Robinhood, Polygon, Arbitrum, Optimism, Avalanche, Linea, Pulse, Fantom, Ronin, Sei, and Monad.

Solana is the reference for depth. The same terminal, labels, and refresh model run across that menu. Chain parity, the multi-chain layout, and the shared dropdown are already shipped. They are not the next milestone.

---

## 4. Tech Stack Providers

Alpha Tek is the product. The names below are upstreams the live site actually reads. They do different jobs: prices, pools, headlines, wallets, charts, launches, and login. Listing them once is enough. The platform does not depend on any one of them for “all chains.”

**Markets and listings:** Binance, CoinMarketCap, CoinGecko, MEXC, CoinEx.

**On-chain pools and pairs:** DexScreener, GeckoTerminal, PancakeSwap, Jupiter, Raydium, FluxBeam, Birdeye, Solscan.

**Launches and terminals:** Pump.fun, GMGN, Axiom, Padre.

**Research and headlines:** CryptoRank, Bitcoin.com, Bloomberg lineup where the feed resolves.

**Wallets, maps, and perps:** Arkham, Bubblemaps, Hyperliquid.

**Charts:** TradingView.

**Account:** Privy (wallet login), Stripe (payments), Telegram (call rooms).

**Still wired, not the spine:** Moralis, for a few remaining EVM and Solana reads.

**Retired:** Cielo. It is not part of the current stack.

The 1,500+ figure is platform endpoints, not a claim that each name above is a separate company count. New feeds are added behind Alpha Tek routes. Public pages do not advertise the vendor as the feature.

---

## 5. DEX Terminal & Usability

### 5.1 One place for all chains

- **Explorer** is the main DEX Terminal: one landing page with summary, 3-column Pump.fun block, narratives, Top Networks, and the **DEX Tracker** table.
- **Tabs** in the DEX Tracker follow the chain dropdown, so the same flow works for every chain in the menu.

### 5.2 Live feel and performance

- **Refresh:** Frontend polls the backend on a short interval for live DEX data. The backend caches those reads so one upstream is not hit on every paint.
- **Status bar:** Shows “Ping” (health) and **“Data: Xs ago”** (or “just now”), updating every second so users always see how fresh the data is.
- **No table flash:** Updates are merged into existing state so the table doesn’t blank on each poll.

### 5.3 Usability goals

- **Single mental model:** One Explorer, one DEX Tracker, one chain selector — same flow for every chain.
- **Clear footprints:** Sidebar for product areas. Status bar for connection and data freshness. Coin and wallet pages keep a way back to the parent view.
- **Accessible defaults:** Solana and Ethereum as default chains where relevant; Top Networks and narratives visible without extra clicks.

---

## 6. Product Footprints & Menu

### 6.1 Current menu (October 18, 2026)

The live portal menu is the surface list in section 2.1. Chain parity, the multi-chain menu, usability polish, and the data surfaces in sections 3 through 5 are shipped. They are the floor, not the roadmap.

### 6.2 How it flows

One chain list in the dropdowns and filters. One DEX view. Deep pages keep context so a coin or wallet can jump back to Explorer. The status bar shows connection health and how fresh the data is.

---

## 7. Roadmap (summary)

Chain parity, the multi-chain menu, usability polish, and the data layer above are done. The next work is the reason the platform exists.

1. **Mainnet and AAI**  
   Launch AAI on mainnet and open the token for what the platform was built to do: access, utility, and a community that can grow without treating the product as a free demo forever.

2. **A community that fills the ecosystem**  
   People learn, stay social, and make call-outs in one place. Look up KOLs. Follow traders worth copying. Advancement comes from the community using the same clean desk, not from scattered chats.

3. **Learn before risking capital**  
   Alpha Trench is the practice floor. Paper books and the extension let someone learn trading, replay flow, and try call-outs before they fund a live wallet.

4. **Clean information, one desk**  
   The community standard is accurate, checkable context in Alpha Tek. The point of the stack is to cut psyop and rumor hops: headlines, wallets, KOLs, and chain data in one product, with the source mix named once in section 4.

5. **Tokenized participation**  
   AAI is how people take part: learn, post, stake utility, and move with the community inside the ecosystem. Devnet programs are already proven. Mainnet is the gate that turns that into the live loop.

---

## 8. Technical Summary

- **Stack:** Next.js, Express, the provider set in section 4, Privy, Stripe, JWT. API library is 1,500+ endpoints. Alpha Tek MCP is coming soon.
- **Security:** No provider keys in the client. Rate limits and cache TTLs protect upstreams.
- **Refresh:** Short poll and backend cache for live DEX data. The status bar shows freshness.
- **Chains:** The 15-chain menu in section 3, with Solana-level depth as the bar.

---

## 9. For the Community

The chain menu and the terminal are in place. What comes next is mainnet AAI, a community that learns and calls together, and Alpha Trench as the way to practice before real capital. The information standard is one clean desk, not a tour of vendor names.

Older chain notes that still mention Cielo or treat Moralis as the whole data layer are historical. They are not the current stack. Architecture and security live in [ALPHA_TEK_PLATFORM_PLAN.md](../ALPHA_TEK_PLATFORM_PLAN.md).

**Alpha Tek — Crypto intelligence at one view.**
