# 📈 Sales Prediction using Machine Learning

A simple machine learning project to predict sales based on historical sales data.

## 📂 Project Structure

- `main.ipynb` — Jupyter Notebook for data exploration, model training, and prediction.
- `train.csv` — Training dataset.
- `test.csv` — Testing dataset.

## 📊 Dataset

The datasets (`train.csv` and `test.csv`) include features such as:

- Item Identifier
- Item Weight
- Item Fat Content
- Item Visibility
- Item Type
- Item MRP (Maximum Retail Price)
- Outlet Identifier
- Outlet Establishment Year
- Outlet Size
- Outlet Location Type
- Outlet Type
- Sales (target variable)

## 🛠️ Installation
  1. Clone the repository:
    ```bash
    git clone https://github.com/RanadiWijaya/SalesPrediction.git
    cd SalesPrediction
    ```

  2. Install the required dependencies:
    `pip install pandas numpy scikit-learn matplotlib seaborn jupyter`

  3. Launch the Jupyter Notebook:
     `jupyter notebook main.ipynb`

🚀 How to Use
Open and run the notebook main.ipynb.
Follow the steps inside the notebook to:
Load and explore the data.
Preprocess and clean the data.
Train the machine learning model.
Evaluate the model.
Predict sales for the test data.

🧠 Model Overview
Models used may include:
- Linear Regression
- Random Forest Regressor
- Evaluation metrics:
- Root Mean Squared Error (RMSE)
- R² Score

📈 Evaluation Metrics
- Root Mean Squared Error (RMSE)
- R² Score (coefficient of determination)

🌟 Future Work
Try more advanced models (XGBoost, LightGBM, etc.)
Perform hyperparameter tuning.
Deploy the model as an interactive web app using Streamlit.

🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to fork the repo and submit a pull request.

📄 License
This project is licensed under the MIT License — see the LICENSE file for details.

