---
name: AWS Lambda
x-slug: aws-lambda
description: AWS Lambda is a zero-administration compute platform for back-end web
  developers that runs your code for you in the AWScloudand provides you with a fine-grained
  pricing structure. AWS Lambda runs your back-end code on its own AWS compute fleet
  of Amazon Elastic Compute Cloud (Amazon EC2) instances across multiple Availability
  Zones in a region, which provides the high availability, security, performance,
  and scalability of the AWS infrastructure.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Functions
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/functions/master/_listings/aws-lambda/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Lambda API - Create Function
  x-api-slug: actioncreatefunction-get
  description: Creates a new Lambda function.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
  humanURL: http://docs.aws.amazon.com/lambda/
  baseURL: :///
  tags: Amazon Web Services, Serverless, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/functions/master/_listings/aws-lambda/actioncreatefunction-get-openapi.md
- name: AWS Lambda API - Delete Function
  x-api-slug: actiondeletefunction-get
  description: Deletes the specified Lambda function code and configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
  humanURL: http://docs.aws.amazon.com/lambda/
  baseURL: :///
  tags: Amazon Web Services, Serverless, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/functions/master/_listings/aws-lambda/actiondeletefunction-get-openapi.md
- name: AWS Lambda API - Get Function
  x-api-slug: actiongetfunction-get
  description: "Returns the configuration information of the Lambda function and a
    presigned URL \n      link to the."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
  humanURL: http://docs.aws.amazon.com/lambda/
  baseURL: :///
  tags: Amazon Web Services, Serverless, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/functions/master/_listings/aws-lambda/actiongetfunction-get-openapi.md
- name: AWS Lambda API - Get Function Configuration
  x-api-slug: actiongetfunctionconfiguration-get
  description: Returns the configuration information of the Lambda function.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
  humanURL: http://docs.aws.amazon.com/lambda/
  baseURL: :///
  tags: Amazon Web Services, Serverless, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/functions/master/_listings/aws-lambda/actiongetfunctionconfiguration-get-openapi.md
- name: AWS Lambda API - List Functions
  x-api-slug: actionlistfunctions-get
  description: Returns a list of your Lambda functions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
  humanURL: http://docs.aws.amazon.com/lambda/
  baseURL: :///
  tags: Amazon Web Services, Serverless, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/functions/master/_listings/aws-lambda/actionlistfunctions-get-openapi.md
- name: AWS Lambda API - List Versions By Function
  x-api-slug: actionlistversionsbyfunction-get
  description: List all versions of a function.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
  humanURL: http://docs.aws.amazon.com/lambda/
  baseURL: :///
  tags: Amazon Web Services, Serverless, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/functions/master/_listings/aws-lambda/actionlistversionsbyfunction-get-openapi.md
- name: AWS Lambda API - Update Function Code
  x-api-slug: actionupdatefunctioncode-get
  description: Updates the code for the specified Lambda function.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
  humanURL: http://docs.aws.amazon.com/lambda/
  baseURL: :///
  tags: Amazon Web Services, Serverless, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/functions/master/_listings/aws-lambda/actionupdatefunctioncode-get-openapi.md
- name: AWS Lambda API - Update Function Configuration
  x-api-slug: actionupdatefunctionconfiguration-get
  description: Updates the configuration parameters for the specified Lambda function
    by using the values provided in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
  humanURL: http://docs.aws.amazon.com/lambda/
  baseURL: :///
  tags: Amazon Web Services, Serverless, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/functions/master/_listings/aws-lambda/actionupdatefunctionconfiguration-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.kinesis.analytics.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.lambda.stack.network
- type: x-authentication
  url: http://docs.aws.amazon.com/lambda/latest/dg/lambda-auth-and-access-control.html
- type: x-best-practices
  url: http://docs.aws.amazon.com/lambda/latest/dg/best-practices.html
- type: x-console
  url: https://console.aws.amazon.com/lambda
- type: x-documentation
  url: http://docs.aws.amazon.com/lambda/latest/dg/API_Reference.html
- type: x-faq
  url: https://aws.amazon.com/lambda/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=186
- type: x-getting-started
  url: https://aws.amazon.com/lambda/getting-started/
- type: x-logging
  url: http://docs.aws.amazon.com/lambda/latest/dg/logging-using-cloudtrail.html
- type: x-partners
  url: https://aws.amazon.com/lambda/partners/
- type: x-pricing
  url: https://aws.amazon.com/lambda/pricing/
- type: x-rate-limits
  url: http://docs.aws.amazon.com/lambda/latest/dg/limits.html
- type: x-road-map
  url: http://aws.amazon.com/releasenotes/
- type: x-use-cases
  url: http://docs.aws.amazon.com/lambda/latest/dg/use-cases.html
- type: x-website
  url: http://docs.aws.amazon.com/lambda/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---