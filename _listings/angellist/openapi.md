swagger: "2.0"
x-collection-name: AngelList
x-complete: 1
info:
  title: AngelList
  description: the-angellist-api-provides-developers-with-a-restful-interface-to-the-angellist-data-set--for-more-information-read-the-oauth-faq-
  termsOfService: https://angel.co/terms
  contact:
    name: AngelList
    url: https://angel.co/api
    email: api@angel.co
  version: v1
host: api.angel.co
basePath: /1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /like:
    post:
      summary: Add Like
      description: Add like.
      operationId: like
      x-api-path-slug: like-post
      parameters:
      - in: query
        name: likable_id
      - in: query
        name: likable_type
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Likes
  /likes:
    get:
      summary: Get Likes
      description: Get likes
      operationId: likes
      x-api-path-slug: likes-get
      parameters:
      - in: query
        name: likable_id
      - in: query
        name: likable_type
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Likes
    post:
      summary: Add Like
      description: Add Like
      operationId: likes
      x-api-path-slug: likes-post
      parameters:
      - in: query
        name: likable_id
      - in: query
        name: likable_type
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Likes
  /likes/{like_id}:
    delete:
      summary: Delete Like
      description: Delete Like
      operationId: likes
      x-api-path-slug: likeslike-id-delete
      parameters:
      - in: query
        name: likable_type
      - in: path
        name: like_id
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Likes