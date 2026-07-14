# Weather Data Analysis & Visualization Project

## 📌 Project Overview
This project presents an end-to-end Exploratory Data Analysis (EDA) and data visualization workflow on comprehensive weather tracking datasets using Python. The objective is to extract meaningful meteorological insights by systematically cleaning datasets, computing crucial statistical indices, and mapping climate trends through advanced data visualizations.

---

## 🛠️ Tools & Technologies Used
* **Python** — Core scripting and logical execution.
* **Pandas** — Data manipulation, structured indexing, and advanced grouping.
* **NumPy** — Fast mathematical array calculations.
* **Matplotlib & Seaborn** — Professional visualization design, trend mappings, and heatmaps.
* **Git & GitHub** — Version control and codebase documentation.

---

## 📂 Dataset Description
The underlying dataset consists of timestamped environment variables containing the following metrics:
* `Date/Time`: Hourly meteorological timestamps.
* `Temp_C` / `Dew Point Temp_C`: Temperature logs in Celsius.
* `Rel Hum_%`: Relative humidity measurements.
* `Wind Speed_km/h`: Automated wind velocity recordings.
* `Visibility_km`: Horizontal clear sight range.
* `Press_kPa`: Atmospheric pressure records.
* `Weather`: Explicit descriptive weather categorization (e.g., Clear, Fog, Snow).

---

## 📊 Analytical Insights & Objective Resolutions
The Python codebase addresses 10 critical data analysis objectives:
1. **Unique Wind Speeds:** Isolated and listed all unique wind velocity instances.
2. **Clear Weather Identification:** Extracted the precise total occurrences where weather conditions were strictly 'Clear'.
3. **Targeted Wind Speed Analysis:** Counted precise instances where wind velocity measured exactly 4 km/h.
4. **Visibility Baseline:** Evaluated the mathematical global mean value for overall visibility.
5. **Atmospheric Pressure Spread:** Calculated the precise Standard Deviation (`std`) of overall pressure in kPa.
6. **Snow Records Evaluation:** Leveraged string pattern matching to flag all sub-conditions recording active snowfall.
7. **Fog Event Segmentation:** Extracted absolute instances strictly bounded to dense 'Fog'.
8. **Conditional Means Matrix:** Grouped every numeric weather variable against independent weather states to view structural averages.
9. **Compound Logical Boundaries (OR):** Isolated events where the weather condition was 'Clear' **or** horizontal visibility peaked past 40 km.
10. **High-Humidity Clear Skies (AND):** Extracted rows filtering for pristine 'Clear' windows that simultaneously held Relative Humidity indices greater than 50%.

---

## 📈 Visualizations Showcase
Below is the updated gallery showcasing the visual assets generated during the EDA workflow:

### 1. Overall Distribution of Wind Speed
A detailed histogram combined with a kernel density curve showing the frequency of different wind speed levels.
![Overall Distribution of Wind Speed](outputs/windspeed_histogram.png)

### 2. Wind Speed Spread Across Top 5 Weather Conditions
A multi-colored box plot illustrating the distribution, median values, and extreme outliers of wind speed separated by the top weather states.
![Wind Speed Spread Across Weather Conditions](outputs/t5weathercondition_box.png)

### 3. Temperature vs Relative Humidity
A scatter plot demonstrating the dense clustering and relationship patterns between atmospheric temperature and humidity metrics.
![Temperature vs Relative Humidity](outputs/tem&humidity_scatter.png)

### 4. Distribution of Temperature
An orange-themed continuous histogram mapping out the exact frequency distribution of temperature values across the collection period.
![Distribution of Temperature](outputs/temperature_histogram.png)

### 5. Temperature Trend Lines (Raw vs Aggregated)
Chronological time-series charts mapping out raw sequential records alongside aggregated seasonal variants.
![Temperature Trend Data](outputs/temperature_line.png)
![Daily Temperature Trend Over Time](outputs/temperature_trend.png)

### 6. Weather Condition Categorical Frequencies
Clean visualizations demonstrating how often categorical weather conditions occur, utilizing clean horizontal groupings and full frequency breakdowns.
![Top 10 Most Frequent Weather Conditions](outputs/weather_bar_chart.png)
![Weather Condition Frequency Count](outputs/weathercondition_bar.png)

### 7. Weather Trend Over Time
A comprehensive line chart capturing time-series fluctuations across consecutive records.
![Weather Line Chart](outputs/weather_line.png)

### 8. Share of Top 10 Weather Conditions
A clean pie chart highlighting the percentage share and proportional distribution of the most dominant weather profiles.
![Weather Distribution Pie Chart](outputs/weatherdistiributiony_pie.png)

---
