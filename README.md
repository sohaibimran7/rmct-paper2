# rmct-paper2

Working manuscript: **Consistency Training while Preserving Monitorability via Rate Matching**.

[Read the current manuscript](main.pdf).

## Build

The entrypoint is `main.tex`, which includes `current-results.tex` and `current-appendix.tex`. The original manuscript source is preserved in the Git history.

With a TeX installation and `latexmk`:

```sh
LC_ALL=C LANG=C latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex
```

## Draft status

This is a provisional research draft, updated 6 October 2026. Blue text marks additions relative to the original manuscript. Results on Gemma-4-12B-IT are in the main text and results on Qwen3.5-9B are in the appendix. All methods are compared at a matched budget of 128 training batches.

The repository contains manuscript source, bibliography, formatting dependencies, figure assets and the compiled PDF. Private experiment data, raw model responses, grading ledgers, credentials and local operational files are not included.
