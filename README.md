# Crop Recommendation System

## About the Project

This project is a Crop Recommendation System that recommends suitable crops based on soil and environmental conditions.

The system uses soil parameters such as Nitrogen (N), Phosphorus (P), Potassium (K), and pH, along with weather information to generate crop recommendations.

## Features

- Crop recommendation based on soil parameters
- Uses N, P, K and pH values
- Uses weather information such as temperature, humidity and rainfall
- Provides top recommended crops
- Machine Learning based prediction
- Weather data obtained using the OpenWeatherMap API

## Dataset

The project uses a crop recommendation dataset containing soil and environmental parameters.

The Mandi dataset used in the project was obtained from Kaggle.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Machine Learning
- OpenWeatherMap API

## Files

- `final_crop_recommendation.ipynb` – Google Colab/Jupyter Notebook containing the complete implementation.
- `Crop_recommendation.csv` – Dataset used for crop recommendation.

## Input Parameters

The system uses the following parameters:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- pH
- Temperature
- Humidity
- Rainfall

## How to Run

1. Download or clone this repository.
2. Open `final_crop_recommendation.ipynb` in Google Colab or Jupyter Notebook.
3. Upload the required dataset.
4. Provide the OpenWeatherMap API key when prompted.
5. Enter the required soil parameters.
6. Run the notebook cells.
7. The system will display the recommended crops.

## Weather API

The project uses the OpenWeatherMap API to obtain weather information.

API key should be kept private and should not be uploaded to GitHub.

## Future Improvements

- Improve prediction accuracy.
- Add more regional and seasonal data.
- Improve weather-based recommendations.
- Develop a user-friendly web/mobile interface.
- Add more datasets for better generalization.

## Project Status

Currently under development.
