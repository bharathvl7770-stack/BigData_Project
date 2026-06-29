# Task 2 — Data Engineering (20%)

**Module:** 7006SCN Machine Learning and Big Data · Coventry University  
**Branch:** `Task2`  
**Week:** Week 2  
**Weight:** 20%

---

## Overview

This task focuses on preparing the HMDA dataset for large-scale machine learning using Apache Spark. Data preprocessing, feature engineering, and the construction of a scalable PySpark ML Pipeline were implemented to transform raw mortgage application data into a model-ready feature set.

---

## Objectives

- Perform distributed data preprocessing
- Handle missing and inconsistent values
- Engineer predictive features
- Encode categorical variables
- Scale numerical features
- Build a reusable Spark ML Pipeline

---

## Notebook

| File | Location |
|------|----------|
| `Task2.ipynb` | `notebooks/` |

Execute this notebook after Task 1.

---

## Commits on this Branch

-"feat(task2_commit1): optimise HMDA data ingestion and partitioning"
-"feat(task2_Commit2): perform data quality assessment and preprocessing"
-"feat(task2_Commit3): implement HMDA preprocessing and feature engineering"
-"feat(task2_commit4): build Spark ML preprocessing pipeline"
-"feat(task2_commit5): prepare model-ready dataset for machine learning"
---

## Pipeline Stages

- Data Cleaning
- Missing Value Handling
- StringIndexer
- OneHotEncoder
- VectorAssembler
- StandardScaler
- Spark ML Pipeline

---

## Key Outputs

| Output | Purpose |
|---------|---------|
| Processed Spark DataFrame | Clean dataset for modelling |
| Feature Vector | Input for Spark ML algorithms |
| Engineered Features | Improved predictive performance |
| Pipeline Model | Reusable preprocessing workflow |

---

## Learning Outcome

Developed a scalable data engineering workflow capable of processing over 11.5 million mortgage application records using distributed computing techniques.
