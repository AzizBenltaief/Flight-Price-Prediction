# ✈️ Flight Price Prediction with Random Forest

This project builds a machine learning model to predict flight ticket prices based on features such as airline, 
source and destination cities, flight duration, number of stops, and more. The dataset contains over 300,000 records of flights in India.

---

## 📁 Dataset

The dataset used is named `Clean_Dataset.csv` and contains the following columns:

| Column             | Description                              |
|--------------------|------------------------------------------|
| airline            | Name of the airline                      |
| flight             | Flight number (dropped in preprocessing) |
| source_city        | Source city                              |
| departure_time     | Departure time slot                      |
| stops              | Number of stops                          |
| arrival_time       | Arrival time slot                        |
| destination_city   | Destination city                         |
| class              | Economy or Business                      |
| duration           | Duration of the flight in hours          |
| days_left          | Days left before departure               |
| price              | Flight ticket price (target variable)    |


