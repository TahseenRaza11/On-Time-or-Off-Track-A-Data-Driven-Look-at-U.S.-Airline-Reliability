#  ✈  On-Time-or-Off-Track-A-Data-Driven-Look-at-U.S.-Airline-Reliability

## 📌 Overview
This project explores a real-world flight delay dataset to identify patterns and factors contributing to delays in air travel. The goal is to uncover meaningful insights using data cleaning, visualization, and statistical analysis to better understand delay behavior across airlines, airports, and time.

---

## 📊 Dataset

- *Source:* [(https://www.kaggle.com/datasets/sriharshaeedala/airline-delay), e.g., Kaggle, FAA, etc.]
- *Total Records:* 171,426
- *Granularity:* Monthly flight-level summary data
- *Time Period:* Includes year and month columns

---

## 🔢 Dataset Features

| Feature | Description |
|--------|-------------|
| year | Year of the flight data |
| month | Month of the flight data |
| carrier | Airline carrier code (e.g., AA, UA) |
| carrier_name | Full name of the airline |
| airport | Airport code |
| airport_name | Full name of the airport |
| arr_flights | Total number of arrival flights |
| arr_del15 | Number of arrival flights delayed by more than 15 minutes |
| carrier_ct | Carrier-caused delay count |
| weather_ct | Weather-related delay count |
| nas_ct | National Aviation System delay count |
| security_ct | Security delay count |
| late_aircraft_ct | Delay count due to late aircraft arrival |
| arr_cancelled | Number of cancelled arrival flights |
| arr_diverted | Number of diverted arrival flights |
| arr_delay | Total arrival delay in minutes |
| carrier_delay | Delay due to the airline carrier |
| weather_delay | Delay due to weather conditions |
| nas_delay | Delay due to the national airspace system |
| security_delay | Delay caused by security issues |
| late_aircraft_delay | Delay caused by a previous flight arriving late |

---

## 🔍 Analysis Performed

- ✅ Data cleaning and type conversions  
- 📈 Exploratory Data Analysis (EDA)  
- 📊 Visualizations using seaborn and matplotlib  
- 🔍 Aggregation and comparison by carrier, airport, and time  
- 🌡 Correlation heatmap between various delay causes and total delay

---

## 📌 Key Findings

1. *Average Arrival Delay by Airline*  
   Some airlines consistently show higher average delays, highlighting operational inefficiencies.

2. *Average Arrival Delay by Month*  
   Seasonal trends observed — with higher delays during certain months (e.g., winter holidays, monsoon).

3. *Average Delay Distribution by Airport*  
   Major airports tend to have higher delay variance compared to regional ones.

4. *Correlation Heatmap*  
   Strong correlations found between arr_delay and delay components like late_aircraft_delay and carrier_delay.

---

## 🛠 Technologies & Libraries Used

- Python (Jupyter Notebook)
- pandas, numpy
- matplotlib, seaborn

---

## 🚀 Future Enhancements

- ✅ Integrate weather data for deeper causal analysis  
- ✅ Develop machine learning models to predict delays  
- ✅ Build an interactive dashboard using Streamlit or Dash

---

## 📁 Folder Structure
