# Random Boolean Network Model
 This is a model of a Random Boolean Network (BRN) reservoir, with input and readout. 
 The folder `simulation` contains four jupyter notebooks to reproduce the experiments performed in the following [article](https://manuneuro.github.io/EmmanuelCalvet/assets/publications/2023_article_emmanuel_calvet_submited.pdf):

 1. `free_evolution`
 2. `attractor_statistics`
 3. `performance_prediction`
 4. `performance_memory`

# Datas

Since the time of computation can be long, the folder `results` also include the four csv 
of all experiments which had been used to produce all plots in the aforementioned article. 

# Analysis of the data

The analyses performed in the article are not yet available in this version of the code. 

# Installation
```
pip install -r requirements.txt
```

# Citation
[![DOI](https://zenodo.org/badge/663163707.svg)](https://zenodo.org/badge/latestdoi/663163707)
```
cff-version: 1.1.0
message: "If you use this software, please cite it as below."
authors:
  - family-names: Joe
    given-names: Johnson
    orcid: https://orcid.org/0000-0000-0000-0000
title: ManuNeuro/binary_model: First release
version: v1.0.0
date-released: 2023-07-06
```
