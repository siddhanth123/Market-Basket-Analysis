# Market Basket Analysis with PySpark and FPGrowth

This repository contains code for performing Market Basket Analysis using PySpark and the FPGrowth algorithm. The analysis is conducted on a dataset obtained from Kaggle, which provides transaction data for market basket analysis.

## Dataset

The dataset used for this analysis is the Groceries Dataset for Market Basket Analysis available on Kaggle. It contains transaction data, including the items purchased by customers.

## FPGrowth Algorithm

The FPGrowth algorithm is a popular method for performing frequent pattern mining and association rule learning. It operates without the need for candidate itemset generation, making it more efficient compared to traditional methods. For more details on the FPGrowth algorithm, refer to the following paper:

Jiawei Han, Jian Pei, and Yiwen Yin. 2000. Mining frequent patterns without candidate generation. SIGMOD Rec. 29, 2 (June 2000), 1–12. DOI: 10.1145/335191.335372

## MLflow

MLflow is an open-source platform for managing the machine learning lifecycle. It provides tools for tracking experiments, packaging and sharing code, and managing models. In this project, MLflow is used to track the execution of the code, log parameters and metrics, and save the trained model. For more information about MLflow, visit the [MLflow website](https://mlflow.org/).

## Usage

### Set up Databricks

Ensure you have a Databricks workspace set up and configured with the necessary dependencies.

### Run the code

Open the notebook in Databricks, and execute the code cell by cell. Ensure that you have provided the correct file paths for the input data files.

### Analyze the results

The code performs market basket analysis using the FPGrowth algorithm and generates recommendations based on the provided sample data. Review the output to understand the associations and patterns identified by the algorithm.
