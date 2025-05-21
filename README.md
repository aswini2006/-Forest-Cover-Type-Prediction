# 🌲 Forest Cover Type Prediction with Random Forest

This project uses a Random Forest Classifier to predict the forest cover type from cartographic variables. It is based on the Forest CoverType dataset.

## 📂 Dataset

The dataset is taken from [Kaggle]([https://www.kaggle.com/competitions/forest-cover-type-prediction/data](https://www.kaggle.com/datasets/aswinireddy610610/forest-cover-dataset)) and includes features like elevation, slope, soil type, and wilderness area to classify forest cover types.

## 🚀 Features

- Preprocessing with `StandardScaler`
- Model training using `RandomForestClassifier`
- Evaluation with accuracy, confusion matrix, and classification report

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/forest-cover-type-prediction.git
   cd forest-cover-type-prediction
2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
   source venv/bin/activate  # or `venv\Scripts\activate` on Windows
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
## 📊 Usage
Place the dataset CSV file in the root directory or modify the path accordingly in the script.

Run the model script:
     ```bash
     python model.py
## 📈 Output
Accuracy score

Confusion Matrix

Classification Report

## 📌 Requirements
See requirements.txt for all dependencies.

## 📄 License
MIT License




