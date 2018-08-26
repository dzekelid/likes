---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Post Gigme Likes Sync
  version: 1.0.0
  description: Post gigme likes sync.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/gigme/likes/sync:
    post:
      summary: Post Gigme Likes Sync
      description: Post gigme likes sync.
      operationId: postApiV1GigmeLikesSync
      x-api-path-slug: apiv1gigmelikessync-post
      parameters:
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Likes
      - Sync
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