# UK Railway System Sales and Customer Behavior Analysis

## Overview

This project analyzes the sales performance and customer behavior of the UK Railway System using a dataset of ticket sales and destination transactions. The dataset includes various aspects such as revenue trends, top routes, customer purchase behavior, railcard usage, and operational performance (e.g., punctuality and delays). The analysis helps provide insights into the railway system's operations and customer experience.

The project is conducted using **Pandas**, **Matplotlib**, and **Seaborn** for data analysis and visualization.

## Project Goals

As a data analyst, I was tasked with answering several business-level questions for the UK Railway System, focusing on the following key areas:

### 1. **Sales Performance**
- **Revenue Trends**: Analyzing how revenues based on ticket prices vary over time (e.g., monthly, weekly).
- **Top Routes**: Identifying the top departure and arrival stations by revenue and the number of tickets sold.
- **Purchase Behavior**: Exploring the distribution of ticket purchases by type (e.g., Advance, Anytime).
- **Popular Ticket Classes**: Comparing ticket sales across different ticket classes (e.g., Standard, First).

### 2. **Customer Behavior**
- **Purchase Channels**: Determining the percentage of tickets purchased online versus at stations.
- **Payment Methods**: Analyzing the most common payment methods used for ticket purchases.
- **Railcard Usage**: Investigating how often customers use railcards and identifying the most popular railcard types.

### 3. **Operational Performance**
- **Punctuality**: Calculating the percentage of trains that arrive on time and identifying which routes or stations have the most delays.
- **Delay Causes**: Examining the most common reasons for delays and identifying routes or times when delays are more frequent.
- **Refund Requests**: Analyzing the number of refund requests made and exploring the correlation between delays and refund requests.

### 4. **Customer Experience**
- **Journey Status Analysis**: Investigating how the journey status (On Time vs. Delayed) impacts customer satisfaction, as inferred from refund requests.

## Tools and Libraries Used
- **Pandas**: Data cleaning, manipulation, and analysis.
- **Matplotlib**: Data visualization.
- **Seaborn**: Enhanced data visualization and statistical plotting.
- **Jupyter Notebook**: Used for coding, documenting, and presenting the analysis.

## Project Structure

```plaintext
├── data/
│   └── railway_dataset.csv         # Dataset used in the analysis
├── notebooks/
│   └── UK_Railway_Analysis.ipynb   # Jupyter notebook containing the full analysis
├── images/
│   └── various visualizations      # Graphs and visual outputs from the analysis
├── README.md                       # Project documentation

## Clone the repository to your local machine:
git clone https://github.com/yourusername/UK-Railway-Analysis.git

##Navigate to the project directory:
cd UK-Railway-Analysis

##Install the required dependencies:
pip install -r requirements.txt

##Open the Jupyter notebook:
jupyter notebook notebooks/UK_Railway_Analysis.ipynb

##Conclusion
This project provides valuable insights into the sales performance, customer behavior, and operational efficiency of the UK Railway System. The results can help inform decisions aimed at improving punctuality, customer satisfaction, and overall service performance.

