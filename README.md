# Graduate Admission Prediction

A regression project that predicts a student's **chance of admission** (0 to 1) to a graduate program using an Artificial Neural Network built with TensorFlow/Keras.

## Dataset
Graduate Admissions dataset (`data/admission_data.csv`) with features such as GRE score, TOEFL score, university rating, SOP, LOR, CGPA, and research experience.

## What it does
- Loads and cleans the data with Pandas
- Splits it into train and test sets using `train_test_split`
- Scales features with `MinMaxScaler`
- Builds a `Sequential` neural network with `Dense` layers
- Trains with Mean Squared Error loss and the Adam optimizer
- Plots training vs validation loss to check for overfitting

## Tech stack
Python, Pandas, NumPy, TensorFlow/Keras, scikit-learn, Matplotlib

## Project structure
```
data/        -> admission_data.csv
notebook/    -> main.ipynb
requirements.txt
```

## Setup
```bash
pip install -r requirements.txt
```

## Run
Open `notebook/main.ipynb` and run all cells.