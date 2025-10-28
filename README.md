# MLFlow Experiment Project

A machine learning project using MLFlow for experiment tracking, model management, and deployment.

## Project Overview

This project demonstrates machine learning experimentation and model management using MLFlow, including:
- Deep learning models with Keras/TensorFlow
- Hyperparameter optimization with Hyperopt
- Model tracking and versioning with MLFlow
- Model deployment capabilities

## Requirements

```txt
mlflow 
scikit-learn
pandas
numpy
keras
tensorflow
hyperopt
```

## Project Structure

```
.
├── DLMLFLOW/               # Deep Learning experiments
│   ├── starter.ipynb      # Main DL training notebook
│   └── mlruns/            # MLFlow experiment tracking
├── MLproject/             # Traditional ML experiments  
│   ├── gettingstarted.ipynb
│   ├── housepricepredict.ipynb
│   └── mlruns/
└── requirements.txt       # Project dependencies
```

## Getting Started

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Start MLFlow tracking server:
```bash
mlflow ui
```

3. Open notebooks to run experiments:
- `DLMLFLOW/starter.ipynb` - Deep learning experiments with Keras
- `MLproject/gettingstarted.ipynb` - Basic MLFlow tutorial
- `MLproject/housepricepredict.ipynb` - House price prediction example


## Viewing Results

Access the MLFlow UI at http://127.0.0.1:5000 to:
- Compare experiment runs
- View model metrics
- Access registered models
- Deploy models to production