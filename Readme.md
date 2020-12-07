[![DOI](https://zenodo.org/badge/DOI/10.TBA/TBA.svg)](https://doi.org/TBA)

# Emergent statistical laws in single-cell transcriptomic data

This repository supports "Emergent statistical laws in single-cell transcriptomic data" paper

# Analyses

## Mouse Cell Atlas

In [this folder](MouseCellAtlas) it is possible to reproduce all the analyses involving Mouse Cell Atlas dataset.

Moreover running [combined_analyses.ipynb](MouseCellAtlas/combined_analyses.ipynb) it is possible to reproduce some analyses comparing different datasets as discussed in the paper.

## Tabula Muris


In [this folder](TabulaMuris) it is possible to reproduce all the analyses involving Tabula Muris dataset.

# Additional Tools

## Download the data
Part of the data and results in this repository are stored using Data Version Control [dvc](https://dvc.org) tool.

It is possible to retrieve the data running
```bash
dvc pull -r mydrive
```

## Run in a Docker container
It is possible to run all the notebooks in this repository in a controlled container simpley running

```bash
cd docker
docker-compose up -d
```

and then pointing a browser to [localhost](http://localhost:8888)