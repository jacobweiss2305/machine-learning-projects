# Binary Classification Example

This project demonstrates binary classification using various machine learning models on synthetic data.

## Overview

The notebook explores:

- Generating synthetic data with different levels of class separation
- Training and evaluating multiple classification models:
  - XGBoost
  - Random Forest  
  - Gradient Boosting
  - AdaBoost
  - Logistic Regression
- Analyzing model performance metrics
- Visualizing data distributions and model results

## Key Files

- `binary-classification/normal_dist_example.ipynb`: Main Jupyter notebook with analysis
- `binary-classification/requirements.txt`: Python package dependencies

## Setup

1. Create a virtual environment:

```bash
python -m venv binary-classification-env
source binary-classification-env/bin/activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook normal_dist_example.ipynb
```

4. Open `normal_dist_example.ipynb`

## Usage

The notebook is divided into sections that:

1. Generate synthetic data 
2. Train and evaluate models
3. Visualize results

Parameters can be adjusted to experiment with different data distributions and model configurations.

## Results

The notebook demonstrates how model performance improves as class separation increases in the synthetic data. Key metrics like accuracy, precision, recall and ROC AUC are compared across models.


