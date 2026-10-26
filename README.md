# Quantitative Research Portfolio

## Start here

1. [V&D Cloud](https://github.com/MJNolan37/vd-cloud) — the most complete evidence path: question, tests, negative result, and Atlas.
2. [Project Parallax](https://github.com/MJNolan37/Project-Parallax) — research judgment and staged execution: coverage gate, preregistration, and an audit finding turned into a regression test.
3. [Options Positioning Research](https://github.com/MJNolan37/options-positioning-research) — synthetic-chain engineering with explicitly scoped validation and gap-aware descriptive charts.

A curated collection of independent quantitative research exploring financial markets, portfolio analytics, statistical validation, and decision-making under uncertainty.

This repository serves as the public entry point to my research portfolio. It highlights selected projects that demonstrate quantitative reasoning, software development, and rigorous research methodology. Each featured project emphasizes reproducibility, transparent assumptions, and careful validation over attractive conclusions.

> **Research Philosophy**
>
> I build research to challenge ideas rather than confirm them. Well-documented negative results are valuable when they meaningfully reduce uncertainty.

---

# Featured Research

## 🔭 Project Parallax

**Project Parallax — Equity Dispersion & Attribution** is an active research project examining how explanations of equity returns change across analytical lenses.

The project asks how the same portfolio outcome may be interpreted differently through dispersion and correlation, variance decomposition, portfolio attribution, factor models, and residual or security-specific effects.

Phase 1's public-data market / industry / firm variance decomposition is complete for 2010–2024, with 24 known-answer validation cases. The sample projects current S&P 500 members backward: large caps only, with survivorship bias of unknown direction and magnitude. Phase 2's [frozen preregistration](https://github.com/MJNolan37/Project-Parallax/blob/main/docs/phase2_preregistration_v1.0.md) and synthetic implementation validation are disclosed; empirical hypothesis testing remains gated and has **not** begun. The existing post-2001 benchmark is [Campbell et al. (2022)](https://www.nber.org/system/files/working_papers/w29916/w29916.pdf).

The research emphasizes:

- disciplined hypothesis and decision governance
- historical replication before original hypothesis testing
- explicit treatment of survivorship and data-quality limitations
- comparison across attribution and factor-model perspectives
- reproducible public-data research
- clear separation between methodological validation and empirical evidence

**[View the repository →](https://github.com/MJNolan37/Project-Parallax)**

**Technologies**

- Python
- Pandas
- NumPy
- Jupyter Notebook
- yfinance
- SEC EDGAR
- Kenneth French Data Library

---

## 📈 V&D Cloud

**Volatility & Dispersion Cloud** is a market-state diagnostic research project inspired by Ichimoku-style regime mapping.

Instead of applying cloud analysis directly to price, the project investigates whether a synthetic market opportunity signal constructed from volatility and dispersion can provide useful descriptive information about market environments.

The research emphasizes:

- hypothesis-driven quantitative research
- statistical validation using multiple robustness checks
- transparent reporting of limitations
- reproducible analysis using public market data

The revised analysis did not establish predictive validity or a consistent advantage over simpler baselines. The [canonical evidence table](https://github.com/MJNolan37/vd-cloud#verified-revised-results) reports exploratory threshold crossings, not validated findings. No selection or multiplicity correction was applied, and the later period was retrospective, not an untouched holdout.

**[View the repository →](https://github.com/MJNolan37/vd-cloud)**

**Technologies**

- Python
- Pandas
- NumPy
- Statsmodels
- Plotly
- Jupyter Notebook

---

## 🌍 Atlas Observatory

Atlas Observatory extends the V&D research into an interactive visualization environment.

It provides a visual framework for exploring market-state diagnostics through dashboards that combine volatility, dispersion, and derived market-state classifications.

The project focuses on making quantitative research easier to interpret while preserving methodological transparency. Zone labels are explicitly provisional and rule-based — a monitoring instrument, not a trading signal.

**[Open the live dashboard →](https://mjnolan37.github.io/vd-cloud/)** · **[View the notebook →](https://github.com/MJNolan37/vd-cloud/tree/main/atlas)**

---

## 🎯 Options Positioning Research

A study of synthetic option-chain structure: a documented schema, wide-to-long contract normalization, eight engineered positioning/liquidity features, cumulative open-interest terrain, and gap-aware longitudinal charting. The [named saved single-snapshot report](https://github.com/MJNolan37/options-positioning-research/blob/main/results/published_check_summary.json) records 10 pass, 2 informational, 0 fail on 2,090 contracts dated 2026-07-20. The 65-date series has descriptive analysis, but no published full-series 12-check report.

Deliberately stops before machine learning. The contribution is engineering, representation, and validation — not prediction, sentiment inference, or trading claims. All option-chain values are synthetic except the underlying's real daily price path.

**[View the repository →](https://github.com/MJNolan37/options-positioning-research)**

**Technologies**

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

# Research Interests

Current areas of focus include:

- Market-state diagnostics
- Portfolio attribution and risk
- Statistical validation
- Options analytics
- Quantitative finance
- Risk modeling
- Machine learning for finance
- Research engineering

---

# Technical Stack

### Languages

- Python
- R
- SQL
- VBA

### Libraries

- Pandas
- NumPy
- Statsmodels
- Plotly
- Matplotlib

### Tools

- Git
- Jupyter
- Obsidian
- Notion

---

# Repository Roadmap

The portfolio will continue to expand as projects complete governance review and become suitable for public release.

Planned additions include:

- Statistical validation utilities
- Macro liquidity forecasting
- Research engineering tools

Projects remain private until they meet documentation, reproducibility, and data-governance standards.

---

# Research Standards

Every published project aims to demonstrate:

- Clear research questions
- Transparent methodology
- Reproducible implementation
- Honest discussion of limitations
- Appropriate validation
- Separation of public and private research artifacts

---

# Contact

If you'd like to discuss quantitative research, portfolio analytics, or financial technology, feel free to connect through GitHub or LinkedIn.
