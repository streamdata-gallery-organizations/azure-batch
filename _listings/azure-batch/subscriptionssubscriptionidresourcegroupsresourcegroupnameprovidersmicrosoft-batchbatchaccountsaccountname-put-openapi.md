---
swagger: "2.0"
x-collection-name: Azure Batch
x-complete: 0
info:
  title: Azure Batch API Batch Account Create
  version: 1.0.0
  description: Creates a new Batch account with the specified parameters. Existing
    accounts cannot be updated with this API and should instead be updated with the
    Update Batch Account API.
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}:
    put:
      summary: Batch Account Create
      description: Creates a new Batch account with the specified parameters. Existing
        accounts cannot be updated with this API and should instead be updated with
        the Update Batch Account API.
      operationId: BatchAccount_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountname-put
      parameters:
      - in: path
        name: accountName
        description: A name for the Batch account which must be unique within the
          region
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Additional parameters for account creation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the new Batch account
      responses:
        200:
          description: OK
      tags:
      - Batch Account
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