# Datasets and APIs

_List of datasets and service APIs with __Financial Markets__ data._

- [Datasets](#datasets)
- [Service APIs](#service-apis)
  - [Explorers](#explorers)
  - [Transactions and Smart contracts decoders](#transactions-and-smart-contracts-decoders)
- [Analytics and Dashboards](#analytics-and-dashboards)
  - [OSINT](#osint)
- [News Aggregators](#news-aggregators)
  - [Fundraising](#fundraising)
  - [LLMs](#llms)


## Datasets

:warning: See [Datasets taxonomy](taxonomy.md#datasets-taxonomy) for more information about Groups column.

| Dataset / Source | Groups | Source type | Description |
|------------------|--------|-------------|-------------|
| [U.S. Securities and Exchange Commission](https://www.sec.gov/edgar/searchedgar/companysearch.html) | Fundamental data > Project metadata; Financial sentiment | Government | Public filings database for US companies |
| [Norges Bank Investment Management](https://www.nbim.no/en/the-fund/investments/#/) | Fundamental data > Project metadata | Institutional | Sovereign wealth fund investment data |
| [Nasdaq: Core US Fundamentals Data](https://data.nasdaq.com/databases/SF1/data) | Fundamental data > Valuation metrics; Fundamental data > Project metadata | Institutional | US company fundamental and financial data |
| [DataHub Economic Data](https://datahub.io/collections/economic-data) | Macroeconomic > Indicators; Alternative & supplementary data | Aggregator | Collection of global economic data feeds |
| [World Bank Open Data](https://data.worldbank.org/) | Macroeconomic > Indicators | Government | Global socioeconomic and development data |
| [Cybersyn](https://www.cybersyn.com/economic-financial/?product_id=1547) | Macroeconomic > Indicators | Commercial | Economic and financial datasets |
| [Individual household electric power consumption](https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption) | Macroeconomic > Indicators | Research dataset | Household electric power consumption data |
| [NASA NEX](https://registry.opendata.aws/nasanex/) | Macroeconomic > Indicators | Government | NASA climate and earth science data |
| [Global Ship Tracking Intelligence](https://www.marinetraffic.com/en/ais/home/centerx:152.9/centery:30.1/zoom:2) | Alternative & supplementary data; Macroeconomic > Market pressure indicators | Commercial | Real-time global ship tracking data |
| [Sanctions & export controls](https://sanctionsnews.bakermckenzie.com/resources/) | Alternative & supplementary data; Macroeconomic > Market pressure indicators | Commercial | Sanction and export control information |
| [DB Nomics](https://db.nomics.world/) ([R package](https://macro.cepremap.fr/article/2019-10/rdbnomics-tutorial/)) | Macroeconomic > Indicators; Alternative & supplementary data | Aggregator | Aggregated official economic time series |
| [Data.Gov](https://www.data.gov/) | Macroeconomic > Indicators; Alternative & supplementary data | Government | US government open data portal |
| [Commodity Futures Trading Commission](https://www.cftc.gov/MarketReports/CommitmentsofTraders/index.htm) | Market data > Derivatives markets; Market data > Exchange activity data; Macroeconomic > Market pressure indicators | Government | US commodity futures market reports |
| [Binance Public Data](https://data.binance.vision/) | Market data > Market microstructure; Market data > Derivatives markets | Exchange | Binance public historic crypto market data |
| [Public Blockchain Datasets in BigQuery](https://github.com/blockchain-etl/public-datasets) | On-chain data | Community | Crypto blockchain data BigQuery public datasets |
| [CBOE](http://cfe.cboe.com/market-data/) | Market data > Derivatives markets; Market data > Price and volume data | Exchange | CBOE futures and volatility index data |
| [Quora: publicly available market data](https://www.quora.com/What-are-some-publicly-available-market-data-feeds) | Alternative & supplementary data | Community | Community-curated list of market data sources |


Kaggle datasets list (unsuitable to production systems, but Ok for research or education purposes):

- [New York Stock Exchange](https://www.kaggle.com/dgawlik/nyse): US stock exchange end-of-day prices  
- [U.S. stocks and ETFs](https://www.kaggle.com/borismarjanovic/price-volume-data-for-all-us-stocks-etfs): Price and volume data for US stocks and ETFs  
- [S&P 500 stock data](https://www.kaggle.com/camnugent/sandp500): S&P 500 daily stock prices  
- [Binance Full History](https://www.kaggle.com/jorijnsmit/binance-full-history): Binance crypto price and volume full history  
- [Binance real time trades BTCUSDT ETHUSDT](https://www.kaggle.com/rossr61938/binance-real-time-trades-btcusdt-ethusdt): Binance real-time crypto trade data  
- [Optiver Realized Volatility Prediction](https://www.kaggle.com/c/optiver-realized-volatility-prediction/data): Order book market microstructure data  
- [Elliptic Data Set](https://www.kaggle.com/ellipticco/elliptic-data-set): Bitcoin transaction data for fraud detection  
- [Bitcoin Blockchain Historical Data](https://www.kaggle.com/bigquery/bitcoin-blockchain): Bitcoin blockchain historic data  
- [Ethereum Blockchain](https://www.kaggle.com/bigquery/ethereum-blockchain): Ethereum blockchain historic data  
- [Bitcoin Historical Data](https://www.kaggle.com/mczielinski/bitcoin-historical-data): Bitcoin price and volume historic data  
- [Complete Historical Cryptocurrency Financial Data](https://www.kaggle.com/philmohun/cryptocurrency-financial-data): Comprehensive crypto price and volume data  
- [400+ crypto currency pairs at 1-minute resolution](https://www.kaggle.com/tencars/392-crypto-currency-pairs-at-minute-resolution): Crypto pairs 1-minute resolution price data  
- [Currency Foreign Exchange Rates](https://www.kaggle.com/datasets/dhruvildave/currency-exchange-rates): Foreign exchange rates per US dollar  
- [Reddit /r/cryptocurrency](https://www.kaggle.com/nickreinerink/reddit-rcryptocurrency): Reddit cryptocurrency community sentiment  
- [Two Sigma Dataset](https://www.kaggle.com/c/two-sigma-financial-news/data): Financial news sentiment dataset  
- [Bitcoin Tweets](https://www.kaggle.com/kaushiksuresh147/bitcoin-tweets): Bitcoin-related tweets and sentiment  
- [Bitcoin Tweets - 16M tweets](https://www.kaggle.com/alaix14/bitcoin-tweets-20160101-to-20190329): Bitcoin tweets with sentiment scores  
- [Hacker News Datasets](https://www.kaggle.com/search?q=Hacker+News+in%3Adatasets): Archive of Hacker News post datasets  
- [Binance Bitcoin Futures Price](https://www.kaggle.com/billqi/binance-bitcoin-futures-price-10s-intervals): Binance Bitcoin futures price at 10s intervals.

## Service APIs

- [Quandl](https://www.quandl.com/) `#crypto` `#free`
- [CoinMarketCap](https://coinmarketcap.com/api/documentation/v1/) `#crypto` `#free`
- [IEX](https://iextrading.com/developers/docs/) and [IEX Cloud](https://iexcloud.io/docs/api/) `#crypto`
- [CryptoCompare](https://min-api.cryptocompare.com/documentation) ([C# client](https://github.com/joancaron/cryptocompare-api/tree/master/docs)) `#crypto`
- [CoinCap](https://docs.coincap.io/?version=latest) `#crypto`
- [Stocktwits](https://api.stocktwits.com/developers/docs/api) `#social` `#stocks` `#crypto` `#futures` `#forex`
- [Alpha Vantage](https://www.alphavantage.co/documentation/) `#crypto`
- [Santiment](https://neuro.santiment.net/) `#crypto` `#on-chain` `#social` `#developer-activity`
- [Brave Newcoin](https://bravenewcoin.com/developers) `#crypto`
- [Nomics](https://docs.nomics.com/) `#crypto` `#market-data`
- [Blockmodo API](https://blockmodo.com/docs/api) `#crypto`
- [Barchart API](https://www.barchart.com/ondemand/api) `#crypto`
- [Cryptocurrency Public APIs](https://github.com/public-apis/public-apis#cryptocurrency) `#index` `#crypto`
- [Finance Public APIs](https://github.com/public-apis/public-apis#finance) `#index` `#finance`
- [Intrinio API](https://docs.intrinio.com/documentation/) `#market-data` `#fundamentals` `#SEC`
- [Rank and Fiels](http://rankandfiled.com/#/data/tickers) `#SEC` `#reports`
- [OpenEDGAR](https://github.com/LexPredict/openedgar) `#SEC` `#reports` `#open-source` `#free`
- [Congressional Stock Brain](https://congressionalstockbrain.com) `#government` `#STOCK-Act` `#free`
- [FMP API](https://financialmodelingprep.com/developer/) `#market-data` `#free`
- [Markets Stack](https://marketstack.com/documentation) `#market-data`
- [FTX API](https://docs.ftx.com/#overview) `#crypto` `#algo-trading` `#market-data` `#spot` `#futures`
- [Coin Metrics Data Encyclopedia API](https://docs.coinmetrics.io/) `#crypto` `#market-data` `#on-chain`
- [Sustainalytics API](https://www.sustainalytics.com/api-data-feeds#api) `#ESG`
- [Blockchain ETL](https://github.com/blockchain-etl) `#crypto` `#blocks` `#ETL` `#OSS`
- [Blockchain.com API](https://www.blockchain.com/api) `#crypto` `#market-data` `#on-chain` `#analytics`
- [Whale Alert API](https://docs.whale-alert.io/#introduction) `#crypto` `#on-chain`
- [OpenSanctions Dataset](https://www.opensanctions.org/datasets/) `#sanctions` `#search-api`
- [Tinkoff Market Data](https://github.com/Tinkoff/investAPI/tree/main/src/marketdata) `#market-data` `#stocks` `#bonds` `#currency`
- [EtherScan](https://etherscan.io/apis) `#crypto` `#ETH` `#on-chain` `#explorers`
- [OpenFIGI API](https://www.openfigi.com/api)
- [CoinGecko API](https://www.coingecko.com/en/api/documentation) `#crypto` `#market-meta`
- [Polygon API](https://polygon.io/docs/stocks/getting-started) `#crypto` `#stocks` `#forex` `#market-data` `#free`
- [TokenLists](https://tokenlists.org/) `#crypto` `#market-meta`
- [Token Unlocks](https://token.unlocks.app/?category=all) `#crypto` `#market-meta`
- [OkLink Market Data API](https://www.oklink.com/docs/en/#market-data-kline) `#crypto` `#market-data` `#DeFi`
- [OkLink AML API](https://www.oklink.com/docs/aml_en/) `#crypto` `#risks`
- [FinHub](https://finnhub.io/) `#market-data` `#fillings` `#fundamentals` `#stock` `#crypto` [tutorial](https://analyzingalpha.com/finnhub-api-python-tutorial)
- [CoinGlass API](https://docs.coinglass.com/reference/general-information-1) `#crypto` `#futures` `#ETF`

### Explorers

- [Blockchain.com explorer](https://www.blockchain.com/explorer) `#crypto` `#on-chain`
- [ChainQuery `getrawtransaction`](https://chainquery.com/bitcoin-cli/getrawtransaction) `#crypto` `#on-chain`
- [EtherScan](https://etherscan.io/) `#crypto` `#ETH` `#on-chain`
- [CoinMarketCap blockchain explorer](https://blockchain.coinmarketcap.com/) `#crypto` `#on-chain` `#explorer`
- [BNB Smart Chain Explorer](https://bscscan.com/) `#crypto` `#BSC` `#on-chain` `#explorer`
- [BitInfoCharts](https://bitinfocharts.com/bitcoin/explorer/) `#crypto` `#on-chain` `#explorer`
-[BitInfoCharts: Blockchains stats](https://bitinfocharts.com/index_v.html)
`#crypto` `#market-meta`
- [MemPool.space](https://mempool.space/) `#crypto` `#on-chain` `#explorer`
- [OkLink](https://www.oklink.com/) `#crypto` `#on-chain` `#explorer`
- [TokenSniffer](https://tokensniffer.com/) `#crypto` `#risks`
- [BlockSec explorer](https://app.blocksec.com/explorer) `#crypto` `#on-chain` `#explorer`

### Transactions and Smart contracts decoders

- [Token Flow](https://app.tokenflow.live/anytx)
- [Etherscan API: contract module](https://api.etherscan.io/api?module=contract&action=getsourcecode&address=<some_address>&apikey=YourApiKeyToken)

## Analytics and Dashboards

- [CoinMarketCap](https://coinmarketcap.com/) `#crypto` `#market-data``#analytics`
- [ContractMarketCap](https://contractmarketcap.com/) `#crypto` `#futures` `#analytics`
- [Public Companies that Own Bitcoin](https://www.buybitcoinworldwide.com/treasuries/) `#crypto` `#stocks`
- [GlassNode Studio](https://studio.glassnode.com/metrics) `#crypto` `#analytics` `#charts`
- [IntoTheBlock](https://app.intotheblock.com/) `#crypto` `#market-data` `#on-chain` `#mining` `#social`
- [CoinGlass: Bitcoin Open Interest](https://www.coinglass.com/BitcoinOpenInterest) `#crypto` `#futures` `#analytics` `#charts`
- [DeFiLlama: Locked Value](https://defillama.com/chains) `#crypto` `#DeFi` `#analytics` `#charts`
- [Messari: DeFi Assets](https://messari.io/screener/defi-assets-7EE8EDB1) `#crypto` `#DeFi` `#analytics` `#charts`
- [Alternative Crypto Fear & Greed Index](https://alternative.me/crypto/fear-and-greed-index/) `#crypto`
- [Glassnode Insights](https://insights.glassnode.com/) `#crypto` `#insights` `#reports`
- [Skew Analytics](https://skew.com/) `#crypto` `#analytics` `#futures` `#spot`
- [Galaxy Digital Research](https://www.galaxydigital.io/research/) `#crypto` `#analytics` `DeFi` `#reports`
- [The Block reports](https://www.theblockcrypto.com/reports) `#crypto` `#analytics` `trends` `#reports`
- [The Block Charts](https://www.theblockcrypto.com/data/decentralized-finance/asset-management) `#crypto` `#DeFi` `#analytics` `#charts`
- [Dune dashboards](https://dune.com/browse/dashboards) `#crypto` `#DeFi` `#analytics` `#community`
- [Token Terminal](https://tokenterminal.com/terminal) `#crypto` `#DeFi` `#analytics` `#charts`
- [BNB Smart Chain Charts & Statistics](https://bscscan.com/charts) `#crypto` `#binance` `#charts`
- [DappRadar: industry overview](https://dappradar.com/industry-overview) `#crypto` `#DeFi` `web3` `#analytics`
- [Coin360](https://coin360.com/) `#crypto` `#analytics` `#charts`
- [GeckoTerminal](https://www.geckoterminal.com/chain-rankings) `#DeFi` `#analytics`
- [L2 Beat](https://l2beat.com/scaling/summary/) `#L2` `#bridges` `#analytics`
- [Connext scan](https://connextscan.io/)  `#L2` `#bridges` `#analytics`

### OSINT

- [SimularWeb](https://www.similarweb.com/)
- [OSINT Framework](https://osintframework.com/)
- [DNS Google](https://dns.google/)
- [OSINT: how to?](https://habr.com/ru/company/deiteriylab/blog/595801/)

## News Aggregators

- [Seeking Alpha: Microsoft news example](https://seekingalpha.com/symbol/MSFT/news) `#CeFi` `#news`
- [Bloomberg: Microsoft news example](https://www.bloomberg.com/quote/MSFT:US) `#CeFi` `#news`
- [Morningstar: Microsoft news example](https://www.morningstar.com/stocks/xnas/msft/news) `#CeFi` `#news`
- [Google Trends](https://trends.google.com/) `#news`
- [DeFi pulse](https://www.defipulse.com/) `#DeFi` `#news`
- [CoinTelegraph](https://cointelegraph.com/) `#crypto` `#news`
- [CryptoPanic](https://cryptopanic.com/) `#crypto` `#news`

### Fundraising

- [Crypto fundraising data](https://messari.io/fundraising-data) `#crypto`
- [Paradigm portfolio](https://www.paradigm.xyz/portfolio) `#crypto`
- [YCombinator companies](https://www.ycombinator.com/companies)
- [DeFi Lama raises](https://defillama.com/raises) `#crypto` `#DeFi`
- [Messari Fundraising Data](https://airtable.com/embed/shrX5Q7HqIo7hrljW/tblaqYnoeg5wjGxqB/viwSuz7UFIrHFGDwr) `#crypto`
- [HashKey Capital Portfolio](https://capital.hashkey.com/en/#portfolio) `#crypto`

### LLMs

- [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) `#forecasting` `#sentiment-analysis`
