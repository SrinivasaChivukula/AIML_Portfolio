📊 Machine Learning Portfolio
Regression • Classification • Deep Learning • Imbalanced Data Handling

This repository contains multiple applied machine learning projects built using Python, Scikit-Learn, TensorFlow, and data processing libraries. It demonstrates complete ML workflows from data preprocessing to model evaluation using real-world datasets such as Seoul Bike Sharing, MAGIC Gamma Telescope, and Wheat Seeds.

🧠 What This Project Taught Me
✔ 1. Data Processing & Feature Engineering

Through these notebooks, I learned how to:

Clean noisy datasets

Handle missing values

Perform feature scaling (StandardScaler)

Analyze correlations

Prepare datasets for ML pipelines

Data Preprocessing Workflow

Raw Data → Cleaning → Feature Engineering → Scaling → Train/Test Split

✔ 2. Machine Learning Models & Evaluation
Regression

Linear Regression

Coefficients, trend analysis

Evaluation using RMSE, MAE, R²

Classification

Logistic Regression

Decision boundaries

Performance metrics: Precision, Recall, F1, AUC

Visualization using confusion matrices

Evaluation Loop
Train Model → Predict → Compare with True Labels → Compute Metrics → Improve Model

✔ 3. Handling Imbalanced Data Using Imbalanced-Learn

I learned why class imbalance negatively affects model accuracy and fairness.
Using RandomOverSampler, I balanced the datasets to improve classification quality.

Before Oversampling:       After Oversampling:
Class 0: ███████████       Class 0: ███████████
Class 1: ███               Class 1: ███████████

✔ 4. Deep Learning Foundations (TensorFlow)

I explored:

Building neural networks using Keras Sequential API

Dense layers & activation functions

Understanding loss curves

How network depth and learning rate affect performance

Sample Neural Network Architecture

Input Layer
     ↓
Dense Layer (ReLU)
     ↓
Dense Layer (ReLU)
     ↓
Output Layer (Sigmoid/Linear)

🔧 Technologies, Libraries & Models Used
Languages & Tools

Python

Jupyter Notebook

Git / GitHub

Libraries

pandas, numpy

matplotlib, seaborn

scikit-learn

imbalanced-learn

tensorflow

Models & Architectures

Linear Regression

Logistic Regression

Neural Networks (TensorFlow)

Oversampling (RandomOverSampler)

Unsupervised clustering methods

🌍 Real-World Applications
🚲 Transportation

Predicting bike rental demand, weather-based forecasting.

🏥 Healthcare

Balancing patient data for disease classification.

💳 Finance

Fraud detection using classification & oversampling.

🛒 Retail

Sales forecasting, clustering for customer segmentation.

🤖 Robotics / IoT

TensorFlow models deployable for smart automation systems.

📁 Project Structure
📦 ml-portfolio/
│── 📓 regression.ipynb
│── 📓 classification.ipynb
│── 📓 unsupervised.ipynb
│── 📁 data/
│     ├── SeoulBikeData.csv
│     ├── magic04.data
│     ├── seeds_dataset.txt
│── requirements.txt
└── README.md

🚀 Getting Started
1. Clone the Repository
git clone https://github.com/your-username/your-repo-name.git

2. Install Dependencies
pip install -r requirements.txt

3. Launch Notebooks
jupyter notebook

📈 Future Improvements

Add RandomForest, SVM, XGBoost models

Include GridSearchCV & RandomizedSearchCV

Use LIME/SHAP for interpretability

Create a Streamlit web app dashboard

Export final models using Pickle

🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to modify.

📜 License

This project is released under the MIT License.