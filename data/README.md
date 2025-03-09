# 📊 Motor Vehicle Crashes Dataset

## 🔹 Overview
This dataset contains information about motor vehicle collisions in New York City. It includes details such as crash date, location, contributing factors, and vehicles involved.

## 🔹 File(s) in this Folder
- **`Motor_Vehicle_Collisions_-_Crashes.csv`** – The main dataset used for analysis.

## 🔹 Source
- Data is obtained from [NYC Open Data - Motor Vehicle Collisions](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95).

## 🔹 Data Description
| Column Name               | Description |
|---------------------------|-------------|
| `CRASH DATE`              | Date of crash occurrence |
| `CRASH TIME`              | Time of crash |
| `BOROUGH`                 | Borough where the crash occurred |
| `ZIP CODE`                | Zip code of crash location |
| `LATITUDE`, `LONGITUDE`   | Geolocation of crash |
| `NUMBER OF PERSONS INJURED` | Number of people injured |
| `NUMBER OF PERSONS KILLED`  | Number of fatalities |
| `CONTRIBUTING FACTOR`     | Primary cause of crash |
| `VEHICLE TYPE`            | Type of vehicle involved |

## 🔹 Usage Notes
- Ensure the dataset is stored in the `dataset/` directory.
- Use Pandas to load and process the dataset:
  ```python
  import pandas as pd
  df = pd.read_csv("dataset/Motor_Vehicle_Collisions_-_Crashes.csv")
  ```

## 🔹 License & Acknowledgements
- This dataset is provided by NYC Open Data and is publicly available.
- Ensure compliance with data usage policies when using this dataset.