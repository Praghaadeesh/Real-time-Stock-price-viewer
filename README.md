# Real-Time Stock Market Dashboard
This project is a React-based web application that allows users to track real-time stock prices. It fetches data from the Alpha Vantage API, providing users with an intuitive interface to monitor stock prices at 5-minute intervals. The dashboard displays a line chart for each tracked stock, allowing for quick visualization of price trends.

# Features
**Real-Time Data:** Fetches and displays stock prices every 5 minutes using the Alpha Vantage API.\
**Add/Remove Stocks:** Users can add any stock symbol to the dashboard and remove it when it's no longer needed.\
**Responsive Charts:** Uses Recharts to render responsive and interactive line charts for stock prices.\
**Error Handling:** Displays error messages if there's an issue with fetching stock data.

## Installation
To run the project locally, follow these steps:

### Clone the repository
```bash
git clone https://github.com/yourusername/stock-market-dashboard.git
cd stock-market-dashboard
```

### Install dependencies
```bash
npm install
```

### Start the application
```bash
npm start
```

The application will be available at http://localhost:3000.

## Screenshots
![image](https://github.com/user-attachments/assets/44e6e3e3-59cc-464e-9c21-d2de6356c50f)


## Usage
**Adding Stocks:** Enter the stock symbol (e.g., AAPL for Apple) in the input field and click "Add Stock" to start tracking its price.\
**Viewing Data:** The stock price data will be displayed in a line chart, showing the price fluctuations over time.\
**Removing Stocks:** Click the "Remove" button next to a stock symbol to stop tracking it.

## Dependencies
**React:** JavaScript library for building user interfaces.\
**Recharts:** A charting library built on React for creating responsive data visualizations.\
**Alpha Vantage API:** Provides real-time and historical stock market data.
