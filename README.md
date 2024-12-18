# Mall Customer Shopping Segmentation Analysis Group Members 

1. Name: Shashank Kumar
   - KU ID: KU2407U370 
2. Name: Sumit Chaudhary
   - KU ID: KU2407U269
2. Name: Suhel Patel
   - KU ID: KU2407U383
2. Name: Harsh Rajpurohit
   - KU ID: KU2407U285
2. Name: Meshva Rao
   - KU ID: KU2407U684

## Objective of the Project
The objective of this project is to segment e-commerce customers based on their spending habits using clustering techniques. By grouping customers with similar spending behaviours, we aim to identify patterns and insights that can help improve targeted marketing, customer engagement, and product recommendations.
## Tools and Libraries Used 
Programming Language: Python
#### Libraries:
1. pandas: For data manipulation and preprocessing.
2. numpy: For numerical operations.
3. matplotlib: For data visualization. 
4. seaborn: For advanced data visualization.
5. sklearn: For machine learning algorithms, including clustering (K-Means). Data Source(s)
6. Dataset: The dataset used for this project is a simulated e-commerce customer data, which includes customer details such as:
   - Customer ID o Total spending (annual)
   - Number of visits 
   - Purchase categories (e.g., electronics, fashion, etc.) 
## Execution Steps (How to run the project) 			
1. Install dependencies:
   - Make sure Python (preferably Python 3.x; we have used Jupyter notebook ) is installed, then install the required libraries using: pip install -r requirements.txt
3. Prepare the data:
   - Ensure that the dataset is in the appropriate directory.
4. Run the Clustering Algorithm:
   - The clustering is implemented using K-Means. To execute the clustering and generate the output. 
5. Visualize the Results:
   - After running the clustering, the results will be available in a visual format. You can explore the visualizations directly viewing them in the notebook (using Jupyter).
7. Interpret Results:
   - Review the customer segments and interpret them based on the spending habits identified by the clustering process. 
   - Detailed insights will be saved as a .csv or .xlsx file in the results/ folder. Summary of Results 
   - Customer Segments: We identified multiple distinct customer segments based on their spending patterns. 
   - Visualizations: The clusters are visualized using scatter plots, bar charts, and other techniques to clearly depict the segmentation. These segments provide actionable insights for improving targeted marketing and personalized offers for each customer group. Challenges Faced 
1. Data Quality: Handling missing or incomplete data was challenging, especially with varying formats in customer spending and visit data. 
2. Choosing the Right Number of Clusters: Determining the optimal number of clusters for K-Means using methods like the Elbow Method and Silhouette Score required experimentation. 
3. Scalability: As the dataset size increased, performing clustering and visualizations became resource-intensive. Future Enhancements
   - Explore other clustering algorithms (e.g., DBSCAN, hierarchical clustering) for comparison.
   - Incorporate more customer features such as demographics and product preferences for more comprehensive segmentation. 
   - Develop a real-time segmentation model using streaming data for dynamic customer profiling.
