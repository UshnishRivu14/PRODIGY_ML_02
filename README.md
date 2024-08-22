---

# **Customer Segmentation Using K-means Clustering**

This project demonstrates the use of the K-means clustering algorithm to segment customers of a retail store based on their purchasing history. The primary goal is to group customers into distinct clusters, allowing businesses to tailor their marketing strategies to different customer segments.

## **Project Overview**

Customer segmentation is a crucial aspect of modern marketing strategies. By analyzing customer data, businesses can identify groups of customers with similar behaviors and preferences. In this project, we use the K-means clustering algorithm to segment customers based on their annual income and spending score.

## **Dataset**

The dataset used in this project is available on Kaggle: [Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python). It contains the following features:
- **CustomerID**: Unique identifier for each customer.
- **Gender**: Gender of the customer.
- **Age**: Age of the customer.
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars.
- **Spending Score (1-100)**: Spending score assigned by the store, ranging from 1 to 100.

## **Project Structure**

The project is organized as follows:

- **data/**: Contains the dataset used in the project.
- **notebooks/**: Jupyter notebooks with the code implementation and analysis.
- **images/**: Visualizations generated during the analysis.
- **README.md**: Project overview and instructions.

## **Getting Started**

### **Prerequisites**

To run the code, you need to have the following packages installed:
- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn

### **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-segmentation-kmeans.git
   ```
2. Navigate to the project directory:
   ```bash
   cd customer-segmentation-kmeans
   ```
3. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

### **Usage**

1. Open the Jupyter notebook `customer_segmentation_kmeans.ipynb`.
2. Run the cells step by step to execute the K-means clustering algorithm.
3. Visualizations will be generated to help you understand the clustering results.

### **Key Steps in the Analysis**

1. **Data Preprocessing:**
   - Selecting relevant features: `Annual Income (k$)` and `Spending Score (1-100)`.

2. **Visualization:**
   - Scatter plot of data points before clustering.
   - Scatter plot of clustered data with centroids marked.

3. **K-means Clustering:**
   - Applying the K-means algorithm to segment the customers into 5 clusters.
   - Using the Elbow Method to determine the optimal number of clusters.

4. **Results:**
   - Interpretation of the clusters and their potential implications for marketing strategies.

## **Results**

The K-means clustering algorithm successfully grouped the customers into 5 distinct clusters based on their annual income and spending score. The centroids of these clusters represent the average income and spending behavior of each group.

## **Contributing**

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## **Contact**

If you have any questions or feedback, feel free to reach out:

- **Email**: ushnishsarkar14@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/ushnish-sarkar-b21208217/

---
