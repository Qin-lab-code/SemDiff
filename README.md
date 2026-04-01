# SemDiff-Semantic-Guided-Diffusion-based-Collaborative-Filtering-Framework

This repository provides the official PyTorch implementation of **SemDiff**.

SemDiff is a diffusion-based recommendation framework designed for sparse recommendation scenarios. Instead of injecting randomly sampled Gaussian noise, SemDiff introduces auxiliary semantic signals derived from modal features into item representations, so as to provide richer semantic information for the diffusion process. In addition, a collaborative training objective strategy is adopted to jointly optimize generation and preference learning.

## Requirements

The code is implemented using **PyTorch**. The required packages are listed below:

```bash
python=3.8.20
torch=2.4.1
numpy=1.24.4
pandas=2.0.3
scikit-learn=1.3.0
scipy=1.10.1
tqdm=4.66.5
```

## Train
For the Office dataset:
```bash
./office.sh
```
