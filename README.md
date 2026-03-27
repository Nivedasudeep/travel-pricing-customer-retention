# Travel-pricing-customer-retention
Exploratory Data Analysis and customer segmentation on hotel booking data to uncover cancellation patterns, demand trends, and support dynamic pricing strategies.

# Travel, Tourism & Hospitality: Customer Retention & Dynamic Pricing Analysis

##  Executive Summary
In the highly competitive travel and hospitality industry, revenue loss often occurs due to high cancellation rates and ineffective pricing strategies. This project analyzes historical hotel booking data to identify key drivers of customer cancellations and uncover seasonal demand patterns. The insights derived aim to support dynamic pricing strategies and targeted customer retention campaigns.


##  Project Objectives
- Analyze customer booking behavior and cancellation trends
- Identify factors influencing high cancellation probability
- Explore seasonal demand and pricing patterns
- Segment customers based on booking behavior
- Provide data-driven insights for revenue optimization (RevPAR)


##  Dataset Description
The dataset contains hotel booking records with features such as:
- Lead Time (days before arrival)
- Average Daily Rate (ADR)
- Booking status (Canceled / Not Canceled)
- Customer type (Corporate, Leisure, etc.)
- Number of weekend and weekday stays
- Deposit type and market segment


##  Technology Stack
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn  
- **Environment:** Jupyter Notebook  



---

## 🔍 Methodology

### 1. Data Cleaning & Preprocessing
- Handled missing values in key columns (agent, company)
- Treated outliers in Average Daily Rate (ADR)
- Created new feature:
  - `total_stay = weekend nights + weekday nights`

---

### 2. Exploratory Data Analysis (EDA)
- Univariate and bivariate analysis
- Correlation matrix to identify key influencing factors
- Cancellation trends across different features
- Distribution analysis of ADR

---

### 3. Customer Segmentation
Customers were grouped based on:
- Booking behavior (early vs last-minute)
- Purpose (corporate vs leisure)
- Stay duration patterns

---

### 4. Seasonal Demand & Pricing Analysis
- Monthly booking trends
- Demand fluctuations over time
- ADR variation across seasons

---

##  Key Insights
- Longer lead times are strongly associated with higher cancellation rates  
- Bookings without deposits have a significantly higher probability of cancellation  
- Peak seasons show increased demand and higher ADR  
- Corporate customers tend to have lower cancellation rates compared to leisure travelers  

---

##  Business Impact
- Enables better forecasting of cancellations  
- Supports dynamic pricing strategies based on demand trends  
- Helps marketing teams target high-risk customers with retention campaigns  
- Improves revenue optimization through data-driven decisions  

---

##  Future Enhancements
- Build predictive models (Logistic Regression) for cancellation prediction  
- Implement dynamic pricing algorithms  
- Develop an interactive dashboard using Power BI or Tableau  
- Deploy model for real-time booking predictions  

---

## 👩‍💻 Author
**Niveda Sudeep**   
📧 nivedasudeep7@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/niveda-sudeep-17868531  





