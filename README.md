### Name: Priyanshu Kumar
### Company: CODTECH IT SOLUTIONS
### ID: CT08DS6396
### Domain: Data Analytics
### Duration:  August 2024 to September 2024
### Mentor: Muzammil Ahmed

---

# Customer Segmentation and Analysis using K-Means Clustering

## Project Overview
This project aims to perform customer segmentation using the K-Means clustering algorithm. Customer segmentation is a crucial task for businesses to understand their customer base and tailor marketing strategies accordingly. By dividing customers into distinct groups based on their behavior and demographic attributes, businesses can create personalized marketing plans and improve customer retention.

The analysis is conducted on the **Mall Customers Dataset**, which contains demographic information like age, annual income, and spending scores of mall customers.

## Dataset
The dataset used in this project is `Mall_Customers.csv`, which includes the following columns:
- **CustomerID**: Unique identifier for each customer
- **Gender**: The gender of the customer (Male/Female)
- **Age**: Age of the customer
- **Annual Income (k$)**: Annual income of the customer in thousand dollars
- **Spending Score (1-100)**: Score assigned to the customer based on their spending behavior

## Project Objectives
- **Data Cleaning**: Handle missing values and correct any inconsistencies in the dataset.
- **Exploratory Data Analysis (EDA)**: Perform descriptive statistics and visualizations to understand customer behavior.
- **K-Means Clustering**: Apply the K-Means algorithm to segment customers based on selected features.
- **Cluster Analysis**: Interpret the results to profile the different customer segments.
  
## Tools and Libraries
The following tools and libraries were used in this project:
- **Python**: Programming language used for data analysis and machine learning.
- **Pandas**: Data manipulation library for handling datasets.
- **NumPy**: Numerical library for array and mathematical operations.
- **Matplotlib** & **Seaborn**: Data visualization libraries used for creating plots and charts.
- **Scikit-learn**: Machine learning library used to implement the K-Means algorithm.

## Key Steps
1. **Data Preprocessing**:  
   - Clean the dataset by handling missing values, encoding categorical variables (Gender), and normalizing the data.
   
2. **Exploratory Data Analysis (EDA)**:  
   - Analyze the demographic distribution (age, income, gender) and spending scores using visualizations.
   - Identify relationships between different features and find outliers that could affect clustering.
   
3. **K-Means Clustering**:  
   - Use the Elbow Method to determine the optimal number of clusters.
   - Apply K-Means clustering to segment the customers.
   
4. **Cluster Interpretation**:  
   - Profile each cluster by analyzing the centroid of the clusters and understanding the key attributes that define each group.
   - Visualize the clusters using 2D and 3D scatter plots.

## Results
- The K-Means algorithm successfully segmented the customers into distinct clusters based on their age, annual income, and spending scores.
- **Cluster Profiles**:
  - **Cluster 1**: High-income, high-spending customers (Premium segment).
  - **Cluster 2**: Younger customers with moderate income and spending scores.
  - **Cluster 3**: Older customers with low income and spending scores.
  - **Cluster 4**: Customers with low income and high spending scores.

The segmentation helps in identifying high-value customers and those who may require targeted marketing to improve their spending behavior.

## Insights and Conclusion
- Customers with high spending scores and incomes represent a premium segment that can be targeted for exclusive offers.
- Low-income and low-spending customers may require different engagement strategies to boost retention and spending.
- This segmentation provides actionable insights for personalized marketing and customer relationship management.

## Future Improvements
- Incorporating more features such as customer purchase history, geographical location, and online behavior could enhance the clustering model.
- Experimenting with other clustering algorithms like Hierarchical Clustering or DBSCAN to compare the results.

## Project Files
- **Customer Segmentation.ipynb**: Jupyter notebook containing the code for the entire analysis.
- **Mall_Customers.csv**: Dataset used for the project.
  
## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Priyanshu9528/Customer-Segmentation-KMeans.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook and run the cells to see the analysis.

## Author
- **Priyanshu Kumar**  
  Enthusiastic and detail-oriented Data Analyst with a strong foundation in Python, SQL, and Data Visualization. Connect with me on [LinkedIn](https://www.linkedin.com/in/priyanshu-kumar-23b1a1220/) and explore more of my work on [GitHub](https://github.com/Priyanshu9528).

---
