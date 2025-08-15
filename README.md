# Rat Neuron Spike Analysis

`Rat_Neurons_Spikes.ipynb` notebook for exploring extracellular spike trains from rat recordings. The notebook looks at basic single-unit timing and pairwise structure.

## What it does
- Load spike times for one or more units.
- Plot rasters and estimate firing rate (binned + optional Gaussian smoothing).
- ISI stats: histogram, mean rate, coefficient of variation (CV), refractory check.
- Autocorrelograms and cross-correlograms to spot rhythms/coupling.
- Optional PSTHs if you provide event timestamps.

## Quick start
```bash
git clone https://github.com/bhavesh-kharat/Rat-Neuron-Spikes-Analysis.git
cd Rat-Neuron-Spikes-Analysis
pip install numpy scipy matplotlib pandas seaborn jupyter
jupyter notebook Rat_Neurons_Spikes.ipynb
