# 🌳 CRISP-DM Tourism Destination Recommendation System

[![Python](https://img.shields.io/badge/Python-3.11.9-blue?logo=python)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikit-learn)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.2.3-150458?logo=pandas)](https://pandas.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)](https://jupyter.org/)

A Data Analytics project applying the **CRISP-DM methodology** to build a **Tourism Destination Recommendation System** using the **Decision Tree algorithm**.

This project was developed as the final assignment for the **Fundamentals of Data Analyst** course, Semester 3, **Universitas Bina Sarana Informatika (2025)**.

---

## 👥 Team Members

| Name | Student ID |
|------|------------|
| NICO ALFIANTO | 19240013 |
| MUHAMMAD IKHSAN BASUKI | 19240452 |
| MARCHO DOMINGGUS DEVIANO TIMISELA | 19240228 |
| AWALUDIN ALAYUBI | 19240187 |
| NETHAR BALAWAN MUALIKUL MULKI | 19240450 |

---

## 🎯 Project Overview

Indonesia's tourism industry generates massive amounts of data, making it difficult for travelers to choose destinations efficiently.

This project applies the **CRISP-DM framework** together with a **Decision Tree Classifier** to classify and recommend tourism destinations based on user ratings from a public Kaggle dataset.

---

## 🔬 Methodology (CRISP-DM)

1. **Business Understanding**
   - Identify the problem of information overload in tourism destination selection.

2. **Data Understanding**
   - Analyze three tourism datasets obtained from Kaggle.

3. **Data Preparation**
   - Merge datasets
   - Handle missing values
   - Encode categorical features
   - Split data into 80% training and 20% testing

4. **Modeling**
   - Build a Decision Tree Classifier using **scikit-learn**

5. **Evaluation**
   - Evaluate the model using:
     - Confusion Matrix
     - Classification Report
   - Model Accuracy: **41%**

6. **Deployment**
   - Classify destination ratings into:
     - Low
     - Medium
     - High

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| Language | Python 3.11.9 |
| IDE | Google Colab, VS Code, Jupyter Notebook |
| Libraries | Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn |

---

## 📊 Key Results

- Decision Tree achieved **41% accuracy**
- Best Recall performance on the **Medium** class (**80%**)
- Model tends to favor the majority class
- Suggested improvements:
  - Feature Engineering
  - Random Forest
  - Collaborative Filtering
  - Hybrid Recommendation Systems

---

## 📂 Repository Structure

```text
.
├── data/
│   └── *.csv
├── notebooks/
│   └── tourism_recommendation.ipynb
├── results/
│   ├── confusion_matrix.png
│   └── decision_tree.png
├── paper/
│   ├── Makalah_CRISP-DM_Tourism.pdf
│   └── Journal.pdf
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run

### 1. Clone this repository

```bash
git clone https://github.com/your-username/crisp-dm-tourism-recommendation-decision-tree.git
```

### 2. Enter the project folder

```bash
cd crisp-dm-tourism-recommendation-decision-tree
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Open the notebook

Run the notebook using **Google Colab** or **Jupyter Notebook**.

---

## 🔗 Links & Resources

[![Open in Colab](https://img.shields.io/badge/Open%20in-Colab-F9AB00?logo=googlecolab)](https://colab.research.google.com/drive/11Cbd_DNi3lxTwl0hhYEnt9hWigPtG5Xw?authuser=0#scrollTo=ZKch4qSNjNqU)

[![Dataset](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?logo=kaggle)](https://www.kaggle.com/datasets/aprabowo/indonesia-tourism-destination)

[![Journal](https://img.shields.io/badge/Journal-PDF-red?logo=adobeacrobatreader)](https://drive.google.com/file/d/1T-qXPhuI0s2l4osOBJX91YiUxhfC584K/view?usp=drivesdk)

[![Journal Template](https://img.shields.io/badge/Journal%20Template-SINTA-0066CC)](https://sinta.kemdiktisaintek.go.id/journals/profile/11523)

### Resources

- **Google Colab Notebook**
  - https://colab.research.google.com/drive/11Cbd_DNi3lxTwl0hhYEnt9hWigPtG5Xw

- **Dataset**
  - https://www.kaggle.com/datasets/aprabowo/indonesia-tourism-destination

- **Academic Paper**
  - `/paper/Makalah_CRISP-DM_Tourism.pdf`

- **Scientific Journal**
  - https://drive.google.com/file/d/1T-qXPhuI0s2l4osOBJX91YiUxhfC584K/view

- **SINTA Journal Template**
  - https://sinta.kemdiktisaintek.go.id/journals/profile/11523

---

## 📄 Publication

This project is also documented as a scientific journal using the **SINTA journal template** provided by the Ministry of Higher Education, Science, and Technology of Indonesia.

---

## 📚 Citation

If you use this project, please cite:

```text
Alfianto, N., Basuki, M. I., Timisela, M. D.,
Alayubi, A., & Mulki, N. B. M. (2025).

Application of CRISP-DM Methodology in Tourism Destination
Recommendation System Using Decision Tree Algorithm.

Universitas Bina Sarana Informatika.
```

---

## 📜 License

This project is licensed under the **MIT License**.

See the [LICENSE](LICENSE) file for more information.
