
# Mumbai Real Estate Price Prediction

## Overview
This project uses a machine learning model to predict real estate prices in Mumbai based on various parameters like location, area, number of bedrooms, and amenities such as lifts, parking, playing areas, and club houses. The predictions are powered by a Random Forest model trained on historical data from the Mumbai real estate market. The web application is built using Streamlit, which allows users to interactively specify the criteria of the property they are interested in and receive a price prediction.

## Features
- Interactive web application made with Streamlit.
- Price prediction using a trained Random Forest model.
- User input for property characteristics:
  - Location (e.g., Andheri, Bandra, Borivali)
  - Area in square feet
  - Number of bedrooms
  - Amenities (Lift, Parking, Playing Area, Club House)
  - Property condition (New or Resale)

## Installation
To run this project locally, follow these steps:
1. Clone the repository:
   ```bash
   git clone [repository-url]
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Usage
After starting the application, use the interface to select the desired location, area, number of bedrooms, and amenities. Click the "Predict" button to view the predicted price range for the specified property settings.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your updates.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

## Acknowledgements
- Thanks to all contributors who have helped in building and refining the machine learning model.
- Data provided by [Data Source Name or URL].
