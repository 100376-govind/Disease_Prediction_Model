🩺 Disease Prediction using Machine Learning

This project demonstrates how to build machine learning models to predict diseases such as Breast Cancer and Diabetes using datasets from sklearn. It compares multiple ML models, evaluates their performance, and visualizes results with ROC curves and feature importance.

⚠️ Heart Disease dataset is referenced in the code but not included by default. You can add your own dataset (heart.csv) if available.

📌 Features

Load and preprocess medical datasets.

Train and evaluate multiple ML models:

Support Vector Machine (SVM)

Logistic Regression

Random Forest

Gradient Boosting

Generate evaluation metrics:

Accuracy Score

Confusion Matrix

Classification Report (Precision, Recall, F1-Score)

Plot ROC Curves with AUC for model comparison.

Show Feature Importance for Random Forest & Gradient Boosting.

Perform Cross-Validation for robustness.

📂 Datasets

Breast Cancer → sklearn.datasets.load_breast_cancer()

Diabetes → sklearn.datasets.load_diabetes()

Converted from regression to binary classification (above/below mean target).

Heart Disease (optional) → Requires external dataset (heart.csv).

⚙️ Installation

Clone the repository and install dependencies:

git clone https://github.com/your-username/disease-prediction.git
cd disease-prediction
pip install -r requirements.txt

Requirements

Python 3.8+

numpy

pandas

matplotlib

seaborn

scikit-learn

(All dependencies are in requirements.txt)

▶️ Usage

Run the script directly:

python disease_prediction.py


It will:

Load datasets.

Train all models.

Print evaluation metrics.

Plot ROC curves and feature importances.

📊 Example Output

Confusion Matrix & Classification Report

ROC Curve comparing SVM, Logistic Regression, Random Forest, Gradient Boosting.

Feature Importance Bar Charts for tree-based models.

📈 Results

Logistic Regression generally performs well on medical datasets.

Random Forest and Gradient Boosting often provide better interpretability via feature importance.

ROC Curve & AUC help visualize model performance trade-offs.

📌 Future Improvements

Add more medical datasets (Heart Disease, Parkinson’s, etc.).

Implement Deep Learning models (ANNs, CNNs).

Build an interactive Streamlit web app for predictions.

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss your ideas.

📜 License

This project is licensed under the MIT License.
