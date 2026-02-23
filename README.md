📌 Project Overview

This project analyzes motor vehicle collision data reported by the New York City Police Department (NYPD) from January to August 2020.

Each record represents a single accident and includes:

Date and time

Borough and ZIP code

Street name

Latitude & Longitude

Vehicles involved

Contributing factors

Casualties (injuries & fatalities)

The goal of this analysis is to identify accident patterns, risk factors, and actionable safety insights.

🎯 Project Objectives

Compare percentage of total accidents by month and identify seasonal patterns.

Analyze accident frequency by day of week and hour of day.

Identify the street with the highest number of reported accidents.

Determine the most common contributing factor (Vehicle 1).

Analyze contributing factors for fatal accidents.

Generate additional insights from the dataset.

🗂 Dataset Information

Source: NYC Open Data

Reporting Authority: NYPD

Timeframe: January – August 2020

File Used: NYC_Collisions.xlsx

🛠 Tools & Technologies Used

Python

Pandas

NumPy

Matplotlib / Seaborn

Jupyter Notebook

Excel (for quick inspection)

📊 Analysis & Insights
1️⃣ Monthly Accident Distribution
% of Total Accidents by Month

The analysis showed variations in accident frequency across months.

Key Observations:

Higher accident rates occurred in early 2020.

A noticeable dip occurred during strict COVID-19 lockdown periods.

Gradual increase as restrictions eased.

Insight:
Traffic volume directly influenced accident frequency. Reduced mobility during lockdown significantly lowered collision numbers.

2️⃣ Accidents by Day of Week & Hour
🚗 Most Accident-Prone Times

Most common day: Weekdays (especially Friday)

Peak hours: Late afternoon & early evening (4 PM – 7 PM)

Reasoning:

Rush hour traffic

Increased commuter activity

Reduced visibility at dusk

Conclusion:
Accidents are strongly correlated with peak traffic hours.

Insight:
Fatal accidents tend to involve high-risk behaviors rather than minor negligence.

📈 Additional Insights
🔎 Borough-Level Observations

Manhattan and Brooklyn reported higher collision counts.

Densely populated boroughs correlate with accident frequency.

🕒 Time-Based Trends

Fewer accidents recorded during late-night hours.

Weekend patterns differ slightly from weekdays.

📍 Location Patterns

Intersections show higher accident rates than mid-block locations.

Commercial zones recorded more incidents.

📊 Dashboard

A visual dashboard was created to summarize:

Monthly accident trends

Peak accident hours

Top contributing factors

Borough comparison

Street-level analysis

📁 Repository Structure
NYC-Collisions-Analysis/
│
├── NYC_Collisions.xlsx
├── JessicaWilliam.ipynb
├── README.md
└── dashboard.png
🚀 How to Run the Project

Clone this repository:

git clone https://github.com/JessicaWilliam/NYC-Collisions-Analysis.git

Install required libraries:

pip install pandas numpy matplotlib seaborn

Open the notebook:

jupyter notebook JessicaWilliam.ipynb
📌 Key Takeaways

✔ Traffic volume significantly affects accident frequency
✔ Rush hours are the most dangerous periods
✔ Driver inattention is the leading cause of collisions
✔ Fatal accidents are more linked to high-risk behaviors


👩‍💻 Author

Jessica William
Data Analyst | Python | Data Visualization
