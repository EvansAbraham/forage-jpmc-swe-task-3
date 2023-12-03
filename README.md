# JPMorgan Chase & Co Software Engineering Virtual Job Simulation Task 3

## Introduction

This project consists of a client-side React application and a server-side Python application. The server displays data visually for the traders, providing market conditions and handling limit orders. The client visualizes the market data in real-time.

## Setup Instructions:

### Client-Side Setup:

1. Navigate to the project root directory.

2. Run the following command to install the necessary client-side dependencies:

   ```bash
   npm install
   ```

3. Start the client application by running:

   ```bash
   npm start
   ```

### Server-Side Setup:

1. Ensure you have Python and pip installed on your system.

2. Navigate to the project root directory.

3. Install the required server-side dependencies using pip and the provided `requirements.txt` file:

   ```bash
   pip install -r requirements.txt
   ```

4. Start the Python server by running:

   ```bash
   python datafeed/server3.py
   ```

   **Note:** Run the server from the root of the project repository.

## Usage:

- Once the server and client are set up, open a web browser and navigate to the provided address (default is http://localhost:3000/).

- Click the "Start Streaming Data" button on the webpage to initiate the data streaming from the server.

## Additional Information:

- The server simulates a trading game, providing market conditions for two stocks (ABC and DEF).

- The client visualizes the market data in real-time using a React application.

- The server-side Python application utilizes a multi-threaded HTTP server to handle requests and simulate trading scenarios.

- Market data includes stock prices, spreads, bids, and asks.

## Troubleshooting:

- If issues arise, ensure that you have followed the setup instructions correctly.

- Check for any error messages in the console or terminal where the server and client are running.

---
