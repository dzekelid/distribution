---
swagger: "2.0"
x-collection-name: AWS CloudFront
x-complete: 0
info:
  title: AWS CloudFront API Get Streaming Distribution Config
  version: 1.0.0
  description: Get the configuration information about a streaming distribution.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateDistribution:
    get:
      summary: Create Distribution
      description: Creates a new web distribution.
      operationId: createDistribution
      x-api-path-slug: actioncreatedistribution-get
      parameters:
      - in: query
        name: CreateDistributionRequest
        description: Root level tag for the CreateDistributionRequest parameters
        type: string
      - in: query
        name: DistributionConfig
        description: The distributions configuration information
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this request
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: VpcIds.N
        description: One or more VPC IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Distribution
  /?Action=CreateDistributionWithTags:
    get:
      summary: Create Distribution With Tags
      description: Create a new distribution with tags.
      operationId: createDistributionWithTags
      x-api-path-slug: actioncreatedistributionwithtags-get
      parameters:
      - in: query
        name: CreateDistributionWithTagsRequest
        description: Root level tag for the CreateDistributionWithTagsRequest parameters
        type: string
      - in: query
        name: DistributionConfigWithTags
        description: The distributions configuration information
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance to unlink from the VPC
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC to which the instance is linked
        type: string
      responses:
        200:
          description: OK
      tags:
      - Distribution
      - Tags
  /?Action=CreateStreamingDistribution:
    get:
      summary: Create Streaming Distribution
      description: Creates a new RMTP distribution.
      operationId: createStreamingDistribution
      x-api-path-slug: actioncreatestreamingdistribution-get
      parameters:
      - in: query
        name: CreateStreamingDistributionRequest
        description: Root level tag for the CreateStreamingDistributionRequest parameters
        type: string
      - in: query
        name: StreamingDistributionConfig
        description: The streaming distributions configuration information
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - Streaming
      - Distribution
  /?Action=CreateStreamingDistributionWithTags:
    get:
      summary: Create Streaming Distribution With Tags
      description: Create a new streaming distribution with tags.
      operationId: createStreamingDistributionWithTags
      x-api-path-slug: actioncreatestreamingdistributionwithtags-get
      parameters:
      - in: query
        name: CreateStreamingDistributionWithTagsRequest
        description: Root level tag for the CreateStreamingDistributionWithTagsRequest
          parameters
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: StreamingDistributionConfigWithTags
        description: The streaming distributions configuration information
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - Streaming
      - Distribution
      - Tags
  /?Action=DeleteDistribution:
    get:
      summary: Delete Distribution
      description: Delete a distribution.
      operationId: deleteDistribution
      x-api-path-slug: actiondeletedistribution-get
      parameters:
      - in: query
        name: BgpAsn
        description: For devices that support BGP, the customer gateways BGP ASN
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: Id
        description: The distribution ID
        type: string
      - in: query
        name: If-Match
        description: The value of the ETag header that you received when you disabled
          the      distribution
        type: string
      - in: query
        name: IpAddress
        description: The Internet-routable IP address for the customer gateways outside
          interface
        type: string
      - in: query
        name: Type
        description: The type of VPN connection that this customer gateway supports
          (ipsec
        type: string
      responses:
        200:
          description: OK
      tags:
      - Distribution
  /?Action=DeleteStreamingDistribution:
    get:
      summary: Delete Streaming Distribution
      description: Delete a streaming distribution.
      operationId: deleteStreamingDistribution
      x-api-path-slug: actiondeletestreamingdistribution-get
      parameters:
      - in: query
        name: CustomerGatewayId
        description: The ID of the customer gateway
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: Id
        description: The distribution ID
        type: string
      - in: query
        name: If-Match
        description: The value of the ETag header that you received when you disabled
          the      streaming distribution
        type: string
      responses:
        200:
          description: OK
      tags:
      - Streaming
      - Distribution
  /?Action=GetDistribution:
    get:
      summary: Get Distribution
      description: Get the information about a distribution.
      operationId: getDistribution
      x-api-path-slug: actiongetdistribution-get
      parameters:
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: HostId.N
        description: The IDs of the Dedicated Hosts
        type: string
      - in: query
        name: Id
        description: The distributions ID
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: NextToken
        description: The token to retrieve the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Distribution
  /?Action=GetDistributionConfig:
    get:
      summary: Get Distribution Config
      description: Get the configuration information about a distribution.
      operationId: getDistributionConfig
      x-api-path-slug: actiongetdistributionconfig-get
      parameters:
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: Id
        description: The distributions ID
        type: string
      - in: query
        name: MaxDuration
        description: This is the maximum duration of the reservation youd like to
          purchase, specified            in seconds
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: MinDuration
        description: This is the minimum duration of the reservation youd like to
          purchase, specified            in seconds
        type: string
      - in: query
        name: NextToken
        description: The token to use to retrieve the next page of results
        type: string
      - in: query
        name: OfferingId
        description: The ID of the reservation offering
        type: string
      responses:
        200:
          description: OK
      tags:
      - Distribution
      - Config
  /?Action=GetStreamingDistribution:
    get:
      summary: Get Streaming Distribution
      description: |-
        Gets information about a specified RTMP distribution, including the distribution
              configuration.
      operationId: getStreamingDistribution
      x-api-path-slug: actiongetstreamingdistribution-get
      parameters:
      - in: query
        name: HostIdSet.N
        description: The ID/s of the Dedicated Host/s that the reservation will be
          associated            with
        type: string
      - in: query
        name: Id
        description: The streaming distributions ID
        type: string
      - in: query
        name: OfferingId
        description: The offering ID of the reservation
        type: string
      responses:
        200:
          description: OK
      tags:
      - Streaming
      - Distribution
  /?Action=GetStreamingDistributionConfig:
    get:
      summary: Get Streaming Distribution Config
      description: Get the configuration information about a streaming distribution.
      operationId: getStreamingDistributionConfig
      x-api-path-slug: actiongetstreamingdistributionconfig-get
      parameters:
      - in: query
        name: AutoPlacement
        description: Specify whether to enable or disable auto-placement
        type: string
      - in: query
        name: HostId.N
        description: The host IDs of the Dedicated Hosts you want to modify
        type: string
      - in: query
        name: Id
        description: The streaming distributions ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Streaming
      - Distribution
      - Config
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