Data-Science-Assignment: eCommerce Transactions Dataset

**Overview**
This repository contains the code and results for a data science assignment based on an eCommerce transactions dataset. The assignment consists of three tasks: Exploratory Data Analysis (EDA), Lookalike Model, and Customer Segmentation (Clustering).

**File Descriptions**

**Customers.csv:** Contains customer-related information such as customer IDs, names, regions, and signup dates.

**Products.csv:** Includes product data like product IDs, names, categories, and prices.

**Transactions.csv:** Records transaction details, including transaction IDs, product IDs, customer IDs, quantities, total values, and prices.

**Notebooks:**

**FirstName_LastName_Task1_EDA.ipynb:** Jupyter notebook where you perform Exploratory Data Analysis (EDA), including data cleaning, visualization, and generating business insights.
**FirstName_LastName_Task2_Lookalike.ipynb:** Jupyter notebook where you develop the Lookalike Model to recommend similar customers based on purchase behavior.
**FirstName_LastName_Task3_Clustering.ipynb:** Jupyter notebook for Customer Segmentation through clustering techniques, analyzing customer behavior patterns.

**Reports:**

**FirstName_LastName_EDA_Report.pdf:** PDF document summarizing the findings from the EDA task, including key insights derived from the data.
**FirstName_LastName_Clustering_Report.pdf:** PDF document discussing the results of the customer segmentation (clustering), including metrics like Davies-Bouldin Index and Silhouette Score.
**Lookalike_Results.csv:** A CSV file that stores the Lookalike Model's recommendations, showing the top 3 similar customers for each of the first 20 customers with corresponding similarity scores.

**requirements.txt:** A text file listing all the Python dependencies needed to run the notebooks (e.g., pandas, numpy, matplotlib, seaborn, etc.).

README.md: This file! It provides a project overview, instructions on how to run the notebooks, and details on the project structure.

**File Naming Convention**

**Notebooks:** The notebook names follow the format FirstName_LastName_Task<task_number>.ipynb. For example:

FirstName_LastName_Task1_EDA.ipynb for Task 1 (Exploratory Data Analysis).
FirstName_LastName_Task2_Lookalike.ipynb for Task 2 (Lookalike Model).
FirstName_LastName_Task3_Clustering.ipynb for Task 3 (Customer Segmentation).

**Reports:** The report files follow the format FirstName_LastName_<task_name>_Report.pdf. For example:

FirstName_LastName_EDA_Report.pdf for the EDA task report.
FirstName_LastName_Clustering_Report.pdf for the Clustering report.

**Lookalike Results:** The file for storing the lookalike model’s output is named Lookalike_Results.csv, which holds the recommendations and similarity scores for each customer.


**Tasks**

****Task 1:** Exploratory Data Analysis (EDA) and Business Insights**

**Objective:**
Perform EDA on the provided eCommerce dataset, which includes customer, product, and transaction data. Derive meaningful business insights based on the analysis.

**Steps:**

Perform EDA on the dataset.
Create relevant visualizations (e.g., customer distribution by region, top-selling products, revenue by category).
Derive at least five business insights from the analysis.

**Deliverables:**
A Jupyter Notebook containing the EDA code and visualizations.
A PDF report summarizing the business insights.

****Task 2**: Lookalike Model**

**Objective:**
Build a Lookalike Model that recommends similar customers based on their profile and transaction history.

**Steps:**

Use customer and product information to calculate similarity scores.
Recommend the top 3 similar customers for each of the first 20 customers.
Save the results in a CSV file that maps each customer to their most similar customers and scores.

**Deliverables:**
A Jupyter Notebook containing the Lookalike Model code.
A CSV file with the lookalike recommendations.

****Task 3**: Customer Segmentation / Clustering**

**Objective:**
Perform customer segmentation using clustering techniques. Use both customer profile and transaction data to segment customers into distinct clusters.

**Steps:**

Use clustering algorithms (e.g., K-Means) to segment customers based on relevant features.
Evaluate the clustering results using metrics like Davies-Bouldin Index and Silhouette Score.
Visualize the clusters using 2D and 3D plots.

**Deliverables:**
A Jupyter Notebook containing the clustering code and visualizations.
A CSV file with the customer segmentation results.

**Evaluation Criteria**

**Task 1: EDA**
**Clarity of Insights:** How well the insights are derived and how actionable they are for the business.
**Visualizations:** Use of appropriate plots to visualize the data and support the insights.

**Task 2: Lookalike Model**
**Model Accuracy:** How well the similarity score matches customer profiles.
**Quality of Recommendations:** Relevance of the top 3 recommended customers.
**Clarity of Code:** Code readability and explanation in the Jupyter Notebook.

**Task 3: Customer Segmentation**
**Clustering Logic:** Appropriateness of the chosen clustering algorithm and features.
**Clustering Metrics:** Evaluation using metrics like Davies-Bouldin Index and Silhouette Score.
**Visual Representation:** Clarity of the cluster visualizations.

**Conclusion**

This project has successfully analyzed eCommerce transaction data to uncover meaningful patterns and insights. By building a lookalike model and segmenting the customer base, the project paves the way for more effective marketing strategies. Future work may include adding more data sources, exploring advanced modeling techniques, or refining the segmentation through deeper feature engineering.

