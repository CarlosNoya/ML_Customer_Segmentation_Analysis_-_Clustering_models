# ML - Customer Segmentation with Clustering Models

### Overview

Project completed for **The Bridge Data Science bootcamp**, focuses on customer segmentation using unsupervised machine learning techniques, specifically clustering models. Exploring different clustering approaches, including KMeans, DBSCAN, and Agglomerative Clustering, and evaluate them based on sample, dendogram, silhouette scores and visual analysis. The final model chosen for the customer segmentation is **KMeans with K=3**, which provides the best silhouette score and visual separation.

### Project Structure

The project is structured as follows:
```
src/
├── data_sample/            # Sample data files used in the project
├── img/                    # Images used in the project
├── notebooks/              # Notebooks for exploration and testing
├── results_notebook/       # Final result notebook
├── presentation/           # Pdf presentation
├── models/                 # Saved models
└── utils/                  # Helper functions and classes
```

### Steps Covered

1. **Importing Libraries**
2. **Problem Statement**
3. **Technical Problem**
4. **Data Access, Visualization, and Exploration**
5. **Data Cleaning**
6. **MiniEDA**
7. **Feature Processing**
8. **Dimensionality Reduction**
9. **Clustering**
10. **Evaluations**
11. **Customer Segmentation**
12. **Model Save**

### How to Run
1. Clone the repository:
   ```bash
    git clone https://github.com/yourusername/customer-segmentation.git
   ```
2. Navigate to the project folder
   ```bash
   cd customer-segmentation
   ```
3. Install the required libraries:
   ```bash
    pip install -r requirements.txt
   ```
4. Run the Jupyter notebook:
   ```bash
    jupyter notebook
   ```
### Dataset
*Customer Personality Analysis* is a detailed analysis of a company’s ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors, and concerns of different types of customers. 

Data source: [Customer Personality Analysis Dataset](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)


### Modeling
- **K-Means:** A widely used method for partitioning the data into K distinct clusters. 
- **DBSCAN:** A density-based clustering technique that groups together points that are closely packed, marking points in low-density regions as outliers.
- **Agglomerative Clustering:** A hierarchical approach that does not require the number of clusters to be specified.

### Model Used
The final model used for customer segmentation is **KMeans with K=3**. This model was selected based on:
- The best silhouette score.
- Visual analysis of clusters in 2D and 3D.
- Insights from sample silhouette analysis.

### Insights
Based on the segmentation, three distinct customer profiles were identified:
- 1. Low Engagement Shoppers: Customers with low spending, lower income, and a preference for visiting websites without purchasing.
- 2. Moderate Shoppers: Customers with moderate spending, a preference for online shopping, and an interest in deals.
- 3. High-Value Shoppers: Customers with high spending, high income, and an interest in premium products like wines, meat, and fish.

### Conclusion
This segmentation model provides valuable insights for targeting customers effectively through personalized marketing strategies. Future work could involve experimenting with other clustering techniques and further improving the model's ability to predict customer behavior.

### Author
**Carlos Noya**
