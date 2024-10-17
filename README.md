
## Setup Instructions
1. Clone the repository:
    ```bash
    git clone https://github.com/Ritish017/customer-segmentation-project.git
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Open the Jupyter notebook (`Customer_segmentation2.ipynb`) to run the code for RFM analysis and K-Means clustering.

4. Load the Tableau workbook (`Customer Segmentation.twbx`) to explore the interactive visualizations.

## Results
### Key Insights from Customer Segmentation:
1. **VIP Customers** (Cluster 1):
   - These customers show the highest engagement and spending patterns, with low recency scores, high frequency, and high monetary values.

2. **Low Engagement Customers** (Cluster 2):
   - Customers in this segment have low frequency and monetary value, indicating a lack of recent purchases and lower overall spending.

3. **Moderate Engagement Customers** (Cluster 0):
   - Customers in this segment have moderate engagement and spend moderately. They could potentially be targeted for further engagement strategies.

4. **Moderate Spending Customers** (Cluster 3):
   - These customers spend moderately but might not engage as frequently as VIPs.

### Tableau Dashboard:
For a detailed visual representation, refer to the **Tableau Dashboard** (`Customer Segmentation.twbx`) for further insights into customer segmentation and performance metrics.

## Tableau Dashboard
The Tableau dashboard provides an interactive way to visualize customer segments and their characteristics. You can filter by clusters, explore metrics like Recency, Frequency, and Monetary values, and gain actionable insights.

## Technologies Used
- **Python**: For data preprocessing, RFM analysis, and K-Means clustering.
- **Pandas, Scikit-learn**: For data manipulation, scaling, and clustering.
- **Matplotlib, Seaborn**: For data visualization.
- **Tableau**: For building the interactive dashboard.
