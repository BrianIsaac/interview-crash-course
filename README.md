# Data Science Interview Crash Course

A comprehensive collection of Jupyter notebooks for data science and machine learning interview preparation. Covers the full spectrum of technical knowledge from core data manipulation to advanced ML, data systems, and API design.

## Notebooks

### Foundational (01-04)

| # | Topic | Description |
|---|-------|-------------|
| 01 | Pandas | DataFrame operations, indexing, merging, groupby, pivot tables, apply/lambda |
| 02 | NumPy | Array creation, indexing, reshaping, broadcasting, statistics, linear algebra |
| 03 | SQL | SQLite queries, JOINs, subqueries, CTEs, window functions, string/date functions |
| 04 | Statistics | Descriptive stats, probability, distributions, CLT, hypothesis testing, A/B testing |

### Applied Machine Learning (05-10)

| # | Topic | Description |
|---|-------|-------------|
| 05 | Machine Learning | Scikit-learn classifiers, regression, evaluation metrics, cross-validation, pipelines |
| 06 | Data Cleaning | Missing values, outliers, encoding, scaling, text preprocessing, feature engineering |
| 07 | NLP & Text Processing | Tokenisation, stemming, TF-IDF, n-grams, text classification, sentiment analysis |
| 08 | Unsupervised Learning | K-Means, hierarchical clustering, DBSCAN, PCA, t-SNE, UMAP, anomaly detection |
| 09 | Time Series | Stationarity, ARIMA, SARIMA, exponential smoothing, forecasting metrics, feature engineering |
| 10 | Deep Learning | Neural networks, activation functions, backpropagation, CNNs, RNNs, transfer learning |

### Data Systems (11-13)

| # | Topic | Description |
|---|-------|-------------|
| 11 | Database Design | Normalisation (1NF-3NF), ER modelling, star/snowflake schemas, indexing, query optimisation |
| 12 | Data Engineering | ETL/ELT, batch vs streaming, data pipelines, orchestration, data quality, scalability |
| 13 | Microservices & APIs | Docker Compose, REST APIs, authentication, Flask, FastAPI, API design best practices |

Each notebook includes teaching sections with code examples followed by practice questions with collapsible answers.

## Setup

```bash
uv sync
uv run jupyter lab
```

## Requirements

- Python 3.12+
- uv package manager

## Key Dependencies

- pandas, numpy, scipy - Data manipulation and computation
- scikit-learn - Machine learning
- matplotlib, seaborn - Visualisation
- statsmodels - Statistical modelling
- nltk - Natural language processing
- umap-learn - Dimensionality reduction

## Licence

MIT
