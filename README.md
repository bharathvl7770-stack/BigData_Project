# Task 1 — Problem & Dataset (10%)

**Module:** 7006SCN Machine Learning and Big Data · Coventry University  
**Branch:** Task1  
**Week:** Week 1–2  
**Weight:** 10%

---

## Overview

This task introduces the mortgage loan approval prediction problem using the **2023 HMDA Mortgage Application Register**. The notebook performs dataset ingestion, verifies the dataset size and schema, explores the initial data distribution, and justifies the use of Apache Spark based on the Five V's of Big Data. Ethical and licensing considerations associated with the HMDA dataset are also discussed.

---

## Problem Statement

The objective is to develop a scalable machine learning pipeline capable of predicting whether a mortgage application will be **approved** or **rejected**. Since the dataset contains more than **11.5 million records** and over **80 attributes**, distributed processing with Apache Spark is required to efficiently perform data engineering and machine learning.

---

## Dataset

| Property | Details |
|----------|---------|
| Dataset | 2023 HMDA One Year National Loan Level Dataset |
| Source | Consumer Financial Protection Bureau (CFPB) |
| Records | 11.5+ Million |
| Features | 80+ Columns |
| Size | >1 GB |
| Format | CSV |
| License | Publicly available for research and educational purposes |

---

## Notebook

| File | Location |
|------|----------|
| `Task1.ipynb` | `notebooks/` |

Execute this notebook before the remaining tasks, as it performs the initial dataset loading and exploratory analysis used throughout the project.

---

## Commits on this Branch

- `feat(task1): initialise project structure and Spark environment`
- `feat(task1): ingest HMDA dataset and verify schema and file size`
- `feat(task1): perform exploratory data analysis, Five V's justification and ethical review`

---

## Key Activities

- Configure Apache Spark environment
- Load HMDA dataset into a Spark DataFrame
- Verify dataset size and schema
- Display sample records using `df.show(20)`
- Perform initial exploratory data analysis
- Justify the Five V's of Big Data
- Review ethical and licensing considerations

---

## Key Outputs

| Output | Purpose |
|---------|---------|
| `df.show(20)` | Preview of the loaded dataset |
| `df.printSchema()` | Verification of the Spark DataFrame schema |
| Dataset Size Verification | Confirms compliance with Big Data requirements |
| Initial Data Exploration | Supports understanding of dataset structure |

---

## Learning Outcome

This task establishes the foundation for the project by validating the HMDA dataset, demonstrating its suitability for distributed machine learning, and preparing the data for subsequent preprocessing, feature engineering and predictive modelling tasks.
