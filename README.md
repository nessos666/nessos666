### Hey, I'm David 👋

I build **systematic algorithmic trading systems** for NQ futures — and the infrastructure around them.

```
Automation │ Anti-overfitting backtesting │ Quant research │ MCP servers │ systemd │ Python
```

---

## GitHub Repos (10)

My public work spans the full stack of algorithmic trading — from statistical foundations to production monitoring.

### 🔬 Quantitative Research

| Project | Stars | What it does | Try it |
|---------|-------|-------------|--------|
| [**nq-strategy-builder**](https://github.com/nessos666/nq-strategy-builder) | ★3 | IS/OOS/Holdout backtesting with NLP-driven strategy composition. Type `./sb.py "FVG + OB NY"` → tier-graded result. **158 files, 60 tests.** | [README](https://github.com/nessos666/nq-strategy-builder#readme) |
| [**quant-tools**](https://github.com/nessos666/quant-tools) | ★ | Ornstein-Uhlenbeck MLE fitting, simulation, bias correction, volatility estimation. Cross-validated against academic references. | [README](https://github.com/nessos666/quant-tools#readme) |
| [**baustein-tester**](https://github.com/nessos666/baustein-tester) | ★ | Isolate and rank signal concepts (FVG, OB, Sweep, Breaker). Hit rate, win rate, overlap, session bias — before building a strategy. | [README](https://github.com/nessos666/baustein-tester#readme) |

### 📡 Infrastructure & Monitoring

| Project | Stars | What it does |
|---------|-------|-------------|
| [**topstepx-api-health-monitor**](https://github.com/nessos666/topstepx-api-health-monitor) | ★4 | 9 automated checks → Trust Score 0-100. Contract rollover, token expiry, bar quality, latency trending. |
| [**rithmic-api-health-monitor**](https://github.com/nessos666/rithmic-api-health-monitor) | ★3 | File-based health monitoring for Rithmic API — 10 checks, no own connection (prevents session conflicts). |
| [**api-health-trust-system**](https://github.com/nessos666/api-health-trust-system) | ★3 | Generic weighted Trust Score for any REST API. Pluggable checks, Telegram alerts, atomic JSON export. |

### 🤖 Automation & AI

| Project | Stars | What it does |
|---------|-------|-------------|
| [**tv-watch-agent**](https://github.com/nessos666/tv-watch-agent) | ★ | Chrome DevTools Protocol-based chart watcher. Session-aware screenshots, CSV logging, auto-backup rotation. |
| [**chart-vision-mcp**](https://github.com/nessos666/chart-vision-mcp) | ★ | **New** — Local MCP server for chart analysis. OpenCV + Tesseract OCR. No API keys, no GPU, fully offline. |
| [**context-bench**](https://github.com/nessos666/context-bench) | ★2 | Self-learning Claude Code plugin. Detects your project from the first message and injects relevant context. |

### 🛠 Developer Tools

| Project | Stars | What it does |
|---------|-------|-------------|
| [**multi-rep-set**](https://github.com/nessos666/multi-rep-set) | ★ | Multi-language code checker. Lint Bash, Python, JS, JSON, YAML, Markdown. Zero dependencies. |

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
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![CDP](https://img.shields.io/badge/CDP-Chrome_DevTools-4285F4?style=flat-square&logo=google-chrome&logoColor=white)
![TradingView](https://img.shields.io/badge/TradingView-131722?style=flat-square&logo=tradingview&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![systemd](https://img.shields.io/badge/systemd-0A0A0A?style=flat-square&logo=systemd)

**Languages:** Python · Bash · Pine Script · JavaScript · SQL

**Infrastructure:** systemd (33 services) · n8n · Grafana · Qdrant · SQLite · Docker

**Trading:** NQ/MNQ Futures · TopStepX · Rithmic · AMP · Interactive Brokers

**AI/ML:** HMM · Optuna · OpenCV · DSPy · HuggingFace · Local LLMs

---

## Philosophy

| Principle | What it means in practice |
|-----------|--------------------------|
| **Anti-overfitting first** | In-sample/OOS/Holdout separation is non-negotiable. Every strategy gets a tier grade. |
| **Degradation is the signal** | A strategy with PF 1.8 IS → 1.7 OOS (5.6% degradation) beats one with 3.0 IS → 1.2 OOS (60%). |
| **Build infrastructure, not magic** | Monitoring, logging, validation before every trade. 33 systemd services. |
| **Open source the tooling** | The big firms have monitoring dashboards. Retail algo traders deserve the same. |
| **Correctness > features** | Every estimator cross-validated against academic references. Verified > engineered. |

---

## About Me

- **11 years** self-employed — tree care, construction, and now algorithmic trading
- **System thinker** — the same structured approach applies to code, markets, and physical work
- **Self-taught** — Python, Linux, quant finance, MCP servers, systemd
- **Languages:** DE (native) · HU (native) · EN (B2/C1)
- **Location:** Germany / Hungary / Remote · open to international opportunities
- **GitHub:** [nessos666](https://github.com/nessos666)
- **LinkedIn:** [linkedin.com/in/david-nessos666](https://linkedin.com/in/nessos666)

---

*Building at the intersection of systematic trading, data science, and Linux automation.
If you find an edge I missed or want to exchange ideas — reach out.*

**github.com/nessos666**
