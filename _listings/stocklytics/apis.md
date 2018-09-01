---
name: Stocklytics
x-slug: stocklytics
description: Build feature rich, fast applications and websites based around accurate
  stock market data. Launch in hours rather than days using the Stocklytics API. The
  Stocklytics API is a powerful, low-cost RESTful API allowing you to create stock/
  financial based apps and websites with data from our service. Such as historical
  stock price data that can be used for creating stock charts and determining trends.
  We also offer a company financial data API which allows your to get company information
  for a particular Stock Code.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stocklytics-logo.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Stocklytics
created: "2018-08-31"
modified: "2018-08-31"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stocklytics/master/_listings/stocklytics/apis.md
specificationVersion: "0.14"
apis:
- name: Stocklytics Company Data API - Company Data
  x-api-slug: companydataapi-version-get
  description: The Company Data API allows you to retrieve company information about
    a particular stock/ticker code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stocklytics-logo.png
  humanURL: http://stocklytics.com
  baseURL: https://api.stocklytics.com//
  tags: Financial News API, Finance, Stack Network, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stocklytics/master/_listings/stocklytics/companydataapi-version-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stocklytics/master/_listings/stocklytics/companydataapi-version-get-openapi.md
- name: Stocklytics Historical Stock Prices API - Historical Prices
  x-api-slug: historicalpricesapi-version-get
  description: The Historical Prices API can be used to look up the Open, Close, High
    and Low price, as well as the volume of stock traded for a stock code within a
    particular date range. The API supports the downloading the entire historical
    data set we have on file for a stock, we index data for a stock with a start date
    of January 1st 1980.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stocklytics-logo.png
  humanURL: http://stocklytics.com
  baseURL: https://api.stocklytics.com//
  tags: Financial News API, Finance, Stack Network, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stocklytics/master/_listings/stocklytics/historicalpricesapi-version-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stocklytics/master/_listings/stocklytics/historicalpricesapi-version-get-openapi.md
- name: Stocklytics Intraday Historical Stock Prices API - Intraday Historical Prices
  x-api-slug: intradayhistoricalpricesapi-version-get
  description: The Intraday Historical Prices API allows you to get a list of the
    price for a particular stock for the current day (or the latest day of trading
    if markets are closed) in 5 minute intervals. This data is perfect for generating
    intraday stock graphs, or performing stock analysis in near real-time. Data for
    this API is updated every 5 minutes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stocklytics-logo.png
  humanURL: http://stocklytics.com
  baseURL: https://api.stocklytics.com//services/pressroom/
  tags: Financial News API, Finance, Stack Network, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stocklytics/master/_listings/stocklytics/intradayhistoricalpricesapi-version-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stocklytics/master/_listings/stocklytics/intradayhistoricalpricesapi-version-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://statuspage.api.gallery.streamdata.io
- type: x-api-stack
  url: http://stocklytics.stack.network
- type: x-base
  url: http://api.stocklytics.com
- type: x-buttons
  url: http://developer.stocklytics.com/stocklytics-button/
- type: x-developer
  url: http://developer.stocklytics.com/
- type: x-key-manager
  url: http://developer.stocklytics.com/keys/
- type: x-selfservice-registration
  url: http://developer.stocklytics.com/signup/
- type: x-website
  url: http://stocklytics.com
- type: x-widgets
  url: http://developer.stocklytics.com/stock-price/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---