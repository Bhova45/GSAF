# 🦈 Global Shark Attack Data Analysis

## 📝 Project Overview

This project focuses on performing a full **Exploratory Data Analysis (EDA)** and data cleaning process on the **Global Shark Attack File (GSAF) dataset**.

The goal was to transform messy, real-world public data into a clean, actionable format and extract key insights regarding the geographical, temporal, and activity-based trends of shark attacks worldwide.

---

## 🔑 Key Findings & Business Insights

The analysis addressed several key questions, yielding the following insights:

### 1. Geographical Risk Profile

* **Finding:** The **USA** records the highest *total number of attacks*, but **Australia** holds the highest number of **fatal attacks (310)**, followed by the USA (**202**).
* **Insight:** While the risk of *interaction* is highest in the USA, the risk of *lethality* is significantly higher in Australia, suggesting a difference in the types of sharks present or emergency response systems. Safety efforts should be tailored to this specific risk profile in each region.

### 2. Activity-Based Risk

* **Finding:** **Surfing** was identified as the activity most frequently associated with recorded attacks, followed by **swimming/wading**.
* **Insight:** Public safety campaigns must be targeted specifically at recreational water users, focusing on avoiding high-risk times (like dawn/dusk) and high-risk environments (like murky river mouths).

### 3. Data Quality and Limitations

* **Finding:** The raw GSAF dataset required extensive cleaning, as **over 80% of records were unusable** until key columns (like the `Injury` column for fatality data) were successfully coerced and imputed.
* **Insight:** This underscores the critical need for **standardized, mandatory global reporting** of shark incidents to improve data reliability for future risk modeling.

---

## 📊 Visualization of Key Data

**Top 5 Countries by Fatal Shark Attacks**

This chart visually demonstrates the difference in risk severity, highlighting Australia's high number of recorded fatalities.

![Bar chart showing the top 5 countries by the number of fatal shark attacks, with Australia leading at 310](fatal_attacks_by_country.png)

---

## 🛠️ Technology Stack

| Component | Purpose |
| :--- | :--- |
| **Python** | Core programming language |
| **Pandas** | Data Cleaning and Analysis |
| **Matplotlib / Seaborn** | Data Visualization |
| **Jupyter Notebook** | Interactive Analysis |
| **Git & GitHub** | Version Control & Hosting |

---

## ⚙️ How to Replicate

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/Bhova45/Global-Shark-Attack-Data-Analysis.git](https://github.com/Bhova45/Global-Shark-Attack-Data-Analysis.git)
    ```
2.  **Open the Notebook:** Launch the **`GSAF.ipynb`** file in a Jupyter environment.
3.  **Run All Cells:** Execute all cells sequentially to reproduce the data cleaning, analysis, and visualizations.
