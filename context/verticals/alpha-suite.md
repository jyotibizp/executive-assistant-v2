# Vertical 2 — Alpha Suite

**Purpose:** market intelligence layer. First used by the internal trading desk with own capital as a lab; later part of a wealth-tech division.
**Principle:** decisions come from the integrated system (macro, flows, internals, positioning, regime, thesis, risk), not standalone signals.

- [ ] Macro Tracker
- [ ] Regime Tracker
- [ ] Stock Screener
- [ ] Options Scout (Options Signal Scout)

## Macro Tracker — spec
- List of macros to track
- Their cyclical pattern
- Current state as a percentile value
- Current state flags:
  - Mean reversion — Y/N
  - Trending — Y/N
  - Consolidating — Y/N

## Regime Tracker — spec
Classify where the market is:
- Near a long-term peak (down / up)
- Near a medium-term peak (down / up)
- In the middle of a cycle

## Options Signal Scout
- NIFTY options setup scanner. Internal use only.
- Stack: FastAPI + PostgreSQL + React, Zerodha Kite Connect for data.
- Repo: [`oscout-v2`](https://github.com/jyotibizp/oscout-v2). (`oscout` v1 is stale.)

## Desks served
- **Trading Desk** — swing/positional, stocks & futures.
- **"The Killers"** — intraday options-buying desk, activated occasionally.
- **Hedge fund designer view** — guides both; risk-parity allocation, regime-based strategy choice.

## Status
- OPEN: build status of each tracker, data sources for macros.
