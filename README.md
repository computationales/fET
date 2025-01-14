# Instructions
[![DOI](https://zenodo.org/badge/491055054.svg)](https://zenodo.org/badge/latestdoi/491055054)

First things first, clone this repo to your local computer:

```
git clone https://github.com/geco-bern/fET
```

To reproduce the analysis and figures, you can follow the steps described in the `analysis` folder and its 'README.md' file. To avoid overwriting the dataframes already loaded in this repo, the scripts contained in the `analysis` folder will save their output in the main directory of the project (aka the directory where this README also is). 

Below is an overview of the content of the others directories. You can refer to the READMEs inside each directory for detailed instructions. You can find [here](https://github.com/geco-bern/R-proj-template) the project template used for this repo, explained in detail (highly suggested to keep your project tidy!). 

* `R`: contains all the R functions (not scripts) used in the analysis.
* `data-raw`: contains raw data and the scripts used to download and extract raw data, as well as other scripts to process the raw data.
* `data`: contains processed data, ready to use for the analysis. It also contains the outputs of the deep neural networks (DNN) model.
* `manuscript`: contains manuscript and figures.
* `vignettes`: contains the vignette to produce Box 1. 

