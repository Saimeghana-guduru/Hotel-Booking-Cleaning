# 🏨 Hotel Booking Demand - Data Cleaning Project

## 📌 Overview
This repository contains my internship Task 1 submission for cleaning and preparing the **Hotel Booking Demand dataset**.  
The project demonstrates data wrangling, feature engineering, and documentation skills.

---

## 📂 Files Included
- **Task1.ipynb** → Jupyter Notebook with the full cleaning pipeline
- **hotel_bookings.csv** → Original raw dataset (too large to preview on GitHub, but downloadable)
- **sample_hotel_bookings.csv** → Smaller sample of the raw dataset (previewable on GitHub)
- **cleaned_hotel_bookings.csv** → Cleaned dataset after preprocessing (too large to preview, downloadable)
- **sample_cleaned_hotel_bookings.csv** → Smaller sample of the cleaned dataset (previewable on GitHub)
- **data_dictionary_with_examples.csv** → Data dictionary with descriptions and sample values
- **data_dictionary.xlsx** → Styled version with colors and borders (for presentation)

---

## 🛠️ Steps Performed
1. **Handled missing values** (children, country, agent, company, unnamed column).
2. **Dropped irrelevant/empty columns** (`company`, `Unnamed: 32`).
3. **Normalized categorical values** (meal codes, hotel names).
4. **Combined fragmented date columns** into a single `arrival_date`.
5. **Engineered new features** (`total_guests`, `stay_length`, `is_weekend`).
6. **Outlier treatment** using IQR method for `adr` and `total_guests`.
7. **Generated a professional data dictionary** with examples and descriptions.

---

## 📊 Dataset Source
Hotel Booking Demand dataset from Kaggle:  
[https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)

---

## 🚀 How to Use
- Clone the repo:
  ```bash
  git clone https://github.com/yourusername/Hotel-Booking-Cleaning-Task1.git
