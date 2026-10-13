# Customer Segmentation Using K-Means Clustering

## Project Overview
This project applies K-Means clustering to a mall customer dataset to identify customer groups based on age, annual income, and spending score.

## Objectives
- Explore and understand customer data.
- Prepare numerical features for clustering.
- Use the Elbow Method to help select the number of clusters.
- Apply K-Means clustering to group customers.
- Visualize and interpret the resulting customer segments.

## Dataset
The project uses the Mall Customers dataset, containing 200 customer records and five columns:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

Dataset source: https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python

## Tools and Libraries
- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Scikit-learn

## Methodology
1. Loaded and inspected the dataset.
2. Checked data quality.
3. Selected Age, Annual Income, and Spending Score as clustering features.
4. Standardized the selected features using StandardScaler.
5. Used the Elbow Method to select four clusters.
6. Trained a K-Means model.
7. Analyzed cluster sizes and average feature values.
8. Created visualizations to compare customer segments.

## Results
The model produced four customer clusters:

| Cluster | Number of Customers |
|---|---:|
| 0 | 65 |
| 1 | 40 |
| 2 | 57 |
| 3 | 38 |
| **Total** | **200** |

The clusters show different average ages, incomes, and spending scores. Cluster 1 has a high average income and spending score, while Cluster 3 has a high average income but a low spending score.

## Visualizations
The `visualizations` folder contains:
- Customer segments by income and spending
- Average customer age by cluster
- Average annual income by cluster
- Average spending score by cluster

## Conclusion
K-Means clustering helped identify four customer segments with different characteristics. These groups can support further customer behaviour analysis and help businesses explore more targeted marketing strategies.

## Project Structure
```text
Customer_segmentation/
├── dataset/
│   └── Mall_Customers.csv
├── notebook/
│   └── Customer_Segmentation.ipynb
├── visualizations/
└── README.md
```

## Author
VISHALI MALLELA

## Internship
CODTECH Data Science Internship