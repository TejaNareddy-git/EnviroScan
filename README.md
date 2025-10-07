# EnviroScan:AI-Powered Pollution Source Identifier using  Geospatial Analytics 
# EnviroScan: Andhra Pradesh Pollution Dashboard

This project is a Streamlit app that visualizes pollution data for Andhra Pradesh. It allows users to filter by city and date, explore pollution trends, source distributions, and view map-based alerts. It also supports SMS alerts for threshold breaches using Twilio.

## Features
- Trend analysis of major pollutants
- Source distribution pie chart with clear labels
- Geographic pollution heatmaps and alerts
- SMS notification for threshold violations
- Data download facility

## Installation

1. Clone the repo:
https://github.com/TejaNareddy-git/EnviroScan

2. Install dependencies:
pip install -r requirements.txt


3. Obtain Twilio credentials and add them in `.streamlit/secrets.toml`:
twilio_account_sid = "your_sid_here"
twilio_auth_token = "your_auth_token_here"
twilio_from_number = "+1234567890"

4. Run the app:
streamlit run dashboard.py


## Data

The project uses `processed_pollution_data.csv` as the sample dataset.

## License

MIT License or specify your preferred license.




