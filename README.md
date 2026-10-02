# rmct-paper2

Working manuscript: **Consistency Training while Mitigating Obfuscation via Rate Matching**.

[Read the current manuscript](manuscript.pdf).

## Build

The current entrypoint is `manuscript.tex`, which includes `current-results.tex` and `current-appendix.tex`. `main.tex` preserves the original manuscript source and is not the current entrypoint.

With a TeX installation and `latexmk`:

```sh
LC_ALL=C LANG=C latexmk -pdf -interaction=nonstopmode -halt-on-error manuscript.tex
```

## Draft status

This is a provisional research draft, updated 2 October 2026. Blue manuscript prose and captions identify additions for review. Historical evaluation results, affected RMCT training, incomplete coverage and unmatched comparisons are explicitly qualified in the manuscript; this repository does not establish clean retraining or final publication claims.

Gemma results are in the appendix. Main monitorability uses only the unfiltered top-right Luna zero-shot, reasoning-only, xhigh FNR–FPR panel. The appendix includes the verbalisation split, calibration configuration comparison and four-quadrant diagnostics.

The repository contains manuscript source, bibliography, formatting dependencies, figure assets and the compiled PDF. Private experiment data, raw model responses, grading ledgers, credentials and local operational files are not included.
