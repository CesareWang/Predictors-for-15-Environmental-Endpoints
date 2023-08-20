# Predictors-for-15-Environmental-Endpoints
Graph Attention Network Models for Predicting 15 Environmental Endpoints

## Getting Started

### Installation

Set up conda environment

```
# create a new environment
$ conda create --name GAT python=3.7
$ conda activate GAT

# install requirements
$ pip install ipykernel
$ pip install torch==1.8.1+cu111 torchvision==0.9.1+cu111 torchaudio===0.8.1 -f https://download.pytorch.org/whl/torch_stable.html
$ conda install -c rdkit rdkit==2019.03.1.0
```


### Dataset

You can download the data in the files under `./data` folder. 

### Prediction

Prediction demo can be found in `./code/prediction.ipynb`. Hyperparameters of the models are stored in `./data/model_details.csv`, and chemicals to be predicted are stored in `./data/dataset.csv`.


## Acknowledgement

source codes called to establish the models: [https://github.com/OpenDrugAI/AttentiveFP]
