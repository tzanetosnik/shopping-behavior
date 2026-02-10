# Customer Shopping Behavior Analysis (Portfolio Project)

This project is part of my **data science / machine learning portfolio** and demonstrates my ability to perform **exploratory data analysis**, build a **classification model**, and extract **business insights** from customer data.

The analysis is implemented in a Jupyter Notebook and focuses on understanding customer shopping patterns and predicting whether a customer has an active subscription using a **Random Forest model**.

---

## 📌 Project Overview

**Goal:**
Analyze customer shopping behavior and identify the most important factors influencing subscription status.

**Key Skills Demonstrated:**

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Data visualization
* Machine learning (classification)
* Model evaluation
* Feature importance interpretation

---

## 📂 Project Structure

```
├── shopping behavior.ipynb   # Main analysis notebook
├── shopping_behavior.csv     # Dataset
├── README.md                 # Project documentation
```

---

## 📊 Dataset

The dataset contains customer-level shopping data, including:

* Demographic information (e.g. age)
* Purchase behavior and spending
* Product categories
* Subscription status (target variable)

The dataset is explored and validated at the beginning of the notebook to assess data quality and structure.

---

## 🔍 Exploratory Data Analysis (EDA)

The EDA focuses on understanding customer behavior through:

* Distribution analysis (e.g. age)
* Purchase amount analysis by product category
* Visual insights into spending patterns

Libraries used:

* **pandas** for data manipulation
* **matplotlib** and **seaborn** for visualization

---

## 🤖 Machine Learning Approach

A **Random Forest Classifier** is trained to predict customer subscription status.

### Workflow:

1. Data preparation and feature selection
2. Train-test split
3. Model training
4. Model evaluation using:

   * Accuracy score
   * Classification report

### Feature Importance

The model’s feature importance is analyzed to highlight which customer attributes most strongly influence subscription decisions, providing interpretable insights rather than just predictions.

---

## 📈 Results & Insights

* The model achieves solid classification performance on unseen data
* Certain behavioral and demographic features play a significant role in predicting subscriptions
* The analysis demonstrates how machine learning can support customer segmentation and business decision-making

---

## 🛠️ Tools & Technologies

* Python
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository
2. Ensure `shopping_behavior.csv` is in the same directory as the notebook
3. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Run the notebook:

```bash
jupyter notebook shopping behavior.ipynb
```

---

## 🔮 Future Improvements

* Hyperparameter tuning for model optimization
* Comparison with additional classification models
* Feature engineering for improved performance
* Deployment as a simple web application

---

 👤 Author

Nikos Tzanetos
Aspiring Data Scientist / Machine Learning Engineer

---

 📄 License

This project is for educational and portfolio purposes. Feel free to explore and reuse the code.


