# Sales Analytics with Python

## Project Overview
This project analyzes global sales data for a retail company operating. The main goal is to clean "dirty" raw data, compute key business metrics, and find actionable insights regarding sales performance, fulfillment speed, and seasonality.

## Data Structure
The analysis unifies data from three CSV files:
* **`events.csv`** — Transactional history and sales events.
* **`products.csv`** — Product catalog.
* **`countries.csv`** — Geographic data (countries and regions).

## Core Steps Taken

### Data Cleaning & Wrangling
* Handled missing values and corrected data type mismatches.
* Removed duplicate rows caused by whitespaces and case-sensitivity.
* Detected and filtered out outliers and operational data anomalies.

### Exploratory Data Analysis (EDA)
* Merged the datasets using Python (`pandas`).
* Analyzed revenue, profit, and order volumes by **Product Category**, **Geography**, and **Sales Channel** (Online vs. Offline).
* Evaluated fulfillment efficiency (days between order and shipping) and its impact on profit.
* Tracked sales dynamics by days of the week to identify product seasonality.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Google Colab

## Project Links
View the full code, charts, and business conclusions here:
🔗 **[Google Colab Notebook](https://colab.research.google.com/drive/10FOdOiB-2v3hTwnqybiDly5fiQrNqpaD?usp=sharing)**
