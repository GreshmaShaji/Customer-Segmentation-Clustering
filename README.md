# Customer Segmentation Analysis

## Project Overview

This project performs customer segmentation using clustering techniques on customer data from a retail store. The goal is to identify different customer groups based on their purchasing behavior and demographics, which can help the marketing team tailor personalized campaigns to different customer segments.

The analysis includes feature engineering, clustering, and visualization of the results to identify high-value customers and those who might benefit from further engagement.

## Dataset
The dataset contains information about customers, including:
- Demographics: `Age`, `Education`, `Marital_Status`, `Living_With`
- Purchasing behavior: `Spent`, `Income`, `NumDealsPurchases`
- Engagement with promotions: `AcceptedCmp1`, `AcceptedCmp2`, etc.
- Other customer details: `Days_Customer`, `Recency`

The data was sourced from a marketing campaign for a grocery retailer.

## Features

- **Feature Engineering**: Created features such as `Days_Customer`, `Family_Size`, and `Total_Promos` to enhance the data and make it more informative for clustering.
- **Clustering Techniques**: Performed unsupervised learning using **K-Means** and **Agglomerative Clustering** to segment customers into different groups based on similar behaviors.
- **Visualization**: Visualized clusters and important features using various plots like scatter plots, boxen plots, and count plots to understand the distribution and patterns in each cluster.

## Project Structure

```bash
├── data/
│   └── marketing_campaign.csv    # Customer data file
├── notebooks/
│   └── customer-segmentation-analysis.ipynb  # Jupyter Notebook containing the analysis
├── README.md                     # Project overview and instructions
├── requirements.txt              # Required Python libraries for the project
```

## Getting Started

### Prerequisites

To run this project, you need to have the following installed:

Python 3.7+
Jupyter Notebook

You can install the required Python libraries using the command:
```
pip install -r requirements.txt
```

### Running the Analysis

1. Clone this repository to your local machine:
```
git clone https://github.com/yourusername/customer-segmentation-analysis.git
```
2. Navigate to the project directory:
```
cd customer-segmentation-analysis
```
3. Open the Jupyter Notebook:
```
jupyter notebook notebooks/customer-segmentation-analysis.ipynb
```
4. Run the cells in the notebook to perform the customer segmentation analysis.

## Key Insights
1. Star Customers: High-income, high-spending customers with frequent interactions are identified as high-value customers. These customers are good candidates for loyalty programs and exclusive offers.
2. Customers Needing Attention: Some clusters showed less frequent purchases and engagement. These customers may need re-engagement campaigns or targeted promotions to increase their spending.

## Conclusion

This project demonstrates how clustering techniques can be used to segment a customer base for personalized marketing strategies. The insights gained from the clustering analysis can help the retail store better understand its customers and optimize its marketing efforts.

## Future Work

- Expand the analysis by using additional clustering techniques, such as DBSCAN or Gaussian Mixture Models.
- Implement more sophisticated feature engineering to capture temporal patterns in customer behavior.
- Use classification algorithms to predict customer responses to future campaigns based on past behaviors

## License

This project is licensed under the MIT License - see the LICENSE file for details.