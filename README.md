# House Price Prediction

This project uses regression models to predict the price of a house given features such as the number of bedrooms, bathrooms, square footage, renovation status, and more.

## Getting Started

1. **Install dependencies**  
   Run the following command in the terminal where this project is located:

   ```
   pip install -r requirements.txt
   ```

2. **Exploratory Data Analysis (EDA) and Preprocessing**  
   - The EDA and preprocessing steps are in `notebooks/EDA.ipynb`.
   - Steps include:
     - Data cleaning (removing nulls, outliers, and unnecessary columns)
     - Feature encoding (ordinal encoding for city, numeric conversion for statezip)
     - Feature scaling (standardization and normalization)
     - Data visualization for understanding distributions and correlations

3. **Preprocessed Data**  
   - The cleaned dataset is saved as `data/cleaned_data.csv` after running the EDA notebook.

4. **Model Training**  
   - Use the cleaned data for training regression models (see additional notebooks/scripts for model training and evaluation).

## Project Structure

```
house-price-prediction-ML/
│
├── data/
│   ├── data.csv
│   └── cleaned_data.csv
├── notebooks/
│   └── EDA.ipynb
├── requirements.txt
└── README.md
```

## Notes

- The EDA notebook provides detailed visualizations and explanations for each preprocessing step.
- Make sure to run the EDA notebook before training any models to ensure you are using the cleaned data.