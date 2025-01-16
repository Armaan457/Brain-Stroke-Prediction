# Brain Stroke Prediction

This project aims to predict the likelihood of a brain stroke using an Artificial Neural Network. The project utilizes **Hyperopt** for hyperparameter tuning and **MLflow** for model tracking and logging.

**Dataset:** https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset


## Setup

Clone the repository:
```sh
> https://github.com/Armaan457/Brain-Stroke-Prediction.git
```

Create and activate a virtual environment:

```sh
> python -m venv venv
> venv\scripts\activate
```

Install dependencies:

```sh
> pip install -r requirements.txt
```

Start tracking server:
```sh
> mlflow ui
```
You can now run the notebook `model.ipynb` which also has the implementation of the complete pipeline along with MLflow inference