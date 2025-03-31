# Crop Price Prediction

## Project Overview
Crop Price Prediction is a machine learning-powered web and mobile application designed to help farmers forecast crop prices based on various influencing factors. The goal is to provide data-driven insights to farmers, enabling them to make informed decisions and optimize their profits. By integrating historical data, climate trends, and market demand, the model improves pricing accuracy and enhances market transparency.

## Features
- **Accurate Price Prediction**: Uses Polynomial Regression to forecast crop prices with improved precision.
- **Data-Driven Insights**: Factors in historical price trends, climate conditions, and market demand to generate predictions.
- **Web and Mobile Application**: Built using Flask for the web interface and Android Studio for mobile users.
- **Buyer-Farmer Direct Interaction**: Enables farmers to connect directly with buyers, reducing reliance on intermediaries.
- **Real-Time Updates**: Dynamic updates to reflect the latest market trends.
- **User-Friendly Interface**: Simple and intuitive UI for easy interaction by farmers and traders.

## Technologies Used
- **Machine Learning**: Python, Scikit-learn (Polynomial Regression)
- **Data Processing**: Pandas, NumPy
- **Web Framework**: Flask
- **Mobile Development**: Android Studio
- **Database**: SQLite / Firebase (if applicable)
- **Visualization**: Matplotlib, Seaborn

## Installation & Usage
### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- pip (Python package manager)
- Flask
- Android Studio (for mobile app development)

### Steps to Run the Web Application
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

### Running the Mobile App
1. Open Android Studio and load the project.
2. Build and run the application on an emulator or physical device.

## Dataset
The model is trained on historical crop price datasets, incorporating features such as:
- Previous price trends
- Climate conditions (temperature, rainfall, humidity)
- Market demand and supply fluctuations
- Sowing and harvesting timeframes
- Regional variations in crop prices

## API Endpoints
If applicable, document API endpoints for fetching data and making predictions:
```sh
GET /predict_price?crop=<crop_name>&region=<region>&climate=<data>
```
Returns predicted price based on input parameters.

## Future Enhancements
- Integration of **Deep Learning Models** for higher accuracy.
- **Weather API Integration** for real-time climate data.
- **Multi-Language Support** for better accessibility to farmers.
- **Blockchain-based Smart Contracts** for secure transactions.

## Contribution
Feel free to contribute by:
- Submitting issues and feature requests.
- Improving the ML model and expanding datasets.
- Enhancing the user interface.
- Adding new features like multilingual support and AI-powered recommendations.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
