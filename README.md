# airbnb-data-analysis

## 📌 Project Overview
This repository contains the Airbnb dataset used for data analysis and visualization.
The dataset is analyzed to understand pricing patterns, property types, host behavior,
and location-based trends.

## 📂 Dataset Information
- File Name: airbnb.csv
- Format: CSV
- Source: Public Airbnb listings data
- Rows: (add number if you want)
- Columns: (add number if you want)

## 🧾 Columns Description
Some important columns included in the dataset:
- id: Unique listing ID
- name: Name of the Airbnb listing
- neighbourhood: Area where the property is located
- room_type: Type of room (Entire home, Private room, Shared room)
- price: Price per night
- minimum_nights: Minimum nights required to book
- number_of_reviews: Total reviews received
- reviews_per_month: Average monthly reviews
- availability_365: Number of days available in a year

## 🛠 Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Google Colab
df = pd.read_csv(url)
df.head()
