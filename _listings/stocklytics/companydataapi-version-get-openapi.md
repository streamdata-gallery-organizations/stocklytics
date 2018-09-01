---
swagger: "2.0"
x-collection-name: Stocklytics
x-complete: 0
info:
  title: Stocklytics Company Data API Company Data
  description: The Company Data API allows you to retrieve company information about
    a particular stock/ticker code.
  version: v1
host: api.stocklytics.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  companyData/{API_VERSION}/:
    get:
      summary: Company Data
      description: The Company Data API allows you to retrieve company information
        about a particular stock/ticker code.
      operationId: getCompanyData
      x-api-path-slug: companydataapi-version-get
      parameters:
      - in: query
        name: api_key
        description: Allows us to identify the request initiator
      - in: path
        name: API_VERSION
        description: Version of the API
      - in: query
        name: stock
        description: The stock code/ticker for the stock to look up
      responses:
        200:
          description: OK
      tags:
      - Companies
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---