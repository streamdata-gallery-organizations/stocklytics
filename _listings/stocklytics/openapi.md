---
swagger: "2.0"
x-collection-name: Stocklytics
x-complete: 1
info:
  title: Stocklytics Intraday Historical Stock Prices API
  description: the-intraday-historical-prices-api-allows-you-to-get-a-list-of-the-price-for-a-particular-stock-for-the-current-day-or-the-latest-day-of-trading-if-markets-are-closed-in-5-minute-intervals--this-data-is-perfect-for-generating-intraday-stock-graphs-or-performing-stock-analysis-in-near-realtime--data-for-this-api-is-updated-every-5-minutes-
  version: v1
host: api.stocklytics.com
basePath: /services/pressroom/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  intradayHistoricalPrices/{API_VERSION}/:
    get:
      summary: Intraday Historical Prices
      description: The Intraday Historical Prices API allows you to get a list of
        the price for a particular stock for the current day (or the latest day of
        trading if markets are closed) in 5 minute intervals. This data is perfect
        for generating intraday stock graphs, or performing stock analysis in near
        real-time. Data for this API is updated every 5 minutes.
      operationId: getIntradayhistoricalpricesApiVersion
      x-api-path-slug: intradayhistoricalpricesapi-version-get
      parameters:
      - in: query
        name: api_key
        description: Allows us to identify the request initiator
      - in: path
        name: API_VERSION
        description: Version of the API
      - in: query
        name: format
        description: Format of returned data
      - in: query
        name: include_date
        description: Include the corresponding date and time of the data
      - in: query
        name: order
        description: Order of returned data sorted by date/time
      - in: query
        name: stock
        description: The stock code/ticker for the stock to look up
      responses:
        200:
          description: OK
      tags:
      - Intraday
      - Historical
      - Prices
---