# **Credit Card Fraud Detection**

## **Overview**  
Credit card fraud is a growing concern in the financial industry, impacting millions of users worldwide. This project applies machine learning techniques to detect fraudulent credit card transactions, leveraging Python and Scikit-Learn. By analyzing transaction data, we aim to improve fraud detection accuracy and minimize financial risks.

## **Features**  
✅ Data preprocessing and feature engineering  
✅ Machine learning models: Decision Tree, Logistic Regression, and Artificial Neural Network (ANN)  
✅ Performance evaluation using accuracy, confusion matrix, and classification reports  
✅ Scalable and adaptable for real-world fraud detection applications  

## **Technologies Used**  
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn  
- **Machine Learning Models**:  
  - Decision Tree Classifier  
  - Logistic Regression  
  - Multi-layer Perceptron (MLP) Classifier (ANN)  

## **Dataset**  
The dataset contains real-world credit card transaction data, with features such as transaction amount, location, merchant details, and more. The target variable (`is_fraud`) indicates whether a transaction is fraudulent (`1`) or legitimate (`0`).  

## **Project Structure**  


📂 Credit-Card-Fraud-Detection
├── 📄 fraudTest.csv # Dataset
├── 📄 fraud_detection.py # Main Python script
├── 📄 README.md # Documentation
├── 📄 requirements.txt # Required libraries


Machine Learning Approach
Data Preprocessing:
Handled missing values and categorical encoding
Standardized numerical features
Split data into training (80%) and testing (20%) sets
Model Training:
Decision Tree, Logistic Regression, and ANN models were trained using the dataset
Model Evaluation:
Accuracy score, confusion matrix, and classification report were used for performance evaluation
Results & Insights
Decision Tree provides explainable predictions but can overfit
Logistic Regression is lightweight but may not capture complex patterns
ANN learns deep patterns but requires fine-tuning for optimal performance
Future Improvements
Implementing advanced models like XGBoost and Random Forest
Integrating real-time fraud detection using streaming data
Enhancing feature selection to improve accuracy
Contributors
👤 Your Name

GitHub: @ian-kwach
LinkedIn: (https://www.linkedin.com/in/ian-kwach-otieno-aa571a210/)
