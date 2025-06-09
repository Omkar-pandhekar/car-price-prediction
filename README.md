# Car Price Prediction Model 🚗

A machine learning-based web application that predicts car prices based on various features using Streamlit.

## Overview 

This project uses machine learning to predict car prices based on various features such as brand, year, kilometers driven, fuel type, and other specifications. The application is built using Python and Streamlit, providing an interactive user interface for price predictions.

## Features 

- Interactive web interface
- Real-time price predictions
- Multiple input parameters:
  - Car Brand
  - Manufacturing Year
  - Kilometers Driven
  - Fuel Type
  - Seller Type
  - Transmission Type
  - Owner History
  - Mileage
  - Engine Capacity
  - Maximum Power
  - Number of Seats

## Technical Stack 

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn (for ML model)
- Pickle (for model serialization)

## Project Structure 

```
Car-Price/
├── app.py              # Main Streamlit application
├── model.pkl           # Trained ML model
├── Cardetails.csv      # Dataset
└── Car_Price_Model.ipynb # Jupyter notebook for model development
```

## Installation 

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Car-Price.git
cd Car-Price
```

2. Install required packages:

```bash
pip install -r requirements.txt
```

## Usage

1. Run the Streamlit app:

```bash
streamlit run app.py
```

2. Open your web browser and navigate to the provided local URL (typically http://localhost:8501)

3. Input the car details using the interactive interface

4. Click "Predict" to get the estimated car price

## Model Details

The model takes into account various features to predict car prices:

- Brand name
- Manufacturing year
- Kilometers driven
- Fuel type (Petrol/Diesel/CNG/LPG)
- Seller type
- Transmission type
- Owner history
- Mileage
- Engine capacity
- Maximum power
- Number of seats

## Contributing 

Feel free to submit issues and enhancement requests!

## License 

This project is licensed under the MIT License - see the LICENSE file for details.
