# ✈️ AirFly Insights: Airline Performance Analysis
This project analyzes airline flight data from 2019 to 2023 to uncover trends in delays, cancellations, and route performance. The analysis combines Python-based data processing with Power BI visualizations to generate actionable insights.

*This project was completed as part of the Infosys Springboard Data Analytics Program.*

## 📊 Problem Statement
The airline industry generates large volumes of operational data, including flight schedules, delays, cancellations, and route information. Analyzing this data is essential to identify inefficiencies, understand delay patterns, and improve operational performance.

This project aims to uncover key trends and provide data-driven insights to enhance airline efficiency and decision-making.

## 📁 Data Description
- Airline dataset covering **2019–2023**
- Contains information on **flight schedules, delays, cancellations, airlines, and routes**
- The dataset has 3M rows and 32 columns
- Refer the AIRFLY_FEATURE_DICT.docx file to understand what each column means

📌 **Raw Dataset Source (Kaggle):**  https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023

## ⚙️ Methodology
- Performed data understanding and explored dataset structure (~3M records)  
- Handled missing values while retaining meaningful nulls  
- Cleaned inconsistent records and optimized data types  
- Created new features such as Month, Day, and Route  
- Conducted exploratory data analysis and delay analysis  
- Built a Power BI dashboard for visualization and insights

## 📊 Dashboard

📌 The Power BI dashboard provides insights into:
- Flight delays and trends  
- Cancellation patterns  
- Airline performance  
- Route-level analysis 


## 📈 Key Analysis
- Identified busiest months, days, and routes  
- Analyzed airline-wise delay performance  
- Compared departure vs arrival delays  
- Explored delay causes (carrier, weather, NAS, etc.)  
- Studied cancellation trends and seasonal impact  

---

## 💡 Recommendations

- Improve carrier-level operational efficiency  
- Optimize departure scheduling and turnaround time  
- Strengthen planning during peak travel periods  
- Enhance weather risk management strategies  
- Focus on improving high-delay routes  

---

## 🛠️ Tools & Skills Used

**Tools:**
- Python  
- Power BI  
- Jupyter Notebook  

**Libraries:**
- Pandas, NumPy  
- Matplotlib, Seaborn  

**Skills:**
- Data Cleaning  
- Exploratory Data Analysis (EDA)  
- Data Visualization  
- Feature Engineering  
- Business Insight Generation  

## 📂 Project Files 
- **AIRFLY_FEATURE_DICT.docx** - Sample dataset and data dictionary
- **FinalAirFlyInsights.ipynb** - Jupyter Notebook with complete analysis 
- **Airline_Performance_Analysis_PPT.pdf** - Final presentation  
- **images/**- Dashboard photo which is used in README.md

## ⚠️ Note on Missing Values
- The dataset contains null values in columns such as **DepDelay, DepTime, TaxiIn, TaxiOut, WheelsOn, and WheelsOff**.  
- These nulls occur due to **cancelled or diverted flights**, where actual flight operations did not take place.  
- Since the real values are unavailable, these nulls were **intentionally retained** to avoid incorrect data imputation.  
- These are considered **valid nulls** and are important for accurate cancellation and disruption analysis. 
