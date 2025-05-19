# KMeans Clustering on Customer Dataset

This project applies the **KMeans clustering** algorithm on a customer dataset containing Age and Income attributes. The goal is to segment customers into distinct groups to enable better insights and decision-making for marketing or business strategies.

---

## Project Description

The dataset consists of customer information with two key features: Age and Income. This project performs the following:

- Loads the dataset from a CSV file.  
- Visualizes the original data distribution with scatter plots.  
- Normalizes the features using Min-Max scaling to bring values into a comparable range.  
- Applies KMeans clustering to group customers into clusters based on similarity.  
- Visualizes the clustered data with color-coded groups and centroids.  
- Uses the Elbow method by plotting Sum of Squared Errors (SSE) to help select the optimal number of clusters.

---

## Key Features

- **Data Visualization:** Scatter plots showing original and clustered data for intuitive understanding.  
- **Data Preprocessing:** Min-Max scaling normalizes the features to improve clustering performance.  
- **KMeans Clustering:** Efficient partitioning of data into k clusters based on Euclidean distance.  
- **Cluster Visualization:** Colored scatter plots with cluster centroids highlighted.  
- **Model Evaluation:** Elbow method graph helps determine the ideal number of clusters by analyzing SSE.

---

## How to Use

1. Place your `Dataset.csv` file containing Age and Income columns in the working directory.  
2. Load the provided Python script or notebook in your environment (e.g., Jupyter Notebook, Google Colab, or any IDE).  
3. Run the code cells or script to:  
   - View original data scatter plots.  
   - Normalize data features.  
   - Perform KMeans clustering with a chosen number of clusters (default is 3).  
   - Visualize clusters and centroids.  
   - Generate the SSE plot to select the best cluster number using the Elbow method.

---

## Results and Insights

- The initial scatter plot helps visualize the natural distribution of data points.  
- After scaling, KMeans groups the data into clusters that capture underlying patterns in Age and Income.  
- Centroids represent the average feature values for each cluster, aiding interpretation.  
- The Elbow plot of SSE versus the number of clusters shows a clear bend, guiding the optimal choice of clusters.

---

## Applications

- Customer segmentation for targeted marketing campaigns.  
- Identifying distinct groups in demographic data.  
- Basic unsupervised learning demonstration in data science education.  
- Can be extended to other domains requiring clustering of numerical data.

---

## Dependencies

- Python 3.x  
- pandas for data manipulation  
- scikit-learn for KMeans and scaling  
- matplotlib for visualization  

---

## Contact

If you have questions, suggestions, or want to collaborate, feel free to reach out!

---

This README provides a comprehensive overview of the KMeans clustering project on customer data and will help users understand, run, and interpret the code results easily.
