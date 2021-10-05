[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5549353.svg)](https://doi.org/10.5281/zenodo.5549353)

# Psoriatic Keratinocyte (psoKC) model

This repository contains ipynb files and psoriatic keratinocyte model-related files as described in paper [_"Logical and experimental modeling of cytokine and eicosanoid signaling in psoriatic keratinocyte"_](https://www.biorxiv.org/content/10.1101/2021.06.07.447313v2)

## How to run this notebook?

### With binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Eirinits/psoKC_model/HEAD)
 
### With docker

1. Install the [colomoto docker image](https://github.com/colomoto/colomoto-docker). 
The model presented in the paper was tested with the version ```2020-01-24```.
2. Install [jupyter notebook](http://jupyter.org/).
3. Clone the repository: ```https://github.com/Eirinits/psoKC_model.git```. 
4. Go to the project repository and launch the notebook: ```colomoto-docker --bind .```
5. The notebook will be available in your web browser at ```http://localhost:8888/```
