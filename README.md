# police
Police Dataset Analysis 

This Python script analyzes traffic stop data to understand patterns in violations, gender-based differences, and age distributions.

Features:

Removes columns that contain only missing values.

Checks whether men or women are stopped more often for speeding violations.

Examines if gender affects the likelihood of being searched during a stop.

Analyzes stop duration by mapping textual durations to numeric values and calculating the mean.

Compares age distributions for different types of violations using groupby and descriptive statistics.

Uses box plots to visualize the relationship between driver age and type of violation.

Requirements:

Python

pandas

numpy

matplotlib

seaborn

How to Run:

Ensure the Police.csv file is downloaded on your system.

Update the file path in the script to match your file location. For example:
df = pd.read_csv("C:/Users/YourName/Downloads/Police.csv")

Run the script using Python:
python police.py
