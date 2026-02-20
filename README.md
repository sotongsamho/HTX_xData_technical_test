# HDB Resale Price Analysis & Prediction

Analysis and modeling of HDB (Housing and Development Board) resale prices in Singapore, identifying key price drivers and building predictive models.

## Project Overview

This project analyzes HDB resale transaction data from 1990 to present, identifying the primary factors influencing resale prices and building predictive models. Key findings show that **town (location)** and **flat type** are the dominant price drivers. Additionally, graph algorithms are applied to identify market structure and influential properties.

## Setup Instructions

### Prerequisites
- Python 3.12+
- pip (Python package manager)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/sotongsamho/HTX_xData_technical_test.git
cd HDB
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Running the Code

1. Open Jupyter Notebook:
```bash
jupyter notebook
```

2. Open `HTX_takehomeassessment.ipynb` and run cells sequentially

## Project Structure

```
├── HTX_takehomeassessment.ipynb
├── requirements.txt           
├── .gitignore   
├── resale-flat-prices-based-on-approval-date-1990-1999.csv 
├── resale-flat-prices-based-on-approval-date-2000-feb-2012.csv 
├── resale-flat-prices-based-on-registration-date-from-jan-2015-to-dec-2016.csv  
├── resale-flat-prices-based-on-registration-date-from-jan-2017-onwards.csv
├── resale-flat-prices-based-on-registration-date-from-mar-2012-to-dec-2014.csv
├── slides               
└── README.md

```

## Notebooks

- **HTX_takehomeassessment.ipynb**: Complete analysis including data cleaning, EDA, model training (Linear Regression & XGBoost), feature importance analysis, and graph algorithms (PageRank, Minimum Spanning Tree)

## Data Source

HDB resale transaction datasets covering 1990 to January 2017 onwards, obtained from official HDB sources.

## Requirements

See `requirements.txt` for full dependency list:
- pandas, numpy (data processing)
- scikit-learn, xgboost (modeling)
- matplotlib, seaborn (visualization)
- networkx (graph analysis)
- jupyter (notebook environment)
