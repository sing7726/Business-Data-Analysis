# Uber Data Analysis Project

## Project Overview
This project analyzes Uber trip data to identify ride demand patterns based on time of day and day of week.

The project was inspired by my own experience working as an Uber driver in 2023. For this portfolio project, I used a public Uber trip dataset from April 2014 to practice data cleaning, feature engineering, visualization, and business insight generation.

## Dataset
The dataset contains Uber trip records from April 2014, including:

- Date and time of trip
- Latitude and longitude
- Uber base code

Dataset source: FiveThirtyEight public Uber trip data.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## Main Steps
1. Loaded the Uber trip dataset from a CSV file.
2. Explored the dataset using basic data inspection methods.
3. Converted the Date/Time column into datetime format.
4. Created new time-based columns such as hour, day, weekday, and weekday name.
5. Analyzed trip patterns by hour, day, and weekday.
6. Created visualizations to identify peak and low-demand periods.
7. Developed business insights based on the analysis.

## Key Insights
- Uber trip demand is lowest during early morning hours.
- Demand increases throughout the day and reaches higher levels during evening hours.
- Time-based features such as hour and weekday help reveal clear ride demand patterns.
- These patterns can support better driver allocation and operational planning.

## Business Recommendation
Uber can improve driver allocation by increasing driver availability during peak demand hours and reducing supply during low-demand periods. This can help reduce rider wait times and improve driver earnings.

## Skills Demonstrated
- Data cleaning
- Feature engineering
- Exploratory data analysis
- Data visualization
- Business insight generation
- Python-based analytical workflow

## Files in This Repository
- `uber_data_analysis.ipynb` — main notebook containing the full analysis
- `README.md` — project description and summary
- `requirements.txt` — Python libraries used in the project
