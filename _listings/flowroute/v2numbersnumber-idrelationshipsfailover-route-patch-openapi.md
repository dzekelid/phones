---
swagger: "2.0"
x-collection-name: Flowroute
x-complete: 0
info:
  title: FlowRoute API Update Failover Voice Route for a Phone Number
  description: Use this endpoint to update the failover voice route for a phone number.
    You must create the route first by following "Create an Inbound Route". You can
    then assign the created route by specifying its value in a PATCH request.
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/numbers/{number_id}/relationships/failover_route:
    patch:
      summary: Update Failover Voice Route for a Phone Number
      description: Use this endpoint to update the failover voice route for a phone
        number. You must create the route first by following "Create an Inbound Route".
        You can then assign the created route by specifying its value in a PATCH request.
      operationId: use-this-endpoint-to-update-the-failover-voice-route-for-a-phone-number-you-must-create-the-route-fi
      x-api-path-slug: v2numbersnumber-idrelationshipsfailover-route-patch
      parameters:
      - in: path
        name: number_id
        description: The phone number in E
      responses:
        200:
          description: OK
      tags:
      - Messaging
      - Failover
      - Voice
      - Routea
      - Phone
      - Number
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