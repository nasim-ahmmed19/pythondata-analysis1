# 🏨 Hotel Booking Insights & Cancellation Prediction

A data-driven project that combines **Exploratory Data Analysis (EDA)**, **Geospatial Visualization**, and **Machine Learning** to analyze hotel booking behavior and predict cancellations.

---
![Hotel-booking](hotel-booking/Screenshot_27.png)
## 🔍 Key Analysis & Exploratory Data Analysis (EDA)
Using **Plotly**, **Seaborn**, and **Folium**, I investigated the following business questions:
* **Guest Origins:** Where do most guests come from? (Visualized with `Folium` HeatMaps).
* **Pricing Trends:** How much do guests pay per night? (Analyzed via `ADR`).
* **Seasonality:** How does the price vary per night over the year?
* **Booking Patterns:** Which are the most busy months and how long do people stay?
* **Missing Data:** Used `missingno` to identify and handle data gaps efficiently.

---

## 🤖 Machine Learning Modeling
I implemented a robust pipeline to predict booking cancellations using multiple algorithms:
* **Algorithms Used:** `Logistic Regression`, `Decision Tree`, `Random Forest`, and `K-Nearest Neighbors (KNN)`.
* **Preprocessing:** `StandardScaler` for feature scaling and `PolynomialFeatures` for capturing complex patterns.
* **Optimization:** Used `GridSearchCV` for hyperparameter tuning and `Cross-Validation` for stable performance.
* **Evaluation:** Detailed analysis using `Confusion Matrix`, `Classification Report`, and `Accuracy Score`.

---

## 🎮 Interactive Features
* **Dynamic Analysis:** Integrated `ipywidgets` (interact/manual) to allow users to filter data and visualizations dynamically within the notebook.
* **Database Management:** Used `SQLAlchemy` and `SQLite` to handle data through SQL queries, presented beautifully with `PrettyTable`.

---

## 🛠️ Tech Stack & Libraries
* **Core:** `Pandas`, `NumPy`
* **Visualization:** `Matplotlib`, `Seaborn`, `Plotly Express`, `Folium`
* **Machine Learning:** `Scikit-Learn`
* **Interactive Tools:** `ipywidgets`
* **Database:** `SQLAlchemy`, `SQLite3`

---

## 📂 Project Structure
* `📂 data/`: Raw and processed hotel booking datasets.
* `📂 notebooks/`: Jupyter notebooks for data cleaning, EDA, and ML model training.
* `📂 images/`: Heatmaps, Star Schemas, and model evaluation charts.
* `README.md`: Project documentation.

---
