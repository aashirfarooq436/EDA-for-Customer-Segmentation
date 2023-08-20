## Project Report: Customer Segmentation for TechElectro Inc.

##### Client Name: TechElectro Inc.
##### Company Name: DataGenius Analytics

### Project Description:
TechElectro Inc., a prominent electronics retailer, aims to optimize its marketing strategies and enhance customer satisfaction through data-driven insights. DataGenius Analytics has been selected to conduct an exploratory data analysis (EDA) project that will help TechElectro Inc. discover meaningful patterns and segment their customers based on their characteristics.

### Dataset:
The dataset provided by TechElectro Inc. contains customer information, purchase history, demographics, and preferences. It consists of 500 customers' data with the following columns:

1. CustomerID
2. Age
3. Gender
4. MaritalStatus
5. AnnualIncome (USD)
6. TotalPurchases
7. PreferredCategory
8. Project Steps:

#### 1. Data Collection:
The dataset was obtained from TechElectro Inc., containing customer information, purchase history, demographics, and preferences.

#### 2. Data Cleaning:
The dataset was cleaned by handling missing values, duplicates, and inconsistencies. This ensures that the data is accurate and reliable for analysis.

#### 3. Data Preprocessing:
Numerical columns were standardized using the StandardScaler. Categorical columns ("Gender," "MaritalStatus," "PreferredCategory") were encoded using label encoding.

#### 4. Exploratory Data Analysis (EDA):
Various visualizations were generated to explore the data and uncover patterns:

1. Distribution plots for Age, Annual Income, and Total Purchases
2. Scatter plot of Age vs. Annual Income
3. 2D density plot of Age vs. Annual Income
4. Box plots of Annual Income and Total Purchases by Preferred Category
5. Pair plot to visualize relationships between numerical variables
6. Count plots for Preferred Category by Gender
#### 5. Customer Segmentation:
K-means clustering was used to segment customers based on their characteristics. The optimal number of clusters was determined using the elbow method. Customers were assigned to clusters, and the distribution of customers across clusters was visualized using a count plot.

### Project Outcome:
The project aimed to provide valuable insights to TechElectro Inc. for optimizing marketing strategies and enhancing customer satisfaction. The final deliverables included:

1. Cleaned and preprocessed dataset
2. Exploratory Data Analysis (EDA) report and visualizations
3. K-means clustering results and cluster distribution visualization
4. Recommendations for marketing strategies based on customer segments
### Conclusion:
Through this project, TechElectro Inc. gained insights into customer preferences and behavior. The customer segmentation allowed them to tailor their marketing strategies to different customer segments, enhancing the effectiveness of their campaigns and improving customer satisfaction.