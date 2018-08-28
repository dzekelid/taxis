swagger: "2.0"
x-collection-name: Transport for London Unified
x-complete: 1
info:
  title: Transport for London Unified
  description: our-unified-api-brings-together-data-across-all-modes-of-transport-into-a-single-restful-api--this-api-provides-access-to-the-most-highly-requested-realtime-and-status-infomation-across-all-the-modes-of-transport-in-a-single-and-consistent-way--access-to-the-developer-documentation-is-available-at-httpsapi-tfl-gov-uk
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