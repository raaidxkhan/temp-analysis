# Temperature Sensor Data Analysis

This project analyzes temperature and humidity data recorded from a custom PCB-based temperature sensor. The goal is to compare the sensor’s data against online weather data to validate performance, detect anomalies, and understand environmental trends over a 24-hour period.

##  Project Contents

- `final24hr.html` – Full HTML report of the analysis (visuals, markdown, results)
- `project.ipynb` / `project.py` – The full Jupyter Notebook or script used
- `data_log.csv` – The raw sensor data file
- `README.md` – This project description

##  Features

- Rolling average trend smoothing
- Comparison of sensor vs. online temperature
- Heatmap analysis by hour and date
- Anomaly detection using z-score
- Correlation and error metrics
- Predictive modeling (linear extrapolation)
- Extra analysis on humidity, day-night segmentation, and sensor drift

##  Technologies Used

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

##  Key Insights

- Measured temperature tracks closely with online data, with minor localized variation.
- Drift plots help highlight offset patterns between the two sources.
- Anomaly detection reveals short bursts of unexpected behavior.
- The sensor shows reliable performance over 24 hours, with distinct day/night patterns.

## ▶ How to Run the Code

1. Clone or download the repository.
2. Ensure the required libraries are installed:
   ```bash
   pip install pandas matplotlib seaborn scipy scikit-learn
