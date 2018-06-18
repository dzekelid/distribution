---
name: AWS CloudFront
x-slug: aws-cloudfront
description: Amazon CloudFront is a global content delivery network (CDN) service
  that accelerates delivery of your websites, APIs, video content or other web assets.
  It integrates with other Amazon Web Services products to give developers and businesses
  an easy way to accelerate content to end users with no minimum usage commitments.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Distribution
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/distribution/master/_listings/aws-cloudfront/apis.md
specificationVersion: "0.14"
apis:
- name: AWS CloudFront API Create Distribution
  x-api-slug: aws-cloudfront-api
  description: Creates a new web distribution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=CreateDistribution
  tags: Distribution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/distribution/master/_listings/aws-cloudfront/actioncreatedistribution-get-openapi.md
- name: AWS CloudFront API Create Distribution With Tags
  x-api-slug: aws-cloudfront-api
  description: Create a new distribution with tags.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=CreateDistributionWithTags
  tags: Distribution, Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/distribution/master/_listings/aws-cloudfront/actioncreatedistributionwithtags-get-openapi.md
- name: AWS CloudFront API Create Streaming Distribution
  x-api-slug: aws-cloudfront-api
  description: Creates a new RMTP distribution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=CreateStreamingDistribution
  tags: Streaming, Distribution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/distribution/master/_listings/aws-cloudfront/actioncreatestreamingdistribution-get-openapi.md
- name: AWS CloudFront API Create Streaming Distribution With Tags
  x-api-slug: aws-cloudfront-api
  description: Create a new streaming distribution with tags.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=CreateStreamingDistributionWithTags
  tags: Streaming, Distribution, Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/distribution/master/_listings/aws-cloudfront/actioncreatestreamingdistributionwithtags-get-openapi.md
- name: AWS CloudFront API Delete Distribution
  x-api-slug: aws-cloudfront-api
  description: Delete a distribution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=DeleteDistribution
  tags: Distribution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/distribution/master/_listings/aws-cloudfront/actiondeletedistribution-get-openapi.md
- name: AWS CloudFront API Delete Streaming Distribution
  x-api-slug: aws-cloudfront-api
  description: Delete a streaming distribution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=DeleteStreamingDistribution
  tags: Streaming, Distribution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/distribution/master/_listings/aws-cloudfront/actiondeletestreamingdistribution-get-openapi.md
- name: AWS CloudFront API Get Distribution
  x-api-slug: aws-cloudfront-api
  description: Get the information about a distribution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=GetDistribution
  tags: Distribution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/distribution/master/_listings/aws-cloudfront/actiongetdistribution-get-openapi.md
- name: AWS CloudFront API Get Distribution Config
  x-api-slug: aws-cloudfront-api
  description: Get the configuration information about a distribution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=GetDistributionConfig
  tags: Distribution, Config
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/distribution/master/_listings/aws-cloudfront/actiongetdistributionconfig-get-openapi.md
- name: AWS CloudFront API Get Streaming Distribution
  x-api-slug: aws-cloudfront-api
  description: |-
    Gets information about a specified RTMP distribution, including the distribution
          configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=GetStreamingDistribution
  tags: Streaming, Distribution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/distribution/master/_listings/aws-cloudfront/actiongetstreamingdistribution-get-openapi.md
- name: AWS CloudFront API Get Streaming Distribution Config
  x-api-slug: aws-cloudfront-api
  description: Get the configuration information about a streaming distribution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=GetStreamingDistributionConfig
  tags: Streaming, Distribution, Config
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/distribution/master/_listings/aws-cloudfront/actiongetstreamingdistributionconfig-get-openapi.md
- name: AWS CloudFront API List Distributions
  x-api-slug: aws-cloudfront-api
  description: List distributions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=ListDistributions
  tags: List, Distributions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/distribution/master/_listings/aws-cloudfront/actionlistdistributions-get-openapi.md
- name: AWS CloudFront API List Distributions By Web A C L Id
  x-api-slug: aws-cloudfront-api
  description: List the distributions that are associated with a specified AWS WAF
    web ACL.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=ListDistributionsByWebACLId
  tags: List, Distributions, Web, C, L, Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/distribution/master/_listings/aws-cloudfront/actionlistdistributionsbywebaclid-get-openapi.md
- name: AWS CloudFront API List Streaming Distributions
  x-api-slug: aws-cloudfront-api
  description: List streaming distributions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=ListStreamingDistributions
  tags: List, Streaming, Distributions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/distribution/master/_listings/aws-cloudfront/actionliststreamingdistributions-get-openapi.md
- name: AWS CloudFront API Update Distribution
  x-api-slug: aws-cloudfront-api
  description: Update a distribution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=UpdateDistribution
  tags: Distribution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/distribution/master/_listings/aws-cloudfront/actionupdatedistribution-get-openapi.md
- name: AWS CloudFront API Update Streaming Distribution
  x-api-slug: aws-cloudfront-api
  description: Update a streaming distribution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=UpdateStreamingDistribution
  tags: Streaming, Distribution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/distribution/master/_listings/aws-cloudfront/actionupdatestreamingdistribution-get-openapi.md
- name: AWS CloudFront API
  x-api-slug: aws-cloudfront-api
  description: Amazon CloudFront is a global content delivery network (CDN) service
    that accelerates delivery of your websites, APIs, video content or other web assets.
    It integrates with other Amazon Web Services products to give developers and businesses
    an easy way to accelerate content to end users with no minimum usage commitments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: :///
  tags: Distribution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/distribution/master/_listings/aws-cloudfront/openapi.md
x-common:
- type: x-analysis
  url: https://aws.amazon.com/cloudfront/reporting/
- type: x-documentation
  url: http://docs.aws.amazon.com/AmazonCloudFront/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/cloudfront/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/cloudfront/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/cloudfront/pricing/
- type: x-service-level-agreement
  url: https://aws.amazon.com/cloudfront/sla/
- type: x-webinars
  url: https://aws.amazon.com/cloudfront/webinars/
- type: x-website
  url: https://aws.amazon.com/cloudfront/
- type: x-whats-new
  url: https://aws.amazon.com/cloudfront/whats-new/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---