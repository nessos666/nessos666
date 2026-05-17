### Hey, I'm David 👋

I build **systematic algorithmic trading systems** for NQ futures — and the infrastructure around them.

Anti-overfitting backtesting · Quant tooling · API monitoring · TradingView automation

---

## Featured Projects

| Project | Stars | Description |
|---------|-------|-------------|
| [nq-strategy-builder](https://github.com/nessos666/nq-strategy-builder) | ★3 | Systematic IS/OOS/Holdout backtesting framework — modular building blocks, NLP parser, Optuna sweeps, anti-overfitting by design |
| [quant-tools](https://github.com/nessos666/quant-tools) | ★ | Ornstein-Uhlenbeck MLE fitting, simulation, bias correction, volatility estimation — cross-validated against academic reference implementations |
| [topstepx-api-health-monitor](https://github.com/nessos666/topstepx-api-health-monitor) | ★4 | Real-time Trust Score 0-100 for TopStepX/ProjectX API — 9 automated checks, contract rollover detection, latency trending |
| [rithmic-api-health-monitor](https://github.com/nessos666/rithmic-api-health-monitor) | ★3 | File-based health monitoring for Rithmic API — 10 checks, prevents session conflicts, Trust Score output |
| [api-health-trust-system](https://github.com/nessos666/api-health-trust-system) | ★3 | Generic weighted Trust Score for any REST API — pluggable checks, Telegram alerts, atomic JSON export |
| [baustein-tester](https://github.com/nessos666/baustein-tester) | ★ | Scan, compare, and rank signal concepts (FVG, OB, Sweep, Breaker) — hit rate, win rate, concept overlap analysis |
| [tv-watch-agent](https://github.com/nessos666/tv-watch-agent) | ★ | Automated chart watcher via Chrome DevTools Protocol — session-aware screenshots, backup rotation |
| [context-bench](https://github.com/nessos666/context-bench) | ★2 | Self-learning Claude Code plugin that auto-injects project context — learns from your work patterns |
| [multi-rep-set](https://github.com/nessos666/multi-rep-set) | ★ | Multi-language code checker — lint Bash, Python, JS, JSON, YAML, Markdown. Zero dependencies. |

---

## Building Blocks Research

```
Signals       │  FVG · Order Block · Liquidity Sweep · BOS · MSS · iFVG · Breaker
Context       │  Session Filter · HRL/LRL Regime · Macro Windows · Trend · PD Array
Entry Logic   │  First Touch · Second Touch · Displacement · CE (50%)
Exit Logic    │  ATR Trail · Breakeven · Next Zone · Session Exit
Research      │  HMM Regime Detection · Event Chain Probability · Pre-Displacement
```

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-blueviolet?style=flat-square)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![CDP](https://img.shields.io/badge/CDP-Chrome_DevTools-4285F4?style=flat-square&logo=google-chrome&logoColor=white)
![TradingView](https://img.shields.io/badge/TradingView-131722?style=flat-square&logo=tradingview&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Languages & Tools:** Python · Bash · Pine Script · JavaScript · SQL · Git · systemd · n8n

---

## Philosophy

1. **Anti-overfitting first** — In-sample/OOS/Holdout separation is non-negotiable
2. **Degradation is the signal** — how a strategy holds up out-of-sample tells you real edge from noise
3. **Build infrastructure, not magic** — monitoring, logging, validation before every trade
4. **Open source the tooling** — the big firms have monitoring dashboards. Retail algo traders deserve the same.
5. **Correctness > features** — every estimator cross-validated against academic references

---

*Building at the intersection of systematic trading, data science, and Linux automation.*

**github.com/nessos666**
