# Dataset Description

This project uses a Dubai real estate dataset to analyze property prices, market trends, and investment opportunities.

# Property Dataset
The dataset contains property listing details such as:
- Location (area-wise property distribution)
- Price (in AED)
- Bedrooms and Bathrooms
- Size (square feet)
- Property Type (Apartment, Villa, Townhouse)
- Developer information
- Year Built (if available)
- Furnishing status (if available)

# Data Processing
- Data cleaning and transformation performed using Power Query
- Removed duplicate records and handled missing values
- Converted price and size columns into numeric format
- Standardized categorical values (location, property type)

# Calculated Fields
- Price per Sqft = Price ÷ Size
- Property Age = 2025 – Year Built
- Listing Category = Budget / Mid-Range / High-End

# Final Dataset
- Cleaned and enriched dataset used for Power BI dashboard development
- Supports analysis of pricing trends, location performance, and property demand
