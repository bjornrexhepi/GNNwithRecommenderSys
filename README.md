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
- **AdressaOneWeek**
- **Globo**

### Scenarios (RecPack)

- **Strong Generalization**: Evaluates model performance on new, unseen users.
- **Timed Last Item Prediction**: Evaluates model performance considering the last item of user interactions.

## File Descriptions

Each notebook is named according to the format `<Model> <Dataset> <Scenario>.ipynb`, which reflects the model, dataset, and scenario being evaluated. Here is a brief description of each file:

- `EASE & Item KNN Adressa Strong Generalization & Timed Last.ipynb`: Implementation of EASE and Item KNN models on the AdressaOneWeek dataset, evaluated under both Strong Generalization and Timed Last scenarios.
- `EASE & Item KNN Globo Strong Generalization & Timed Last.ipynb`: EASE and Item KNN models on the Globo dataset, evaluated under both Strong Generalization and Timed Last scenarios.
- `EASE & Item KNN MSD Strong.ipynb`: EASE and Item KNN models applied to the Million Song Dataset, focusing on Strong Generalization.
- `LightGCN Adressa Strong Generalization.ipynb`: LightGCN model on the AdressaOneWeek dataset, evaluated under the Strong Generalization scenario.
- `LightGCN Adressa Timed Last.ipynb`: LightGCN model on the AdressaOneWeek dataset, focusing on the Timed Last Item Prediction scenario.
- `LightGCN Globo Strong Generalization.ipynb`: LightGCN model on the Globo dataset, evaluated under the Strong Generalization scenario.
- `LightGCN Globo Timed Last Item Prediction.ipynb`: LightGCN model on the Globo dataset, focusing on the Timed Last Item Prediction scenario.
- `LightGCN MSD Strong.ipynb`: LightGCN model on the Million Song Dataset, evaluated under the Strong Generalization scenario.
- `NGCF Adressa Strong.ipynb`: NGCF model applied to the AdressaOneWeek dataset, focusing on the Strong Generalization scenario.
- `NGCF Adressa Timed Last.ipynb`: NGCF model on the AdressaOneWeek dataset, evaluated under the Timed Last Item Prediction scenario.
- `NGCF Globo Strong.ipynb`: NGCF model on the Globo dataset, evaluated under the Strong Generalization scenario.
- `NGCF Globo Timed Last.ipynb`: NGCF model on the Globo dataset, focusing on the Timed Last Item Prediction scenario.
- `NGCF MSD.ipynb`: NGCF model on the Million Song Dataset, evaluated under the Strong Generalization scenario.
- `PinSAGE Adressa Strong.ipynb`: PinSAGE model on the AdressaOneWeek dataset, focusing on Strong Generalization.
- `PinSAGE Adressa Timed Last.ipynb`: PinSAGE model on the AdressaOneWeek dataset, evaluated under the Timed Last Item Prediction scenario.
- `PinSAGE Globo Strong.ipynb`: PinSAGE model on the Globo dataset, evaluated under the Strong Generalization scenario.
- `PinSAGE Globo Timed Last.ipynb`: PinSAGE model on the Globo dataset, focusing on the Timed Last Item Prediction scenario.
- `PinSAGE MSD.ipynb`: PinSAGE model on the Million Song Dataset, evaluated under the Strong Generalization scenario.

