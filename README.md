# VJ-stock-trading-app

This is a semi-automated decision-support stock trading application that fetches real-time stock data and displays it in a web dashboard. It includes trading signals and basic risk management.

## Features
- Real-time stock data (using Alpaca API).
- Moving Average Crossover strategy for trade signals.
- Interactive web-based dashboard (React).

## Installation
### Backend (Flask)
1. Navigate to the `backend` folder.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the server:
   ```bash
   python app.py
   ```

### Frontend (React)
1. Navigate to the `frontend` folder.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the React app:
   ```bash
   npm start
   ```

## Deployment
- Flask backend: Deploy on Heroku or AWS Lambda.
- React frontend: Deploy on Netlify or Vercel.

## Notes
Replace placeholder API keys in the `backend/app.py` file with your actual Alpaca API credentials.
