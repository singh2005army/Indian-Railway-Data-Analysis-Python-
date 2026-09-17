<h1 align="center">🚆 Indian Railways: Comprehensive Operations & Network Connectivity Analysis</h1>

## 🚀 Project Overview
This project provides an in-depth analysis of Indian Railways' scheduling and operational patterns. By leveraging data science techniques, the project explores train frequencies, corridor traffic, station connectivity, and weekly operational trends using a dataset of over 11,000 train entries.

## 🛠 Tech Stack
* **Language:** Python
* **Libraries:**
    * **pandas:** Data Manipulation & Cleaning
    * **matplotlib & seaborn:** Data Visualization
    * **numpy:** Numerical Operations
    * **networkx:** Graph Theory/Network Analysis

## 📊 Key Features & Analysis
The analysis is divided into four main levels:

1. **Exploration & Cleaning:** Standardizing station names, handling missing values, and identifying unique network nodes.
2. **Transformation & Aggregation:**
    * Calculating average daily loads per station.
    * Filtering data to identify "Suburban" vs "Long-Distance" services.
    * Corridor analysis (identifying the busiest two-way routes).
3. **Advanced Pattern Analysis:**
    * Visualization of train distribution throughout the week.
    * Correlation analysis between train types and station traffic.
4. **Reporting & Visualization:**
    * **Heatmaps:** Showing traffic intensity between top 20 stations.
    * **Network Graphs:** Representing the connectivity of the top 75 routes using `networkx`.
    * **Trend Analysis:** Line and bar charts mapping the weekly operational density.

## 📈 Key Insights
* **Busiest Hubs:** CST-MUMBAI, SEALDAH, and CHENNAI BEACH emerge as the most critical nodes in the network.
* **Weekly Trends:** Operational loads remain relatively stable, with slight peaks in mid-week and Friday schedules.
* **Traffic Composition:** A significant portion of the dataset consists of suburban/local train operations, which heavily influence the density of the urban rail network.

## 📂 Project Structure
* `Railway_info.csv`: The source dataset containing train numbers, names, routes, and operational days.
* `Railway_Analysis.ipynb`: The complete notebook containing the data pipeline from cleaning to visual reporting.

## 💡 How to Run
1. Ensure you have the required libraries installed:
   ```bash
   pip install pandas matplotlib seaborn numpy networkx
Update the file path in the read_csv function to match your local directory.
Run the notebook sequentially to reproduce the visualizations and reports.

👤 Author - 
Kshitiz Singh
