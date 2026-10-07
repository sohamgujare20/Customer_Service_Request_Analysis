<p align="center">
  <img src="https://img.shields.io/badge/Language-Python-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Data_Analysis-Pandas_%26_NumPy-green?style=for-the-badge&logo=pandas" />
  <img src="https://img.shields.io/badge/Statistics-Kruskal--Wallis_Test-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Visualization-Seaborn_%26_Matplotlib-yellow?style=for-the-badge" />
</p>

<h1 align="center">NYC 311 Customer Service Request Analytics</h1>

<p align="center">
  <strong>An end-to-end Python data wrangling, exploratory analysis, and statistical hypothesis testing solution for New York City 311 service calls.</strong>
</p>

---

### 📌 Project Executive Summary
This project analyzes over **364,000 service request records** from New York City (NYC 311 calls) to identify complaint patterns, evaluate response times, and uncover spatial distributions across boroughs. By applying advanced data wrangling, geospatial plotting, and non-parametric statistical testing (Kruskal-Wallis H Test), this analysis delivers actionable operational insights for city agency efficiency.

> [!IMPORTANT]
> **Key Finding:** Response times vary significantly across different complaint categories and locations. Statistical testing confirmed $p < 0.05$, rejecting the null hypothesis ($H_0$) and proving that average request closing time is non-uniform across complaint types.

---

### 📊 Dataset
Download the dataset from Kaggle to run this project:
[**311 Service Requests from 2010 to Present**](https://www.kaggle.com/datasets/josefsieber/311-service-requests-from-2010-to-present)

---

### 🛠️ Technical Workflow & Tools
- **Python Data Stack:** Utilized `Pandas` and `NumPy` for data cleaning, time-elapsed calculations, missing value imputation, and DataFrame transformations.
- **Exploratory Data Analysis (EDA):**
  - Converted `Created Date` and `Closed Date` into elapsed resolution time in seconds (`Request_Closing_Time`).
  - Handled missing values (imputed missing cities as `Unknown City`).
  - Evaluated concentration of complaints using **Scatter** and **Hexbin** spatial density plots.
- **Data Visualization:** Used `Matplotlib` and `Seaborn` to construct frequency plots, borough-wise complaint distributions, and comparative bar charts.
- **Statistical Testing:** Conducted a **Kruskal-Wallis H Test** using `scipy.stats` to test if response times are statistically equal across complaint types.

---

### 📈 Strategic & Operational Insights
- **Top Complaint Categories:** Non-emergency municipal issues like *Blocked Driveway*, *Illegal Parking*, and *Noise - Street/Sidewalk* consistently constitute the highest volume of calls in NYC.
- **Spatial Distribution:** Brooklyn and Queens exhibit dense concentrations of parking and noise-related complaints, requiring targeted police precinct resource allocation.
- **Resolution Efficiency:** Computing descriptive statistics for resolution time revealed notable variance in average response speed depending on incident type and borough.

---

### 📂 Repository File Structure
| File / Directory | Description |
| :--- | :--- |
| 📓 `Customer_Service_Request_Analysis.ipynb` | **Main Jupyter Notebook** containing data wrangling, EDA, charts, and statistical tests. |
| 📄 `Customer_Service_Request_Analysis_Project.pdf` | **Project Brief & Requirements** outlining problem statements and objectives. |
| 📊 `311_Service_Requests_from_2010_to_Present.csv` | Raw source dataset containing 364,558 NYC service request records. |

---

## 👨‍💻 Professional Background
**Soham Gujare** *Computer Science Engineer & Aspiring Data Analyst*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/sohamgujare)
[![GitHub](https://img.shields.io/badge/GitHub-View_Projects-black?style=flat-square&logo=github)](https://github.com/sohamgujare20)
