# Customer Segmentation using K-Means Clustering

## Project Overview
This project focuses on using **K-Means Clustering**, an unsupervised machine learning algorithm, to group retail store customers based on their purchase history. The goal is to identify distinct customer segments to enable personalized marketing strategies and better customer relationship management.

## Dataset
The dataset contains customer purchase history, including features such as:
- **Customer ID**: Unique identifier for each customer
- **Annual Spending**: Total spending by the customer over a year
- **Purchase Frequency**: Number of purchases made by the customer
- **Average Basket Size**: Average value of each purchase
- **Other relevant attributes**

## Key Steps in the Project

1. **Data Preprocessing**
   - Handling missing values
   - Scaling numerical features using **StandardScaler**
   - Encoding categorical features (if any)

2. **Exploratory Data Analysis (EDA)**
   - Visualized purchase patterns and relationships between features
   - Analyzed correlations to identify influential factors

3. **K-Means Clustering**
   - Determined the optimal number of clusters using the **Elbow Method** and **Silhouette Score**
   - Applied the K-Means algorithm to cluster customers



## Tools and Technologies
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Clustering Algorithm**: K-Means
- **Visualization**: PCA plots, Cluster heatmaps

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/mukul2309/PRODIGY_ML_02.git
   ```

## Future Scope
- Incorporating additional customer behavior data, such as web browsing patterns
- Using advanced clustering techniques like DBSCAN or hierarchical clustering for comparison
- Building a dashboard for real-time segmentation insights

## Conclusion
This project highlights the power of clustering algorithms like K-Means in deriving meaningful insights from customer data. These insights can significantly improve marketing strategies and enhance customer satisfaction.
