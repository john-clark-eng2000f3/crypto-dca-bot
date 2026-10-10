# crypto-dca-bot

I DCA into a handful of coins and got tired of copy-pasting prices into a spreadsheet. This fetches current prices from the CoinGecko public API and appends them to a local SQLite file. I run it from cron a few times a week.

## install

pip install -r requirements.txt

## usage

python crypto_dca_bot.py

The first time you run it with no coins configured, it tells you to add some. After that, no-args fetches and logs prices.

<!-- updated: 2026-10-10 -->
