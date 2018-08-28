---
swagger: "2.0"
x-collection-name: AWS Lambda
x-complete: 0
info:
  title: AWS Lambda API Update Function Configuration
  version: 1.0.0
  description: Updates the configuration parameters for the specified Lambda function
    by using the values provided in the request.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateFunction:
    get:
      summary: Create Function
      description: Creates a new Lambda function.
      operationId: createFunction
      x-api-path-slug: actioncreatefunction-get
      parameters:
      - in: query
        name: Code
        description: The code for the Lambda function
        type: string
      - in: query
        name: DeadLetterConfig
        description: The parent object that contains the target Amazon Resource Name
          (ARN) of an Amazon SQS queue or Amazon SNS topic
        type: string
      - in: query
        name: Description
        description: A short, user-defined function description
        type: string
      - in: query
        name: Environment
        description: The parent object that contains your environments configuration
          settings
        type: string
      - in: query
        name: FunctionName
        description: The name you want to assign to the function you are uploading
        type: string
      - in: query
        name: Handler
        description: The function within your code that Lambda calls to begin execution
        type: string
      - in: query
        name: KMSKeyArn
        description: The Amazon Resource Name (ARN) of the KMS key used to encrypt
          your functions environment variables
        type: string
      - in: query
        name: MemorySize
        description: The amount of memory, in MB, your Lambda function is given
        type: string
      - in: query
        name: Publish
        description: This boolean parameter can be used to request AWS Lambda to create
          the Lambda function and publish a version as an atomic operation
        type: string
      - in: query
        name: Role
        description: The Amazon Resource Name (ARN) of the IAM role that Lambda assumes       when
          it executes your function to access any other Amazon Web Services (AWS)
          resources
        type: string
      - in: query
        name: Runtime
        description: The runtime environment for the Lambda function you are uploading
        type: string
      - in: query
        name: Timeout
        description: The function execution time at which Lambda should terminate
          the function
        type: string
      - in: query
        name: VpcConfig
        description: If your Lambda function accesses resources in a VPC, you provide
          this parameter identifying the list of security group IDs and subnet IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Functions
  /?Action=DeleteFunction:
    get:
      summary: Delete Function
      description: Deletes the specified Lambda function code and configuration.
      operationId: deleteFunction
      x-api-path-slug: actiondeletefunction-get
      parameters:
      - in: query
        name: FunctionName
        description: The Lambda function to delete
        type: string
      - in: query
        name: Qualifier
        description: Using this optional parameter you can specify a function version       (but
          not the $LATEST version) to direct AWS Lambda to delete a       specific
          function version
        type: string
      responses:
        200:
          description: OK
      tags:
      - Functions
  /?Action=GetFunction:
    get:
      summary: Get Function
      description: "Returns the configuration information of the Lambda function and
        a presigned URL \n      link to the."
      operationId: getFunction
      x-api-path-slug: actiongetfunction-get
      parameters:
      - in: query
        name: FunctionName
        description: The Lambda function name
        type: string
      - in: query
        name: Qualifier
        description: Using this optional parameter to specify a function version or
          an alias name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Functions
  /?Action=GetFunctionConfiguration:
    get:
      summary: Get Function Configuration
      description: Returns the configuration information of the Lambda function.
      operationId: getFunctionConfiguration
      x-api-path-slug: actiongetfunctionconfiguration-get
      parameters:
      - in: query
        name: FunctionName
        description: The name of the Lambda function for which you want to retrieve
          the configuration information
        type: string
      - in: query
        name: Qualifier
        description: Using this optional parameter you can specify a function version
          or an alias name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Functions
  /?Action=ListFunctions:
    get:
      summary: List Functions
      description: Returns a list of your Lambda functions.
      operationId: listFunctions
      x-api-path-slug: actionlistfunctions-get
      parameters:
      - in: query
        name: Marker
        description: Optional string
        type: string
      - in: query
        name: MaxItems
        description: Optional integer
        type: string
      responses:
        200:
          description: OK
      tags:
      - Functions
  /?Action=ListVersionsByFunction:
    get:
      summary: List Versions By Function
      description: List all versions of a function.
      operationId: listVersionsByFunction
      x-api-path-slug: actionlistversionsbyfunction-get
      parameters:
      - in: query
        name: FunctionName
        description: Function name whose versions to list
        type: string
      - in: query
        name: Marker
        description: Optional string
        type: string
      - in: query
        name: MaxItems
        description: Optional integer
        type: string
      responses:
        200:
          description: OK
      tags:
      - Functions
  /?Action=UpdateFunctionCode:
    get:
      summary: Update Function Code
      description: Updates the code for the specified Lambda function.
      operationId: updateFunctionCode
      x-api-path-slug: actionupdatefunctioncode-get
      parameters:
      - in: query
        name: FunctionName
        description: The existing Lambda function name whose code you want to replace
        type: string
      responses:
        200:
          description: OK
      tags:
      - Functions
  /?Action=UpdateFunctionConfiguration:
    get:
      summary: Update Function Configuration
      description: Updates the configuration parameters for the specified Lambda function
        by using the values provided in the request.
      operationId: updateFunctionConfiguration
      x-api-path-slug: actionupdatefunctionconfiguration-get
      parameters:
      - in: query
        name: FunctionName
        description: The name of the Lambda function
        type: string
      responses:
        200:
          description: OK
      tags:
      - Functions
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