swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/stationary/html/{brandId}:
    get:
      summary: "Does a simple merge of the selected envelopeTemplatePack using the
        data supplied\r\nwill only use certain merge functions, and the correspondence
        can only contain one envelope and the envelope can only contain one document."
      description: "Does a simple merge of the selected envelopetemplatepack using
        the data supplied\r\nwill only use certain merge functions, and the correspondence
        can only contain one envelope and the envelope can only contain one document.."
      operationId: Stationary_HtmlStationaryBybrandId
      x-api-path-slug: apistationaryhtmlbrandid-get
      parameters:
      - in: path
        name: brandId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Does
      - Simple
      - Merge
      - Of
      - Selected
      - EnvelopeTemplatePack
      - Using
      - Data
      - "Supplied\r\nWill"
      - Only
      - Use
      - Certain
      - Merge
      - Functions
      - ""
      - Correspondence
      - Can
      - Only
      - Contain
      - Envelope
      - Envelope
      - Can
      - Only
      - Contain
      - Document
  /api/stationary/sms/{brandId}:
    get:
      summary: "Does a simple merge of the selected envelopeTemplatePack using the
        data supplied\r\nwill only use certain merge functions, and the correspondence
        can only contain one envelope and the envelope can only contain one document."
      description: "Does a simple merge of the selected envelopetemplatepack using
        the data supplied\r\nwill only use certain merge functions, and the correspondence
        can only contain one envelope and the envelope can only contain one document.."
      operationId: Stationary_SmsStationaryBybrandId
      x-api-path-slug: apistationarysmsbrandid-get
      parameters:
      - in: path
        name: brandId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Does
      - Simple
      - Merge
      - Of
      - Selected
      - EnvelopeTemplatePack
      - Using
      - Data
      - "Supplied\r\nWill"
      - Only
      - Use
      - Certain
      - Merge
      - Functions
      - ""
      - Correspondence
      - Can
      - Only
      - Contain
      - Envelope
      - Envelope
      - Can
      - Only
      - Contain
      - Document