# Portfolio
## About
Hello, I'm Xiang Ding, a results-driven Data Analyst with seven years of experience in end-to-end data analysis, SQL, data governance, and predictive modeling. I'm proficient in analyzing complex datasets to deliver actionable business insights using tools like MySQL, Python, Power BI, and Tableau. Additionally, I'm adept at designing and implementing data models and dashboards to support data-driven decision-making.

It is my Master's degree in International Studies with a focus on economics that introduced me to quantitative methods through courses in mathematics, statistics, and econometrics. This sparked my interest in data and its applications.
 
Subsequently, as a sovereign credit rating analyst at Lianhe Credit Rating, I gained practical experience in data collection, mining, quality assessment, and analysis. I was instrumental in developing the company's first sovereign rating model, collaborating closely with the IT department.
 
Recognizing the need for a more systematic foundation in data science, I completed a Data Science Diploma at the Toronto Institute of Data Science and Technology. This program equipped me with a comprehensive skill set, including proficiency in Python, SQL, machine learning, and cloud platforms like AWS and Azure. I also had the opportunity to apply my knowledge through several impactful projects.
 
Building on this academic and practical experience, I have successfully delivered two projects as a data science consultant at Beam Data.

In my free time, I enjoy exploring new data analysis tools and techniques, and I am always looking for opportunities to expand my knowledge and skills. Whether working on a team or independently, I am driven by the thrill of discovering new insights and the satisfaction of using data to solve complex problems.

