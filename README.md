📊 **Customer Churn Analysis**

This repository contains an Exploratory Data Analysis (EDA) notebook focused on identifying and understanding the patterns and factors contributing to customer churn in a telecommunications company. The analysis uses a publicly available dataset and leverages Python libraries like pandas, matplotlib, seaborn, and numpy.

📁 **Project Structure**

.
├── CCA.ipynb              # Jupyter Notebook containing the full analysis
├── Customer churn dataset.csv (not included here, link below)
└── README.md              # Project documentation

🚀 **Getting Started**

🛠️ *Requirements*

▪︎ Python 3.10+

▪︎ Jupyter Notebook / Google Colab

*Libraries*:

▪︎ pandas

▪︎ numpy

▪︎ matplotlib

▪︎ seaborn

*Install dependencies*:

pip install pandas numpy matplotlib seaborn

📌 **Dataset**

The analysis is based on the Telco Customer Churn dataset, which includes information such as:

▪︎ Customer demographics

▪︎ Account information

▪︎ Services signed up for

▪︎ Churn status (Yes/No)



🔍 **Key Steps in Analysis**

1. *Data Loading & Cleaning*:

▪︎ Mounted Google Drive and imported CSV.

▪︎ Replaced blank values and converted TotalCharges to numeric.

▪︎ Handled data types and confirmed absence of null/duplicate entries.

2. *Data Transformation*:

▪︎ Converted SeniorCitizen binary column (0/1) to readable format (Yes/No).

3. *Visual Explorations*:

▪︎ Distribution of churned vs. non-churned customers using bar and pie charts.

4. *Churn distribution by*:

▪︎ Gender

▪︎ Senior Citizen status

▪︎ Tenure

▪︎ Contract Type

▪︎ Payment Method

▪︎ Multi-panel categorical variable analysis (PhoneService, Streaming, TechSupport, etc.)

5. *Insights*:

▪︎ Short-tenure customers tend to churn more.

▪︎ Month-to-month contracts correlate with higher churn.

▪︎ Internet services (especially Fiber Optic) and lack of support features impact churn.

▪︎ Engagement in digital services is a strong churn predictor.

📷 **Sample Visualizations**

📌 Count of customers by churn status

📌 Percentage churn via pie chart

📌 Stacked bar chart showing churn by senior citizen status

📌 Histogram of tenure colored by churn

📌 Multiple countplots for categorical variables related to services

📈 **Conclusion**

This analysis provides valuable insights into what drives customer churn. It can help in designing retention strategies by focusing on tenure, contract types, and digital service offerings.

👨‍💻 **Author**

Priyanshu Mishra
BTech CSIT Student | Data Enthusiast
📧 priyanshu.mishra080808@gmail.com
