# customer-segmentation-kmeans
Customer Segmentation using K-Means Clustering: Analyzing brand preferences across 30K shoppers. Includes KNN imputation for missing data, feature scaling, and cluster profiling.
# Customer Segmentation using K-Means Clustering  
*Analyzing Brand Preferences Across 30,000 Shoppers*  

---

## **Project Overview**  
**Objective**: Identify distinct customer segments based on brand engagement patterns to enable targeted marketing strategies.  

**Key Features**:  
✔ K-Means clustering with optimal cluster detection (Elbow Method)  
✔ Automated handling of missing data using KNN Imputer  
✔ Mixed-data preprocessing pipeline (numeric + categorical)  
✔ Interpretable cluster naming based on brand affinities  

---

## **Technical Implementation**  

### **1. Data Preparation**  
- **Dataset**: 30,000 records × 37 features (brand metrics + demographics)  
- **Missing Values**: KNN-imputed for `Gender` column  


### **2. Clustering
Algorithm: K-Means (k=4 optimized via Elbow Method)

Cluster Profiles:

Cluster      	Name	                Dominant Brands
 0            Premium Trendsetters	Dior, Scabal, Jordan
 1	          Casual Buyers        	Low engagement across brands
 2            Tech & Gear Fans	    LG, Microsoft, Wrangler
 3	          Fila Loyalists	      Extreme Fila preference
