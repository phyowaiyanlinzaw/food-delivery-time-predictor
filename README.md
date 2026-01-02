# 🚚 Food Delivery ETA Prediction

## 📌 Project Overview
This project focuses on building a **Predictive Machine Learning Model** to estimate the arrival time (ETA) for food deliveries. [cite_start]This is a core feature for on-demand platforms like **LINE MAN Wongnai** to optimize logistics and enhance user experience[cite: 1].

---

## 🚀 Key Features
* [cite_start]**Data Cleaning:** * Handled missing values (`NaN`) and performed string manipulation[cite: 1].
    * [cite_start]Extracted numerical values from complex string formats (e.g., converting **"(min) 28"** to float)[cite: 1].
* [cite_start]**Feature Engineering:** * Engineered a **Spatial Feature (Distance)** by calculating the distance between the restaurant and the delivery location using GPS coordinates[cite: 1].
* [cite_start]**Modeling:** * Utilized **Random Forest Regressor** to train on 80% of the data and predict delivery times[cite: 1].
* [cite_start]**Evaluation:** * Evaluated model performance using the **R-squared ($R^2$) score** to understand predictive accuracy[cite: 1].

---

## 🛠️ Technologies Used
* **Language:** `Python`
* **Libraries:** `Pandas`, `NumPy`, `Scikit-learn`
* **Environment:** `Google Colab`

---

## 📊 Dataset
The project uses the **Food Delivery Dataset** from Kaggle, which includes:
* [cite_start]**Delivery Person Details:** Age and Ratings[cite: 1].
* [cite_start]**Location Data:** Latitude and Longitude of both the Restaurant and the Delivery location[cite: 1].
* [cite_start]**Target Variable:** Time taken for delivery in minutes[cite: 1].

---

## 📈 Future Improvements
1.  Incorporate **Weather** and **Traffic** data to improve model accuracy.
2.  Implement the **Haversine Formula** for more precise distance calculations.
3.  Experiment with other algorithms like **XGBoost** or **LightGBM**.

---

## 👨‍💻 Author
**Phyo Wai Yan Lin Zaw**
* [cite_start]**Education:** Software Engineering Student at Mae Fah Luang University (**GPAX 4.0**) [cite: 1]
* [cite_start]**Achievement:** **1st Place Winner** - LINE x MFU Hackathon 2025 [cite: 1]
* **Contact:** [GitHub](https://github.com/phyowaiyanlinzaw) | [cite_start][Email](mailto:phyowaiyanlinzaw.3005@gmail.com) [cite: 1]
