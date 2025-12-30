# Multiscale Motif Representations for TIMEVIEW

This repository contains supplementary code for the research task submission extending [TIMEVIEW](https://github.com/vanderschaarlab/TIMEVIEW) with wavelet-based multiscale motif representations.

## Setup

1. Clone the TIMEVIEW repository:
```bash
git clone https://github.com/vanderschaarlab/TIMEVIEW.git
cd TIMEVIEW
```

2. Create and activate the conda environment:
```bash
conda env create -f environment.yml
conda activate timeview
```

3. Install additional dependency:
```bash
pip install PyWavelets
```

4. Place `recruitment_task_haaris.ipynb` in `TIMEVIEW/timeview/` and run:
```bash
cd timeview
jupyter notebook recruitment_task_haaris.ipynb
```

## Contents

- `recruitment_task_haaris.ipynb`: Demonstrates multiscale wavelet decomposition with TIMEVIEW's B-spline basis, synthetic HRV signal generation, and oscillatory motif extraction.

## Reference

Kacprzyk, K., et al. (2024). Towards Transparent Time Series Forecasting. ICLR 2024.
