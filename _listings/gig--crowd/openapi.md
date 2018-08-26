---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
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
---