---

# 📊 Used Car Market Analysis using Web Scraping & EDA

A data analysis project that collects real-world used car listing data through **API-based web scraping** and performs **Exploratory Data Analysis (EDA)** to understand the factors influencing resale prices in the used car market.

This project focuses on analyzing the **Hyderabad used car market** using data scraped from an online automobile marketplace.

---

# 🚀 Project Overview

The used car market is rapidly growing, making it difficult for buyers and sellers to determine the correct resale value of vehicles.

This project aims to:

* Collect real-world used car data using **web scraping**
* Clean and structure the collected dataset
* Perform **feature engineering**
* Conduct **Exploratory Data Analysis (EDA)**
* Identify **key factors influencing resale prices**

---

# 🎯 Problem Statement

The used car market is growing rapidly, making it difficult for buyers and sellers to determine the correct resale value of vehicles. This project analyzes a used car dataset using Exploratory Data Analysis (EDA) to understand how factors influencing used car prices in Hyderabad.

* Vehicle age
* Kilometers driven
* Brand reputation
* Fuel type
* Transmission type
* Ownership history

Understanding how these factors influence resale value can help **buyers, sellers, and marketplaces make better pricing decisions**.

---

# 🌐 Data Source

Dataset was collected through **API-based web scraping** from:

**Source:** [https://www.cars24.com](https://www.cars24.com)

Instead of using a pre-existing dataset, the project simulates a **real-world data collection pipeline** where data is extracted directly from a live website.

---

# ⚙️ Tech Stack

### Programming Language

* Python

### Libraries Used

* **Requests** – API based web scraping
* **Pandas** – Data processing
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Plotly** – Interactive visualizations

---

# 📦 Dataset Information

The dataset contains information about **used car listings in Hyderabad**.

### Dataset Size

* **Total Records:** ~1500 listings
* **Total Features:** 13+ columns

### Key Features

| Column             | Description                      |
| ------------------ | -------------------------------- |
| brand              | Car manufacturer                 |
| model              | Vehicle model                    |
| variant            | Model variant                    |
| year               | Manufacturing year               |
| price              | Resale price                     |
| fuel_type          | Petrol / Diesel / CNG / Electric |
| transmission       | Manual / Automatic               |
| km_driven          | Distance traveled                |
| ownership          | Number of previous owners        |
| body_type          | Hatchback / Sedan / SUV          |
| registration_state | Registration location            |

---

# 🧹 Data Cleaning

Before analysis, the dataset was checked for:

* Missing values
* Duplicate rows
* Data consistency

### Observations

* No missing values were found
* No duplicate records were detected
* Data was clean and well structured

---

# 🛠 Feature Engineering

Additional features were created to extract deeper insights from the dataset.

### Derived Features

* **car_age** → Current year − manufacturing year
* **price_segment** → Budget / Mid-range / Premium
* **km_per_year** → Vehicle usage intensity
* **price_per_year** → Depreciation indicator
* **is_first_owner** → Ownership classification

These features help analyze **vehicle depreciation, usage patterns, and market segmentation**.

---

# 📊 Exploratory Data Analysis (EDA)

EDA was performed in three stages:

### 1️⃣ Univariate Analysis

Understanding the distribution of individual variables.

Examples:

* Price distribution
* Brand distribution
* Fuel type distribution
* Transmission type distribution
* Vehicle age distribution
* Kilometers driven distribution

---

### 2️⃣ Bivariate Analysis

Understanding relationships between two variables.

Examples:

* Car Age vs Price
* Kilometers Driven vs Price
* Fuel Type vs Price
* Transmission Type vs Price
* Ownership vs Price
* Most listed car models by brand
* Price segment distribution

---

### 3️⃣ Multivariate Analysis

Understanding relationships between multiple variables simultaneously.

Examples:

* Correlation heatmap
* Brand vs Body Type vs Price analysis

---

# 🔍 Key Insights

### 🚗 Vehicle Age is the Strongest Price Driver

Older cars experience significant depreciation compared to newer vehicles.

### 🛣 Usage Impacts Resale Value

Cars with higher mileage generally have lower resale prices.

### 🏆 Market is Dominated by Few Brands

Brands like **Maruti and Hyundai dominate the resale listings**.

### 🚙 SUVs Command Premium Prices

SUVs often maintain higher resale value compared to hatchbacks and sedans.

### ⛽ Petrol and Diesel Dominate the Market

Electric and hybrid vehicles are still rare in the used car ecosystem.

### 👤 Ownership History Matters

Single-owner vehicles generally maintain higher resale value.

---

# 📈 Business Insights

This analysis provides valuable insights for different stakeholders.

### Buyers

Identify vehicles that provide **better value based on mileage, age, and brand reliability**.

### Sellers

Understand **factors affecting resale pricing**.

### Marketplaces

Improve **price recommendation systems and listing optimization**.

### Data Science Applications

Provides a strong foundation for building **machine learning models for used car price prediction**.

---

# 📁 Project Structure

```
used-car-market-analysis
│
├── data
│   └── used_car_dataset.csv
│
├── notebooks
│   └── Used_Car_Market_Analysis.ipynb
│
├── images
│   └── visualizations
│
├── presentation
│   └── project_presentation.pdf
│
├── README.md
└── requirements.txt
```

---

# ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/yourusername/used-car-market-analysis.git
```

---

### 2️⃣ Install Dependencies

```
pip install -r requirements.txt
```

---

### 3️⃣ Run the Notebook

```
jupyter notebook
```

Open:

```
Used_Car_Market_Analysis.ipynb
```

---

# 📌 Future Work

Future improvements for this project include:

* Building **machine learning models for price prediction**
* Adding **time series market analysis**
* Expanding scraping to **multiple cities**
* Creating an **interactive dashboard**

---

# 👨‍💻 Authors

* **MD. Sami Ur Rahaman **
* **Shaik Rizwan**
* **Saran Sri Bharagava posika**

Batch No: 474
Innomatics Research Labs

---

# ⭐ If you like this project

Give the repository a ⭐ on GitHub!

---

# 📜 License

This project is for **Educational and Research purposes**.

---


