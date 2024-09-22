# Customer-Segmentation-using-K-Means-Clustering

This project performs customer segmentation using K-Means clustering on a customer dataset. The goal is to group customers based on their purchasing and cash advance behavior. 

### Dataset
The dataset contains information such as customer purchases, balance, cash advance, credit limit, payments, and more.

### Key Steps:
1. Data Cleaning: Missing values are removed.
2. Data Preprocessing: The numerical features are standardized.
3. Elbow Method: The optimal number of clusters is determined using the elbow method.
4. K-Means Clustering: K-means clustering is applied to segment customers based on their `PURCHASES` and `CASH_ADVANCE`.
5. Visualization: The clusters are visualized using a scatter plot.

### Dependencies:
- pandas
- matplotlib
- scikit-learn

### How to run:
1. Clone the repository:
    ```bash
    git clone https://github.com/US-PRASATH/Customer-Segmentation-using-K-Means-Clustering
    ```
2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the code:
    Open `customer_segmentation_kmeans.ipynb` in Jupyter Notebook to execute the code.

### Elbow Method:
The elbow method helps to identify the optimal number of clusters by plotting the inertia (within-cluster sum of squares) against the number of clusters.

### K-Means:
K-Means clustering is used to group customers based on their purchasing and cash advance behavior. In this project, we use 3 clusters based on the elbow method.

### Visualization:
A scatter plot is created to visualize customer clusters based on their purchases and cash advances.


