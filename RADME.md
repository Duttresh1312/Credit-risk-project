Credit Default Prediction using American Express Dataset
This project tackles the problem of predicting customer defaults using the American Express Default Prediction competition dataset from Kaggle. It involves data sampling, preprocessing, feature engineering, model training with hyperparameter tuning, and strategy evaluation.

📁 Dataset Source
The dataset used is from the official Kaggle competition:
👉 American Express - Default Prediction

🧠 Project Structure
1. Data Sampling
File: Data_sampling.ipynb

Description: Uses 20% of the original train_labels data and merges it with train_data for a faster and resource-efficient experimentation setup.

Optional: You can skip this step and use the full dataset or perform your own data split as needed.

2. Main Workflow
File: credit-risk-project.ipynb

This notebook covers the core pipeline of the project:

I. Data Preprocessing: Cleaning and formatting the data for analysis and model building.

II. Feature Engineering: Creating meaningful features to improve model performance.

III. Model Training: Building machine learning models for credit default prediction.

IV. Grid Search: Hyperparameter tuning to optimize model performance.

V. Model Selection: Choosing the best-performing model based on evaluation metrics.

3. Strategy Analysis
File: creditrisk-project-strategy.ipynb

This notebook contains additional insights and strategic evaluation of model performance, along with suggestions for improvement and business applicability.

⚙️ How to Use
Clone this repository.

Download the dataset from Kaggle.

Start with Data_sampling.ipynb (optional).

Run through credit-risk-project.ipynb for full model pipeline.

Explore creditrisk-project-strategy.ipynb for final insights and deployment considerations.

📌 Note
This project is optimized for fast experimentation on large datasets by using a sampled subset of the data. It can be scaled up for full dataset training based on available computational resources.
