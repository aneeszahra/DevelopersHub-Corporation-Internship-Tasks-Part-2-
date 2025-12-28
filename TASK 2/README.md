 Task 2: Customer Segmentation Using Unsupervised Learning
 Objective

Cluster customers based on their spending patterns to create marketing strategies tailored to each group.

 Dataset

**Mall Customers Dataset**
Includes demographic and spending-related features: CustomerID, Gender, Age, Annual Income, and Spending Score.

 Approach

1. **EDA**

   * Explored feature distributions and relationships.
   * Visualized spending vs income patterns by gender.
2. **Clustering**

   * Scaled numerical features using StandardScaler.
   * Applied **K-Means Clustering** and determined optimal clusters via **Elbow Method**.
3. **Dimensionality Reduction**

   * Applied **PCA** for 2D visualization of clusters.
4. **Insights**

   * Identified 5 major customer segments:

     * High-income, high-spenders
     * High-income, low-spenders
     * Low-income, moderate-spenders, etc.

 Results & Insights

* Clear separation achieved using PCA visualization.
* Business recommendation:

  * Target high-income low-spenders with premium loyalty offers.
  * Focus budget campaigns on moderate-spending middle-income groups.

 Skills Gained

* K-Means clustering and PCA visualization
* Customer segmentation and insight extraction
* Data-driven marketing strategy development
