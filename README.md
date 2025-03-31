# Crop-Price-Prediction

## Project Overview
Crop Price Prediction is a machine learning-powered web and mobile application designed to help farmers forecast crop prices based on various influencing factors. The goal is to provide data-driven insights to farmers, enabling them to make informed decisions and optimize their profits.

## Features
- **Accurate Price Prediction**: Uses Polynomial Regression to forecast crop prices.
- **Data-Driven Insights**: Factors in historical price trends, climate conditions, and market demand.
- **Web and Mobile Application**: Built using Flask for the web interface and Android Studio for mobile users.
- **Buyer-Farmer Direct Interaction**: Enables farmers to connect directly with buyers, reducing reliance on intermediaries.

## Technologies Used
- **Machine Learning**: Python, Scikit-learn (Polynomial Regression)
- **Data Processing**: Pandas, NumPy
- **Web Framework**: Flask
- **Mobile Development**: Android Studio
- **Database**: SQLite / Firebase (if applicable)

## Installation & Usage
1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-repo/crop-price-prediction.git
   cd crop-price-prediction
   ```
2. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the web application**:
   ```sh
   python app.py
   ```
4. **Access the application**: Open `http://127.0.0.1:5000/` in your browser.

## Dataset
The model is trained on historical crop price datasets, incorporating features such as:
- Previous price trends
- Climate conditions
- Market demand
- Sowing and harvesting timeframes

## Model Performance
The Polynomial Regression model has been optimized for accurate price predictions, achieving a reasonable error margin through hyperparameter tuning.

## Contribution
Feel free to contribute by:
- Submitting issues and feature requests
- Improving the ML model
- Enhancing the user interface

## License
This project is licensed under the MIT License - see the LICENSE file for details.
