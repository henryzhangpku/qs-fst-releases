# QS FST — Releases

Pre-built binaries for **QS FST (Full Self Trading)**, the QuantSignals trading agent CLI.

Install:

```bash
curl -fsSL https://quantsignals.xyz/fst | bash
```

Then launch anywhere with `qs`. Docs and product: https://quantsignals.xyz/fst

This repository hosts release artifacts only.

## What is released here

| Tag prefix | Product |
|---|---|
| `vX.Y.Z` | QS FST CLI (`qs`), the **latest** release; Linux, macOS and Windows binaries with `.sha256` files |
| `desktop-vX.Y.Z` | QS FST 0DTE Trader desktop app |
| `stocktrader-desktop-vX.Y.Z` | QS FST Stock Trader desktop app |
| `randomtrader-desktop-vX.Y.Z` | Kalshi trader (Random Trader) desktop app |
| `fst-desktop-vX.Y.Z` | QS FST desktop app for macOS |
| `remoteangel-vX.Y.Z` | Remote Angel desktop app |

Desktop releases are published as **pre-releases**, so `/releases/latest` (what the
installer and `qs update` read) always resolves to the newest CLI. The desktop apps
find their updates through the manifests in `updaters/<app>/latest.json`.

---

## Author

**Henry Zhang** — quantitative engineer; fifteen years building research platforms and production trading systems, including eight years at BlackRock and two at PIMCO.

[LinkedIn](https://www.linkedin.com/in/henryzhang99/) · [GitHub](https://github.com/henryzhangpku) · [Substack](https://henryzhang.substack.com) · [officialhenryzhang.com](https://www.officialhenryzhang.com)

More work: [Autonomous Quant Researcher](https://github.com/henryzhangpku/autonomous-quant-researcher) (an LLM proposes, trusted code decides) · [research2prod](https://github.com/henryzhangpku/research2prod) (research code that is already production code) · [mft-engine](https://github.com/henryzhangpku/mft-engine) (one Rust code path for backtest and live) · [GPU price index](https://github.com/henryzhangpku/gpu-price-index) (a daily benchmark built like a settlement index) · [all repositories](https://github.com/henryzhangpku?tab=repositories)
