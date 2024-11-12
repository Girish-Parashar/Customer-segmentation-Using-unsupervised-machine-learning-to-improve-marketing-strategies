# Customer Segmentation Using Unsupervised Machine Learning
<p align="center">
  <img src="https://github.com/Girish-Parashar/Customer-segmentation-Using-unsupervised-machine-learning-to-improve-marketing-strategies/blob/main/Leonardo_Phoenix_Design_a_sophisticated_visual_for_Customer_Se_2.jpg" width="500"/>
</p>


This project applies **unsupervised machine learning techniques**, specifically **clustering**, to segment customers based on their **demographics**, **purchase history**, and **browsing behavior**. The goal is to derive actionable insights that can help businesses create more targeted marketing strategies, improve customer satisfaction, and drive business growth.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Dataset](#dataset)
4. [Clustering Techniques](#clustering-techniques)
5. [Implementation](#implementation)
6. [Results](#results)
7. [Conclusion](#conclusion)
8. [Installation](#installation)
9. [Usage](#usage)

## Project Overview

Customer segmentation is an essential part of marketing strategies, helping businesses target the right audience with personalized messages and offers. This project uses **unsupervised machine learning** to segment customers into meaningful groups based on shared characteristics such as demographics, purchase behavior, and online activity.

The primary goal of this project is to:

- **Segment customers** based on data-driven insights.
- **Improve marketing strategies** by targeting specific customer groups.
- **Increase customer satisfaction** by delivering personalized experiences.
- **Boost business growth** by optimizing customer engagement.

## Technologies Used

- **Python** (for data processing and machine learning)
- **Pandas** (for data manipulation)
- **NumPy** (for numerical computations)
- **Scikit-learn** (for machine learning models)
- **Matplotlib & Seaborn** (for data visualization)
- **Jupyter Notebook** (for interactive development)

## Dataset

The dataset used in this project contains customer data including the following attributes:

| CustomerID | Gender | Age | Annual Income (k$) | Spending Score (1-100) |
|------------|--------|-----|--------------------|------------------------|
| 0          | Male   | 19  | 15                 | 39                     |
| 1          | Male   | 21  | 15                 | 81                     |
| 2          | Female | 20  | 16                 | 6                      |
| 3          | Female | 23  | 16                 | 77                     |

- **CustomerID**: Unique identifier for each customer.
- **Gender**: Gender of the customer (Male/Female).
- **Age**: Age of the customer.
- **Annual Income (k$)**: Customer's annual income in thousands of dollars.
- **Spending Score (1-100)**: A score assigned to the customer based on their spending behavior, with 100 being the highest spender.

The data is preprocessed to handle missing values, normalize features, and prepare it for clustering.

## Clustering Techniques

We used the following clustering algorithms to segment customers:

1. **K-Means Clustering**: A popular method for dividing customers into **K** distinct clusters based on similarities.
2. **Hierarchical Clustering**: An alternative to K-Means, this technique builds a tree of clusters for more flexible segmentation.

Both models are used to group customers based on shared attributes to identify natural patterns within the data.

## Implementation

1. **Data Preprocessing**: 
    - Handle missing values
    - Normalize data
    - Feature selection

2. **Clustering Model**: 
    - K-Means Clustering
    - Hierarchical Clustering

3. **Visualization**: 
    - Plot cluster distributions using **Matplotlib** and **Seaborn**
    - Visualize key metrics such as cluster size, average spending, and engagement levels

4. **Analysis**: 
    - Identify the most significant features for segmentation
    - Determine which clusters correspond to high-value or at-risk customers

## Results

After implementing the clustering models, we obtained **distinct customer segments** that show meaningful patterns in their behavior. Key insights include:

- Segment 1: High-value customers with frequent purchases and high engagement.
- Segment 2: Price-sensitive customers with moderate purchases.
- Segment 3: Low-engagement customers with irregular buying patterns.

These insights can help tailor marketing efforts for each segment, resulting in more effective campaigns and higher conversion rates.

## Conclusion

The project demonstrated how unsupervised machine learning, specifically clustering techniques, can be used to identify distinct customer segments. By analyzing customer data, businesses can gain actionable insights to create targeted marketing campaigns, improve customer experiences, and drive growth.

## Installation

To run this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation.git
