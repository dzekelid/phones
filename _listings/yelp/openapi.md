swagger: "2.0"
x-collection-name: Yelp
x-complete: 1
info:
  title: Yelp V3
  description: yelps-fusion-api-allows-you-to-get-the-best-local-business-information-and-user-reviews-of-over-million-businesses-in-32-countries
  version: 1.0.0
host: api.yelp.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /businesses/search/phone:
    get:
      summary: Get Businesses Search Phone
      description: Get businesses search phone.
      operationId: getBusinessesSearchPhone
      x-api-path-slug: businessessearchphone-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: phone
      responses:
        200:
          description: OK
      tags:
      - Businesses
      - Search
      - Phone