# 🚀 Bank Marketing Campaign Analysis

## 📌 Project Overview
This project analyzes a **Bank Marketing Campaign Dataset** using machine learning techniques to predict whether a customer will subscribe to a term deposit. It includes data preprocessing, exploratory data analysis (EDA), feature selection, handling class imbalance using SMOTE, and training multiple machine learning models.

## 📊 Dataset
The dataset comes from a direct marketing campaign of a Portuguese banking institution. It contains client information, campaign details, and the final outcome (`y`: yes/no for subscription).

- **Source:** Kaggle
- **Format:** CSV file (`bank.csv`)
- **Key Features:**
  - 🏦 Client information (age, job, marital status, education, etc.)
  - 📞 Contact details (communication type, day, month, etc.)
  - 🔍 Previous campaign outcomes (previous attempts, success rate, etc.)
  - 🎯 Target variable (`y` - Subscription to term deposit: Yes/No)

## 🔄 Project Workflow
```plaintext
1. 📥 Data Ingestion:
   - Load the dataset.

2. 📊 Exploratory Data Analysis (EDA):
   - Check dataset shape, missing values, and class distribution.
   - Visualize categorical feature distributions.

3. 🛠️ Data Preprocessing:
   - Encode categorical features using Label Encoding.
   - Convert the target variable (`y`) into binary format (1: Yes, 0: No).

4. 🎯 Feature Selection:
   - Use Recursive Feature Elimination (RFE) with a Random Forest Classifier to select the top 10 features.

5. ⚖️ Handling Imbalanced Data:
   - Apply **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the dataset.

6. 📏 Standardization:
   - Scale numerical features using **StandardScaler**.

7. 🤖 Model Training & Evaluation:
   - Train and evaluate three models:
     - Logistic Regression
     - Naïve Bayes
     - K-Nearest Neighbors (KNN)
   - Compare accuracy, confusion matrices, and classification reports.
```

## 📈 Results
```plaintext
| Model Name            | Accuracy Score |
|----------------------|---------------|
| Logistic Regression  |  **0.838796**     |
| Naïve Bayes         |  **0.755523**     |
| KNN                 |  **0.845836**     |
```

## ⚡ Installation & Usage
```sh
# Clone the repository
git clone https://github.com/yourusername/bank-marketing-analysis.git
cd bank-marketing-analysis

# Install dependencies
pip install -r requirements.txt

# Run the script
python bank_marketing_analysis.py
```

## 📦 Dependencies
```plaintext
- Python 3.x
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn, Imbalanced-learn
```

## 🚀 Future Enhancements
```plaintext
- Implement deep learning models.
- Tune hyperparameters for better accuracy.
- Deploy as a web application for real-time predictions.
```

## 👨‍💻 Author
```plaintext
Jayesh Patil  
📧 Email: [your-email@example.com](mailto:your-email@example.com)  
🔗 LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/your-profile/)  
```

## 📜 License
```plaintext
This project is licensed under the MIT License.
```

