---
swagger: "2.0"
x-collection-name: Apica
x-complete: 0
info:
  title: Alerts API Alerts Targets
  description: Gets a list of all alert targets that are visible to you as a customer.
  version: 1.0.0
host: api.serverdensity.io.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '/alerts/targets ':
    ' get ':
      summary: Alerts Targets
      description: Gets a list of all alert targets that are visible to you as a customer.
      operationId: -alerts-targets-
      x-api-path-slug: alertstargets-get
      responses:
        200:
          description: OK
      tags:
      - Alerts
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