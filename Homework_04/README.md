# CS 6220 – Homework 4

Implements the Apriori algorithm from scratch (support, confidence, lift,
frequent itemset mining with join/prune/count, and anti-monotone association
rule generation), plus hierarchical agglomerative clustering with efficient
incremental distance updates (min_dist / max_dist).

## Contents
- `CS6220_DM_Homework04_Rutuja.ipynb` — main notebook: Apriori, Apriori_rules,
  HAC, and all report experiments.
- `clustering.txt` — 2D dataset used for the hierarchical clustering part.
- `requirements.txt` — dependencies.

## Setup
```bash
pip install -r requirements.txt
jupyter lab
```
Open `CS6220_DM_Homework04_Rutuja.ipynb`, make sure `clustering.txt` is in
the same folder, and run all cells.

## Notes
All cells are pre-run with outputs saved. The full write-up (pseudocode,
tables, and discussion) is in the accompanying report.
