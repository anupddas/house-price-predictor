# Real Estate Price Prediction

## Overview
The Real Estate Price Prediction project aims to develop a web application that predicts housing prices in Bangalore using machine learning algorithms. The application provides users with accurate forecasts based on various features of properties, enabling informed decision-making in real estate investments.

## Features
- **User-friendly Interface**: An intuitive web interface allowing users to input property details.
- **Machine Learning Models**: Implementation of advanced machine learning algorithms to ensure accurate predictions.
- **Dynamic Price Forecasting**: Real-time predictions based on user input and historical data.

## Technologies Used
- **Backend**: Python
- **Framework**: Flask
- **Frontend**: HTML, CSS, JavaScript
- **Machine Learning Libraries**: Scikit-learn, Pandas, NumPy
- **Deployment**: Nginx on AWS EC2

## Installation
To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/real-estate-price-prediction.git
   cd real-estate-price-prediction
2. Create a virtual environment and activate it:
   ```bash
   python -m venv .venv
   .venv\Scripts\activate  # On Windows
   # source .venv/bin/activate  # On macOS/Linux
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
4. Run the server:
   ```bash
   python server.py
5. Access the application at http://127.0.0.1:5000

## Usage
1. Input property details (e.g., location, size, number of bedrooms, etc.).
2. Click on the "Predict Price" button to receive an estimated price for the property.
3. View the results displayed on the screen.

## Future Work
- Enhance the model with more features and hyperparameter tuning for improved accuracy.
- Implement user authentication for a personalized experience.
- Expand the dataset with more properties to enhance prediction capabilities.

## License
This project is licensed under the Unlicense. See the LICENSE file for details. 

## Contact
For any inquiries or feedback, feel free to reach out to me at anupddas8@gmail.com.
