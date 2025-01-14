# Customer Segmentation for Retail Optimization

## Overview
This project focuses on analyzing customer data from a retail company to identify behavioral patterns and segment customers into distinct groups. These insights enable the company to:
- Strategically plan marketing campaigns.
- Identify target audiences for new products.
- Recognize high-value customers and optimize customer engagement strategies.

**Dataset Source**: [Customer Personality Analysis](https://www.kaggle.com/imakash3011/customer-personality-analysis)

---

## Key Highlights
- **Industry Application**: Retail customer segmentation and behavior analysis.
- **Techniques Used**: Data preprocessing, exploratory data analysis (EDA), clustering using K-Means, and actionable insights generation.
- **Output**: Detailed customer clusters with actionable recommendations for business optimization.

---

## Project Workflow
### 1. **Introduction**
   - A brief overview of the objectives, dataset, and project relevance.

### 2. **Data Preprocessing**
   - **Feature Engineering**: Creating meaningful features for analysis.
   - **Data Cleaning**: Handling missing values, removing outliers, and dropping irrelevant variables.
   - **Categorical Transformation**: Encoding categorical variables for clustering.

### 3. **Exploratory Data Analysis (EDA)**
   - Visualized feature distributions and relationships.
   - Identified behavioral trends and purchasing patterns across customers.

### 4. **Clustering**
   - **Scaling**: Standardized features to improve clustering efficiency.
   - **Dimensionality Reduction**: Applied Principal Component Analysis (PCA) to reduce feature complexity.
   - **Clustering Algorithm**: Used K-Means to group customers into distinct clusters.

### 5. **Evaluation and Insights**
   - Analyzed the characteristics of each cluster and derived actionable business recommendations.

---

## Clustering Insights
### **Cluster 1**:
- Comprises ~20% of customers.
- Medium income group.
- All customers have at least one child.
- Highly responsive to discounts.
- Prefers non-essential items (e.g., wine, gold).

### **Cluster 2**:
- Largest segment (~44% of customers).
- Lower income group with minimal spending habits.
- Majority lack higher education.
- Slightly younger demographic.

### **Cluster 3**:
- Represents ~36% of customers.
- High-income group with significant spending.
- Most customers have zero or one child.
- Minimal interest in discounts.

---

## Recommendations
1. **Target Cluster 1**:
   - Focus marketing efforts on offering discounts on non-essential items.
   - Design campaigns tailored to this group’s sensitivity to price reductions.

2. **Engage Cluster 3**:
   - Provide personalized services and premium offers to maintain loyalty.
   - Avoid discount-heavy campaigns, as they are less effective for this segment.

3. **Optimize Campaigns**:
   - Exclude Cluster 3 from discount promotions to reduce marketing inefficiencies.
   - Concentrate on enhancing customer satisfaction for high-value customers.

---

## Repository Structure
```plaintext
├── marketing_campaign.csv       # Dataset containing customer information
├── customer_segmentation.ipynb  # Jupyter Notebook with the complete analysis
├── README.md                    # Project documentation