Here is my latest [CV](https://docs.google.com/document/d/1fzozA5KAxOIedaaAhJWrXJ-ttko0JFmZ1uIQrm98L5Y/edit?tab=t.0) for your reference.

This is a repository to showcase skills, share projects and track my progress in Data Analytics / Data Science related topics.

## Table of Contents

* About
* Portfolio Projects
  - Predictive Modeling
    - Corporate Credit Rating Forecasting
    - Loan Default Prediction
  - Data Visualization and Reporting
    - Metabase Dashboard on Website Traffic and Marketing Campaigns
    - Criminal Cases in Los Angeles
    - Global Financial Markets
  - Web Scraping
    - Condo.ca Analysis
  - Data Pipeline and Model Development
    - Twitter Sentment Analysis
 * Contact
  
## Portfolio Projects
In this section I will list data analytics projects briefly describing the technology stack used to solve cases.

### Corporate Credit Rating Forecasting
**Goal:** to predict the rating result of a given company based on selected financial and other key indicators.

**Description:** This project is to develop a predictive model upon a dataset related to thousands of corporate credit ratings assigned by several leading credit agencies. A combination data analytic skills and technologies, including machine learning and deep learning were used to ensure the final accuracy of predictions.  

**Skills:** data cleaning, exploratory data analysis, model development, hyperparameter tuning, model validation, and model interpretation.

**Technology:** MySQL, Python(Pandas & Numpy), Scikit-Learn, Tensorflow, Kinesis, Machine Learning, Deeplearning.

**Results:** achieved a satisfactory prediction accuracy greater than 0.66.

**Code:** [Corporate Credit Rating Forecasting](https://github.com/BlazingTheTrail/Projects/blob/main/Corporate_Credit_Rating_Forecast.ipynb)
  
### Loan Approval POC Model
**Goal:** to accurately deny loan applicants that should be denied while minimizing the number of denied applicants that should be approved.

**Description:** This project is to build a machine learning based model able to predict default probabilities of loan applicants. 3-month bank transaction records of thousands historical applicants were used for training and testing the model, with a desired accuracy rate of 70% set by the client.

**Skills:** MySQL, Python(Pandas & Numpy), Scikit-Learn, Tensorflow, Kinesis, Machine Learning, Deeplearning.

**Technology:** MySQL, Python(Pandas & Numpy), Scikit-Learn, Tensorflow, Kinesis, Machine Learning, Deeplearning, FastAPI, Docker

**Result:** succeeded in reaching the desired accuracy rate of 70%

**Porject File:** [Loan Approval POC Model](https://www.notion.so/Loan-Approval-POC-Model-051e5375ef654ca7a838a7067b7fe1ae?pvs=4)

**Note:** Since the code of this project contains non-public information, here I just provide you with the priliminary project launching file above for your reference.

### Metabase Dashboard on Website Traffic and Marketing Campaigns
**Goal:** to develop a sophisticated solution that provides an easier yet deeper understanding of a client's website traffic and the efficacy of their marketing campaigns

**Description:** Our client - a leading institution in Canada, heavily relies on its official website for marketing and user acquisition. The institute’s management places great importance on website data research, utilizing several tools, particularly the Google Analytics 4, to evaluate its marketing effectiveness. However, the current Google Analytics dashboard falls short of providing deep insights and a user-friendly interface regarding the effectiveness of marketing campaigns. To address this gap, the management has been seeking a better solution, leading to the launch of this Project.

**Skills:** data extracting, data quality assessment, data cleaning, data analyzing, data visualisation

**Technology:** Airbyte, PostgreSQL, DataGrip, Google Analytics 4, Metabase

**Result:** The easy-to-use design of the Metabase dashboards ensures our client to efficiently navigate and leverage the wealth of data to optimize its marketing strategies.

**Project summary:** [Metabase Dashboard on Website Traffice and Marketing Campaigns](https://www.notion.so/Visualization-Project-Summary-64ff7b58c9bd482f97d58597fe3c2b29)

### Criminal Cases in Los Angeles
**Goal:** to present the criminal cases in Los Angeles in the year of 2010

**Description:** This project is developed to display the criminal cases in Los Angeles in the year of 2010. A variety of metrics and dimentions, such as occurence hours, victim genders, occurence neighborhood, criminal type and their relationships were anyalized in details, enabling audience to better understand the criminal cases in Los Angeles during that period of time.

**Skills:** data collection, data cleaning, data analysis, and data visualization

**Technology:** MySQL, DataGrip, Tableau

**Result:** Criminal cases in Los Angeles in the year of 2010 are clearly presented.

**Go to Tableau Dashboard** [Criminal Cases in Los Angeles](https://public.tableau.com/views/Crime2010LA/DashboardCrimeinLosAngeles?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

### Global Financial Markets
**Goal:** to present trends of global financial markets in a given month

**Description:** This project is developed to display the changes happened in global financial markets, including foreign exchange markets, stock marketes, bond markets, commodity markets, and inter-bank markets, with the aim to help our client making data-driven decisions and maximize its profits.

**Skills:** data load, data cleaning, data analysis, data visualization

**Technology:** MySQL, DataGrip, Tableau

**Result:** trends of selected global financial markets are clearly presented.

**Go to Tableau Deshboard** [Global Financial Markets](https://public.tableau.com/app/profile/xiang.ding/viz/GlobalFinancialMarkets/DashboardforGlobalFinancialMarket)

### Condo.ca Analysis
**Goal:** to analyze Toronto's condo rental status

**Decription:** This project includes to use web scraping approach to extract needed data from Condo.ca, to develop a structured data set for further analysis, to cleanup and analyze the data, and finally to accomplished the data visualization.

**Skils:** data crawling, dataset building, data cleaning, data analysis, and data visualization

**Technology:** Python, Seaborn, Matplotlib

**Result:** succeeded in presenting the status of Toronto condo rental status.

**code** [Condo.ca analysis](https://github.com/BlazingTheTrail/Projects/blob/main/WebScraping_Project_Condos_Final_%20(2).ipynb)

### Twitter Sentiment Analysis
**Goal:** to analyze the sentiments of selected twitters.

**Description:** This project is developed to analyze the twitter sentiment on AI topic. Specifically, I extracted 10,000 twitters, dated on December 8, 2022 and containing the topic of AI, then built up a dataset for later analysis. Further， I cleaned up the data, transformed the features and trained and evaluated a analytical model. 

**Skills:** Load Dataset, Data Cleaning, Feature Transformer, Label Encoder, Model Training, Model Evaluation, Use Pipeline

**Technology:** AWS(EC2, S3), NPL, PySpark(Databricks), Athena, QuickSight

**Result:** Suceeded in analyzing twetter sentiment.

**Code:** [Twitter Sentiment Analysis](https://community.cloud.databricks.com/?o=631023994280248#notebook/373927016902082/command/373927016902083)

**Note:** Databricks user name and password for viewing the code are available upon request.


## Contact
Email: [dingxiangonline@gmail.com](mailto:dingxiangonline@gmail.com)
