# Customer Segmentation and Personality Analysis Using KMeans Clustering

In this project, I explored how unsupervised learning can be used to segment customers based on demographic and behavioral data. The goal was to identify distinct customer groups that could help businesses make better marketing and product decisions.

## Overview

The dataset contains information about individual customers, including:

- Age, income, education
- Marital status and family structure
- Spending behavior across different product categories

I used this data to group customers into segments using KMeans clustering.

## Steps Taken

1. **Data Cleaning and Preprocessing**  
   I handled missing values, removed irrelevant columns, and created new features like family size and total number of children.

2. **Feature Scaling**  
   StandardScaler was used to normalize the numerical features to ensure all variables contributed equally to the clustering.

3. **Finding Optimal Clusters**  
   I used the Elbow Method and Silhouette Score to determine the best number of clusters for the dataset.

4. **Applying KMeans Clustering**  
   I trained the KMeans model and added the cluster labels to the dataset for further analysis.

5. **Dimensionality Reduction and Visualization**  
   PCA was used to reduce the data to 2 components for easier visualization of clusters.

6. **Cluster Analysis**  
   I analyzed the average age, income, spending, and family size in each cluster to understand how they differ.

## Key Observations

- Some customer groups have high spending with smaller families, while others have larger families but lower average spending.
- A few clusters showed unique patterns in spending or income, which could be useful for targeted marketing.
- The visualizations helped confirm that the clusters formed meaningful and distinguishable groups.

## Technologies Used

- Python 3.10  
- pandas, numpy  
- seaborn, matplotlib  
- scikit-learn (StandardScaler, KMeans, PCA)  
- yellowbrick (for visualizing clustering metrics)

## How to Run

1. Download or clone the repository  
2. Ensure the dataset (`marketing_campaign.csv`) is in the same folder as the notebook  
3. Install required libraries:
   ```bash
   pip install pandas seaborn matplotlib scikit-learn yellowbrick
   ```
4. Open the notebook in Jupyter and run the cells in order from top to bottom.
5. You will see the cleaned data, clustering process, and final analysis results as you go through the notebook.

## Files Included

- `Customer_Segmentation_KMeans.ipynb` – Jupyter notebook containing the full code, visualizations, and analysis  
- `marketing_campaign.csv` – The dataset used for customer segmentation  
- `requirements.txt` – List of Python libraries required to run the project  
- `README.md` – Project overview and documentation  
- `.gitignore` – Optional file to exclude unnecessary system or environment files


## Final Thoughts

This project gave me hands-on experience with clustering techniques and how they can be applied in real-world marketing scenarios. It also helped me improve my skills in data preprocessing, visualization, and model evaluation.
I developed this project as part of my personal learning journey in data science and machine learning.

---
> Developed by Amirhosein Ashrafian — Published in July 2025
