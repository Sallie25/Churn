# Customer Churn Report

![Random_store_image](https://github.com/user-attachments/assets/bc82e72b-cd42-44d9-a7e7-f9a79b262207)


##  Introduction
Customer churn is a critical metric for businesses aiming to retain their customer base and maintain profitability. This project explores churn behavior using a secondary dataset, transforming raw data into actionable insights through visualizations and KPIs.

##  Problem Statement
The goal is to identify patterns and drivers of customer churn in a subscription-based business. By analyzing customer demographics, product usage, and satisfaction metrics, we aim to uncover key factors influencing churn and recommend strategies to improve retention.

##  Skills Demonstrated
- SQL for data extraction and transformation  
- Data cleaning and preprocessing  
- KPI development and dashboard design  
- Exploratory Data Analysis (EDA)  
- Insight generation and storytelling  
- Visualization using BI tools (e.g., Power BI, Tableau)

## Data Sourcing
- **Source Type**: Secondary  
- **Origin**: Public dataset simulating customer behavior in a subscription service  
- **Fields Included**: Customer ID, Age, Tenure, Product usage, Card type, Revenue, Satisfaction score, Complaints

---

##  Data Transformation
- **Cleaning**: Removed duplicates, handled missing values  
- **Feature Engineering**: Created churn flag, grouped customers by card/product type  
- **Aggregation**: Calculated KPIs such as churn rate, average satisfaction, and revenue per segment  
- **Normalization**: Standardized numerical fields for comparison

---

##  KPI Analysis & Insights
<img width="655" height="60" alt="Image" src="https://github.com/user-attachments/assets/3ea55ba2-3457-4cf3-8315-8f710dfbe224" />


### 1. **Total Customers**
- **Value**: 10,000  
- **Insight**: Represents the full customer base under analysis.

### 2. **Retained Customers**
- **Value**: 7,962  
- **Retention Rate**: 79.62%  
- **Insight**: High retention suggests overall customer satisfaction, but churn still affects ~20% of the base.

### 3. **Churned Customers**
- **Value**: 2,038  
- **Churn Rate**: 20.38%  
- **Insight**: Indicates a need to investigate churn drivers such as dissatisfaction or product mismatch.

### 4. **Average Satisfaction**
- **Score**: 3.01 / 5  
- **Insight**: Below-average satisfaction may correlate with churn. Improving service quality could reduce churn.

### 5. **Average Age**
- **Value**: 45 years  
- **Insight**: Middle-aged customers dominate the base. Tailoring services to this demographic may improve retention.

### 6. **Average Tenure**
- **Value**: 5.01 years  
- **Insight**: Long tenure suggests loyalty, but churn among long-term users could signal deeper issues.

---

##  Visual Analysis
--- 
### 🔹 Churn by Revenue

<img width="1168" height="626" alt="Image" src="https://github.com/user-attachments/assets/f6e6677b-fda2-4bc6-b40f-a9914e51307c" />

- **Observation**: Higher revenue segments show lower churn.  
- **Action**: Premium customers are more loyal—consider upselling strategies.

### 🔹 Churn by Product

<img width="1070" height="680" alt="Image" src="https://github.com/user-attachments/assets/f5c8e76b-0957-4172-a956-81b27f0944d5" />

- **Observation**: Certain products have higher churn rates.  
- **Action**: Reevaluate product value propositions and customer fit.

### 🔹 Churn by Card Type

<img width="993" height="613" alt="Image" src="https://github.com/user-attachments/assets/c0ffd6be-509d-461c-b67f-8062f86ad16e" />

- **Observation**: Card type influences churn behavior.  
- **Action**: Analyze benefits and usage patterns per card type.

### 🔹 Complaints vs. Churn

<img width="1176" height="638" alt="Image" src="https://github.com/user-attachments/assets/1325875e-415d-4a9c-8a8a-beae939ebb4b" />

- **Observation**: Customers with complaints have significantly higher churn.  
- **Action**: Enhance complaint resolution processes to retain dissatisfied customers.

### 🔹 Satisfaction vs. Churn

<img width="984" height="625" alt="Image" src="https://github.com/user-attachments/assets/53be4bf2-e9fb-49b0-ae12-8902a5b53a9a" />

- **Observation**: Lower satisfaction scores correlate with churn.  
- **Action**: Prioritize customer experience improvements.

---

##  Extended KPI Analysis & Insights

### 🔹 Churned Customers by Gender

<img width="957" height="740" alt="Image" src="https://github.com/user-attachments/assets/e714f9b5-5bce-45af-acb9-824ec88835fa" />

- **Observation**: Female customers show a slightly higher churn rate than male customers.  
- **Insight**: Gender-specific engagement strategies may help reduce churn.

### 🔹 Churn by Location

<img width="1884" height="729" alt="Image" src="https://github.com/user-attachments/assets/51925797-5ab5-480d-b7ce-3312a0226a58" />

- **Observation**: Churn rates vary significantly by region. South East and South West show higher churn.  
- **Insight**: Regional churn patterns suggest localized issues—consider region-specific retention campaigns.

### 🔹 Churn by Credit Score

<img width="751" height="681" alt="Image" src="https://github.com/user-attachments/assets/ea994e51-de4e-4405-b3e5-82ed8495f53f" />

- **Observation**: Customers with lower credit scores tend to churn more.  
- **Insight**: Financial stress may contribute to churn. Offering flexible payment plans could help.

### 🔹 Churn by Age and Age Group.

<img width="1666" height="655" alt="Image" src="https://github.com/user-attachments/assets/34720d5e-3bc2-4f6a-90fc-7acdced1ede8" />

- **Observation**: Younger customers (under 30) show higher churn. Also, age group 30–40 has the highest churn volume
- **Insight**: Younger demographics may be more price-sensitive or less loyal. Tailored onboarding and incentives could improve retention.This group may be balancing financial and lifestyle changes—targeted support could reduce churn.


##  Conclusion
This analysis reveals that churn is influenced by satisfaction, complaints, product type, revenue tier, demographics, and geography. A segmented approach is essential to address the diverse needs of the customer base.

##  Recommendations
- Launch targeted retention campaigns for high-churn segments  
- Improve complaint handling and customer support  
- Enhance product offerings for low-satisfaction groups  
- Monitor KPIs regularly to track churn trends  
- Develop gender-specific loyalty programs  
- Launch regional retention initiatives in high-churn areas  
- Provide financial wellness tools for low credit score customers  
- Create youth-focused engagement campaigns  
- Monitor churn by age group to adapt lifecycle marketing
