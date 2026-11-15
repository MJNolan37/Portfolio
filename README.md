# Quantitative Research Portfolio

[GitHub profile](https://github.com/MJNolan37) / Portfolio

Research pipelines, statistical validation and interactive tools built with public or synthetic data. This index provides the evidence and scope behind the short project summaries on my profile.

## Project Index

| Project | What I built | Inspect |
|---|---|---|
| V&D Cloud and Atlas | Volatility-and-dispersion research pipeline and a descriptive monitoring dashboard | [Research](https://github.com/MJNolan37/vd-cloud) · [Dashboard](https://mjnolan37.github.io/vd-cloud/) |
| Project Parallax | Market / industry / firm variance decomposition and staged research validation | [Repository](https://github.com/MJNolan37/Project-Parallax) |
| Options Positioning Research | Synthetic option-chain pipeline, engineered features and descriptive charts | [Repository](https://github.com/MJNolan37/options-positioning-research) |
| AI Research Playbook | Documented research workflow and reusable templates | [Playbook](https://github.com/MJNolan37/ai-research-playbook) |

## V&D Cloud and Atlas

Built an Ichimoku-inspired regime framework using volatility and cross-sectional dispersion, first for QQQ and then for a developed-market ETF panel. The work includes data preparation, baseline comparisons, HAC/Newey-West inference, permutation diagnostics and retrospective chronological stability analysis.

**Result and scope.** The revised analysis did not establish predictive validity or a consistent advantage over simpler baselines. The [canonical evidence table](https://github.com/MJNolan37/vd-cloud#verified-revised-results) separates exploratory threshold crossings from validated findings. No selection or multiplicity correction was applied; the later period was retrospective, not an untouched holdout.

### Atlas: the descriptive dashboard

Atlas turns the descriptive learning into an interactive TQQQ monitoring view, with QQQ as a return-alignment benchmark. It displays a saved, manually regenerated daily-data snapshot rather than live quotes. Its provisional state labels are descriptive, with no validated forecasting claim.

[Research and reproduction instructions](https://github.com/MJNolan37/vd-cloud) · [Open Atlas](https://mjnolan37.github.io/vd-cloud/) · [Dashboard calculations](https://github.com/MJNolan37/vd-cloud/tree/main/atlas)

## Project Parallax

Rebuilt a published three-component equity variance decomposition on public data for 2010–2024. Completed Phase 1 measurement work with 24 known-answer validation cases, documented coverage and missing-data decisions, and disclosed a frozen Phase 2 specification with synthetic implementation validation.

**Sample and interpretation.** The sample projects current S&P 500 members backward. It covers large caps and carries survivorship bias whose direction and magnitude have not been established for this dataset. The [Campbell et al. (2022) paper](https://www.nber.org/system/files/working_papers/w29916/w29916.pdf) provides the post-2001 comparison benchmark.

**Next-stage boundary.** At the [October 25, 2026 status snapshot](https://github.com/MJNolan37/Project-Parallax/blob/38411cc050696efde85d7702c9a11b9ad985c693/docs/A1_STATUS.md), the H1 critical value remained unresolved and no empirical H1/H2 analysis had been run. Implementation validation and the research hypotheses are separate milestones.

[Repository and methodology](https://github.com/MJNolan37/Project-Parallax) · [Validation-gate case study](https://github.com/MJNolan37/ai-research-playbook/blob/main/case-studies/parallax-validation-gate.md)

## Options Positioning Research

Built a synthetic option-chain research testbed: a documented schema, wide-to-long contract normalization, eight positioning and liquidity features, cumulative open-interest terrain, automated validation and charts across a 65-date series.

**Validation and scope.** The [saved single-snapshot check report](https://github.com/MJNolan37/options-positioning-research/blob/main/results/published_check_summary.json) covers 2,090 contracts dated July 20, 2026, with 10 checks passing, two informational and none failing. That report covers one snapshot; the longer series has descriptive analysis. All option-chain values are synthetic, apart from the underlying's real daily price path. The project demonstrates engineering and representation without establishing predictive or trading performance.

[Repository, pipeline and charts](https://github.com/MJNolan37/options-positioning-research)

## Research Workflow

[AI Research Playbook](https://github.com/MJNolan37/ai-research-playbook) documents how I frame AI-assisted work, check claims, retain decision authority and record what each build teaches me. Its main case follows Parallax's calibration gate at the documented snapshot.

[Read the playbook](https://github.com/MJNolan37/ai-research-playbook) · [Reusable templates](https://github.com/MJNolan37/ai-research-playbook/tree/main/templates)

## Tools Used in These Projects

Python · pandas · NumPy · statsmodels · Plotly · Matplotlib · Jupyter · Git

AI tools assist implementation and review. The research questions, methodological decisions and final interpretations are mine.

## License

Copyright © 2026 Matthew Nolan (MJNolan37). Except where otherwise noted, the original text and diagrams in this repository are licensed under [CC BY 4.0](LICENSE). Linked repositories, external material and third-party assets retain their own licenses and terms.
