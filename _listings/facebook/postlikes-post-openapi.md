---
swagger: "2.0"
x-collection-name: Facebook
x-complete: 0
info:
  title: Facebook Post Add Likes
  description: Likes this post.
  version: 1.0.0
host: graph.facebook.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{album}/likes:
    get:
      summary: Get Album Likes
      description: The likes made on this album
      operationId: getAlbumLikes
      x-api-path-slug: albumlikes-get
      parameters:
      - in: path
        name: album
        description: Represents the ID of the album object
      responses:
        200:
          description: OK
      tags:
      - Album
      - Likes
    post:
      summary: Post Album Likes
      description: Likes the album
      operationId: postAlbumLikes
      x-api-path-slug: albumlikes-post
      parameters:
      - in: path
        name: album
        description: Represents the ID of the album object
      responses:
        200:
          description: OK
      tags:
      - Album
      - Likes
    delete:
      summary: Delete Album Likes
      description: Unlikes the album
      operationId: deleteAlbumLikes
      x-api-path-slug: albumlikes-delete
      parameters:
      - in: path
        name: album
        description: Represents the ID of the album object
      responses:
        200:
          description: OK
      tags:
      - Album
      - Likes
  /{checkin}/likes:
    get:
      summary: Get Checkin Likes
      description: Users who like this checkin.
      operationId: getCheckinLikes
      x-api-path-slug: checkinlikes-get
      parameters:
      - in: path
        name: checkin
        description: Represents the ID of the checkin object
      responses:
        200:
          description: OK
      tags:
      - Checkin
      - Likes
    post:
      summary: Post Checkin Likes
      description: Likes this checkin.
      operationId: postCheckinLikes
      x-api-path-slug: checkinlikes-post
      parameters:
      - in: path
        name: checkin
        description: Represents the ID of the checkin object
      responses:
        200:
          description: OK
      tags:
      - Checkin
      - Likes
    delete:
      summary: Delete Checkin Likes
      description: Unlikes this checkin.
      operationId: deleteCheckinLikes
      x-api-path-slug: checkinlikes-delete
      parameters:
      - in: path
        name: checkin
        description: Represents the ID of the checkin object
      responses:
        200:
          description: OK
      tags:
      - Checkin
      - Likes
  /{comment}/likes:
    get:
      summary: Get Comment Likes
      description: All the likes on this comment
      operationId: getCommentLikes
      x-api-path-slug: commentlikes-get
      parameters:
      - in: path
        name: comment
        description: Represents the ID of the comment object
      responses:
        200:
          description: OK
      tags:
      - Comment
      - Likes
    post:
      summary: Post Comment Likes
      description: Likes the comment
      operationId: postCommentLikes
      x-api-path-slug: commentlikes-post
      parameters:
      - in: path
        name: comment
        description: Represents the ID of the comment object
      responses:
        200:
          description: OK
      tags:
      - Comment
      - Likes
    delete:
      summary: Delete Comment Likes
      description: Unlikes the comment
      operationId: deleteCommentLikes
      x-api-path-slug: commentlikes-delete
      parameters:
      - in: path
        name: comment
        description: Represents the ID of the comment object
      responses:
        200:
          description: OK
      tags:
      - Comment
      - Likes
  /{link}/likes:
    get:
      summary: Get Link Likes
      description: Users who like this link.
      operationId: getLinkLikes
      x-api-path-slug: linklikes-get
      parameters:
      - in: path
        name: link
        description: Represents the ID of the link object
      responses:
        200:
          description: OK
      tags:
      - Link
      - Likes
    post:
      summary: Post Link Likes
      description: Likes this link.
      operationId: postLinkLikes
      x-api-path-slug: linklikes-post
      parameters:
      - in: path
        name: link
        description: Represents the ID of the link object
      responses:
        200:
          description: OK
      tags:
      - Link
      - Likes
    delete:
      summary: Delete Link Likes
      description: Unlikes this link.
      operationId: deleteLinkLikes
      x-api-path-slug: linklikes-delete
      parameters:
      - in: path
        name: link
        description: Represents the ID of the link object
      responses:
        200:
          description: OK
      tags:
      - Link
      - Likes
  /{note}/likes:
    get:
      summary: Get Note Likes
      description: Users who like this note.
      operationId: getNoteLikes
      x-api-path-slug: notelikes-get
      parameters:
      - in: path
        name: note
        description: Represents the ID of the note object
      responses:
        200:
          description: OK
      tags:
      - Note
      - Likes
    post:
      summary: Post Note Likes
      description: Likes this note.
      operationId: postNoteLikes
      x-api-path-slug: notelikes-post
      parameters:
      - in: path
        name: note
        description: Represents the ID of the note object
      responses:
        200:
          description: OK
      tags:
      - Note
      - Likes
    delete:
      summary: Delete Note Likes
      description: Unlikes this note.
      operationId: deleteNoteLikes
      x-api-path-slug: notelikes-delete
      parameters:
      - in: path
        name: note
        description: Represents the ID of the note object
      responses:
        200:
          description: OK
      tags:
      - Note
      - Likes
  /{photo}/likes:
    get:
      summary: Get Photo Likes
      description: Users who like this photo.
      operationId: getPhotoLikes
      x-api-path-slug: photolikes-get
      parameters:
      - in: path
        name: photo
        description: Represents the ID of the photo object
      responses:
        200:
          description: OK
      tags:
      - Photo
      - Likes
    post:
      summary: Post Photo Likes
      description: Likes this photo.
      operationId: postPhotoLikes
      x-api-path-slug: photolikes-post
      parameters:
      - in: path
        name: photo
        description: Represents the ID of the photo object
      responses:
        200:
          description: OK
      tags:
      - Photo
      - Likes
    delete:
      summary: Delete Photo Likes
      description: Unlikes this photo.
      operationId: deletePhotoLikes
      x-api-path-slug: photolikes-delete
      parameters:
      - in: path
        name: photo
        description: Represents the ID of the photo object
      responses:
        200:
          description: OK
      tags:
      - Photo
      - Likes
  /{post}/likes:
    get:
      summary: Get Add Likes
      description: Users who like this post.
      operationId: getAddLikes
      x-api-path-slug: postlikes-get
      parameters:
      - in: path
        name: post
        description: Represents the ID of the post object
      responses:
        200:
          description: OK
      tags:
      - Post
      - Likes
    post:
      summary: Post Add Likes
      description: Likes this post.
      operationId: postAddLikes
      x-api-path-slug: postlikes-post
      parameters:
      - in: path
        name: post
        description: Represents the ID of the post object
      responses:
        200:
          description: OK
      tags:
      - Post
      - Likes
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