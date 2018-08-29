---
swagger: "2.0"
x-collection-name: Azure Batch
x-complete: 0
info:
  title: Azure Batch API Batch Account Regenerate Key
  version: 1.0.0
  description: Regenerates the specified account key for the Batch account.
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountname-put
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
    patch:
      summary: Batch Account Update
      description: Updates the properties of an existing Batch account.
      operationId: BatchAccount_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountname-patch
      parameters:
      - in: path
        name: accountName
        description: The name of the account
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Additional parameters for account update
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
      responses:
        200:
          description: OK
      tags:
      - Batch Account
    delete:
      summary: Batch Account Delete
      description: Deletes the specified Batch account.
      operationId: BatchAccount_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountname-delete
      parameters:
      - in: path
        name: accountName
        description: The name of the account to be deleted
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
          to be deleted
      responses:
        200:
          description: OK
      tags:
      - Batch Account
    get:
      summary: Batch Account Get
      description: Gets information about the specified Batch account.
      operationId: BatchAccount_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountname-get
      parameters:
      - in: path
        name: accountName
        description: The name of the account
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
      responses:
        200:
          description: OK
      tags:
      - Batch Account
  /subscriptions/{subscriptionId}/providers/Microsoft.Batch/batchAccounts:
    get:
      summary: Batch Account List
      description: Gets information about the Batch accounts associated with the subscription.
      operationId: BatchAccount_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftbatchbatchaccounts-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Batch Account
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts:
    get:
      summary: Batch Account List By Resource Group
      description: Gets information about the Batch accounts associated within the
        specified resource group.
      operationId: BatchAccount_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccounts-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group whose Batch accounts to list
      responses:
        200:
          description: OK
      tags:
      - Batch Account
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/syncAutoStorageKeys
  : post:
      summary: Batch Account Synchronize Auto Storage Keys
      description: Synchronizes access keys for the auto storage account configured
        for the specified Batch account.
      operationId: BatchAccount_SynchronizeAutoStorageKeys
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountnamesyncautostoragekeys-post
      parameters:
      - in: path
        name: accountName
        description: The name of the Batch account
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
      responses:
        200:
          description: OK
      tags:
      - Batch Account
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/regenerateKeys
  : post:
      summary: Batch Account Regenerate Key
      description: Regenerates the specified account key for the Batch account.
      operationId: BatchAccount_RegenerateKey
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountnameregeneratekeys-post
      parameters:
      - in: path
        name: accountName
        description: The name of the account
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The type of key to regenerate
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
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