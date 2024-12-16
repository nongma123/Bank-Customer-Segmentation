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

1. **Read and Preview the Data**  
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
       ![Minimum and maximum values](screenshots/min_max_value.png)
     - The distribution of numerical features.
       ![distribution of numerical](screenshots/distribution.png)

5. **Engineer a New Feature**  
   - Create a new feature called **`ProductsPerYear`**:  
      ![ProductsPerYear](screenshots/new_feature.png)

## 🚀 **Objective 2: Cluster the Customers (Round 1)**  
The second objective is to segment customers using **K-Means clustering**. The steps include:

1. **Standardize the Data**  
   - Scale the data so that each column has a **mean of 0** and a **standard deviation of 1**.  
     ![Standardize the Data](screenshots/Standardize_the_Data.png)
2. **Create an Inertia Plot**  
   - Fit **K-Means clustering models** on the standardized data for **2 to 15 clusters**.
     ![Create an Inertia Plot](screenshots/K-Means.png) 
   - Plot the inertia values to identify the optimal number of clusters using the **elbow method**.
     ![Plot the inertia values](screenshots/Plot_the_inertia.png)

3. **Fit the Optimal K-Means Model**  
   - Determine the elbow point from the inertia plot and use that value of **k** to fit the K-Means model.
     ![Optimal K-Means Model](screenshots/Optimal_K-Means.png) 

4. **Analyze the Clusters**  
   - Check the **number of customers** in each cluster to understand the cluster distribution.
     ![number of customers](screenshots/number_of_customers.png)  

5. **Interpret the Clusters**  
   - Create a **heat map** of cluster centers to visualize feature values for each cluster.
     ![heat map](screenshots/heat_map.png) 
   - Analyze and interpret the characteristics of the clusters.
     ![Analyze and interpre](screenshots/Analyze_and_interpre.png)

