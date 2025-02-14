# Customer Segmentation Using K-Means Clustering

## Overview
This project focuses on **customer segmentation** using **K-Means clustering** on an **Online Retail II** dataset. The objective is to group customers based on their purchasing behavior to gain insights into different customer segments.

## Technologies Used
- **Programming Language:** Python  
- **Libraries:**
  - numpy & pandas (data manipulation)
  - scikit-learn (machine learning)
  - seaborn & matplotlib (data visualization)
- **Tools:** Jupyter Notebook

## Dataset
- The dataset used is **Online Retail II**, containing transaction details for different customers.
- Preprocessing steps were performed to clean the data and handle missing values.

## Steps in the Project
1. **Data Cleaning & Preprocessing**
   - Identified and handled missing values.
   - Standardized numerical features using `StandardScaler`.
2. **Feature Engineering**
   - Extracted relevant features to improve clustering performance.
3. **Model Training & Evaluation**
   - Applied **K-Means Clustering** using `scikit-learn`.
   - Used the **Elbow Method** to determine the optimal number of clusters.
4. **Data Visualization & Analysis**
   - Created scatter plots and cluster heatmaps to interpret customer groups.



## Results
- The model successfully segmented customers into distinct groups based on their purchasing patterns.
- Visualizations provided insights into high-value and low-value customer clusters.

## Future Improvements
- Apply **DBSCAN** or **Hierarchical Clustering** for comparison.
- Incorporate **RFM (Recency, Frequency, Monetary) Analysis** for better segmentation.
- Deploy the clustering model as a web dashboard.

## License
This project is open-source and available under the **MIT License**.

