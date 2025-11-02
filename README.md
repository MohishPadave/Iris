
## Project 2: Iris Dataset - Classification, Regression & Clustering

### 📌 Objective

To explore and apply different machine learning techniques — **Classification**, **Regression**, and **Clustering** — using the classic **Iris Dataset**.

---

### 📊 Dataset Information

**Source:** [Iris Dataset (Kaggle)](https://www.kaggle.com/datasets/uciml/iris)
**Rows:** 150 | **Columns:** 5

**Columns:**

* `SepalLengthCm`
* `SepalWidthCm`
* `PetalLengthCm`
* `PetalWidthCm`
* `Species` (Target)

---

### ⚙️ Steps Performed

#### **1️⃣ Classification**

**Goal:** Predict the flower species using Decision Tree and Naive Bayes.

* **Algorithms Used:**

  * Decision Tree Classifier
  * Gaussian Naive Bayes
* **Results:**

  * Both models achieved **~97–98% accuracy** due to the dataset’s simplicity and clear class separation.

#### **2️⃣ Regression**

**Goal:** Predict a **numerical value** (e.g., PetalWidth) from other features.

* **Algorithm Used:** Linear Regression
* **Metric:** R² score ≈ **0.93** — strong relationship between PetalLength and PetalWidth.

#### **3️⃣ Clustering**

**Goal:** Group flowers based on their measurements and compare clusters with actual species.

* **Algorithms Used:**

  * K-Means
  * DBSCAN
  * Agglomerative Clustering
* **Results:**

  * K-Means with **k=3** closely matched the three real species.
  * DBSCAN identified outliers and density-based clusters.
  * Agglomerative Clustering showed hierarchical relationships.

---

### 🧠 Insights

* The dataset is highly separable — Petal length and width are the strongest predictors.
* Even unsupervised models (like K-Means) can closely approximate true species labels.
* Excellent dataset for learning **basic ML techniques**.

---

### 🛠️ Tools & Libraries Used

`Python`, `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-learn`

---

## 📂 Repository Structure

```
├── Iris_Dataset_Analysis/
│   ├── data/
│   ├── notebooks/
│   ├── models/
│   └── README.md
│
└── main_README.md  ← (this file)
```

---

## 🚀 How to Run

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/ml-projects.git
   cd ml-projects
   ```
2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Run notebooks in Google Colab or Jupyter

   ```bash
   jupyter notebook
   ```

