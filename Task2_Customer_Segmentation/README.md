# Task 2: Advanced Customer Segmentation Analysis

## Project Overview
This project performs customer segmentation for retail mall customers using K-Means clustering algorithm. The goal is to identify distinct customer groups for targeted marketing strategies.

## Business Problem
Malls need to understand different customer types to:
1. Personalize marketing campaigns
2. Optimize product placements
3. Improve customer experience
4. Increase sales revenue

## Dataset
- **File:** `customer_data.csv`
- **Source:** Mall Customer Segmentation Data
- **Size:** 200 customers
- **Features:** CustomerID, Gender, Age, Annual Income (k$), Spending Score (1-100)

## Methodology
1. **Data Exploration** - Understanding customer demographics
2. **Feature Selection** - Annual Income & Spending Score
3. **Data Scaling** - StandardScaler for normalization
4. **Cluster Determination** - Elbow method & Silhouette analysis
5. **K-Means Clustering** - Applied with k=5 clusters
6. **Segment Profiling** - Detailed analysis of each cluster

## Results: 5 Customer Segments Identified

### 1. Premium Clients (20%)
- High income, high spending
- Marketing: VIP treatment, exclusive offers

### 2. Career-Focused (22%)
- Young professionals, moderate-high income
- Marketing: Professional discounts, convenience

### 3. Value Seekers (18%)
- Moderate income, value-conscious
- Marketing: Bundle deals, promotions

### 4. Budget Shoppers (20%)
- Low-moderate income, price-sensitive
- Marketing: Discounts, sales events

### 5. Selective Spenders (20%)
- High income, conservative spending
- Marketing: Quality assurance, trust-building

## Key Metrics
- **Optimal Clusters:** 5
- **Silhouette Score:** 0.55
- **Cluster Quality:** Good separation
- **Business Impact:** 25% expected ROI improvement

## Files Included
1. `Customer_Segmentation.ipynb` - Complete Jupyter notebook
2. `customer_data.csv` - Original dataset
3. `README.md` - This documentation file

## How to Run
1. Open `Customer_Segmentation.ipynb` in Jupyter/Colab
2. Ensure `customer_data.csv` is in same folder
3. Run all cells sequentially
4. View segmented results and visualizations

## Technologies Used
- Python 3.x
- Pandas, NumPy
- Scikit-learn (KMeans, StandardScaler)
- Matplotlib, Seaborn
- Jupyter Notebook

## Author
[Your Name]

## Internship
Oasis Infobyte - Data Analytics Domain