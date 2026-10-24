# Big Data Analytics with PySpark and Databricks

A collection of Big Data Analytics projects developed as part of my MSc Artificial Intelligence studies at the University of Salford.

The projects demonstrate large-scale data processing, analytical querying, machine learning and recommendation systems using Apache Spark and Databricks.

## Technologies Used

- Python
- PySpark
- Apache Spark SQL
- Spark MLlib
- Databricks
- MLflow
- Jupyter Notebooks

## Project 1: Clinical Trials Data Analysis

**Folder:** `clinical-trials-analysis`

This project analyses clinical trial data using Spark SQL to investigate study types, medical conditions, trial durations and trends in Alzheimer's-related completed studies.

**Key activities:**
- Loading and exploring structured clinical trial data
- Data preprocessing and handling complex fields
- SQL-based filtering, aggregation and analysis
- Analysing clinical trial patterns and trends

**Notebook:** `clinical_trials_analysis.ipynb`

## Project 2: Steam Game Recommendation System

**Folder:** `steam-recommendation-system`

This project develops a collaborative filtering recommendation system using Spark MLlib's Alternating Least Squares (ALS) algorithm.

The system uses Steam user interaction data, including game purchases and playtime, to generate personalised game recommendations.

**Key activities:**
- Loading and preprocessing user-game interaction data
- Preparing data for collaborative filtering
- Training and evaluating ALS recommendation models
- Comparing model configurations using RMSE
- Tracking experiments using MLflow

**Notebook:** `steam_recommendation.ipynb`

## Running the Projects

The notebooks were developed in Databricks using Apache Spark.

To reproduce the analyses:

1. Set up a Databricks workspace with Spark support.
2. Import the relevant notebook.
3. Make the required datasets available in your workspace.
4. Update the dataset paths to match your environment.
5. Run the notebook cells in order.

**Note:** The original notebooks reference datasets stored in a Databricks Unity Catalog environment. These datasets are not included in this repository, so the notebooks are not immediately reproducible without access to equivalent data.

## Author

Mohamed Amine Elorabi

MSc Artificial Intelligence — University of Salford

[GitHub Profile](https://github.com/AmineOrb)

