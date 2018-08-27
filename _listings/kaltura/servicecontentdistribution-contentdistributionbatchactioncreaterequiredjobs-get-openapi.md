---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Contentdistribution Contentdistributionbatch Action
    Createrequiredjobs
  description: creates all required jobs according to entry distribution dirty flags
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/attuversedistribution_attuverse/action/getFeed:
    get:
      summary: Get Service Attuversedistribution Attuverse Action Getfeed
      description: ""
      operationId: attUverse.getFeed
      x-api-path-slug: serviceattuversedistribution-attuverseactiongetfeed-get
      parameters:
      - in: query
        name: distributionProfileId
      - in: query
        name: hash
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Attuversedistribution
      - Attuverse
      - Action
      - GetFeed
  /service/avndistribution_avn/action/getFeed:
    get:
      summary: Get Service Avndistribution Avn Action Getfeed
      description: ""
      operationId: avn.getFeed
      x-api-path-slug: serviceavndistribution-avnactiongetfeed-get
      parameters:
      - in: query
        name: distributionProfileId
      - in: query
        name: hash
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Avndistribution
      - Avn
      - Action
      - GetFeed
  /service/comcastmrssdistribution_comcastmrss/action/getFeed:
    get:
      summary: Get Service Comcastmrssdistribution Comcastmrss Action Getfeed
      description: ""
      operationId: comcastMrss.getFeed
      x-api-path-slug: servicecomcastmrssdistribution-comcastmrssactiongetfeed-get
      parameters:
      - in: query
        name: distributionProfileId
      - in: query
        name: hash
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Comcastmrssdistribution
      - Comcastmrss
      - Action
      - GetFeed
  /service/contentdistribution_contentdistributionbatch/action/createRequiredJobs:
    get:
      summary: Get Service Contentdistribution Contentdistributionbatch Action Createrequiredjobs
      description: creates all required jobs according to entry distribution dirty
        flags
      operationId: contentDistributionBatch.createRequiredJobs
      x-api-path-slug: servicecontentdistribution-contentdistributionbatchactioncreaterequiredjobs-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Contentdistributionbatch
      - Action
      - CreateRequiredJobs
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