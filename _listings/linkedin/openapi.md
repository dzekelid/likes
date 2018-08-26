---
swagger: "2.0"
x-collection-name: LinkedIn
x-complete: 1
info:
  title: LinkedIn
  description: bring-user-profiles-and-professional-networks-to-your-apps-
  version: 1.0.0
host: api.linkedin.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /companies/{id}/updates/key={update-key}/likes:
    get:
      summary: Get Companies Updates Key Update Key Likes
      description: Get companies  updates key update key likes
      operationId: getCompaniesUpdatesKeyUpdateKeyLikes
      x-api-path-slug: companiesidupdateskeyupdatekeylikes-get
      responses:
        200:
          description: OK
      tags:
      - Companies
      - ""
      - Updates
      - Key
      - Update
      - Key
      - Likes
---