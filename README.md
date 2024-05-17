# InterpretE

This is the repository for our research paper *Bring back Semantics to Knowledge Graph Embeddings : An Interpretability Approach*.

### Code

All the experiments done in the paper are sorted by dataset on each folder. All the generated files
used to run the experiments (entity types, location with abstraction) are placed in the folder `data/` for each dataset. You will also need to install the [LibKGE library](https://github.com/uma-pi1/kge.git) in order to load the pre-trained models.

### Data

In order to run the scripts you need to place `train.csv`, `valid.csv` and `test.csv` file in the folder `data/`for each corresponding dataset.

### Pretrained Embedding Models

The KG embedding models that were used in this work were downloaded from the [LibKGE repository](https://github.com/uma-pi1/kge.git) wherever available. The rest of the models were trained by [Jain et al.](https://link.springer.com/chapter/10.1007/978-3-030-77385-4_9). Once you have downloaded the pre-trained models, make sure they are stored in the `./embeddings` directory located in the root of this repository.
