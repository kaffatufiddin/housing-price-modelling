# California Housing Price Prediction

## Goal
The objective of this project is to develop a price prediction model for housing in California using data from the 1990 census.

## Dataset
The dataset used for this project is the **California Housing Price Dataset**. This dataset provides housing data collected during the 1990 census and is publicly available on Kaggle.

### Features Description
The dataset contains the following features:

- **`longitude`**: A measure of how far west a house is; higher values indicate farther west.
- **`latitude`**: A measure of how far north a house is; higher values indicate farther north.
- **`housing_median_age`**: Median age of a house within a block; lower values indicate newer buildings.
- **`total_rooms`**: Total number of rooms within a block.
- **`population`**: Total number of people residing within a block.
- **`households`**: Total number of households (a group of people residing within a home unit) within a block.
- **`median_income`**: Median income for households within a block of houses (measured in tens of thousands of US Dollars).
- **`ocean_proximity`**: Location of the house relative to the ocean/sea.
- **`median_house_value`**: Median house value for households within a block (measured in US Dollars).

### Ocean Proximity Explanation
- **`ISLAND`**: Indicates the house is located on an island.
- **`<1H OCEAN`**: Indicates the house is less than one hour away from the ocean.
- **`NEAR OCEAN`**: The block is closer to the ocean than `<1H OCEAN`.
- **`NEAR BAY`**: The block is near a bay, which is a body of water connected to an ocean or lake.
- **`INLAND`**: The house is not near the coast and is located inland.

## Model Development
Several machine learning models were evaluated for predicting housing prices. The best-performing model in terms of accuracy and efficiency was the **LightGBM** model.

### Key Steps:
1. **Data Preprocessing**: Cleaning and preparing the dataset for analysis.
2. **Feature Engineering**: Creating and selecting features to enhance model performance.
3. **Model Training and Evaluation**: Training multiple models and comparing their performance.
4. **Final Model Selection**: Choosing the LightGBM model as the best-performing model.

## Author
This project was created and maintained by **Kaffatufiddin**.
