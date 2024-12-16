# 🔍 **Customer Segmentation Analysis**

## 📝 **Project Overview**  
As a **Data Scientist** at the **Bank of Mavenland**, I was tasked with segmenting the bank's current customers.
The goal was to **identify distinct customer groups** and recommend tailored **products or services** for each segment based on data analysis and clustering techniques.

## 🎯 **The Assignment**  
The product team aimed to better understand their customer base and deliver solutions that cater to different segments.  
- **Objective**: Segment the bank's current customers using clustering methods.  
- **Outcome**: Provide recommendations for potential new products or services tailored to each segment.

## 🚀 **Project Objectives**  
1. **Prepare the data**  
2. **Cluster the customers (Round 1)**  
3. **Cluster the customers (Round 2)**  
4. **Explore the clusters and make recommendations**  

## 🛠️ **Technologies Used**  
- **Python**  
- **Pandas**  
- **Scikit-Learn**  
- **Matplotlib / Seaborn**  
- **Jupyter Notebook**  

## 📈 **Results**  
The project successfully segmented customers into distinct clusters, allowing the bank to make **data-driven decisions**.
Tailored recommendations for new products and services were provided for each segment to enhance customer satisfaction and drive business growth.

## 🚀 **Objective 1: Prepare the Data for Modeling**  
The first objective is to prepare the data for modeling by:  
- Selecting a subset of fields.  
- Ensuring all fields are numeric.  
- Exploring distributions of the selected features.  
- Engineering a new feature to enhance segmentation quality.

Read the "Bank_Churn.csv" file and preview the top 5 rows
1.  **Read and Preview the Data**  
   - Load the **`Bank_Churn.csv`** file.  
   - Preview the **top 5 rows** to understand the structure of the dataset.
   ![Top 5 Rows](screenshots/top_5_rows.png)

2. **Create a DataFrame**  
   - Include all fields except **`CustomerId`**, **`Surname`**, and **`Exited`**.
      ![Create a DataFrame](screenshots/dataFrame.png) 

3. **Make All Text Fields Numeric**  
   - Convert categorical or text-based fields into numerical format using techniques such as **label encoding** or **one-hot encoding**.
     ![Fields Numeric](screenshots/fields_mumeric.png)
     
4. **Explore the Data**  
   - Analyze the data by examining:  
     - Minimum and maximum values of each column.  
       ![FMinimum and maximum values](screenshots/min_max_value.png)
     - The distribution of numerical features.
       ![distribution of numerical](screenshots/distribution.png)

5. **Engineer a New Feature**  
   - Create a new feature called **`ProductsPerYear`**:  
     - This feature can be calculated by dividing the total number of products by the number of years the customer has been with the bank (e.g., `NumOfProducts / Tenure`).

   
