# Water Level Prediction with MLP Neural Network

This repository contains a Jupyter Notebook (`Water_Level_Prediction.ipynb`) that demonstrates water level prediction using a Multi-Layer Perceptron (MLP) Neural Network. The goal is to predict water levels based on various environmental factors such as evaporation, salinity, and precipitation.

## Requirements

- numpy
- pandas
- keras
- sklearn
- matplotlib

## Data

The data is loaded from the file `waterlevels.csv`, which contains the following columns:
- `Date`: The date of the data entry
- `Evaporation`: Evaporation rate in the environment
- `Salinity`: Salinity level in the water
- `Precipitation`: Precipitation rate
- `Water Level`: The target variable to predict, i.e., the water level

## Data Preprocessing

The data is normalized using Min-Max scaling to bring all features within the range [0, 1]. The target variable (`Water Level`) is also scaled to facilitate neural network training.


## Results

The trained model is saved as `model.h5` for future use.

## How to Use

To run the notebook, ensure that you have the required dependencies installed. You can install them using pip:
```shell
pip install numpy pandas keras scikit-learn matplotlib
```


Then, open the Jupyter Notebook `Water_Level_Prediction.ipynb` and execute each cell to run the entire pipeline.

Feel free to explore the code, modify the model architecture, or use different datasets for water level prediction.

## Note

The provided data and model are for demonstration purposes only and may not represent a production-ready solution. For real-world applications, consider collecting more data, optimizing the model architecture, and performing further evaluations.

