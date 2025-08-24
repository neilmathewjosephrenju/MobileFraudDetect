# MobileFraudDetect

# MobileFraudDetect

# LightGBM Fraud Detection Project

## Project Structure
- `train_lightgbm.py`: Python script to train the LightGBM model with hyperparameter tuning.
- `predict.py`: Script demonstrating how to predict with the trained model.
- `requirements.txt`: Python dependencies.
- `.gitignore`: Files and directories excluded from version control.

## Installation
1. Clone the repository: git clone https://github.com/neilmathewjosephrenju/MobileFraudDetect.git


2. Create and activate a virtual environment (optional but recommended):


3. Install dependencies:


## Model Parameters
The model was tuned with the following hyperparameters for optimal performance:
- `num_leaves`: 80
- `max_depth`: 13
- `learning_rate`: 0.2355
- `subsample`: 0.7
- `colsample_bytree`: 0.8
- `reg_lambda`: 0.5
- `reg_alpha`: 1.0
- `min_child_samples`: 40
- `n_estimators`: 150

## Performance
- Best F1 Score: 0.9444
- Accuracy: 0.95


## Downloading Dataset

Due to size constraints, the dataset is not included in this repository.

You can download the dataset from Kaggle here:

[Download Dataset from Kaggle]([https://www.kaggle.com/datasets/your-dataset-link](https://www.kaggle.com/datasets/ealaxi/paysim1))


## Contributing
Contributions are welcome! Please fork the repository and create a pull request.

## License
This project is licensed under the MIT License.
