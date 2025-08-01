# Bank Customer Segmentation

This project demonstrates customer segmentation for a bank using unsupervised machine learning techniques, specifically K-Means clustering and Principal Component Analysis (PCA). The analysis is performed on a dataset of banking customers, with the goal of identifying distinct customer segments based on their financial behaviors and characteristics.

## Project Structure
- `Bank Customer Segmentation.ipynb`: Main Jupyter notebook containing all code, analysis, and visualizations.
- `Bank_data.csv`: Dataset from Kaggle used for analysis. 

## Workflow Overview
1. **Import Libraries and Data**: Load required Python libraries and the customer dataset.
2. **Exploratory Data Analysis (EDA)**: Analyze data structure, handle missing values, detect outliers, and visualize distributions.
3. **Correlation Analysis**: Examine relationships between variables using a correlation matrix.
4. **Data Standardization**: Standardize features for clustering.
5. **K-Means Clustering**:
   - Use the Elbow Method to determine the optimal number of clusters.
   - Apply K-Means to segment customers.
   - Visualize cluster centroids and interpret segment characteristics.
6. **Cluster Insights**: Summarize the main features and behaviors of each customer segment.
7. **Prediction**: Assign cluster labels to each customer and analyze segment distribution.
8. **Dimensionality Reduction (PCA)**: Reduce data to principal components for visualization.
9. **Cluster Visualization**: Display clusters in principal component space.
10. **Conclusion**: Discuss the business value of customer segmentation for banks.

## Key Technologies
- Python (pandas, numpy, seaborn, matplotlib, scikit-learn)
- Jupyter Notebook

## How to Run
1. Open `Bank Customer Segmentation.ipynb` in Jupyter Notebook or VS Code.
2. Ensure `Bank_data.csv` is in the same directory.
3. Run each cell sequentially to reproduce the analysis and visualizations.

## Insights
- The notebook identifies four distinct customer segments based on financial activity and credit behavior.
- Each segment is described in detail, providing actionable insights for marketing, product development, and customer relationship management.

## Author
Agustín Rojas  
[LinkedIn](https://www.linkedin.com/in/agust%C3%ADnsilviorojas/)

---
For questions or feedback, please contact: agustinsilviorojas@outlook.com.ar
