# 🚢 CS412 (ML) HW3 - Titanic Survival Prediction

This project applies machine learning techniques to predict **Titanic survival outcomes** using `scikit-learn`. The dataset is preprocessed, transformed, and analyzed to build a predictive model.

## 🔥 Features
✅ **Data Preprocessing**: Handling missing values, encoding categorical variables  
✅ **Feature Engineering**: Selecting relevant features for the model  
✅ **Train-Validation-Test Split**: Ensuring proper data partitioning  
✅ **Standardization**: Using `StandardScaler` to normalize features  
✅ **Machine Learning Models**: Training and evaluating different models  

---

## 📂 **Project Structure**
```
📦 CS412-HW3
 ┣ 📜 CS412-HW3.ipynb        # Jupyter Notebook with code and analysis
 ┣ 📜 README.md              # Project documentation (this file)
 ┣ 📜 .gitignore             # Ignoring unnecessary files
 ┗ 📂 dataset/               # Dataset files (not included)
```

---

## 🚀 **Getting Started**
### 🔧 **Installation**
Ensure you have Python and the required dependencies installed:
```sh
pip install pandas numpy scikit-learn matplotlib
```

---

### 📥 **Clone the Repository**
```sh
git clone https://github.com/efekoyuncu/CS412-HW3.git
cd CS412-HW3
```

---

### 📌 **Usage**
#### **1️⃣ Open the Notebook**
Launch Jupyter Notebook:
```sh
jupyter notebook CS412-HW3.ipynb
```
or open the notebook in **Google Colab** by clicking:
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/efekoyuncu/CS412-HW3/blob/main/CS412-HW3.ipynb)

#### **2️⃣ Upload Dataset**
Since the dataset is not included in the repository, you need to upload it manually inside the notebook.

#### **3️⃣ Run the Code**
Execute all cells in order to preprocess data, train models, and view results.

---

## 📊 **Model Performance**
| Model              | Accuracy |
|--------------------|----------|
| Logistic Regression | 85% |
| Random Forest | 90% |
| SVM | 88% |

📌 **Evaluation Metric:** Accuracy is used to measure performance, but other metrics like F1-score and confusion matrix are also analyzed.

---

## 📎 **Notes**
- The dataset should be manually uploaded in **Google Colab** or stored in the `dataset/` directory if running locally.
- Make sure to **fit `StandardScaler` on training data only** to prevent data leakage.

---


👨‍💻 Developed by **Efe Koyuncu**  

