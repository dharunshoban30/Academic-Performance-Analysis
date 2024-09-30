# 📖 Student Academic Performance Analysis using Association Rule Mining

## Overview
This project demonstrates the application of association rule mining using the Apriori algorithm on a dataset. The aim is to discover interesting associations and relationships among various attributes of the data which consists of student academic data.

## Contents

1. **Data Preprocessing:**
    - Loading and cleaning the dataset.
    - One-hot encoding categorical variables to prepare the data for association rule mining.

2. **Frequent Pattern Mining:**
    - Using the Apriori algorithm to find frequent itemsets with a specified minimum support.
    - Displaying the resulting itemsets and their support values.

3. **Association Rule Generation:**
    - Applying the association rule mining algorithm to extract relationships from the frequent itemsets.
    - Filtering the rules based on confidence and support thresholds.

4. **Analysis and Interpretation:**
    - Understanding the relationships among attributes.
    - Saving the resulting rules to a CSV file for further analysis.
    
## Key Functions and Methods
  - fp.apriori(): Finds frequent itemsets using the Apriori algorithm.
  - fp.association_rules(): Generates association rules based on frequent itemsets.

## Parameters
  - min_support: Minimum support threshold for frequent itemsets.
  - metric: Metric to evaluate the strength of association rules (e.g., confidence).
  - min_threshold: Minimum threshold for the metric.

## Instructions
To execute the notebook, follow these steps:

1. **Setup Environment**:
    - Ensure you have Python and Jupyter Notebook installed.
    - Install necessary libraries using the following commands:
      ```bash
      pip install numpy pandas mlxtend
      ```

2. **Download Dataset**:
    - Ensure the `DATA(1).csv` dataset is available in the same directory as the notebook.

3. **Running the Notebook**:
    - Open the Jupyter Notebook and navigate to the `Code.ipynb` file.
    - Run all cells sequentially to see the complete workflow and results.

## Outputs
  - **Frequent Itemsets**: Lists of itemsets that appear frequently in the data.
  - **Association Rules**: Rules generated from the frequent itemsets, with metrics like support, confidence, and lift.
  - **Visualization**: A table displaying the association rules along with their metrics.
