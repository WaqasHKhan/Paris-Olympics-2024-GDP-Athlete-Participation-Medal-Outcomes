# 🏅 Paris Olympics 2024 - GDP, Athlete Participation & Medal Outcomes

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![EDA](https://img.shields.io/badge/EDA-Exploratory%20Data%20Analysis-orange)
![Web Scraping](https://img.shields.io/badge/Web%20Scraping-BeautifulSoup-yellow)
![APIs](https://img.shields.io/badge/API-REST-red)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 🔍 Project Overview

This project analyzes the relationship between **economic strength**, **athlete participation**, and **Olympic medal performance** using data from the **Webpages and APIs**

[https://en.wikipedia.org/wiki/List_of_IOC_country_codes​

https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal)​

https://en.wikipedia.org/wiki/2024_Summer_Olympics​]

By combining **web-scraped datasets** with **API-sourced medal counts**, the analysis evaluates whether countries with higher GDPs or larger athlete delegations consistently achieve stronger Olympic outcomes.

The project is structured as an **end-to-end data analytics case study**, covering:
- Data acquisition (APIs + scraping)
- Data cleaning and normalization
- Exploratory data analysis (EDA)
- Statistical correlation and regression
- Insight-driven storytelling

---

## 🎯 Business & Analytical Scenarios

### Scenario 1  
**Does a country’s GDP influence the total number of medals won?**

> Hypothesis: Higher economic capacity enables better training infrastructure, talent pipelines, and resource allocation, leading to higher medal counts.

### Scenario 2  
**Does the number of athletes participating affect medal outcomes?**

> Hypothesis: Larger athlete delegations increase exposure across events, improving medal probability.

---

## 🗂️ Datasets Used

| Dataset | Source | Method |
|------|------|------|
| GDP by Country | [Wikipedia](https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal)) | Web Scraping |
| Medals by Country | [Codante.io Olympic API](https://apis.codante.io/olympic-games/countries?page={page}) | REST API |
| Number of Athletes | [Olympic participation pages](https://en.wikipedia.org/wiki/2024_Summer_Olympics) | Web Scraping |
| Normalization Dataset | [Wikipedia](https://en.wikipedia.org/wiki/List_of_IOC_country_codes) | Web Scraping |

Country names and codes were standardized using official IOC mappings to ensure accurate joins.

---

## 🧪 Methodology

### 1️⃣ Data Collection
- Consumed external APIs for real-time medal counts  
- Scraped structured and semi-structured HTML pages using **BeautifulSoup**

### 2️⃣ Data Wrangling & Transformation
- Cleaned country names and standardized IOC country codes  
- Transformed GDP and participation metrics into comparable numeric formats  
- Normalized datasets to ensure consistency across scales

### 3️⃣ Data Integration
- Joined GDP, athlete participation, and medal datasets  
- Resolved mismatches (e.g., *United States* vs *USA*)

### 4️⃣ Exploratory Data Analysis (EDA)
- Correlation analysis
- Linear regression modeling
- Visual storytelling with regression plots

---

## 📈 Key Visualizations

### 📊 GDP vs Total Medals Won
> **Matplotlib scatter plot with regression line**

📌 *🥇 Medals Won vs GDP:*  

[Medals Won vs GDP](Medals%20Won%20vs%20GDP.png)

---

### 📊 Athletes Participated vs Medals Won
> **Seaborn regression plot**

📌 *🥇 Medals Won vs Number of Athletes Participated:*  
[Medals Won vs No. of Athletes Participated](Medals%20won%20vs%20No.%20of%20Athlets%20Participated.png)


---

## 💡 Key Insights

- **Positive correlation between GDP and medal count**
  - Economically stronger countries consistently outperform lower-GDP nations
- **Athlete delegation size is a strong performance multiplier**
  - Larger teams increase medal opportunities across events
- **Structural advantages matter**
  - Investment capacity, infrastructure, and scale significantly influence outcomes

---

## 📊 Business & Policy Implications

- **Sports funding efficiency:** Medal outcomes correlate with investment scale
- **Talent pipeline strategy:** Broader participation improves performance probability
- **Benchmarking:** Enables fairer comparisons when normalized by GDP or athlete count

These insights are relevant for **sports federations, policymakers, and performance analysts** evaluating ROI on athletic investment.

---
### 📄 Full Project-Report
👉 [![Click20%Here20%to20%Open](https://img.shields.io/badge/Project-Report-red)](Paris_Olympics_2024-Report.pdf)

---
## 🔧 Tech Stack

- **Python**
- **Pandas & NumPy** - Data manipulation
- **BeautifulSoup** - Web scraping
- **REST APIs** - Medal data ingestion
- **Matplotlib & Seaborn** - Statistical visualization
- **Jupyter / Google Colab** - Interactive analysis

---


---

## 🚀 Why This Project Matters

This project demonstrates:
- Real-world **data acquisition from unreliable sources**
- **Multi-source data integration**
- Statistical reasoning using correlation and regression
- Clear translation of data insights into **business-relevant conclusions**

It is designed to be **portfolio-ready** for roles in:
- Data Analytics
- Business Intelligence
- Applied Data Science
- Sports Analytics

---

## 📬 Next Enhancements
- Add medal efficiency metrics (medals per athlete/medals per GDP)
- Introduce predictive modeling
- Expand analysis to historical Olympic Games

---
## 👤 Author

**Waqas Hameed**

![GitHub](https://img.shields.io/badge/GitHub-000000?logo=github&logoColor=white)![Dashboard PDF](https://img.shields.io/badge/@WaqasHKhan-white)

Data Analyst | Business Intelligence | Data Storyteller | Visualization & Reporting

---
⭐ If you found this project insightful, feel free to star the repository!
