# 🔍 Crime Pattern EDA Project

This repository contains an end-to-end exploratory data analysis (EDA) on a synthetic crime dataset crafted to simulate realistic and insightful criminal activity across Indian cities.

---

## 🏛️ Project Overview

This project explores trends and patterns in crime using a generated dataset of 10,000 records. It analyzes attributes such as time of occurrence, weapon used, city, victim age, and more, to identify insights that could be relevant for law enforcement, safety analysis, or surveillance systems.

---

## 🔢 Dataset Description

* **File**: `crime_data.csv`
* **Records**: 10,000 simulated crime incidents

### ✏️ Features:

* `City` – Location of the crime
* `Crime Description` – Type of crime (e.g., Assault, Theft)
* `Weapon Used` – Weapon involved, if any
* `Time of Occurrence` – Timestamp of when the crime occurred
* `Victim Age` – Age of the victim
* `Police Deployed` – Number of officers involved
* `Case Closed` – Whether the case was resolved (1 = Yes, 0 = No)

---

## 🖊️ EDA Process

### 1. **Data Cleaning**

* Converted time columns to datetime
* Verified value ranges and data types

### 2. **Univariate Analysis**

* Distribution of crime types, cities, and victim ages
* Weapon usage frequency

### 3. **Bivariate/Multivariate Analysis**

* Time-of-day patterns vs. weapon use
* City-wise weapon distribution
* Police deployed vs. case closure rate

### 4. **Custom Patterns Added**

* More violent crimes (e.g., gun use) occur during the day
* Higher crime density during evening and night hours

---

## 📊 Key Insights

* **Top Crime Cities:**

  * Mumbai, Delhi, Bangalore are the top 3

* **Most Common Crimes:**

  * Theft, Assault, Robbery dominate

* **Weapon Usage:**

  * \~36% of crimes involved no weapons
  * Knives and blunt objects more common than firearms

* **Time Patterns:**

  * Evening and night show higher crime frequency
  * Gun-related crimes skewed toward daytime

* **Case Closure Rate:**

  * \~44% of cases closed

* **Police Deployment:**

  * More officers typically deployed for violent crimes

---

## 📅 Tools & Technologies

* **Language**: Python
* **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
* **Data Generation**: Custom logic to simulate realistic trends

---

## 🚀 Getting Started

1. Clone the repo
2. Open the Jupyter notebook provided
3. Run the EDA cell-by-cell
4. Modify plots or perform deeper analysis as needed

---

## 💼 Additional Notes

This EDA project was inspired by the need to visualize and understand patterns in crime data for potential integration with surveillance systems. For real-time weapon detection and AI-based tracking, check out this separate project:
[🔗 Real-time Enemy Detection](https://github.com/r4kno/The_God-s_Eye)

---
## 📬 Contact

For any queries, reach out at [onkargupta0864@gmail.com] or connect via [LinkedIn](https://www.linkedin.com/in/onkar-gupta-6398ba264/).

---

