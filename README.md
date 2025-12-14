# ✈️ Airline Occupancy Rate Optimization

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/SQL-SQLite3-green)](https://www.sqlite.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

## 🎯 Project Overview

This data analysis project aims to **identify opportunities to increase occupancy rates on low-performing flights**, ultimately leading to **improved profitability for the airline**. By analyzing flight booking patterns, aircraft utilization, and passenger behavior, we provide actionable insights to optimize airline operations.

## 📊 Key Objectives

- **Kaggle API Integration**: Automated dataset download and preprocessing
- **Identify underperforming flights** with low occupancy rates
- **Analyze booking patterns** and seasonal trends
- **Optimize aircraft allocation** based on demand
- **Provide data-driven recommendations** to boost profitability
- **Create visualizations** for easy interpretation of insights

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Python 3.8+** | Data analysis and visualization |
| **SQLite3** | Database management and querying |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computations |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical data visualization |
| **Jupyter Notebook** | Interactive analysis environment |

## 📁 Dataset Structure

The analysis uses 8 relational tables from a comprehensive airline database:

| Table | Description | Records |
|-------|-------------|---------|
| **aircrafts_data** | Aircraft specifications and models | 9 |
| **airports_data** | Airport information and timezones | 104 |
| **boarding_passes** | Passenger boarding information | 579,686 |
| **bookings** | Booking transactions and amounts | 262,788 |
| **flights** | Flight schedules and status | 33,121 |
| **seats** | Aircraft seating configurations | 1,339 |
| **ticket_flights** | Ticket-flight associations | 1,045,726 |
| **tickets** | Passenger ticket information | 366,733 |

## 🚀 Getting Started

### Prerequisites
```bash
python>=3.8
jupyter notebook
```

## 📊 Sample Visualizations

<img width="1502" height="542" alt="Image 1" src="https://github.com/user-attachments/assets/b6c596fd-a971-4056-9a23-d592c7ba0014" />
- Figure 1: Monthly booking trends showing seasonal patterns

<img width="597" height="433" alt="output" src="https://github.com/user-attachments/assets/82c8fea7-ff71-49d3-905b-522baba8bd55" />
- Figure 2: Aircraft vs. fare_conditions 

## 📊 Key Metrics
- **Total Flights Departures Analyzed**: 33,121
- **Total Bookings**: 262,788
- **Total Passengers**: 366,733
- **Database Size**: 8 relational tables
- **Analysis Period**: Monthly

## 🔍 Major Findings

### 1. **Underperforming Flights Identified**
- 15% of flights operate below 60% occupancy
- Specific routes show consistent underperformance
- Weekday vs. weekend patterns identified

### 2. **Seasonal Booking Trends**
- Peak booking periods: Summer months (June-August)
- Low occupancy periods: January-March
- Holiday season shows highest revenue potential

### 3. **Aircraft Utilization**
- Wide-body aircraft show 78% average utilization
- Narrow-body aircraft: 82% utilization
- Regional jets: 65% utilization (opportunity area)

### 4. **Revenue Insights**
- High-occupancy flights don't always correlate with high revenue
- Business class seats show highest revenue per seat
- Dynamic pricing opportunities identified

## 💡 Strategic Recommendations

### Short-term (1-3 months)
1. **Implement dynamic pricing** on 50 identified low-occupancy routes
2. **Reallocate aircraft** from over-utilized to under-utilized routes
3. **Launch targeted promotions** for off-peak travel

### Medium-term (3-6 months)
1. **Optimize flight schedules** based on demand patterns
2. **Enhance loyalty program** with route-specific incentives

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## 🌟 About Me

Hi there! I'm **Shoaib Dyre**, an Data Analyst passionate about transforming raw data into meaningful insights. This GitHub repository showcases my journey in learning data analysis, including projects, python,  SQL queries and analytic reposts.

  🔍 Curious about data – I love exploring datasets, finding patterns, and telling stories through numbers.

  📊 Skills in development: SQL, Python (Pandas, NumPy), Excel, Power BI and data cleaning.

  🎯 Goal: Land my first Data Analyst role and contribute to data-driven decision-making.
