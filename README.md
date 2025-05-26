# Customer Segmentation using KMeans Clustering

This project focuses on segmenting mall customers based on their behavior and purchase data to provide insights for marketing strategies. The analysis is performed using the KMeans clustering algorithm.

## Overview

Customer segmentation is a crucial technique for businesses to understand their customer base better. By grouping customers into distinct segments, targeted marketing strategies can be developed to enhance customer engagement and increase sales. This project utilizes the "Mall Customer Segmentation Data" dataset from Kaggle to identify customer segments within a shopping mall.

## Dataset

The dataset used in this project is the "Mall Customer Segmentation Data," obtained from [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python).

### Description

This dataset was created for the purpose of learning customer segmentation concepts, also known as market basket analysis.  It includes basic information about mall customers obtained through membership cards. The columns in the dataset are:

-   **CustomerID:** Unique ID assigned to each customer
-   **Gender:** Gender of the customer
-   **Age:** Age of the customer
-   **Annual Income (k$):** Annual income of the customer in thousand dollars
-   **Spending Score (1-100):** A score assigned to the customer by the mall based on customer behavior and spending data

### Business Problem

The mall management aims to understand its customers better, specifically identifying groups of customers (target customers) that can be easily targeted. This understanding will enable the marketing team to plan appropriate and effective strategies.

## Methodology

The project employs the KMeans clustering algorithm to segment customers based on their annual income and spending score. The optimal number of clusters is determined using the Elbow Method.  The analysis helps to visualize and interpret different customer segments, providing actionable insights for the mall's marketing team.

## Files

-   `clustering.ipynb`: Jupyter Notebook containing the code for data loading, exploration, preprocessing, clustering, and visualization.
-   `Mall_Customers.csv`: The dataset used for the analysis.

## Libraries Used

-   pandas
-   matplotlib
-   yellowbrick
-   scikit-learn (sklearn)

## Setup

1.  Clone the repository:

    ```bash
    git clone <repository_url>
    ```

2.  Ensure you have Python 3.x installed.

3.  Install the required libraries:

    ```bash
    pip install pandas matplotlib scikit-learn yellowbrick
    ```

4.  Run the Jupyter Notebook `clustering.ipynb` to reproduce the analysis.

## Results

The analysis results in distinct customer segments, which can be used by the marketing team to tailor their strategies. For example, segments might include:

-   High Income, High Spending Score: Target for premium products.
-   Low Income, High Spending Score: Potential for promotional offers.
-   High Income, Low Spending Score: Needs to be engaged more.

## Conclusion

This project provides a clear methodology for customer segmentation using KMeans clustering. The insights gained can help the mall develop more effective marketing campaigns, leading to increased customer satisfaction and revenue.

## Author

fiksdeveloper | dicoding academy

## Acknowledgements

-   The "Mall Customer Segmentation Data" dataset provided by Kaggle.
-   The developers of the Python libraries used in this project.
