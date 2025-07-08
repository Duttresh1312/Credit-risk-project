# 🧾 Credit Default Prediction using American Express Dataset

This project tackles the problem of predicting customer defaults using the [American Express Default Prediction](https://www.kaggle.com/competitions/amex-default-prediction/overview) competition dataset from Kaggle. It involves data sampling, preprocessing, feature engineering, model training with hyperparameter tuning, and strategy evaluation.

---

## 📁 Dataset Source

The dataset used is from the official Kaggle competition:  
👉 [American Express - Default Prediction](https://www.kaggle.com/competitions/amex-default-prediction/overview)

---

## 🧠 Project Structure

### 1. **Data Sampling**

- **File**: `Data_sampling.ipynb`  
- **Description**: Uses 20% of the original `train_labels` and merges it with `train_data` to enable faster experimentation.  
- *Optional*: You may skip this step and use your own data split if needed.

---

### 2. **Main Pipeline**

- **File**: `credit-risk-project.ipynb`  
- **Includes**:
  - ✅ **Data Preprocessing**
  - ✅ **Feature Engineering**
  - ✅ **Model Training**
  - ✅ **Grid Search (Hyperparameter Tuning)**
  - ✅ **Model Selection**

---

### 3. **Strategy Evaluation**

- **File**: `creditrisk-project-strategy.ipynb`  
- **Description**: Explores final insights, strategic decision support, and model implications for real-world credit risk applications.

---

## ⚙️ How to Use

1. **Clone** this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git

2. 📥 **Download** the dataset from Kaggle:  
   [American Express - Default Prediction](https://www.kaggle.com/competitions/amex-default-prediction/data)

3. 🧪 **(Optional)** Start with `Data_sampling.ipynb` to work with a smaller subset of the data for faster processing.

4. 🧠 **Run** `credit-risk-project.ipynb` to go through the complete pipeline:
   - Data preprocessing
   - Feature engineering
   - Model training
   - Grid search
   - Best model selection

5. 📊 **Explore** `creditrisk-project-strategy.ipynb` for final insights, strategy evaluation, and deployment considerations.

---

## 📌 Note

This project is optimized for **fast experimentation** by using a sampled subset of the full dataset (20%).  
You can scale up to use the complete dataset depending on your hardware and computational resources.

---

## 🧰 Tools & Technologies Used

- 🐍 Python (`Pandas`, `NumPy`, `Scikit-learn`)
- 📓 Jupyter Notebooks
- 🤖 Machine Learning (`XGBoost`, `Neural Networks`, `GridSearchCV`)
- 📊 Kaggle Dataset


