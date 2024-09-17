
# Project 2: Crimes in the USA

# Introduction

This analysis focuses on communities within the United States, utilizing a combination of socio-economic, law enforcement, and crime data. The dataset integrates socio-economic information from the 1990 U.S. Census, law enforcement statistics from the 1990 U.S. Law Enforcement Management and Administrative Statistics (LEMAS) survey, and crime data from the 1995 FBI Uniform Crime Reporting (UCR) program. Together, these sources provide a comprehensive view of the factors influencing violent crime rates across various U.S. communities during this period [1].

# Project Overview

In this project, I focused on understanding the relationship between socio-economic factors and violent crime rates in U.S. communities by leveraging three criminological theories: anomie, strain, and social differentiation. To begin, I cleaned and pre-processed the dataset to ensure accuracy and consistency. After preparing the data, I conducted a thorough analysis to identify key variables that align with the chosen theories. Based on this analysis, I developed three multiple regression models, each corresponding to one of the criminological frameworks. These models aim to explain how the socio-economic conditions tied to each theory can help understand and predict crime patterns in different communities.

# Dataset

The "Communities and Crime" dataset combines socio-economic data from the 1990 U.S. Census, law enforcement data from the 1990 Law Enforcement Management and Administrative Statistics (LEMAS) survey, and crime data from the 1995 FBI Uniform Crime Reporting (UCR) program. It includes 1994 observations and 128 variables that capture a range of factors such as income levels, education, employment, and family structure. The target variable is the violent crime rate per population, making this dataset useful for exploring how community-level socio-economic indicators relate to crime rates across different U.S. communities [1].


# Scope and Limitations

# Scope

This project aims to explore the relationship between community-level socio-economic factors and violent crime rates using the "Communities and Crime" dataset. The analysis focuses on understanding how various socio-economic indicators, such as income, education, unemployment, and family structure, might influence crime. By creating multiple regression models based on criminological theories like anomie, strain, and social differentiation, this study seeks to provide insights into the underlying mechanisms driving violent crime rates across different U.S. communities. The findings can contribute to developing prevention strategies and policies aimed at reducing crime through community interventions.

# Limitations

* Data Timeframe: The socio-economic data is from 1990, and the crime data is from 1995. This temporal gap may limit the accuracy of analyzing current crime trends or more recent shifts in socio-economic conditions.
* Missing Data: The dataset contains missing values for several communities, which may reduce the reliability of the results if key data points are missing.
* Geographical Limitations: The dataset only covers U.S. communities, limiting the generalizability of the findings to other countries with different socio-economic and cultural contexts.
* Assumed Causal Relationships: While the regression models can show correlations between socio-economic factors and crime rates, they do not prove direct causality. Other unobserved factors could influence crime rates.
* Multicollinearity: Some variables in the dataset may be highly correlated, potentially leading to issues with multicollinearity in the regression models, which could distort the significance of the predictors.
* Simplified Theories: The application of criminological theories like anomie, strain, and social differentiation is simplified to fit a quantitative model, and some nuances of these theories may not be fully captured through the available data.


# Future Work 

For future work, additional criminological theories could be explored to enhance the understanding of crime patterns. Additionally, refining the existing models by including or excluding specific variables could improve accuracy and provide a more comprehensive explanation of the factors influencing violent crime. This approach may lead to more robust and insightful models, offering better predictive capabilities and deeper theoretical applications.

# Getting Started

To replicate or build upon this analysis, follow these steps:

Download the Dataset: Obtain the dataset from Link<https://archive.ics.uci.edu/dataset/183/communities+and+crime>

Data Overview: Review the variable descriptions and examine the statistical summary of each variable (see summarystatistics and variabledescription). Analysis: Use the provided scripts and tools for conducting the descriptive analysis. Results: Review the findings, interpretations and insights under each model in the file. 

# Tools and Libraries

* Python
* SQL
* Pandas
* Numpy
* Matplotlib/Seaborn/Plotly (for visualization)
* Jupyter Notebook (optional, for interactive analysis)

# Files Included
* Crimes_in_the_USA.ipynb (Jupyter notebook with analysis and findings)
* requirements: The required libraries
* summarystatistics
* variabledescription

# Contributing
If you have suggestions for improving the analysis or expanding the scope, please feel free to contribute. Open issues and pull requests are welcome.

# Contact
For questions or further information, please contact Eva Milona at evamilona1@gmail.com.

# References

[1] UCI Machine Learning Repository. (1999). Communities and Crime Data Set. Link:<https://archive.ics.uci.edu/dataset/183/communities+and+crime>

