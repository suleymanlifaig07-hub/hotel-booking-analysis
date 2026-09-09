# Hotel Booking Analysis

## Project Overview
This project analyzes an anonymous hotel booking dataset covering the years **2015–2017**.
The main goal of the project was to analyze hotel reservation trends over time and identify the main factors that may influence booking behavior across different categories.

## Tools Used
- Python
- Pandas
- Matplotlib
- Power Query
- Power BI

## Data Cleaning
During the data cleaning process:
- Missing values were identified and analyzed.
- Duplicate records were detected and removed.
- A column containing mostly unusable or missing values was removed.
- Columns with a small number of missing values were handled using fillna().
- The dataset was prepared for further exploratory analysis.

## Exploratory Data Analysis
The EDA process included:
- groupby() analysis
- value_counts() analysis
- Correlation analysis
- Statistical summaries using describe()
- Data visualization with Matplotlib
- Outlier detection
- IQR method to calculate lower and upper boundaries for numerical variables
The main purpose of the EDA was to better understand reservation patterns and the relationships between different booking-related variables.

## Power BI Dashboard
The Power BI dashboard was created around four main KPIs:
- **Total Bookings**
- **Canceled Bookings**
- **Repeat Guests**
- **Average Daily Rate (ADR)**
These KPIs were analyzed by:
- Country
- Market Segment
- Room Type
- Year
- Month
Interactive slicers were also added so users can filter multiple categories and observe how the KPI values change.

## Key Insights
The main findings from the analysis were:
- Reservation volumes showed a declining pattern across the analyzed period.
- No single factor appeared to fully explain the decrease in reservations.
- Many reservations were made for stays of approximately **2–3 days**.
- Customer types showed relatively small differences in booking behavior.
- The **Online TA** market segment generated significantly more bookings than the other market segments.
- **Portugal (PRT)** had the highest number of bookings among the countries in the dataset.

## Dashboard Preview
![Hotel Booking Dashboard](images/Screenshot%202026-09-09%20215541.png)
