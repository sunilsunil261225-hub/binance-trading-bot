Binance Futures Testnet Trading Bot

Setup

Install dependencies:
pip install -r requirements.txt

Set API keys:

Windows:
set BINANCE_API_KEY=your_api_key
set BINANCE_API_SECRET=your_secret_key

Run

MARKET order:
python cli.py --symbol BTCUSDT --side BUY --type MARKET --quantity 0.001

LIMIT order:
python cli.py --symbol BTCUSDT --side SELL --type LIMIT --quantity 0.001 --price 80000

Features

- MARKET and LIMIT orders
- Logging
- CLI inputs
- Error handling