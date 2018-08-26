---
swagger: "2.0"
x-collection-name: Tumblr
x-complete: 1
info:
  title: Tumblr
  description: ntshare-photos-mobile-apps-and-social-network-using-tumblrs-apis-n----
  version: 1.0.0
host: api.tumblr.com
basePath: /v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/likes:
    get:
      summary: Get User Likes
      description: Use this method to retrieve the liked posts that match the OAuth
        credentials submitted with the request.
      operationId: user.likes.get
      x-api-path-slug: userlikes-get
      parameters:
      - in: query
        name: limit
        description: 'The number of results to return: 1???20, inclusive'
      - in: query
        name: offset
        description: Liked post number to start at
      responses:
        200:
          description: OK
      tags:
      - User
      - Likes
---