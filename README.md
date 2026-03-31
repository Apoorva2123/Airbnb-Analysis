# 🏡 Airbnb Price Prediction

## 📌 Overview
This project aims to predict Airbnb listing prices using machine learning based on features like location, room type, host behavior, amenities, and reviews.
## 📂 Dataset

This project uses two main datasets:

- **Listings Data (Primary Dataset):**  
  Contains detailed information about each Airbnb property, including price, location (city, district), room type, host details, amenities, availability, and review scores.  
  This dataset serves as the main source for building the price prediction model.
- **Reviews Data (Supplementary Dataset):**  
  Includes information about user reviews such as review date and reviewer ID.  
  This data is aggregated (e.g., number of reviews, recent activity) and merged with the listings data to enrich features related to popularity and trust.

Together, these datasets provide both **property-level features** and **user engagement signals**, helping improve the accuracy of price prediction.
