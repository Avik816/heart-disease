# Heart Disease Prediction Using Machine Learning and Neural Networks

This project focuses on predicting heart disease using machine learning and deep learning techniques. It includes data exploration, preprocessing, feature selection, model training using Keras, and evaluation with metrics.

---

## 🚀 Features

- Data exploration and visualization
- Feature selection using Chi-Square and ExtraTreesClassifier
- Deep learning model with `Keras Sequential`
- Hyperparameter tuning with `Keras Tuner`
- Evaluation using classification metrics

---

## 🗂️ Project Structure

```
heart-disease-prediction/
│
├── heart disease prediction.ipynb       # Main notebook with all code
├── heart disease prediction.csv         # Dataset (input)
├── requirements.txt                     # Python dependencies
└── README.md                            # Project documentation
```

---

## 📊 Dataset

- **Source**: heart disease dataset in CSV format
- **Features**: Clinical attributes like age, sex, chest pain type, blood pressure, cholesterol, etc.
- **Target**: Presence (`1`) or absence (`0`) of heart disease

---

## 🔧 Methods and Techniques

### 🧹 Preprocessing
- Null value and NaN detection
- Min-Max scaling on features

### 📈 Feature Selection
- Chi-Square test (`SelectKBest`)
- Tree-based method (`ExtraTreesClassifier`)

### 🧠 Deep Learning Model
- Built with `tensorflow.keras.Sequential`
- Dense layers with ReLU activation
- Adam optimizer for training

### 🔍 Hyperparameter Tuning
- Done using `Keras Tuner` with `RandomSearch`

---

## 🧪 Evaluation

- Train/Test accuracy
- Confusion Matrix
- Classification Report

---

## ✅ Requirements

Install the required packages using:

```bash
pip install -r requirements.txt
```

---

## 💻 Running the Notebook

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/heart-disease-prediction.git
    cd heart-disease-prediction
    ```

2. Make sure the CSV file is in the same directory.

3. Launch Jupyter and open the notebook:
    ```bash
    jupyter notebook "heart disease prediction.ipynb"
    ```

---


## 📜 License

This project is open-source and available under the MIT License.
