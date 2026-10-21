# CS 6220 – Homework 3

Implements k-NN from scratch (Lp distance, prediction, decision-boundary
visualization, train/LOOCV-test error), a perceptron training rule, and
single-neuron gradient descent training with pluggable activation and cost
functions. Also includes two runs of the provided gradient-flow demo
(sigmoid+MSE baseline vs. cross-entropy) used to study vanishing gradients.

## Contents
- `CS6220_DM_Homework03_Rutuja.ipynb` — main notebook: k-NN, perceptron,
  single-neuron training, and all report experiments.
- `HW3_gradient_flow_mnist.ipynb` — demo notebook run with sigmoid + MSE
  (baseline, gets stuck at ~11% accuracy).
- `Q12_HW3_gradient_flow_mnist.ipynb` — demo notebook run with cross-entropy
  + identity output activation (reaches ~91% accuracy).
- `requirements.txt` — dependencies.

## Setup
```bash
pip install -r requirements.txt
jupyter lab
```
Open `CS6220_DM_Homework03_Rutuja.ipynb` and run all cells. The two demo
notebooks require internet access to download MNIST.

## Notes
All cells are pre-run with outputs saved. The full write-up (pseudocode,
tables, and discussion) is in the accompanying report.
