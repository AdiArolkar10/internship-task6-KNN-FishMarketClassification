📌 Note: This task is part of a structured internship to reinforce basic ML skills.
It’s not meant to reflect my current skill level or portfolio quality.

# 🐟 Fish Market Classification with KNN

This project applies the **K-Nearest Neighbors (KNN)** algorithm to classify fish species based on physical measurements.  
The dataset is loaded directly from **Hugging Face**, so no manual upload is required.

---

## 📂 Dataset

**Source:** [Fish Market Dataset – scikit-learn on Hugging Face](https://huggingface.co/datasets/scikit-learn/Fish)  
**Features:**
- `Weight` (g)
- `Length1`, `Length2`, `Length3` (cm)
- `Height` (cm)
- `Width` (cm)

**Target:**
- `Species` (e.g., Bream, Roach, Pike, Smelt, etc.)

---

## 📊 What the Project Does
- Loads dataset directly from Hugging Face.
- Encodes categorical labels (`Species`) into numbers.
- Scales features for KNN using `StandardScaler`.
- Splits into train/test sets.
- Trains and evaluates KNN classifier.
- Visualizes:
  - Confusion Matrix
  - Accuracy vs K plot

---

## 🚀 How to Use

### **Run in Google Colab**
1. Open Google Colab: [https://colab.research.google.com/](https://colab.research.google.com/)
2. Create a new notebook and paste the code from `fish_knn.py` or `fish_knn.ipynb`.
3. Run all cells — dataset will be automatically downloaded from Hugging Face.
