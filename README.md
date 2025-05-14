# Istanbul Apartment Rent Price Prediction

This project focuses on predicting apartment rental prices in **Istanbul** using machine learning techniques. The goal is to create a regression model that can estimate rent prices based on apartment features such as size, number of rooms, location, and more.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Data Preparation](#data-preparation)
- [Modeling](#modeling)
- [Results](#results)
- [Usage](#usage)
- [License](#license)

## Overview

Rent prices in Istanbul can vary significantly based on region and apartment features. This project aims to build a predictive model that can help estimate monthly rental costs using historical data scraped or collected from real estate listings.

The notebook covers:

- Data loading and preprocessing  
- Feature engineering  
- Exploratory data analysis (EDA)  
- Training regression models  
- Model evaluation

## Dataset

The dataset contains features such as:

- **Location** (district/neighborhood)  
- **Square meters**  
- **Number of rooms**  
- **Floor**  
- **Building age**  
- **Heating type**  
- **Price (target variable)**

> Note: The dataset may be sourced from web scraping or a CSV file. If it’s not included in the repo, please add your own dataset in the expected format.

## Technologies Used

- Python 3  
- pandas  
- NumPy  
- scikit-learn  
- Matplotlib / Seaborn  
- XGBoost or other regressors (optional)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/bakituncher/istanbul_rent.git
cd istanbul_rent
