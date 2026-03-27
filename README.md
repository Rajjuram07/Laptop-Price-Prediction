# Laptop Price Prediction

## Project Description
This project predicts the price of laptops based on various features such as brand, type, RAM, weight, touchscreen, screen size, resolution, CPU, HDD, SSD, GPU, and operating system. The prediction model is trained using machine learning techniques on a dataset of laptop specifications and prices.

The project includes a Streamlit web application (`app.py`) that allows users to input laptop specifications and get an estimated price prediction.

## Installation

1. Clone the repository or download the project files.
2. Install the required Python packages using:

```
pip install -r requirements.txt
```

## How to Run

To run the Streamlit app, use the following command in the project directory:

```
streamlit run app.py
```

This will launch a web interface where you can select laptop features and get a price prediction.

## Project Files

- `app.py`: Streamlit application for laptop price prediction.
- `LaptopPricePrediction.ipynb`: Jupyter notebook containing data analysis, preprocessing, and model training.
- `laptop_data.csv`: Dataset containing laptop specifications and prices.
- `pipe.pkl`: Serialized machine learning model pipeline used for prediction.
- `df.pkl`: Serialized dataframe used in the app for feature options.

## Dependencies

The project uses the following Python libraries:

- streamlit
- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn
- xgboost

## Acknowledgements

This project is developed as part of a machine learning minor project.
