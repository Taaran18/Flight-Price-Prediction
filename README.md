
# Flight Price Prediction

A machine learning project designed to predict flight ticket prices based on historical data and flight details. This project builds and deploys a predictive model, offering users an intuitive web interface for obtaining price estimates.

## Overview

### Project Highlights
- **Data Exploration**: Analyze and visualize flight price datasets to uncover patterns and insights.  
- **Model Building**: Train machine learning models using features like airline, source, destination, journey dates, and departure times to predict flight prices. Evaluate and compare model performance.  
- **Web Application**: Deploy the trained model via a simple Flask web app, enabling users to interact and obtain predictions effortlessly.

### Repository Structure
- **`data_exploration.ipynb`**: Notebook for dataset analysis and visualization.  
- **`model_building.ipynb`**: Notebook for training and evaluating machine learning models.  
- **`app.py`**: Flask application that serves predictions from the trained model.  

---

## Features
- **Interactive Web Interface**: Enter flight details (e.g., airline, source, destination, journey date) to get price predictions.  
- **Customizable Inputs**: Tune predictions with optional additional flight details.  
- **Accurate Modeling**: Leverages advanced machine learning techniques for reliable price estimates.  

---

## Dependencies

This project uses the following libraries:  
- Python 3  
- NumPy  
- Pandas  
- Scikit-Learn  
- XGBoost  
- Flask  

Refer to `requirements.txt` for a complete list of dependencies.  

---

## Usage

### Running the Web Application
1. Clone the repository and navigate to the project directory.  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Start the Flask web app:  
   ```bash
   python app.py
   ```
4. Open the application in your browser at `http://localhost:5000`.

### Input Fields
Provide the following mandatory details for accurate predictions:  
- **Airline**  
- **Source**  
- **Destination**  
- **Journey Date**  
- **Departure Time**  

Additional flight details can further enhance prediction accuracy.

---

## Contribution

Contributions are welcome! You can help improve:  
- Model accuracy and feature selection.  
- User interface of the web app.  
- Bug fixes and documentation enhancements.  

---

## Author
Developed by **Taaran Jain**.  

Feel free to submit issues or pull requests to collaborate on this project.
