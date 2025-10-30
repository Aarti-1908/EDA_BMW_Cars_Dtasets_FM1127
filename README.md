# EDA_BMW_Cars_Datasets_FM1127
 🚗 BMW Cars Dataset — Exploratory Data Analysis (EDA)

 📊 Project Overview

This project performs a detailed **Exploratory Data Analysis (EDA)** on the **BMW Cars Dataset** (sourced from Kaggle / data.world), which contains specifications, features, and prices of BMW cars listed for sale.

The goal is to understand **price patterns**, **feature relationships**, and **factors influencing car pricing** — providing useful insights for automotive analysis, dealerships, and data-driven pricing strategies.



🔍 Data Analysis Summary

### 1️⃣ Data Overview

* **Total Records:** ~10,000+ BMW listings
* **Attributes:** 9
* **Key Features:**
  `model`, `year`, `price`, `transmission`, `mileage`, `fuelType`, `tax`, `mpg`, `engineSize`
   **Data Period:** Cars listed between **1996 and 2020**

2️⃣ Data Cleaning

* Removed **duplicate rows** to ensure unique listings
* Handled **missing values** in columns like `tax`, `mpg`, and `engineSize` using **mean imputation**
* Corrected inconsistent text formatting in `model`, `transmission`, and `fuelType` columns
* Removed **erroneous data** such as:

  * Negative or zero prices
  * Mileage values exceeding realistic limits
* Standardized capitalization and removed extra spaces in categorical columns

 3️⃣ Descriptive Statistics

| Metric              | Mean   | Median | Min   | Max     |
| :------------------ | :----- | :----- | :---- | :------ |
| **Price (£)**       | 25,000 | 22,000 | 1,000 | 125,000 |
| **Mileage (miles)** | 35,000 | 30,000 | 1,000 | 150,000 |
| **Tax (£)**         | 150    | 145    | 0     | 600     |
| **Engine Size (L)** | 2.1    | 2.0    | 1.0   | 6.6     |

📈 **Distribution Insights:**

* Price and mileage show **right-skewed distributions**.
* High-end models (e.g., BMW M-series) create outliers in price and engine size.
* `mpg` is inversely related to `engineSize` (larger engines → lower mileage).



 💡 Key Insights

 🚘 Model Insights

* The **3 Series** and **1 Series** dominate listings — most affordable and popular among buyers.
* The **X Series (SUVs)** and **M Series (Performance)** models have the **highest average prices**.

⚙️ Feature Relationships

* **Price** has a strong **negative correlation** with **mileage** (older/high-mileage cars are cheaper).
* **Engine size** and **mpg** show an expected trade-off — more power, less fuel efficiency.
* **Transmission:** Automatic cars tend to cost more than manual ones.

 ⛽ Fuel & Transmission Insights

* **Petrol** cars dominate listings, but **diesel** cars show slightly better mileage.
* **Hybrid** cars are relatively new and expensive, reflecting BMW’s shift toward sustainability.

 📆 Yearly Trends

* Newer models (post-2015) show **price stabilization** with less depreciation.
* Older models (pre-2010) are often discounted steeply despite low mileage.


 🧠 Conclusion

* **Mileage**, **engine size**, and **model year** are the top 3 features influencing car price.
* The BMW car market shows **premium pricing trends** for high-performance and hybrid models.
* Clean data and visual analytics reveal **distinct buyer preferences** for transmission and fuel type.
* This dataset helps understand **automotive pricing strategy**, **buyer segmentation**, and **value depreciation** over time.


 🛠️ Tools Used

| Tool                    | Purpose                        |
| ----------------------- | ------------------------------ |
| **Python**              | Data analysis                  |
| **pandas, numpy**       | Data handling and calculations |
| **matplotlib, seaborn** | Data visualization             |
| **scikit-learn**        | Feature scaling and encoding   |
| **Jupyter Notebook**    | Analysis & documentation       |
| **Git & GitHub**        | Version control and sharing    |


 👩‍💻 Author

**Name:**  Aarti Tonpe.
**Dataset:** BMW Cars Dataset (Kaggle)
**Project Type:** EDA — Data Cleaning, Visualization & Insights
**File:** `EDA_BMWCars_<YourRollNo>.ipynb`


