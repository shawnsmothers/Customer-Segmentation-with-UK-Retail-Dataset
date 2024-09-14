# Customer-Segmentation-with-UK-Retail-Dataset
K-Mean Clustering Machine Learning on Customers 

This project focuses on customer segmentation using the UK Retail Dataset to identify distinct customer groups and optimize marketing strategies through data-driven insights. The primary technique used for clustering was **K-Means Clustering**, which helps uncover meaningful patterns in customer behavior.

## Project Overview

The objective of this project is to analyze customer data, identify different customer segments, and visualize these segments to understand their characteristics and purchasing behaviors.

## Key Steps

1. **Data Cleaning and Exploratory Analysis:**
   - Cleaned the dataset to handle missing values and irrelevant data.
   - Conducted exploratory data analysis (EDA) to gain initial insights into the data distribution and key patterns.

2. **Handling Outliers:**
   - Separated the data into two distinct datasets: one containing outliers and the other with non-outliers.
   - This approach ensured that the clustering models could be more precise and focused, minimizing the impact of extreme values.

3. **Building Clustering Models:**
   - Applied **K-Means Clustering** to both datasets (outliers and non-outliers) to create separate models.
   - Analyzed the clustering results to identify patterns and segment customers effectively.

4. **Visualization:**
   - Unified the datasets to create a final visualization using a bar chart with cluster labels and the monetary value per 100 pounds.
   - This visualization highlights the different customer segments, their size, and their corresponding monetary values, aiding in strategic decision-making.

## Results

- Successfully segmented customers into different clusters based on purchasing behavior, recency, frequency, and monetary value.
- Provided insights into customer groups, such as "VIP High-Spenders," "Loyal Regulars," and "At-Risk or Inactive," enabling targeted marketing and retention strategies.

## Conclusion

This project demonstrates how K-Means Clustering can be effectively applied to retail data to uncover actionable insights about customer behavior. By handling outliers separately and visualizing the results, the project provides a comprehensive understanding of different customer segments and their value to the business.

## Tools and Technologies Used

- **Python**: Pandas, NumPy, Seaborn, Matplotlib, Scikit-Learn
- **Jupyter Notebook**

## Future Improvements

- Incorporate additional features such as customer demographics or product categories.
- Explore other clustering techniques (e.g., DBSCAN, Hierarchical Clustering) to compare results.
- Implement machine learning models to predict customer lifetime value (CLV) and churn.
