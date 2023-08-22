# CO2 Emissions Prediction from Sentinel-5P Data

## Description

This repository contains the code and information for a competition focused on predicting CO2 emissions using Sentinel-5P data. The goal is to leverage weekly extracted features from January 2019 to November 2022 to predict CO2 emissions, with the additional use of time information.

## Dataset
You can get the dataset through link : https://www.kaggle.com/competitions/playground-series-s3e20/data
The dataset consists of seven main features extracted from Sentinel-5P satellite data:

- **Sulphur Dioxide (SO2)**: Measured using COPERNICUS/S5P/NRTI/L3_SO2, with sub-features like column_number_density calculated using the DOAS technique.
- **Carbon Monoxide (CO)**: Measured using COPERNICUS/S5P/NRTI/L3_CO, including column_number_density and related sub-features.
- **Nitrogen Dioxide (NO2)**: Measured using COPERNICUS/S5P/NRTI/L3_NO2, with similar sub-features.
- **Formaldehyde (HCHO)**: Measured using COPERNICUS/S5P/NRTI/L3_HCHO, including column_number_density and more.
- **UV Aerosol Index (AER_AI)**: Measured using COPERNICUS/S5P/NRTI/L3_AER_AI.
- **Ozone (O3)**: Measured using COPERNICUS/S5P/NRTI/L3_O3.
- **Cloud**: Measured using COPERNICUS/S5P/OFFL/L3_CLOUD.

For more detailed information about each feature and how they are measured, you can refer to the provided links.

## Approach

In this project, the Ridge Regression algorithm was employed for predicting CO2 emissions. Ridge Regression was chosen due to its ability to mitigate overfitting by introducing a small penalty term. The approach involves using the extracted features along with time information to build a predictive model.


Feel free to adapt and extend the code and analysis according to your needs!

## Contributions

Contributions to this project are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
