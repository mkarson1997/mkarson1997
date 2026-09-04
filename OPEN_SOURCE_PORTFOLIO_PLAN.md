# Open Source Portfolio Plan

This file is the source of truth for preparing Mahmoud Karzoun's repositories for public open-source release.

## Release rule

A repository is not marked **PUBLIC-READY** until all of the following are true:

- no live credentials, tokens, private keys, passwords, cookies, or local `.env` files are tracked;
- no real user/customer/runtime databases, logs, screenshots, exports, or personal data are tracked;
- generated caches/build output and local virtual environments are excluded;
- third-party code/assets/data are identified and their licenses/attribution are preserved;
- project-authored code has an explicit license when appropriate;
- README explains what the project is, how to run it, limitations, and current maturity honestly;
- a security policy or security boundary is documented for projects with authentication, automation, finance, or external integrations;
- tests/CI are added where they materially improve confidence;
- any credential discovered in an archive or Git history is rotated before public release.

## Current portfolio queue

| Repository | Status | Public-release blockers | Development direction |
|---|---|---|---|
| `scorebot` | 🟡 NEAR-READY | Add explicit project license and third-party/legal notice for official API/app analysis; final secret/history review | Flagship Telegram/FastAPI reliability case study; preserve tests, provider abstraction and admin security |
| `karzoun-media-factory` | 🟡 NEAR-READY | Add license; final secret/history/large-repo review; document third-party AI/YouTube/OpenArt boundaries | Flagship automation/orchestration platform with safety gates, tests and reproducible local demo |
| `mk-nuclear-spacecraft` | 🟡 CLEANUP | Add license and clear scope/safety statement; keep public material conceptual/software-focused | Open-source agent/orchestration and isolation laboratory; avoid actionable hazardous engineering material |
| `My-Digital-Factory` | 🟡 INCOMPLETE | Missing `warehouse` module; add README, license, tests and CI | Reconstruct a small privacy-aware email analysis pipeline or package it as a coherent showcase |
| `crypto` | 🟠 HOLD | Generalize personal runtime config; add `.env.example`, gitignore/license/tests; rotate credentials discovered in separate uploaded bot archives before related publication | Educational trading/research automation only; paper-trading/backtesting-first architecture |
| `KARZOUN_ULTRA` | 🟠 CLEANUP | Remove tracked runtime config, backup/patch debris and stray files; review asset rights; verify examples contain placeholders only | Consolidate into a clean AI media automation framework with one canonical architecture and test path |
| `peyzaj-erp` | 🟠 CLEANUP | Remove/reconcile nested legacy copy `main/peyzaj-1.0`; strengthen root ignore rules; audit deployment examples and asset/license boundaries | ERP flagship with Laravel/mobile/deployment story, clean monorepo layout and reproducible demo data |
| `bhs-core` | 🔴 BLOCKED | Hardcoded demo API keys/admin password fallbacks, prefilled browser credentials, runtime logs/data, pycache and generated artifacts are tracked | Security flagship after fail-closed configuration, synthetic fixtures, clean data boundaries, tests and threat model |

## Uploaded local archives

### `pro-max-creative-frontend-skill`

The uploaded skill source contains no obvious secrets and is suitable for a dedicated public repository after adding a polished README, license, contribution guidance, examples, and versioning. The GitHub connection cannot create a new repository, so repository creation is the only manual account-level step.

### Crypto/Freqtrade archives

The uploaded local crypto archives are **not safe to publish raw**. One archive contains live-looking Binance and Telegram credentials; another contains Telegram/API-server secrets plus runtime logs and a SQLite trades database. Those credentials must be rotated/revoked and runtime data must be removed. The uploaded Freqtrade source is upstream GPL-licensed software and must remain attributed/licensed as a derivative/fork rather than being presented as original work.

## Publication order

1. `scorebot`
2. `karzoun-media-factory`
3. `mk-nuclear-spacecraft`
4. `My-Digital-Factory`
5. `crypto`
6. `KARZOUN_ULTRA`
7. `peyzaj-erp`
8. `bhs-core`

The order favors repositories that can become high-quality public engineering artifacts quickly while keeping risky or messy repositories private until their release blockers are actually removed.
