# Datasets and APIs

_List of datasets and service APIs with __Financial Markets__ data._

- [Taxonomy](#taxonomy)
- [Datasets](#datasets)
- [Open Data](#open-data)
- [Service APIs](#service-apis)
  - [Explorers](#explorers)
  - [Transactions and Smart contracts decoders](#transactions-and-smart-contracts-decoders)
- [Analytics and Dashboards](#analytics-and-dashboards)
  - [OSINT](#osint)
- [News Aggregators](#news-aggregators)
  - [Fundraising](#fundraising)
  - [LLMs](#llms)

## Taxonomy

- Market data
  - Global identifiers
    - Currency ISO codes
    - FIGI
    - Sectors
  - Spot
    - LOB (levels)
    - OHLCVs
    - Trades
  - Derivatives
    - Open interest
    - Fear/greed index
- Financial analysis
  - Technical analysis
    - Trend indicators: SMA, EMA, sRSI, [CMF](https://corporatefinanceinstitute.com/resources/knowledge/trading-investing/chaikin-money-flow-cmf/)
    - Price diffs / log return
    - Divergences: ask/bid imbalance, sell/buy imbalance
    - Volatility
  - Fundamental analysis
    - Funds audit results
  - Ratings
- Open Data
  - Company fillings
  - Macro-economic data
  - ESG related reports (climate, carbon emission)
  - Security audit results
- News
  - News sentiment
  - News entities graph
  - Fundraising
  - Trends
- Public social networks
  - Twitter
  - reddit
- Private social networks
  - Telegram channels
  - Discord chats
- Activity
  - On-chain activity
  - Project development activity
  - Vulnerability detection activity
  - Insiders activity
  - Cargo/traffic activity

## Datasets

- [CBOE](http://cfe.cboe.com/market-data/) `#vix` `#futures`
- [DB Nomics](https://db.nomics.world/) ([R package](https://macro.cepremap.fr/article/2019-10/rdbnomics-tutorial/)) `#data-feed`
- [Commodity Futures Trading Commission](https://www.cftc.gov/MarketReports/CommitmentsofTraders/index.htm) `#commodity` `#reports`
- [U.S. stocks and ETFs](https://www.kaggle.com/borismarjanovic/price-volume-data-for-all-us-stocks-etfs) `#NYSE` `#NASDAQ` `#ETF` `#1-day-candle`
- [S&P 500 stock data](https://www.kaggle.com/camnugent/sandp500) `#sp-500` `#1-day-candle`
- [DataHub Economic Data](https://datahub.io/collections/economic-data) `#data-feed` `#macroeconomics`
- [Bitcoin Historical Data](https://www.kaggle.com/mczielinski/bitcoin-historical-data) `#bitcoin` `#1min-candle`
- [Complete Historical Cryptocurrency Financial Data](https://www.kaggle.com/philmohun/cryptocurrency-financial-data) `#crypto` `#1-day-candle`
- [New York Stock Exchange](https://www.kaggle.com/dgawlik/nyse) `#NYSE` `#sp-500` `#1-day-candle` `#fundamentals`
- [Foreign Exchange Rates 2000-2019](https://www.kaggle.com/brunotly/foreign-exchange-rates-per-dollar-20002019) `#forex` `#1-day-candle`
- [Binance Full History](https://www.kaggle.com/jorijnsmit/binance-full-history) `#crypto` `#binance` `#1min-candle`
- [Binance Bitcoin Futures Price](https://www.kaggle.com/billqi/binance-bitcoin-futures-price-10s-intervals) `#crypto` `#binance` `#futures` `#10sec-candle`
- [Binance real time trades BTCUSDT ETHUSDT](https://www.kaggle.com/rossr61938/binance-real-time-trades-btcusdt-ethusdt) `#crypto` `#binance`
- [Reddit /r/cryptocurrency](https://www.kaggle.com/nickreinerink/reddit-rcryptocurrency) `#crypto` `#community`
- [Two Sigma Dataset](https://www.kaggle.com/c/two-sigma-financial-news/data) `#news` `#sentiment` `#competition`
- [Hacker News Datasets](https://www.kaggle.com/search?q=Hacker+News+in%3Adatasets) `#hackers`
- [Optiver Realized Volatility Prediction](https://www.kaggle.com/c/optiver-realized-volatility-prediction/data) `#orderbook` `#competition`
- [Binance Public Data](https://data.binance.vision/) `#spot` `#futures` `#binance` `#crypto`
  - [Data landing](https://www.binance.com/en/landing/data)
  - [Github repo](https://github.com/binance/binance-public-data/)
- [Quora: publicly available market data](https://www.quora.com/What-are-some-publicly-available-market-data-feeds) `#data-list` `#community`
- [Elliptic Data Set](https://www.kaggle.com/ellipticco/elliptic-data-set) `#bitcoin` `#transaction` `#fraud`
- [Bitcoin Blockchain Historical Data](https://www.kaggle.com/bigquery/bitcoin-blockchain) `#bitcoin` `#blocks`
- [Public Blockchain Datasets in BigQuery](https://github.com/blockchain-etl/public-datasets) `#crypto` `#datasets` `#blocks`
- [Bitcoin Tweets](https://www.kaggle.com/kaushiksuresh147/bitcoin-tweets) `#bitcoin` `#tweets` `#sentiment` `#live`
- [Bitcoin Tweets - 16M tweets](https://www.kaggle.com/alaix14/bitcoin-tweets-20160101-to-20190329) `#bitcoin` `#tweets` `#sentiment`
- [Ethereum Blockchain](https://www.kaggle.com/bigquery/ethereum-blockchain) `#ETH` `#blocks` `#live`
- [400+ crypto currency pairs at 1-minute resolution](https://www.kaggle.com/tencars/392-crypto-currency-pairs-at-minute-resolution) `#crypto` `#1min-candle` `#live`
- [Core US Fundamentals Data](https://data.nasdaq.com/databases/SF1/data) `#fundamental` `#US`
- [Currency Foreign Exchange Rates](https://www.kaggle.com/datasets/dhruvildave/currency-exchange-rates) `#forex` `#1-day-candle`
- [Cybersyn](https://www.cybersyn.com/economic-financial/?product_id=1547) `#economics` `

## Open Data

- [U.S. Securities and Exchange Commission](https://www.sec.gov/edgar/searchedgar/companysearch.html) `#SEC` `#report`
- [Data.Gov](https://www.data.gov/) `#climate` `#healthcare` `#government`
- [World Bank Open Data](https://data.worldbank.org/) `#macroeconomics` `#world`
- [Individual household electric power consumption](https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption) `#climate`
- [NASA NEX](https://registry.opendata.aws/nasanex/) `#climate`
- [Norges Bank Investment Management](https://www.nbim.no/en/the-fund/investments/#/)
- [Global Ship Tracking Intelligence](https://www.marinetraffic.com/en/ais/home/centerx:152.9/centery:30.1/zoom:2), AIS Marine Traffic `#ship` `#geo`
- [Sanctions & export controls](https://sanctionsnews.bakermckenzie.com/resources/) `#sanctions` `#index`

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
