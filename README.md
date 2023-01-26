<!-- omit in toc -->
# Symphonypy
Porting of [Symphony R](https://github.com/immunogenomics/symphony) package to Python

- [Installation](#installation)
- [Usage](#usage)
  - [Preprocessing](#preprocessing)
  - [Run symphony](#run-symphony)
  - [Transfer labels](#transfer-labels)
  - [Map UMAP](#map-umap)
  - [Map tSNE with `openTSNE`](#map-tsne-with-opentsne)
- [Benchmarking](#benchmarking)

> Currently under development:
> - evaluation of confidence metrics
> - precomputed symphony reference datasets
> - Python package


## Installation
Symphonypy package might be installed via pip:
```
pip install symphonypy
```

## Simple usage
Here are Jupyter-notebooks with simple examples of how to use symphonypy
- with [pre-built references](notebooks/Symphonypy_precomputed.ipynb) from original Symphony,
- with [reference building](notebooks/Symphonypy_simple_tutorial.ipynb) from scratch.

## Benchmarking
- Harmony (R) vs harmonypy benchmarking:
  - [benchmarking/Benchmarking_harmony_PBMC_Satija.ipynb](benchmarking/Benchmarking_harmony_PBMC_Satija_CITEseq.ipynb)
- Symphony (R) vs symphonypy benchmarking: [benchmarking/Benchmarking_symphony_PBMC.ipynb](benchmarking/Benchmarking_symphony_PBMC.ipynb)
- PBMC example from the Symphony repo: [benchmarking/validation_PBMC_example.ipynb](benchmarking/validation_PBMC_example.ipynb)

Download data used in benchmarking: [benchmarking/data_download.ipynb](benchmarking/data_download.ipynb)
