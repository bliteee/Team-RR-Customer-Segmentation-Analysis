# Mall Customer Shopping Segmentation Analysis Group Members 

1. Name: Shashank Kumar Roll Number: KU2407U370 
2. Name: Sumit Chaudhary Roll Number: KU2407U269

## Objective of the Project
The objective of this project is to segment e-commerce customers based on their spending habits using clustering techniques. By grouping customers with similar spending behaviours, we aim to identify patterns and insights that can help improve targeted marketing, customer engagement, and product recommendations.
## Tools and Libraries Used 
1. Programming Language: Python
/ Libraries:
3. pandas: For data manipulation and preprocessing.
4. numpy: For numerical operations.
5. matplotlib: For data visualization. 
6. seaborn: For advanced data visualization.
7. sklearn: For machine learning algorithms, including clustering (K-Means). Data Source(s)
8. Dataset: The dataset used for this project is a simulated e-commerce customer data, which includes customer details such as:
  - Customer ID o Total spending (annual)
  - Number of visits 
  - Purchase categories (e.g., electronics, fashion, etc.) 
## Execution Steps (How to run the project) 			
1. Install dependencies: Make sure Python (preferably Python 3.x; we have used Jupyter notebook ) is installed, then install the required libraries using: pip install -r requirements.txt
2. Prepare the data: o Ensure that the dataset is in the appropriate directory.
3. Run the Clustering Algorithm: o The clustering is implemented using K-Means. To execute the clustering and generate the output. 
4. Visualize the Results: After running the clustering, the results will be available in a visual format. You can explore the visualizations directly viewing them in the notebook (using Jupyter).
5. Interpret Results: o Review the customer segments and interpret them based on the spending habits identified by the clustering process. 
- Detailed insights will be saved as a .csv or .xlsx file in the results/ folder. Summary of Results 
- Customer Segments: We identified multiple distinct customer segments based on their spending patterns. 
- Visualizations: The clusters are visualized using scatter plots, bar charts, and other techniques to clearly depict the segmentation. These segments provide actionable insights for improving targeted marketing and personalized offers for each customer group. Challenges Faced 
1. Data Quality: Handling missing or incomplete data was challenging, especially with varying formats in customer spending and visit data. 
2. Choosing the Right Number of Clusters: Determining the optimal number of clusters for K-Means using methods like the Elbow Method and Silhouette Score required experimentation. 
3. Scalability: As the dataset size increased, performing clustering and visualizations became resource-intensive. Future Enhancements 
- Explore other clustering algorithms (e.g., DBSCAN, hierarchical clustering) for comparison.
- Incorporate more customer features such as demographics and product preferences for more comprehensive segmentation. 
- Develop a real-time segmentation model using streaming data for dynamic customer profiling.
