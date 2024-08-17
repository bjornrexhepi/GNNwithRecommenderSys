# GNN Recommender Systems Project

This repository contains implementations of various Graph Neural Network (GNN) models applied to different datasets within the context of recommender systems. The models are evaluated across multiple scenarios using the RecPack library.

## Project Structure

The project is organized into several Jupyter notebooks, each focusing on a specific combination of model, dataset, and evaluation scenario. Below is a breakdown of the files:

### Models

- **LightGCN**
- **EASE & ItemKNN**
- **NGCF**
- **PinSAGE**

### Datasets

- **MSD**: Million Song Dataset.
- **Adressa**: News Recommendation Dataset.
- **Globo**: Brazilian News Dataset.

### Scenarios (RecPack)

- **Strong Generalization**: Evaluates model performance on new, unseen users.
- **Timed Last**: Evaluates model performance considering the last item of user interactions.
- **Last Item Prediction**: Focuses on predicting the last item in a user's interaction history.

## File Descriptions

Each notebook is named according to the format `<Model> <Dataset> <Scenario>.ipynb`, which reflects the model, dataset, and scenario being evaluated. Here is a brief description of each file:

- `LightGCN Adressa Strong Generalization.ipynb`: Implementation of the LightGCN model on the Adressa dataset, evaluated under the Strong Generalization scenario.
- `LightGCN Globo Timed Last Item Prediction.ipynb`: LightGCN model on the Globo dataset, focusing on Timed Last Item Prediction.
- `NGCF MSD Strong.ipynb`: Implementation of NGCF on the Million Song Dataset, evaluated under Strong Generalization.
- `PinSAGE Globo.ipynb`: PinSAGE model applied to the Globo dataset without a specified scenario.
- `EASE & Item KNN MSD Strong.ipynb`: A combined model of EASE and Item KNN applied to the Million Song Dataset under the Strong Generalization scenario.
- `...` (Continue with other files similarly)

## Getting Started

To run the notebooks, you will need to have the following dependencies installed:

- Python 3.x
- Jupyter Notebook
- RecPack
- PyTorch (for GNN models)
- PyTorch Sparse
- Pandas
- NumPy
