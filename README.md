# Customer-Segmentation-using-RFM-Analysis-K-Means-Clustering

# Dataset link:https://www.kaggle.com/datasets/yasserh/customer-segmentation-dataset

This project uses **RFM analysis** (Recency, Frequency, Monetary) and **K-Means clustering** to segment customers based on their purchasing behavior.

## Steps

1. **Data Cleaning**
   - Remove missing CustomerIDs
   - Drop canceled orders
   - Create `TotalAmount = Quantity × UnitPrice`

2. **RFM Calculation**
   - Recency: days since last purchase
   - Frequency: number of unique invoices
   - Monetary: total spending

3. **Preprocessing**
   - Standardize RFM features
   - Determine optimal clusters using the Elbow method

4. **Clustering**
   - Apply K-Means to RFM data
   - Assign cluster labels

5. **Visualization**
   - Elbow plot
   - RFM pairplot
   - PCA 2D cluster plot
   - Cluster profile summary

## Output
- RFM table per customer  
- Cluster labels  
- Visualizations  
- Basic behavioral insights for each segment
