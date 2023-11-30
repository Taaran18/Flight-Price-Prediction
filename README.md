# Flight Price Prediction
This project aims to predict flight ticket prices based on historical data. It uses machine learning (ML) to build a model that can predict prices of upcoming flights given other relevant details.

## Overview
- `data_exploration.ipynb` - Explores and visualizes the flight price dataset to gain insights 
- `model_building.ipynb` - Trains ML models to predict flight prices based on details like airline, source location, destination location, dates of travel etc. Evaluates performance of models
- `app.py` - Simple Flask web app to get flight price predictions from trained ML model based on user inputs

## Usage
The trained flight price predictor model is served through a simple web interface built in Flask.

### Dependencies
- Python 3, NumPy, Pandas, Scikit-Learn, XGBoost, Flask
- See `requirements.txt` for all dependencies 

### Running Web App
```
$ python app.py
```
The app will be served at `http://localhost:5000`

Enter relevant flight details like airlines, source, destination etc. and the predicted flight price will be displayed. At least the following fields need to be provided for an accurate price estimate:
* Airline
* Source 
* Destination
* Journey Date
* Departure Time

There are additional options to further tune the prediction if more flight details are known.

## Contributors
Contributions to improve model accuracy, add features or fix bugs are welcome!

- Taaran Jain

Let me know if you need any changes or have additional sections that you would like covered in the README!