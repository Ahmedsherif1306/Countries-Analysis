
#  Countries Analysis Project Documentation

##  Project Overview

This project focuses on collecting, cleaning, analyzing, and visualizing global country data to extract meaningful insights about **population distribution and country sizes**.
The final output is a visually appealing **dashboard** that highlights key global statistics and comparisons between countries.

---

##  Project Objectives

* Collect real-world data from the web using scraping techniques
* Clean and transform raw data into an analysis-ready format
* Analyze global population and area metrics
* Build an informative and visually attractive dashboard

---

##  Data Source

* Website: **Scrape This Site – Simple Countries Page**
  [https://www.scrapethissite.com/pages/simple/](https://www.scrapethissite.com/pages/simple/)
* Data includes:

  * Country name
  * Capital
  * Population
  * Area (km²)

---

##  Project Workflow & Steps

### 1️⃣ Data Scraping

* Extracted country data from the website using a web scraping script.
* The scraped data was saved in a structured format suitable for analysis (CSV).

---

### 2️⃣ Data Import Using Excel Power Query

* Imported the scraped dataset into **Excel using Power Query**.
* Used Power Query as the main data source for transformation and preparation.
* This approach ensures:

  * Reproducibility
  * Easy refresh of data
  * Clean data pipeline

---

### 3️⃣ Data Cleaning & Transformation

Performed multiple cleaning steps, including:

* Renaming columns for clarity
* Converting data types (population and area to numeric values)
* Handling missing or inconsistent values
* Ensuring country names and continents are standardized

The result was a **clean and analysis-ready dataset**.

---

### 4️⃣ Data Analysis

Key analytical tasks included:

* Identifying:

  * Most populated countries
  * Least populated countries
  * Largest countries by area
  * Smallest countries by area
* Comparing population vs. area for selected countries
* Aggregating data to highlight global patterns

---

### 5️⃣ Data Visualization & Dashboard Creation

* Built a dashboard containing:

  * Bar charts for most and least populated countries
  * Area vs. population comparisons
  * Smallest and largest countries analysis
  * World map visualization showing population distribution
* Focused on:

  * Clear layout
  * Consistent color theme
  * Easy-to-read visuals
  * Insight-driven storytelling

---

## 📊 Most Important Insights

* China is the **most populated country** in the dataset
* Vatican City is the **smallest country by area**
* Russia is the **largest country by land area**
* There is **no direct correlation** between country size and population
* Some very small countries still have significant population density

---

## 🧠 Key Learnings

* Web scraping is a powerful way to obtain real-world datasets
* Power Query is an efficient tool for data cleaning and transformation
* Data visualization plays a crucial role in communicating insights
* A structured workflow improves both analysis quality and project clarity

---

## 🛠️ Tools & Technologies Used

* **Web Scraping** (data collection)
* **Excel Power Query** (data cleaning & transformation)
* **Data Visualization Tools** (dashboard creation)
* **GitHub** (project version control and documentation)
