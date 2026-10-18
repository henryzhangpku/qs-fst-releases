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
