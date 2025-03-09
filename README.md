# Motor Vehicle Crashes - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project focuses on analyzing motor vehicle collisions in New York City. The objective is to explore various factors contributing to crashes, such as time of day, day of the week, vehicle models involved, and regional distribution. By leveraging data visualization techniques, we aim to identify trends and accident hotspots.

## 📊 Key Questions Addressed
1. What are the peak hours for crashes?
2. Which days of the week see the highest number of accidents?
3. How does the time of a crash relate to injury severity and fatalities?
4. Which car models are most frequently involved in crashes?
5. Which boroughs/cities experience the most crashes?
6. Where are the high-risk accident hotspots in NYC?

## 📂 Dataset Information
- **Source:** [NYC Open Data - Motor Vehicle Collisions](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)
- **Description:** Contains detailed records of motor vehicle crashes in New York City, including date, time, location, contributing factors, and vehicle types.
- **File Used:** `Motor_Vehicle_Collisions_-_Crashes.csv`

## 🛠️ Technologies Used
- **Python:** Data processing and analysis
- **Pandas, NumPy:** Data wrangling and manipulation
- **Matplotlib, Seaborn:** Data visualization
- **Folium:** Geospatial visualization

## 📈 Data Processing & Analysis Steps
1. **Data Loading:** Importing the dataset using Pandas.
2. **Data Cleaning:** Handling missing values, correcting data types, and filtering unnecessary records.
3. **Exploratory Data Analysis (EDA):** Generating descriptive statistics and visual insights.
4. **Visualization:** Using plots, heatmaps, and maps to highlight patterns and trends.
5. **Geospatial Analysis:** Mapping accident hotspots using Folium.

## 📌 Key Insights
- Identified peak accident hours and high-risk days.
- Discovered trends in crash severity based on time.
- Visualized borough-wise distribution of accidents.
- Mapped high-risk locations in NYC.

## 📜 How to Use This Project
### 🔹 Prerequisites
Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Required libraries: `pandas`, `numpy`, `seaborn`, `matplotlib`, `folium`

### 🔹 Installation
Clone this repository:
```bash
git clone https://github.com/your-github-username/EDA_motor_vehicle_crashes.git
cd EDA_motor_vehicle_crashes
```
Install dependencies:
```bash
pip install -r requirements.txt
```

### 🔹 Running the Notebook
Open Jupyter Notebook and run:
```bash
jupyter notebook
```
Then open `motor_vehicle_crashes_EDA.ipynb` and execute the cells.

## 📁 Project Structure
```
EDA_motor_vehicle_crashes/
│-- dataset/                   # Contains the raw dataset
│-- notebooks/                 # Jupyter notebooks for analysis
│-- images/                    # Visualization images (if applicable)
│-- motor_vehicle_crashes_EDA.ipynb  # Main notebook
│-- requirements.txt            # Dependencies list
│-- README.md                   # Project documentation
```

## 🤝 Contributing
Feel free to fork this repository and submit pull requests if you have improvements or new insights to add.

## 📜 License
This project is open-source and available under the MIT License.

---
🚀 **Happy Analyzing!** 🎯

