<img width="2048" height="1536" alt="walmart_png" src="https://github.com/user-attachments/assets/ade6487a-e46b-46f3-b433-ca27f3101da2" />

# 🛒 Walmart Black Friday Analysis



## 📑 Project Summary
Conducted Exploratory Data Analysis (EDA) to identify differences in customer purchasing behavior
using Average Transaction Value across gender, age, city category, and marital ststus. Derived
actionable insights by identifying high-value and low-value customer segments and proposed data-driven
business recommendations to improve customer acquisition and revenue.
  

## 📂 Notebook Overview
* Data Cleaning and Feature Transformaation.
* Handling missing values and Outliers.
* Univariate and Multivariate analysis.
* Data driven Insights and recommendations.

## 🎯Objective 
* Tracking the amount spent per transaction by female and male.
* Inference after computing the average female and male expenses.
* Use the Central limit theorem or bootstrapping to compute the <br>
  Cofidence interval.
* Conclude the results and check if the confidence intervals of average <br>
  male and female spends are overlapping or not overlapping.
* Perform the same activity for Married vs Unmarried and Age.
* Extract key insights, Give recommendations and action items to <br>
  Walmart based on insights.

## 📈 key Insights


### **📊 Executive Summary & Key Takeaways**
* **The Revenue Engine:** Total revenue is primarily driven by **Customer Volume  
(Distribution)** across Age and Marital Status, but in City Categories, **Average  
 Transaction Value (ATV)** is the real differentiator.

* **The Hero Categories:** Product Categories **1, 5, and 8** are the business's backbone,   
driving **73% of overall revenue** across almost all customer segments.

* **The Ideal Profile:** High-value revenue is heavily anchored toward **Male customers**,  
 individuals **aged 26–35**, and residents of **City Category B**.




### **👥 Customer Demographics**

#### **1. Gender Dynamics**
* **Revenue Dominance:** Male customers account for **77% of total  transaction   
  revenue**,driven by a larger customer base and a significantly higher volume  
  of products purchased per transaction.

* **Shared Preferences:** Despite differences in overall spending volume, purchasing  
 patterns are identical: both genders allocate roughly **70% of their spend** to  
  Product Categories 1, 5, and 8.

#### **2. Age Distribution & Spending Hierarchy**
* **The Sweet Spot (26–35):** The 26–35 age cohort forms the majority of the   
  customer base and generates the highest total transaction volume.
* **ATV Hierarchy:** Average transaction value follows a distinct age-based lifecycle: <br>

  $$\text{26–35} > (\text{18–25}, \text{36–45}) > (\text{46–50}, \text{51–55}) > \text{55+} > \text{0–17}$$
  
* **Behavioral Clustered Habits:** Purchasing behaviors are highly aligned between  
 specific age groups: (18–25 $\approx$ 36–45) and (46–50 $\approx$ 51–55).

#### **3. Marital Status & City Tenure**
* **Marital Status:** **Unmarried customers** make up the majority of the database. Their   
transaction share perfectly mirrors their population size, with no notable variance in  
 purchase behavior or ATV compared to married customers.

* **City Tenure Churn:** Customers in their **1st year of city residency** are the   highest  
revenue contributors. Customer density steadily declines for every subsequent year  
of residency.

#### **4 City Category Analysis**
* **City  Category B (High Value / Premium):** The highest revenue contributor, driven by  
 a superior ATV. Customers here purchase high volumes and are notably **less price-sensitive**.

* **City Category A (High Volume / Balanced):** Matches City B in terms of product   
quantities purchased, but has lower average transaction values (higher price sensitivity).

* **City  Category C (Mass Market / Low Yield):** Despite having the highest number of   
total customers, City C contributes the least to overall transactions due to exceptionally  
 low purchase quantities.


### **🎯 Strategic Customer Segmentation**
Segments are defined by Average Transaction Value (ATV) thresholds derived from multivariate  
 analysis.

#### **1. High-Value Segment ($>\text{ATV } 1,000,000$)**

**Strategic Focus:** Retention and premium upselling.
* Males in City Categories A & B
* City Category B residents aged 18–25, 26–35, 36–45, 46–50, and 51–55
* City Category A residents aged 26–35 and 36–45


#### **2. High-Mid Value Segment ($\text{ATV } 800,001 - 1,000,000$)**

**Strategic Focus:** Cross-selling Core Categories (1, 5, 8).
* Females in City Categories A & B

* City Category B residents aged 0–17 and 55+

* City Category A residents aged 18–25, 46–50, and 51–55

* Males aged 18–25, 26–35, and 36–45

#### **3. Low-Mid Value Segment ($\text{ATV } 600,000 - 800,000$)**

**Strategic Focus:** Volume-driving promotions
* City Category A residents aged 0–17

* Males aged 0–17, 46–50, and 51–55

* Females aged 18–25, 26–35, 36–45, and 46–50

