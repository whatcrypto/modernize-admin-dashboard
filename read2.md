# WhatCrypto Web Application

WhatCrypto is a cryptocurrency portfolio management tool that provides real-time buy/sell signals, model portfolios, and insights for crypto traders and investors. This platform helps users make data-driven investment decisions by monitoring the performance of selected cryptocurrencies.

## Features

- **Dashboard**: Overview of portfolio performance, recent transactions, and asset allocation.
- **Model Portfolios**: Curated lists of coins expected to grow (e.g., 10X, 20X, 50X, 100X portfolios).
- **Trading Signals**: Real-time buy/sell alerts based on technical analysis.
- **Coin Details**: Comprehensive view of each coin’s performance, technical indicators, and price charts.
- **Insights**: Key alerts like buy points, sell points, and new portfolio additions/removals.
- **Alerts**: Get notifications for significant price movements and volume changes.
- **Membership Plans**: Offer different tiers of membership with varying levels of access.


## How to Set Up

### Prerequisites

- Node.js & npm installed
- React knowledge
- Vercel account for deployment
- Airtable account for data management

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/whatcrypto/whatcrypto-webapp.git

2. mkdir

mkdir whatcrypto
cd whatcrypto

# Creating main project folders
mkdir components pages layouts styles data utils services config

# Creating subfolders for specific features
cd components
mkdir Dashboard ModelPortfolios TradingSignals CoinDetails Insights Alerts

cd ../pages
mkdir api portfolio signals coins insights

# Back to root for additional files
cd ..
touch README.md .env .gitignore


Install dependencies:

npm install

Create a .env file with your Airtable and API keys:

AIRTABLE_API_KEY=<your_airtable_api_key>
COIN_API_KEY=<your_coinmarketcap_or_other_api_key>

Run the development server:

npm run dev

Open http://localhost:3000/ to view the app.

Deployment

To deploy on Vercel:

Install Vercel CLI:

npm install -g vercel vercel



Technologies Used

React: Frontend framework for building components.
Next.js: Server-side rendering and API routes.
Airtable: For managing cryptocurrency and portfolio data.
Vercel: Hosting and deployment.
Tailwind CSS: Styling framework for responsive design.
ApexCharts: Interactive cryptocurrency price charts.

Roadmap

Add user authentication with Firebase.
Expand portfolios to include DeFi and NFT assets.
Create custom portfolio feature for users.
Add more technical indicators (Bollinger Bands, MACD).

whatcrypto/
│
├── components/
│   ├── Dashboard/
│   ├── ModelPortfolios/
│   ├── TradingSignals/
│   ├── CoinDetails/
│   ├── Insights/
│   ├── Alerts/
│
├── pages/
│   ├── api/        # For backend APIs like fetching live prices, etc.
│   ├── portfolio/  # Portfolio pages
│   ├── signals/    # Buy/Sell signals pages
│   ├── coins/      # Specific coin detail pages
│   ├── insights/   # Insights and alerts
│
├── layouts/         # Reusable layouts
├── styles/          # Global CSS, Tailwind CSS config, etc.
├── data/            # Static data like portfolio compositions
├── utils/           # Utility functions like formatters
├── services/        # Services for API calls, Airtable integrations
├── config/          # Global app config, constants
├── .env             # Environment variables like API keys
├── .gitignore       # Git ignore file
└── README.md        # Project documentation
