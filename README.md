# DSPy Optimization — Interactive Notebooks

The 12 companion notebooks from the **Optimizer University** DSPy prompt-optimization portfolio —
twelve real lessons, each rendering the **actual** compiled programs and scorecards from real runs.

**They're artifact-driven:** every chart and number comes from a genuine optimization run, baked into
the notebook. Open any of them and the real results are already rendered — **no LM, no GPU, no API key,
no setup.**

## 📓 View the notebooks

> **Tip:** GitHub's inline `.ipynb` viewer can fail to render the heaviest notebooks (they emit large
> styled-HTML outputs) with *"Unable to render code block."* The **nbviewer** links below render them
> reliably. Both show the same pre-computed results.

| # | Notebook | View |
|---|---|---|
| 00 | Introduction — the portfolio at a glance | [nbviewer](https://nbviewer.org/github/mediamanipulation/dspy-optimization-notebooks/blob/main/00_introduction.ipynb) |
| 01 | Signatures, Modules & Metrics | [nbviewer](https://nbviewer.org/github/mediamanipulation/dspy-optimization-notebooks/blob/main/01_signatures_modules_metrics.ipynb) |
| 02 | LabeledFewShot — the demos it chose | [nbviewer](https://nbviewer.org/github/mediamanipulation/dspy-optimization-notebooks/blob/main/02_labeled_fewshot.ipynb) |
| 03 | BootstrapFewShot — teacher traces | [nbviewer](https://nbviewer.org/github/mediamanipulation/dspy-optimization-notebooks/blob/main/03_bootstrap_fewshot.ipynb) |
| 04 | MIPROv2 & Search | [nbviewer](https://nbviewer.org/github/mediamanipulation/dspy-optimization-notebooks/blob/main/04_mipro_and_search.ipynb) |
| 04b | GEPA — the 8,078-char evolved instruction | [nbviewer](https://nbviewer.org/github/mediamanipulation/dspy-optimization-notebooks/blob/main/04b_gepa.ipynb) |
| 05 | Data Generation — the 63/160 → 160/160 fix | [nbviewer](https://nbviewer.org/github/mediamanipulation/dspy-optimization-notebooks/blob/main/05_data_generation.ipynb) |
| 06 | Tracing & Inspection — crack open a program | [nbviewer](https://nbviewer.org/github/mediamanipulation/dspy-optimization-notebooks/blob/main/06_tracing_and_inspection.ipynb) |
| 07 | Structured Extraction (UC02, +10.6%) | [nbviewer](https://nbviewer.org/github/mediamanipulation/dspy-optimization-notebooks/blob/main/07_structured_extraction.ipynb) |
| 08 | RAG & When NOT to Optimize (UC03, +0.0%) | [nbviewer](https://nbviewer.org/github/mediamanipulation/dspy-optimization-notebooks/blob/main/08_rag_and_when_not_to_optimize.ipynb) |
| 09 | Zero-Shot Constraints (UC04, +9.1%) | [nbviewer](https://nbviewer.org/github/mediamanipulation/dspy-optimization-notebooks/blob/main/09_zero_shot_constraints.ipynb) |
| 10 | Generation + LM-Judge (UC05, +11.4%) | [nbviewer](https://nbviewer.org/github/mediamanipulation/dspy-optimization-notebooks/blob/main/10_generation_and_lm_judge.ipynb) |

## ▶️ Reading vs. running

These notebooks are **pre-rendered** — open any nbviewer link above and every result is already
there, no LM, no GPU, no setup. This repo is the **view-only** copy: the outputs you see were
produced by the original optimization runs and baked into the `.ipynb`.

To *execute or modify* them against the live run artifacts (the compiled programs + scorecards),
use the full course bundle from the main project.

## The portfolio behind them

Five real tasks put through a baseline and a suite of DSPy optimizers, scored on a held-out dev set
with cache disabled. **Four wins via different levers — and one honest case where the right call was
*not* to optimize.**

| Use case | Before → After | Lift | Winning lever |
|---|---|---|---|
| Sales Email | 61.0 → 72.4% | **+11.4%** | Reflective GEPA |
| Contract Extractor | 78.4 → 89.0% | +10.6% | Bootstrapped + search |
| Clinical Note | 69.6 → 78.7% | +9.1% | Reflective GEPA |
| Ticket Router | 92.8 → 96.8% | +4.0% | Few-shot demos |
| RAG Answer | 80.9 → 80.9% | +0.0% | (baseline wins) |

*The model never got smarter — we just got better at asking.*
