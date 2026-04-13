# 🌍 Country Data Analysis using REST API

##  Project Overview

This project demonstrates how to fetch real-time # 🌍 Country Data Analysis using REST API (Python + Pandas)

It simulates a real-world data analyst workflow where data is retrieved programmatically, cleaned, and analyzed to extract meaningful insights.

---

## 🎯 Objectives

* Fetch live data from the REST API
* Handle JSON responses
* Convert raw data into structured format
* Perform data analysis using Pandas
* Extract meaningful insights

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas 📊
* Requests 🌐
* Jupyter Notebook

---

## 🔗 Data Source

- REST Countries API  
- Endpoint: https://restcountries.com/v3.1/all  
- Website: https://restcountries.com

---

## ⚙️ Project Workflow

### 1️⃣ Data Fetching

* Sent a GET request to the API
* Validated response using status codes
* Handled errors using try-except

### 2️⃣ Data Processing

* Parsed JSON data
* Extracted key fields:

  * Country Name
  * Population
  * Region
  * Area
* Converted data into Pandas DataFrame

### 3️⃣ Data Analysis

* Identified the region with the highest population
* Found the country with the largest area

---

## 📊 Key Insights

* 🌏 Region with Highest Population: **Asia**
* 🌍 Largest Country by Area: **Russia**

---

## 📸 Output Screenshot

![Project Output](screenshot.png)

---

```

## 📁 Project Structure

country-data-analysis/
│
├── country_analysis.ipynb
├── screenshot.png
├── README.md

```

---

## ▶️ How to Run

```bash
pip install requests pandas
```

```bash
jupyter notebook
```

Open `country_analysis.ipynb` and run all cells.

---

## 💡 Learning Outcomes

* Working with REST APIs
* JSON data handling
* Data cleaning and transformation
* Real-world data analysis workflow

---

## 👨‍💻 Author

**Azaz Ahmed**

---

⭐ If you like this project, give it a star!

