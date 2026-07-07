# Data Science & Machine Learning Projects in Python

This repository contains a collection of Python-based data science projects covering machine learning, econometrics, clustering, dimensionality reduction, macroeconomic analysis, and financial time-series modelling.

The projects were developed in Jupyter Notebook and focus on practical data analysis workflows: data cleaning, exploratory data analysis, feature engineering, statistical modelling, machine learning, visualization, and interpretation of results.

## Projects

### 1. Neural Network for Banknote Authentication

**File:** `Klasyfikacja.ipynb`

This project implements a neural network from scratch for a binary classification problem using the Banknote Authentication dataset. The model classifies banknotes as genuine or forged based on statistical features extracted from wavelet-transformed banknote images.

The project includes:
- data loading and preprocessing,
- train-test split,
- manual implementation of a feedforward neural network,
- softmax output layer and cross-entropy loss,
- gradient descent optimization,
- comparison of different activation functions,
- testing different hidden layer sizes, learning rates, test sizes, and epoch counts,
- accuracy evaluation on training and test sets.

**Main topics:** neural networks, classification, gradient descent, activation functions, model evaluation.

---

### 2. Customer Segmentation with K-Means

**File:** `Project_k_mean_EDA.ipynb`

This project focuses on customer segmentation using credit card customer data. The goal is to identify groups of customers with similar financial and behavioral characteristics using exploratory data analysis, feature engineering, scaling, and K-Means clustering.

The project includes:
- exploratory data analysis of customer attributes,
- handling numerical and categorical variables,
- feature engineering,
- standardization of input variables,
- choosing the number of clusters using inertia analysis,
- K-Means clustering,
- interpretation of customer segments,
- business insights for each cluster.

**Main topics:** customer segmentation, K-Means, clustering, EDA, feature engineering, business analytics.

---

### 3. Macroeconomic and Fiscal Country Analysis

**File:** `SAD.ipynb`

This project analyzes macroeconomic and fiscal indicators for countries using World Bank-style data. The analysis compares countries across variables such as inflation, GDP growth, unemployment, interest rates, government revenue, public debt, and fiscal stability indicators.

The project includes:
- preprocessing of macroeconomic panel data,
- exploratory data analysis by country and continent,
- correlation analysis,
- visual analysis of macroeconomic indicators,
- linear ordering methods,
- standardized sum method,
- rank-based scoring,
- Hellwig development measure,
- hierarchical clustering,
- K-Means clustering,
- HDBSCAN clustering,
- PCA and UMAP visualization.

**Main topics:** macroeconomic analysis, country ranking, fiscal indicators, clustering, PCA, UMAP, HDBSCAN.

---

### 4. Multidimensional Analysis of Countries

**File:** `SAD_V2.ipynb`

This project studies the multidimensional structure of countries based on socio-economic, demographic, geographic, and sectoral indicators. The goal is to check whether countries from similar geographic regions form natural clusters in a multidimensional feature space.

The project includes:
- data preprocessing and cleaning,
- exploratory analysis of country-level indicators,
- correlation analysis,
- anomaly detection with Isolation Forest,
- dimensionality reduction using PCA,
- metric and non-metric MDS,
- t-SNE visualization,
- UMAP visualization,
- interpretation of regional patterns,
- comparison of dimensionality reduction methods.

**Main topics:** multidimensional data analysis, anomaly detection, PCA, MDS, t-SNE, UMAP, socio-economic indicators.

---

### 5. Spectral Analysis of S&P 500 Returns

**File:** `Tymoteusz_Hanusiak_kod.ipynb`

This project analyzes daily S&P 500 returns using time-series and spectral analysis methods. The project studies stationarity, periodic patterns, and frequency-domain properties of financial returns.

The project includes:
- downloading S&P 500 data from Yahoo Finance,
- calculation of daily returns,
- stationarity testing using ADF and KPSS tests,
- raw periodogram analysis,
- Welch periodogram estimation,
- Daniell smoothing window,
- comparison of spectral estimators,
- analysis of incomplete time-series data,
- Lomb-Scargle periodogram for missing observations.

**Main topics:** financial time series, stationarity, ADF test, KPSS test, spectral analysis, periodogram, Lomb-Scargle.

---

### 6. Econometric Model for California Housing Prices

**File:** `ekonometria.ipynb`

This project builds and evaluates an econometric model for California housing prices. The analysis uses housing market data to explain and predict median house values based on income and location-related variables.

The project includes:
- data loading and preprocessing,
- exploratory data analysis,
- visualization of housing prices and geographic patterns,
- log-transformation of variables,
- OLS regression modelling,
- train-test split,
- residual diagnostics,
- autocorrelation tests,
- heteroskedasticity tests,
- normality tests,
- multicollinearity checks,
- HAC/Newey-West robust standard errors,
- Ramsey RESET test,
- prediction on test data,
- evaluation using RMSE, MAE, MSE, and MAPE.

**Main topics:** econometrics, OLS regression, housing prices, residual diagnostics, robust standard errors, prediction.

---

## Technologies

- Python
- NumPy
- pandas
- matplotlib
- seaborn
- scikit-learn
- statsmodels
- scipy
- plotly
- yfinance
- UMAP
- HDBSCAN
- Jupyter Notebook

## Main Areas

- Data analysis
- Machine learning
- Econometrics
- Time-series analysis
- Financial data analysis
- Clustering
- Dimensionality reduction
- Macroeconomic analysis
- Statistical modelling