#### **4. Low-Value Segment ($<\text{ATV } 600,000$)**

**Strategic Focus:** Low-cost digital engagement or basket-building incentives.

* All customers (regardless of Gender or Age) living in City Category C

* City Category  A residents aged 55+

* Females aged 0–17, 51–55, and 55+

* Males aged 55+


### **📌 Key Strategic Note:**
 * City Category B is an absolute powerhouse. Every single customer demographic  
  (regardless  of age or gender) residing in City B falls strictly into either the High-  
  Mid or High-Value segment, proving it to be your most lucrative market.



## 🚀 Business Recommendations

**📈 1. High-Yield Customer Acquisition Strategies**
* Target Premium Demographics, Prioritize acquisition campaigns targeting  
  Male customers in City Categories A and B.
* Establish B2B2C affiliate programs with corporate offices, since the major   
  working class, 26–45 age cohort represents the highest-spending Customers.
* Allocate the primary share of the general marketing budget to City Category B  
 Since, it is a common sub-segment in all the high or high-mid value segments.

**🚀 2. Customer Lifetime Value (LTV) & Youth Awareness**

* Capture the Next Generation (Ages 0–17),Secure early brand loyalty by   
  aggressively targeting the under-18 demographic.

* Formulate Traditional & Digital Stretegy. Run targeted ads on kid-focused   
television networks and leverage social media influencers who command  
 a heavy underage following.

**💸 3. Average Order Value (AOV) Optimization**
* Introduce volume-based tier rewards,To counter low transaction values  
  among Females, Seniors(50+).
* Implement structural cart incentives such as, buy 'x' get 'y' free or get  
 'x'% discount on the purchase of 'y' number of quantities.
* Bundle/Package complementary products together at a slight discount to  
  naturally push these specific segments into purchasing higher quantities  
  per transaction.

**💎 4. Premium Retention: High-Value Segment VIP Track**

**Target Customers:** Males in Cities A & B, Age 26–45 in City A,  
                      and Age 18–55 in City B.

* Establish personalized email and SMS workflows to instantly notify them  
  of premium arrivals and exclusive previews.

* Issue high-value, time-sensitive loyalty coupons (e.g., "Valid for the next  
  'x' days only") to compress the time window between their purchases.

**🔄 5. Multi-Year Residency Retention & Loyalty**

* Combat the natural residency churn rate by introducing a structured loyalty   
  points system specifically tracking city tenure. Reward customers who have   
  resided in the city for 1+ years with higher point-multipliers to incentivize  
   frequent in-store visits.

* Enhance end-to-end customer service (both floor assistance during shopping and   
 post-purchase resolution). Superior service is the lowest-cost,highest-return  
  mechanism to retain long-term city residents.

**🧲 6. Customer Retention Stretegy**
* Extend highly targeted post-Black Friday promotional windows with strategic,  
   short-term discounts on top-selling Product categories for high value segments.
   
* Closely monitor local competitor pricing and matching structures. Deploy aggressive,  
 localized promotional counter-offers during major regional festivals and peak retail   
 holiday sales.

## 📊 Visualizations
### Distribution of Gender
<img width="2391" height="622" alt="image" src="https://github.com/user-attachments/assets/9a000214-6877-4e46-a48a-a16f7314661f" />

*Percentage of male and female customers and percentage of their total transaction*


### CI Visualization
<img width="1247" height="451" alt="image" src="https://github.com/user-attachments/assets/696a93dd-2dbe-4af8-ae24-c2b44b35e1e5" />

*95% Confidence Interval of female and male average per transaction*

### Gender Purchasing Pattern
<img width="1667" height="628" alt="image" src="https://github.com/user-attachments/assets/a07ee0c5-0b52-4086-978a-97d0734ddb67" />

*Allocation of money on each product category by each gender*

## Average spending of different products
<img width="1574" height="689" alt="image" src="https://github.com/user-attachments/assets/1aede5ae-e778-4af2-a882-103ef959e069" />

*female and male average spending on top 20 products*


### Total transaction: Marital Status
<img width="1584" height="684" alt="image" src="https://github.com/user-attachments/assets/97442700-ec4a-47ef-a624-45cd745a53e8" />

*Percentage of total spending by married and unmarried customers*

## Total Spending: Age
<img width="1279" height="650" alt="image" src="https://github.com/user-attachments/assets/93532b81-a064-46ff-8c1d-ccaae3e33bfc" />

*Percentage of total spending by different age groups*

## Average Spending: Age
<img width="1012" height="496" alt="image" src="https://github.com/user-attachments/assets/ef2e1382-1843-466d-8136-d70d8956ed6d" />

*Average per transaction by each age group*

## Segments
<img width="1574" height="628" alt="image" src="https://github.com/user-attachments/assets/d66a591a-c713-4121-a92b-3469616b0907" />

*High and low value segments*


