 # Business Calculator

A lightweight business tool that combines real-time currency conversion with live business news headlines.
Enter a country code, amount, and target currency — it converts the value and pulls the latest business news for that country.

## What It Does

- Accepts currency codes (e.g. KES, USD, UGX, TZS), amount, and target currency
- Fetches live exchange rates via ExchangeRate-API
- Converts amount instantly (e.g. 5000 KES to USD)
- Generates top 3 business news headlines for the source country via NewsAPI
- Validates all inputs before search

## Setup

No install needed. This is a single-file frontend app.

You will need 2 free API keys:

1. **ExchangeRate-API Key:** https://www.exchangerate-api.com/
2. **NewsAPI Key:** https://newsapi.org/

Clone or download `index.html` and open in your browser.

## Usage

1. Enter country code e.g `KES`, `USD`, `UGX`
2. Enter amount e.g `5000`
3. Enter final currency e.g `USD`
4. Paste your ExchangeRate API key and News API key
5. Click **Search**

```html
Country: KES
Amount: 5000
Target: USD
