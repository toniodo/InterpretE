# InterpretE

This is the repository of our research paper [*Bring back Semantics to Knowledge Graph Embeddings : An Interpretability Approach*](https://link.springer.com/chapter/10.1007/978-3-031-71170-1_17) which have been accepted at the [18th International conference on
Neural-Symbolic Learning and Reasoning](https://sites.google.com/view/nesy2024/home). 

An extended version of the short paper has been submitted at the Neurosymbolic Artificial Intelligence Journal. The Supplementary Material of this submission can be found in this repository via this [link](https://github.com/toniodo/InterpretE/edit/main/supplementary_material.pdf).

### Code

All the experiments done in the paper are sorted by dataset on each folder. All the generated files
used to run the experiments (entity types, location with abstraction) are placed in the folder `data/` for each dataset. If you use a conda environment you can create the environment using the `environment.yml` file, otherwise a `requirements.txt` file is also given. You will also need to install the [LibKGE library](https://github.com/uma-pi1/kge.git) from the official repository in order to load the pre-trained models.

### Data

In order to run the scripts you need to place `train.csv`, `valid.csv` and `test.csv` file in the folder `data/`for each corresponding dataset.

### Pretrained Embedding Models

The KG embedding models that were used in this work were downloaded from the [LibKGE repository](https://github.com/uma-pi1/kge.git) wherever available. The rest of the models were trained by [Jain et al.](https://link.springer.com/chapter/10.1007/978-3-030-77385-4_9). Once you have downloaded the pre-trained models, make sure they are stored in the `./embeddings` directory located in the root of this repository.
