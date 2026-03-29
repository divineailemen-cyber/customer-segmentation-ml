# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Overview

This project applies K-Means clustering, an unsupervised machine learning algorithm, to segment customers into distinct groups based on their behavior.

The goal is to uncover hidden patterns in customer data that can help businesses make informed marketing and strategic decisions.

---

## 📊 Dataset

The dataset is stored in the `/data` folder as `customers.csv`.

Features include:

* Age
* Annual Income (k$)
* Spending Score (1–100)

---

## ⚙️ Tools & Technologies

* Python
* Jupyter Notebook
* Pandas & NumPy
* Scikit-learn
* Matplotlib

---

## 🧠 Methodology

### 1. Feature Selection

Relevant features such as income and spending score were selected for clustering.

### 2. Elbow Method

Used to determine the optimal number of clusters.

![Elbow Method](images/elbow_method.png)

### 3. Model Training

K-Means clustering algorithm was applied to group customers.

### 4. Visualization

Clusters were visualized to understand customer segments.

![Customer Segments](images/clusters.png)

---

## 📈 Key Insights

* High Income, High Spending → Premium customers
* High Income, Low Spending → Potential to target
* Low Income, High Spending → Active but budget-conscious
* Low Income, Low Spending → Low engagement

---

## 📁 Project Structure

data/ → dataset
notebooks/ → Jupyter Notebook
images/ → visual outputs
README.md → documentation
requirements.txt → dependencies
.gitignore → ignored files

---

## ▶️ How to Run

1. Clone the repository
2. Install dependencies:
   pip install -r requirements.txt
3. Run Jupyter Notebook:
   jupyter notebook
4. Open:
   notebooks/customer_segmentation_kmeans.ipynb

---

## 🎯 Objective

To use clustering techniques to better understand customer behavior and support data-driven decision-making.

---

## 🚀 Future Improvements

* Add more features for clustering
* Try hierarchical clustering
* Build a dashboard for visualization

---

## 🤝 Contribution

Pull requests are welcome.

---

## 📬 Contact

Feel free to reach out for collaboration.

