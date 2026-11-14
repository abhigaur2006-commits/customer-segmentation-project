# Customer Segmentation Project

Customer segmentation using RFM analysis and K-Means clustering on the Superstore sales dataset.

## What It Does
- Builds **Recency, Frequency and Monetary (RFM)** features for every customer
- Adds demographic context: customer segment (Consumer, Corporate, Home Office) and region
- Scales the data and chooses the number of clusters with the **elbow method** and **silhouette score**
- Clusters customers with **K-Means** (k = [your k]) and profiles each segment
- Visualizes the segments in 2D and 3D scatter plots

## Customer Segments Found
| Cluster | Name | Customers | Avg Recency (days) | Avg Orders | Avg Spend |
|---|---|---|---|---|---|
| 0 | [name] | [x] | [x] | [x] | $[x] |
| 1 | [name] | [x] | [x] | [x] | $[x] |
| 2 | [name] | [x] | [x] | [x] | $[x] |
| 3 | [name] | [x] | [x] | [x] | $[x] |

## Recommendations
- Reward loyal high-value customers with loyalty programs
- Win back inactive customers with discount offers
- Encourage new customers to buy again
- Target big occasional spenders with bundles

## How to Run
1. Open `Customer_Segmentation_Project.ipynb` in Google Colab
2. Upload `train.csv` to the Files panel
3. Click Runtime -> Run all

## Dataset
[Superstore Sales (Kaggle)](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)

## Tools
Python, Pandas, NumPy, scikit-learn, Plotly

## Author
Abhinav Gaur
