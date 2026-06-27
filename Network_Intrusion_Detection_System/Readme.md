# Network Intrusion Detection System

An Intrusion Detection System (IDS) built using a deep neural network with **self-supervised contrastive learning**, classifying network traffic as normal or malicious without requiring labeled training data.

Published in **IJSRD Vol. 11, Issue 3** — [read the paper](./IJSRDV11I30128.pdf)

---

## Overview

Traditional IDS methods depend on labeled data, which is expensive and limited in coverage. This project applies self-supervised contrastive learning to learn meaningful representations from unlabeled network traffic, then classifies it using a fully connected feedforward ANN.

Two detection approaches are covered:

- **Signature-based detection** — matches traffic against known attack patterns
- **Anomaly detection** — flags deviations from learned normal behavior

---

## Architecture

- Fully connected feedforward Artificial Neural Network (ANN)
- Self-supervised contrastive learning for representation learning on unlabeled data
- Binary classification output: normal vs. malicious traffic

---

## Dataset

NSL-KDD dataset — a refined version of the KDD Cup 1999 dataset, commonly used for network intrusion detection research.

[Dataset link](./Dataset.md)

---

## Dependencies

```
numpy
pandas
scikit-learn
tensorflow
matplotlib
```

Install with:

```bash
pip install numpy pandas scikit-learn tensorflow matplotlib
```

---

## Getting Started

1. Clone the repository
2. Install dependencies (see above)
3. Open `Intrusion-Detection-ML-CD.ipynb` in Jupyter Notebook
4. Run all cells sequentially

---

## Disclaimer

This is an academic research project. The model has not been validated for real-world deployment and would require further testing, tuning, and integration work before production use.
