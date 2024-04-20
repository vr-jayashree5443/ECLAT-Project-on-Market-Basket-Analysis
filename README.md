# ECLAT-Project-on-Market-Basket-Analysis

## Introduction
This project aims to perform Market Basket Analysis using the ECLAT algorithm. Market Basket Analysis is a data mining technique used to uncover associations between products purchased together. ECLAT (Equivalence Class Clustering and Bottom-Up Lattice Traversal) is an efficient algorithm for frequent itemset mining, particularly suitable for large datasets.

## Installation
Before running the code, ensure you have the `pyECLAT` library installed. You can install it via pip:

```bash
pip install pyECLAT
```

## Dataset
The dataset used in this project is available [here](https://drive.google.com/file/d/1y5DYn0dGoSbC22xowBq2d4po6h1JxcTQ/view). It contains transactional data representing items bought together by customers.

## Libraries
The following libraries are used in this project:
- `numpy` (Numerical Python): For numerical computing.
- `pandas` (Python Data Analysis Library): For data manipulation and analysis.
- `pyECLAT`: For implementing the ECLAT algorithm.

## Code Overview
1. **Importing Libraries**: Necessary libraries are imported, and `pyECLAT` is installed if not already present.
2. **Loading the Dataset**: The dataset is loaded into a Pandas DataFrame for analysis.
3. **Data Analysis**: Initial exploration of the dataset is conducted, including checking the first few rows and unique values in the dataset.
4. **Market Basket Analysis with ECLAT**:
    - The ECLAT algorithm is applied to the dataset to perform Market Basket Analysis.
    - The dataset is transformed into a binary format suitable for ECLAT analysis.
    - Frequent itemsets and their supports are extracted using the ECLAT algorithm with specified parameters.
  
