# Customer Segmentation & Churn Pattern Analytics in European Banking

## Project Overview

Customer churn is a major challenge for retail banks because losing customers directly impacts revenue and long-term profitability. This project analyzes customer data from a European bank to identify churn patterns, high-risk customer segments, and key behavioral factors influencing customer attrition.

Using data analytics and visualization techniques, the project explores how demographic, financial, and engagement-related variables affect churn. The analysis helps banks design data-driven retention strategies to improve customer lifetime value.

---

## Objectives

The main objectives of this project are:

* Analyze customer churn behavior in a European banking dataset
* Identify high-risk customer segments
* Understand the influence of demographic and financial attributes
* Discover geographic churn differences
* Build an interactive Streamlit dashboard for business insights
* Provide strategic recommendations for customer retention

---

## Dataset Description

The dataset contains approximately **10,000 customer records** with demographic and financial information.

| Feature         | Description                               |
| --------------- | ----------------------------------------- |
| CustomerId      | Unique customer identifier                |
| Surname         | Customer last name                        |
| CreditScore     | Customer credit score                     |
| Geography       | Customer country (France, Spain, Germany) |
| Gender          | Male or Female                            |
| Age             | Customer age                              |
| Tenure          | Years with the bank                       |
| Balance         | Account balance                           |
| NumOfProducts   | Number of bank products used              |
| HasCrCard       | Credit card ownership                     |
| IsActiveMember  | Customer activity status                  |
| EstimatedSalary | Estimated salary                          |
| Exited          | Target variable (1 = churn, 0 = retained) |

---

## Methodology

### Data Cleaning

* Removed irrelevant columns such as CustomerId and Surname
* Checked for missing values
* Converted categorical variables to numerical format

### Exploratory Data Analysis (EDA)

Analyzed churn patterns based on:

* Geography
* Age groups
* Gender
* Account balance
* Customer engagement
* Product usage

### Customer Segmentation

Customers were segmented based on:

* Demographic attributes
* Financial characteristics
* Customer engagement levels

### Visualization

Data insights were visualized using:

* Bar charts
* Box plots
* Distribution plots
* KPI metrics

### Dashboard Development

An interactive **Streamlit dashboard** was developed to present insights dynamically.

---

## Key Insights

### Geography Impact

Customers located in **Germany show the highest churn rate** compared to France and Spain.

### Age Influence

Customers aged **above 45 years** are more likely to churn.

### Engagement Level

Inactive members show **significantly higher churn probability**.

### Product Usage

Customers using **only one banking product churn more frequently** than customers using multiple services.

### High Value Customer Risk

Customers with **high account balances represent major revenue risk when they churn**.

---

## Business Recommendations

### Target High-Risk Segments

Focus retention programs on customers in high-churn regions such as Germany.

### Increase Customer Engagement

Use email campaigns, mobile notifications, and personalized offers to engage inactive customers.

### Product Bundling Strategy

Encourage customers with one product to adopt additional services such as:

* Credit cards
* Loans
* Investment products

### Premium Customer Retention

Provide personalized services and relationship managers for high-value customers.

---

## Streamlit Dashboard

The project includes an interactive dashboard built using **Streamlit**.

Dashboard Features:

* KPI metrics (Churn rate, total customers, average balance)
* Country-wise churn analysis
* Age vs churn visualization
* Product usage analysis
* Customer segmentation insights
* Interactive filters

Run the dashboard using:

streamlit run app.py

---

## Technologies Used

| Tool       | Purpose                   |
| ---------- | ------------------------- |
| Python     | Data analysis             |
| Pandas     | Data manipulation         |
| NumPy      | Numerical computing       |
| Matplotlib | Data visualization        |
| Seaborn    | Statistical visualization |
| Streamlit  | Interactive dashboard     |

---

## Project Structure

Bank-Churn-Analytics
│
├── European_Bank.csv
├── app.py
├── research_paper.pdf
├── executive_summary.pdf
├── requirements.txt
└── README.md

---

## Future Improvements

Potential enhancements include:

* Building machine learning models for churn prediction
* Deploying the dashboard on Streamlit Cloud
* Implementing real-time customer churn prediction
* Developing advanced customer recommendation systems

---

## Conclusion

This project demonstrates how data analytics and customer segmentation techniques can help banks identify churn patterns and improve retention strategies. By leveraging insights from demographic, behavioral, and financial data, banks can make data-driven decisions that enhance customer satisfaction and long-term profitability.
