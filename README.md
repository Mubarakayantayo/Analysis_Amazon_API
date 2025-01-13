# Project Title: Analyzing E-commerce Product Reviews and Pricing Strategies

## Overview

This project focuses on analyzing e-commerce product reviews and pricing strategies by leveraging data from the Amazon API. The analysis includes data preprocessing, outlier handling, clustering, and regression analysis to uncover trends and insights about product pricing and customer feedback.

## Objectives

1. **Retrieve real-time product data** using the Amazon API for specific ASINs.

2. **Preprocess and normalize the dataset** for accurate analysis.

3. **Perform clustering analysis** to group products based on features.

4. **Conduct regression analysis** to predict product pricing.

5. **Visualize data** through scatter plots and heatmaps for deeper insights.

## Dataset

The dataset was programmatically acquired using the RapidAPI **"Real-Time Amazon Data"** API. The following ASINs (Amazon Standard Identification Numbers) were used to fetch product details:

**B0BR3M8XHK:** Type C Hub

**B0D8BFNBS4:** Knife Sharpener

**B0017L4PH0:** Airhead Candy

**B07WXJFFSY:** Starburst Candy

**B0CP9YBWMG:** Stanley Quencher H2.0 Tumbler

**B083L8RNJR:** TOLOCO Massage Gun

**B0CRQXPZWY:** Car Vacuum Cleaner

**B07QR4Q42L:** AstroAI Tire Inflator

**B0CXQ87QYN:** NicBex Full Length Mirror

**B07QLQ3QP4:** Air Wick Plug-in Scented Oil Starter Kit

## Key Sections

1. **E-commerce Product Analysis Using Amazon API**

 - Setup and usage of the API to acquire data.

2. **Data Acquisition and Description**

 - Description of the dataset and features retrieved from the API.

3. **Observations from the Scatter Plot**

 - Visual analysis of feature relationships.

4. **Data Normalization**

 - Scaling features to ensure uniformity.

5. **Handle Outliers**

 - Identification and handling of outliers for clean data.

6. **Analysis of the Heatmap**

 - Correlation matrix to identify relationships among features.

7. **Clustering Analysis**

 - Grouping similar products based on attributes.

## Dependencies

To run this project, ensure the following Python libraries are installed:

*pandas*

*numpy*

*matplotlib*

*seaborn*

*scikit-learn*

*requests*

*scipy*

## Installation

1. Clone this repository.

2. Install the required libraries using pip:

pip install pandas numpy matplotlib seaborn scikit-learn requests scipy

3. Obtain an API key for the **"Real-Time Amazon Data"** API from RapidAPI and configure it in the notebook.

## Usage

1. **Open the Jupyter Notebook in this repository.**

2. **Follow the sections step by step to:**

 - Fetch data from the Amazon API.

 - Process and visualize the data.

 - Perform clustering and regression analysis.

3. Review the outputs and plots generated to draw insights.

## Results

The analysis includes:

**Scatter plots** showing feature relationships.

**Heatmaps** highlighting feature correlations.

**Clustering results** to group products based on attributes.

**Regression analysis** to predict pricing trends.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

 - RapidAPI for providing the **"Real-Time Amazon Data"** API.

 - The developers of the libraries used in this project for their contributions.

