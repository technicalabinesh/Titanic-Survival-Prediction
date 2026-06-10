# Titanic Survival Prediction

A machine learning project that predicts passenger survival on the Titanic dataset using a `RandomForestClassifier`.

## Project Files

- `titanic_survival_prediction.py` - training, evaluation, and prediction script
- `Titanic_Survival_Prediction.ipynb` - notebook version of the workflow
- `train_data.csv` - training dataset
- `test_data.csv` - test dataset
- `titanic_model.pkl` - saved model artifact

## Features

- Loads and prepares Titanic training data
- Trains a Random Forest model
- Evaluates performance with accuracy, classification report, and confusion matrix
- Generates predictions for test data
- Exports `submission.csv` in Kaggle-ready format

## Requirements

- Python 3.8+
- pandas
- numpy
- scikit-learn

Install dependencies:

```bash
pip install pandas numpy scikit-learn
```

## How to Run

```bash
python titanic_survival_prediction.py
```

> Note: The script currently uses Colab-style paths (`/content/train_data.csv` and `/content/test_data.csv`).  
> If running locally, update those paths to local file names (`train_data.csv`, `test_data.csv`).

## Output

After running, the script creates:

- `submission.csv` containing:
  - `PassengerId`
  - `Survived`

## License

This project is licensed under the MIT License.