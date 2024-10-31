# token_blance_usd_value_by_address
# ERC20 Token Balance and USD Value Tracker

This web application allows users to fetch and display the balances of all ERC20 tokens held by a specific wallet address, along with their USD values, using the Moralis API and DexScreener API.

## Features

- Input wallet address to retrieve token balances.
- Display each token's name, symbol, balance, USD price, USD value, 24-hour price change, liquidity, market cap, and trading volume.
- Progress bar to indicate the fetching process.
- Sortable table headers for better data management.
- Total net worth display for all tokens in USD.

## Requirements

- An API key from Moralis.
- A modern web browser to run the application.

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/0xbhagi/token_blance_usd_value_by_address.git
cd token_blance_usd_value_by_address
```

### 2. Open the HTML File
Simply open the index.html file in your preferred web browser.

### 3. Enter Your Moralis API Key
In the application, find the input field labeled "Moralis API Key".
Enter your Moralis API Key.
### 4. Enter the Wallet Address
In the "Enter wallet address" field, input the wallet address you want to check.
Click the "Get Balances" button.
### 5. View Results
The application will fetch the balances and display them in a table.
The total net worth will be calculated and shown above the table.
Use the table header to sort by different columns.

### API Endpoints Used
Moralis API - Used to fetch ERC20 token balances.

Endpoint: https://deep-index.moralis.io/api/v2/{address}/erc20?chain=base
Headers: accept: application/json, X-API-Key: <YOUR_API_KEY>
DexScreener API - Used to fetch the USD value and other market data for each token.

Endpoint: https://api.dexscreener.com/latest/dex/tokens/{tokenAddress}

### Code Structure
HTML: The main layout of the application, including the search bar and table structure.
CSS: Styles for the application for better usability and visual appeal.
JavaScript: Logic to handle API calls, data processing, and UI interactions.
Contributions
Contributions are welcome! Please fork the repository and submit a pull request.

### License
This project is licensed under the MIT License.

### Contact
For any questions, feel free to contact me
