# Customer Segmentation Analysis

## Project Overview

This project performs customer segmentation using **RFM (Recency, Frequency, Monetary) analysis** and **K-Means clustering**. The goal is to understand customer purchasing behavior and help businesses develop targeted marketing strategies.

## Objectives

* Analyze customer purchasing patterns.
* Calculate Recency, Frequency, and Monetary values.
* Group customers into meaningful segments using K-Means clustering.
* Generate insights to support customer retention and marketing decisions.

## Technologies Used

* Python
* Pandas and NumPy
* Matplotlib and Seaborn
* Scikit-learn
* Jupyter Notebook
* Excel and CSV

## Dataset

The project uses the **Online Retail** dataset from the UCI Machine Learning Repository.

Dataset source: https://archive.ics.uci.edu/dataset/352/online+retail

## Project Workflow

1. Load and explore the retail dataset.
2. Clean missing values, duplicates, and invalid transactions.
3. Calculate total transaction amounts.
4. Perform RFM analysis.
5. Scale customer features.
6. Use the Elbow Method to help select the number of clusters.
7. Apply K-Means clustering.
8. Evaluate and visualize customer segments.
9. Export customer-level segments and cluster profiles.

## Project Structure

* `Customer_Segmentation.ipynb` — analysis and machine learning workflow.
* `Online Retail.xlsx` — dataset.
* `outputs/customer_segments.csv` — customer segment assignments.
* `outputs/cluster_profiles.csv` — summary statistics for each cluster.

## Results

The project groups customers according to their purchasing behavior. The resulting segments can help businesses identify loyal customers, high-value customers, customers who may need re-engagement, and other purchasing patterns based on the calculated cluster profiles.

## How to Run

1. Clone or download this repository.
2. Install the required Python libraries:
   `pip install pandas numpy matplotlib seaborn scikit-learn openpyxl jupyter`
3. Open `Customer_Segmentation.ipynb` in Jupyter Notebook.
4. Run the notebook cells in order.

## Future Improvements

* Build an interactive Power BI dashboard.
* Develop customer retention strategies based on segment behavior.
* Experiment with other clustering techniques.

## Author

**Gayatri Datir**
