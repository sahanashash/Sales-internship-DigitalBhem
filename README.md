# Sales-internship-DigitalBhem
# 🛒 Sales Forecasting with KNN and Linear Regression

This project focuses on building and evaluating **regression models** for predicting daily item sales using **K-Nearest Neighbors Regressor (KNN)** and **Linear Regression**. It uses the `Sales.csv` dataset and includes data preprocessing, model training, and performance evaluation.

## 📁 Project Structure

```bash
sales-forecasting/
├── README.md
├── sales_knn_lr.py
├── Sales.csv
├── requirements.txt
└── images/ (optional for plots or results)
```

## 📊 Dataset

* **File**: `Sales.csv`
* **Features**: Various numerical predictors (e.g., shop, item, category IDs, prices, etc.)
* **Target**: `item_cnt_day` — the number of items sold in a day
* **Note**: The column `date` is dropped for modeling purposes

## ⚙️ Features

* Preprocessing with missing column cleanup and feature scaling
* Multiple regression models:

  * KNN Regressor with and without distance weighting
  * Linear Regression
* Evaluation using:

  * Mean Squared Error (MSE)
  * Mean Absolute Error (MAE)
  * R² Score

## 🚀 Getting Started

1. Clone the Repository

```bash
git clone https://github.com/your-username/sales-forecasting.git
cd sales-forecasting
```

2. Add the Dataset

Place your `Sales.csv` file in the project directory or update the path accordingly.

3. Install Dependencies

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install pandas scikit-learn
```

4. Run the Code

```bash
python sales_knn_lr.py
```


## 📈 Output Example

🔹 KNN Regressor

k = 1
MSE: 2.45
R² Score: 0.71

Distance-weighted k = 1
MSE: 2.12
R² Score: 0.75

🔹 Linear Regression

Linear Regression Performance:
MSE: 2.32
MAE: 1.08
R² Score: 0.72

*(Values are illustrative — your actual output may vary)*

## 🧪 Requirements

* Python 3.7+
* pandas
* scikit-learn

### `requirements.txt`

```txt
pandas
scikit-learn
```

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 👤 Author

**Sahana N S**
GitHub: [@your-username](https://github.com/SahanaShash)
