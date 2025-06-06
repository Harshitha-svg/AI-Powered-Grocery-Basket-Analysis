# AI-Powered-Grocery-Basket-Analysis

### 📌 Project Overview

* Applied **Apriori Algorithm** to analyze customer purchase patterns from a grocery dataset.
* Identified **frequent itemsets** and generated **association rules** to reveal product affinities.
* Aimed to assist in **personalized recommendations**, **cross-selling**, and **market strategy**.

---

### 📂 Dataset

* Dataset: [Groceries Dataset from Kaggle](https://www.kaggle.com/datasets/heeraldedhia/groceries-dataset)
* Contains:

  * `Member_number` – unique customer ID
  * `Date` – transaction date
  * `itemDescription` – purchased item

---

### 🧠 Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **MLxtend** (for Apriori and association rules)
* **Matplotlib** and **Seaborn** (for data visualization)

---

### ⚙️ Key Features

* Data preprocessing: grouped item transactions
* One-hot encoding for model compatibility
* Frequent itemset mining using **Apriori Algorithm**
* Rule generation with **support**, **confidence**, and **lift**
* Visualizations for:

  * Frequent itemsets
  * Support vs Confidence with Lift
* Rule interpretation in plain English

---

### 📊 Visual Insights

* Bar plot of top 10 frequent itemsets
* Bubble plot of association rules (lift = size)
* Textual interpretation of top rules

---

### 🎯 Use Cases

* Product recommendation engine
* Market strategy optimization
* Basket bundling or combo offers
* Targeted advertising based on buying behavior

---

### 🚀 How to Run

1. Clone the repo
2. Download the dataset from Kaggle
3. Install required packages using `pip install -r requirements.txt`
4. Run `AI_Grocery_Basket_Analysis.ipynb` in Jupyter Notebook

---

### 📌 Future Scope

* Add a Streamlit UI for interactive recommendations
* Use clustering for customer segmentation
* Incorporate time-based trends (seasonal demand)

---


