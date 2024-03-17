# Machine Learning Training Notebooks
This repository contains notebooks that have been used to improve machine learning skills.

</br>

# Content Table
### Clustering
- [Agglomerative Clustering](Clustering%20-%20Agglomerative%20Clustering/7%20-%20Agglomerative%20Clustering.ipynb)
- [DBSCAN](Clustering%20-%20DBSCAN/7%20-%20DBSCAN.ipynb)
- [EM Algorithm](Clustering%20-%20EM%20Algorithm/7%20-%20EM%20Algorithm.ipynb)
- [K-Means](Clustering%20-%20K-Means/7%20-%20K-Means.ipynb) 7 - K-Means - Customer Segmentation.ipynb
- [Gradient Descent](Gradient%20Descent/%20-%20Gradient%20Descent%20Medical%20Health.ipynb)
- [Annoy Product Search](Text%20-%20Annoy%20Product%20Search/14%20-%20Text%20-%20Annoy%20Product%20Search.ipynb)
- [Annoy](Text%20-%20Text%20-%20Annoy/14%20-%20Text%20-%20Annoy.ipynb)
- [TF-IDF](Text%20-%20Text%20-%20TF-IDF/14%20-%20Text%20-%20TF-IDF.ipynb)
- [Time Series](Text%20-%20Time%20Series/15%20-%20Text%20-%20Time%20Series.ipynb)

### Clustering
- [1 - Marketing Web Scraping](#1---marketing-web-scraping) (Scraping, EDA, Power BI)
- [2 - Car Price Predict](#2---car-price-predict) (EDA, Feature Engineering, Machine Learning)

### Text
- [3 - Report Automation](#3---report-automation) (MySQL, Python)
- [4 - Sales Management](#4---sales-management) (SQL, EDA, Plotly Dash)
- [5 - Recommendation System](#5---recommendation-system) (EDA, Feature Engineering, Machine Learning, Python)

</br>


# Portfolio Projects
## 1 - Marketing Web Scraping 
<code>[Script](1%20-%20Marketing%20Web%20Scraping/Marketing%20Web%20Scraping.py)</code>
<code>[Dashboard](1%20-%20Marketing%20Web%20Scraping/Marketing%20Web%20Scraping%20Power%20BI%20Demo.pbix)</code>

### - Description - 
A parser script that collects data from the Semrush platform without using an API (is an optional service). The script runs on the chrome driver, logs into the platform and parses all the necessary reports. There are 28 reports per domain, including semiannual historical data (separated by months), all the information about the traffic: bounce, splits by devices, traffic source, unique users, conversion percentage, staying duration, search engine hits, backlinks etc.  The total number of reports is ~ 22 400, the output number of reports is 6. The script processes the empty reports, assigns the necessary attributes and generates new ones (missing indicators). The prepared reports are uploaded to the prepared dashboard to visualize all the data.

### - Results - 
Reporting automation. Data visualization. Thanks to parsing of historical data we managed to save on platform fees (monthly expenses for plan + tax and Traffic Analytics API + tax).

### - Skills -
report automation, data parser, data cleaning, feature engineering, data visualization

### - Technology -
Python, Pandas, Numpy, Selenium, Power BI

</br>

[Scroll up](#content-table)

</br>

## 3 - Report Automation
<code>[V7001 (Py)](3%20-%20Report%20Automation%20Script/V7001.py)</code>
<code>[V7002 (Py)](3%20-%20Report%20Automation%20Script/V7002.py)</code>
<code>[V7003 (Py)](3%20-%20Report%20Automation%20Script/V7003.py)</code>
<code>[V7004 (Py)](3%20-%20Report%20Automation%20Script/V7004.py)</code>
<code>[V7001 (SQL)](3%20-%20Report%20Automation%20Script/v7001_sql.sql)</code>
<code>[V7003 (SQL)](3%20-%20Report%20Automation%20Script/v7003_sql.sql)</code>

### - Description - 
A family of scripts for automating reports on closed and open trades, deposits and withdrawals, and hedge fund information for a national bank. A bot for sending reports to everyone assigned.

### - Skills - 
SQL Query, report automation.

### - Technology - 
Python, Pandas, Numpy, mysql.connector, openpyxl, MySQL.

### - Results -
Creation of a script to automate reporting.

</br>

[Scroll up](#content-table)

</br>

### 4 - Sales Management
<code>[Notebook](4%20-%20Sales%20Management/Sales%20Management.ipynb)</code>
<code>[PlotlyDash (Files)](4%20-%20Sales%20Management/Plotly%20Dash/index.py)</code>
<code>[Power BI](4%20-%20Sales%20Management/Sales%20Management%20Dashboard.pbix)</code>

### - Description - 
To increase profits by prioritizing the placement of goods in the storage area, it is necessary to set the profitability of goods by region. Additionally, the cost of transporting goods is reduced.
For this purpose, a request was formed to unload the data. Collection, analysis and preprocessing was done using the python programming language. Dashboards in Power BI and the created web service were prepared.

### - Skills - 
data cleaning, data analysis, descriptive statistics, central limit theorem, hypothesis testing, data visualization, feature engineering, machine learning.

### - Technology - 
SQL (SSMS, clearing tables), Python (data preprocessing, data preparation for the dashboard, pandas, numpy, seaborn, itertools, matplotlib, dash, plotly.express), Jupyter Lab (creating the plotly dash app)
Power BI (Creating an interactive dashboard), Heroku (Upload the Plotly Dash App)

### - Results - 
Automated data collection, preprocessing of received data, updating dashboards for visualization.

</br>

[Scroll up](#content-table)
