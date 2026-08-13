# puranjay haldankar

● ml researcher · founder · mumbai → atlanta · cs @ georgia tech '30

building **Soverin** — real-life cognition in games

---

## // now

- `building` — **Soverin Labs**, real-life cognition in games `stealth`
- `research` — pan-stress hub genes in CTCs via GNNs · NeurIPS target
- `research` — HMM regime models for sports outcomes · MIT URTC 2026 target
- `shipping` — sbl.you, deterministic coaching for lifters
- `interests` — ML · quant finance · market microstructure · algo trading · LLM evals

---

## // selected work

**`Soverin Labs`** · ML developer · Jul 2026 – present · `stealth`
Real-life cognition in games. Under wraps — more soon.
`Game Dev` `ML` `Cognition`

**`Gaussian HMM Football Predictor`** · live-tested on WC 2026
Elo tells you who is better. It cannot tell you who is *in form*. Models form as a hidden Markov state per team, keeps the full distribution over all 7 states instead of collapsing to a point estimate, and feeds the joint 7×7 grid plus both entropies into a logistic head. Trained on **33,455** matches across 217 teams; genuinely out-of-sample, walk-forward, on all 104 World Cup 2026 fixtures.
`65.4%` all 104 WC matches · `82.1%` on 84 decisive matches · beats XGBoost and Random Forest on identical features
*Honest limitation: on raw pick accuracy it ties Elo. The edge is probability quality — draws, calibration, confidence gating.*
`Python` `hmmlearn` `scikit-learn` `McNemar / bootstrap CIs` `paper in progress`

**`BroScienceBench`** · benchmark v1.1 · frozen
An LLM benchmark for gym misinformation — confident, popular, evidence-contradicting training and nutrition claims. Core finding: **multiple choice saturates** (7 of 8 models hit ~100%) and hides everything; the open-ended protocol opens a real **76–98% gradient**. Scored for both accuracy and myth-adherence, graded by a judge outside every evaluated model family.
`246` items · `8` models · `0.89` Gwet's AC₁ (judge agreement)
`Python` `OpenRouter` `Wilson CIs` `exact McNemar` `HuggingFace dataset + datasheet`

**`CTC Hypoxia & Circadian Mechanism`** · research · Dr. Sarita Poonia
Single-cell RNA-seq re-analysis of breast-cancer circulating tumour cells, integrating GSE126669 and GSE180097 via Harmony. The interesting part is what broke: two of three positive results turned out to be artifacts — cell-line composition (a textbook Simpson's paradox) and immune-cell contamination. What survives is a GSEA-validated hypoxia survival program and an independent reproduction of rest-phase CTCs being more proliferative.
`306` single CTCs across 2 datasets · `3/5` findings survived de-confounding · `p=0.0036` rest-phase proliferation
`R` `Seurat` `Harmony` `fgsea` `MSigDB`

**`IB Cognito`** · co-founder & CTO · Jul 2024 – present · `live 🟢`
Free IB learning platform built from scratch → **10k monthly users across 108 countries**, zero marketing budget. Backed by WACP International.
`React` `Node.js` `PostgreSQL` · [ibcognito.com](https://ibcognito.com)

**`sbl.you`** · founder · Jun 2026 – present · `in development`
Science-based lifting, handled for you. A rules-and-stats engine computes every number from your own logs; the LLM layer only narrates what the code already produced, so it can't hallucinate your lifts. Apple Health ingest, Hevy/CSV import.
`Expo` `React Native` `Supabase` `HealthKit` `TypeScript`

**`Black-Scholes Options Pricer`** · complete
European option pricing from scratch — analytical Black-Scholes, all 5 Greeks (Δ Γ V Θ ρ), Monte Carlo via geometric Brownian motion. `norm_cdf` hand-implemented via Abramowitz & Stegun (err < 7.5e-8). Zero financial libraries.
`Python` `NumPy` `Monte Carlo` `from scratch`

**`Ensemble Stock Forecaster`** · published · RARS, Sep 2025
Multi-model ensemble over RF, XGBoost, ARIMA, Prophet and Gradient Boosting on SPY, with 15+ technical indicators. `55%` directional accuracy · `150+` downloads.
`Python` `XGBoost` `Streamlit` `yfinance`

**`Hot Corners`** · shipped
macOS menu-bar app that launches any app when you flick the cursor into a screen corner. Per-corner assignment, activation delay, no dock icon. Built because macOS only lets you bind corners to system actions, not to apps.
`Swift` `AppKit` `SwiftPM`

**`RSA Decryption Time Modeller`** · IB IA · A grade
Full RSA pipeline from scratch with naïve trial division and Pollard's Rho factorization engines. Benchmarked across 4–13 digit primes, extrapolated to real 308-digit keys: `10^313s` naïve vs `10^152s` Rho.
`Python` `Cryptography` `Number Theory` `from scratch`

---

## // experience

| role | org | when |
|---|---|---|
| ML Developer | Soverin Labs | Jul 2026 – present |
| Founder | sbl.you | Jun 2026 – present |
| ML Researcher | Independent · Dr. Sarita Poonia | Apr 2026 – present |
| Co-Founder & CTO | IB Cognito | Jul 2024 – present |
| Co-ops Lead | MLV | Feb 2026 – present |
| AI/ML Intern | Pharmint | Jun – Aug 2025 |
| Web Developer | sanjayrajawat.com · 3k+ paid users, Stripe infra | Jun – Sep 2025 |
| Policy Research Intern | Government of Uttar Pradesh | May – Jul 2025 |
| Library Development Manager | Share A Book India · 100+ students | Mar 2025 – May 2026 |
| Teaching Intern | Schoolhouse.world + Udaan · 80+ learners, 20+ countries | Jul 2024 – Jun 2025 |

---

## // awards

🥇 **All India Rank 1** — ICSE Computer Science · CISCE Merit Certificate
🥉 **AMO 2024 Bronze** — World Rank 17 · India Rank 14 · SIMCC
🏆 **Principal's Award** — 6 of 100 students, all-rounder excellence · Apr 2026
💡 **Young Innovator's Award** — for IB Cognito, built to 10k users mid-IBDP · Apr 2026
📈 **4th Place, Harvard Stock Pitch** — Harvard Student Agencies · Sep 2024
🔬 **IRO 2025 Honor Roll** — International Research Olympiad
🥉 **NJCO 2024 Bronze** — National Junior Chemistry Olympiad
📄 **Published Researcher (×2)** — RARS Sep 2025 · IERJ Dec 2024

---

## // stack

`Python` `PyTorch` `R` `Swift` `TypeScript` `React` `React Native` `Node.js` `SQL` `PostgreSQL` `Supabase` `Expo` `scikit-learn` `Seurat` `Figma`

---

## // find me

[phaldankar3@gatech.edu](mailto:phaldankar3@gatech.edu) · [github](https://github.com/puranjayh) · [linkedin](https://linkedin.com/in/puranjay-haldankar)

// open to research collabs, builder chats, and good ideas
