---
swagger: "2.0"
x-collection-name: Transport for London Unified
x-complete: 0
info:
  title: Transport for London Unified Stop Point stop Point Id  Taxi Ranks
  description: Gets a list of taxi ranks corresponding to the given stop point id..
  version: v1
host: api.tfl.gov.uk
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /StopPoint/{stopPointId}/TaxiRanks:
    get:
      summary: Stop Point stop Point Id  Taxi Ranks
      description: Gets a list of taxi ranks corresponding to the given stop point
        id..
      operationId: StopPoint_GetTaxiRanksByIds
      x-api-path-slug: stoppointstoppointidtaxiranks-get
      parameters:
      - in: path
        name: stopPointId
        description: stopPointId is required to get the taxi ranks
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - Stop
      - Point
      - Id
      - ""
      - Taxi
      - Ranks
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