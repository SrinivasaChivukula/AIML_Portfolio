# 📊 Machine Learning Portfolio  
### **Regression • Classification • Deep Learning • Imbalanced Data Handling**

This repository contains multiple applied Machine Learning projects implemented using  
**Python, Scikit-Learn, TensorFlow, and advanced data preprocessing techniques**.

The work demonstrates **end-to-end ML pipelines**, from data ingestion and visualization to model training, balancing, optimization, and evaluation.  
Real-world datasets used include:

- **Seoul Bike Sharing Dataset**  
- **MAGIC Gamma Telescope Dataset**  
- **Wheat Seeds Dataset**

---

## 🧠 What I Learned

### ✔ **1. Data Processing & Feature Engineering**
I practiced essential preprocessing techniques such as:

- Data cleaning & handling missing values  
- Outlier checks  
- Scaling numerical features using **StandardScaler**  
- Correlation analysis  
- Preparing data for ML pipelines  

**Data Preprocessing Workflow**
```
Raw Data → Cleaning → Feature Engineering → Scaling → Train/Test Split
```

---

### ✔ **2. Machine Learning Models & Evaluation**

#### **Regression Models**
- Linear Regression  
- Coefficients interpretation  
- RMSE, MAE, R² evaluation  

#### **Classification Models**
- Logistic Regression  
- Decision boundaries  
- Confusion Matrix, Precision, Recall, F1-Score, AUC  

**Evaluation Loop**
```
Train Model → Predict → Compare with True Labels → Compute Metrics → Improve Model
```

---

### ✔ **3. Handling Imbalanced Data (Imbalanced-Learn)**
Using **RandomOverSampler**, I learned how to fix skewed class distributions.

```
Before Oversampling:              After Oversampling:
Class 0: ███████████████          Class 0: ███████████████
Class 1: ████                     Class 1: ███████████████
```

This significantly improved classification fairness and model accuracy on minority classes.

---

### ✔ **4. Deep Learning Foundations (TensorFlow)**

Skills gained:

- Building neural networks using **Keras Sequential API**  
- Understanding activation functions, layers, and optimizers  
- Interpreting training/validation loss curves  
- Designing deeper networks for improved performance  

**Example Neural Network Architecture**
```
Input Layer
    ↓
Dense Layer (ReLU)
    ↓
Dense Layer (ReLU)
    ↓
Output Layer (Sigmoid / Linear)
```

---

## 🔧 Technologies & Libraries Used

### **Languages & Tools**
- Python  
- Jupyter Notebook  
- Git / GitHub  

### **Libraries**
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- imbalanced-learn  
- tensorflow  

### **Models & Techniques**
- Linear Regression  
- Logistic Regression  
- Neural Networks (TensorFlow/Keras)  
- Oversampling (RandomOverSampler)  
- Unsupervised Learning (Clustering methods)  

---

## 🌍 Real-World Applications

### 🚲 **Transportation**
- Predicting bike rental demand  
- Optimizing resource allocation based on weather  

### 🏥 **Healthcare**
- Disease classification with imbalanced patient records  

### 💳 **Finance**
- Fraud detection and risk analysis  

### 🛒 **Retail**
- Sales forecasting  
- Clustering for customer segmentation  

### 🤖 **Robotics & IoT**
- TensorFlow models deployable on edge automation systems  

---

## 📁 Project Structure

```
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
```

---

## 🚀 Getting Started

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/your-repo-name.git
```

### **2. Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3. Launch Jupyter Notebooks**
```bash
jupyter notebook
```

---

## 📈 Future Improvements
- Add RandomForest, SVM, XGBoost models  
- Hyperparameter tuning using GridSearchCV & RandomizedSearchCV  
- Add Explainable AI (LIME, SHAP)  
- Deploy with Streamlit or Flask  
- Save trained models using Pickle / Joblib  

---

## 🤝 Contributing
Pull requests are welcome!  
For major changes, please open an issue first to discuss what you would like to modify.

---

## 📜 License
Released under the **MIT License**.
