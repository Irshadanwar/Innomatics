# Innomatics Research Labs - Data Science with GenAI Internship | Entrance Test

This repository contains my solution for the **Innomatics Research Labs Data Science with GenAI Internship Entrance Test Hackathon**. The hackathon involves working with real estate property data, including information about properties, photos, and user interactions. The goal is to clean, merge, analyze, and extract valuable insights from these datasets to answer business-related questions.

## Project Overview

The project utilizes three datasets:
1. **Property Data**: Contains detailed information about listed properties including their characteristics, location, amenities, and pricing.
2. **Property Photos Data**: Provides information about the photos uploaded for each property, which requires data cleaning to extract the number of photos.
3. **Property Interactions Data**: Captures user interactions with properties, showing how often each property was viewed or contacted.

## Datasets

### 1. Property Data
This dataset contains various attributes related to the properties listed on the platform, such as:
- `property_id`: Unique identifier for each property.
- `type`: Type of property (e.g., apartment, house).
- `activation_date`: Date when the property was activated on the platform.
- `bathroom`: Number of bathrooms in the property.
- `floor`: Floor number where the property is located.
- ... (additional columns).

### 2. Property Photos Data
This dataset contains information about the photos uploaded for each property:
- `property_id`: Unique identifier for each property.
- `photo_urls`: Corrupted JSON-like strings representing photo URLs.

### 3. Property Interactions Data
This dataset captures the interactions users have with the properties:
- `property_id`: Unique identifier for each property.
- `request_date`: Timestamp of a user interaction (e.g., contacting the owner).

## Tasks

The hackathon consists of the following tasks:

1. **Data Merging**: Combine 64 CSV files into a single DataFrame and handle data consistency and formatting.
2. **Data Cleaning**: Identify and clean common data issues, especially the corrupted photo URLs.
3. **Feature Engineering**: Create new features such as `photo_count` and `total_interactions` based on the data.
4. **Exploratory Data Analysis (EDA)**: Answer a set of business-related questions based on insights derived from the data.

## Key Insights

The goal is to answer questions related to property analysis, such as:
- Rent distribution across different locations.
- Relationship between property attributes and rent.
- Interaction trends based on property features and user behavior.
- Identification of key factors affecting rent prices, such as amenities (gym, lift, swimming pool).

## Installation

Clone this repository to your local machine:

```bash
git clone https://github.com/Irshadanwar/Innomatics-Hackathon.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

## Usage

1. Load the datasets into your local environment.
2. Perform data cleaning, merging, and feature engineering.
3. Use Pandas and other libraries to explore the data and answer the EDA questions.
4. Commit your changes regularly and submit your final answers.

## Files

- `PropertyData.csv`: Contains the property details.
- `PropertyPhotosData.csv`: Contains the photo data.
- `PropertyInteractionsData.csv`: Contains user interaction data.
- `EDA_Answers.ipynb`: Jupyter notebook containing the analysis and solutions for the questions.
- `requirements.txt`: List of required Python libraries.

## Conclusion

This project demonstrates the ability to merge large datasets, clean data, engineer features, and perform exploratory data analysis. By answering the provided business questions, we gain valuable insights into the real estate platform's properties and user interactions, which can be used for future business strategies.
