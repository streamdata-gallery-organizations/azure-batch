---
swagger: "2.0"
x-collection-name: Azure Batch
x-complete: 0
info:
  title: Azure Batch API Location Get Quotas
  version: 1.0.0
  description: Gets the Batch service quotas for the specified subscription at the
    given location.
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
    patch:
      summary: Batch Account Update
      description: Updates the properties of an existing Batch account.
      operationId: BatchAccount_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountname-patch
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountname-delete
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountname-get
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
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-batchbatchaccounts-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccounts-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnamesyncautostoragekeys-post
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameregeneratekeys-post
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
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/listKeys
  : post:
      summary: Gets the account keys for the specified Batch account.
      description: This operation applies only to Batch accounts created with a poolAllocationMode
        of 'BatchService'. If the Batch account was created with a poolAllocationMode
        of 'UserSubscription', clients cannot use access to keys to authenticate,
        and must use Azure Active Directory instead. In this case, getting the keys
        will fail.
      operationId: BatchAccount_GetKeys
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnamelistkeys-post
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
      - Account Key
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/applications/{applicationId}/versions/{version}/activate
  : post:
      summary: Application Package Activate
      description: Activates the specified application package.
      operationId: ApplicationPackage_Activate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationidversionsversionactivate-post
      parameters:
      - in: path
        name: accountName
        description: The name of the Batch account
      - in: path
        name: applicationId
        description: The ID of the application
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
      - in: path
        name: version
        description: The version of the application to activate
      responses:
        200:
          description: OK
      tags:
      - Application Package
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/applications/{applicationId}
  : put:
      summary: Application Create
      description: Adds an application to the specified Batch account.
      operationId: Application_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-put
      parameters:
      - in: path
        name: accountName
        description: The name of the Batch account
      - in: path
        name: applicationId
        description: The ID of the application
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
      responses:
        200:
          description: OK
      tags:
      - Application
    delete:
      summary: Application Delete
      description: Deletes an application.
      operationId: Application_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-delete
      parameters:
      - in: path
        name: accountName
        description: The name of the Batch account
      - in: path
        name: applicationId
        description: The ID of the application
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
      responses:
        200:
          description: OK
      tags:
      - Application
    get:
      summary: Application Get
      description: Gets information about the specified application.
      operationId: Application_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Batch account
      - in: path
        name: applicationId
        description: The ID of the application
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
      responses:
        200:
          description: OK
      tags:
      - Application
    patch:
      summary: Application Update
      description: Updates settings for the specified application.
      operationId: Application_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-patch
      parameters:
      - in: path
        name: accountName
        description: The name of the Batch account
      - in: path
        name: applicationId
        description: The ID of the application
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
      responses:
        200:
          description: OK
      tags:
      - Application
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/applications/{applicationId}/versions/{version}
  : put:
      summary: Application Package Create
      description: Creates an application package record.
      operationId: ApplicationPackage_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationidversionsversion-put
      parameters:
      - in: path
        name: accountName
        description: The name of the Batch account
      - in: path
        name: applicationId
        description: The ID of the application
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
      - in: path
        name: version
        description: The version of the application
      responses:
        200:
          description: OK
      tags:
      - Application Package
    delete:
      summary: Application Package Delete
      description: Deletes an application package record and its associated binary
        file.
      operationId: ApplicationPackage_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationidversionsversion-delete
      parameters:
      - in: path
        name: accountName
        description: The name of the Batch account
      - in: path
        name: applicationId
        description: The ID of the application
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
      - in: path
        name: version
        description: The version of the application to delete
      responses:
        200:
          description: OK
      tags:
      - Application Package
    get:
      summary: Application Package Get
      description: Gets information about the specified application package.
      operationId: ApplicationPackage_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationidversionsversion-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Batch account
      - in: path
        name: applicationId
        description: The ID of the application
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
      - in: path
        name: version
        description: The version of the application
      responses:
        200:
          description: OK
      tags:
      - Application Package
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/applications
  : get:
      summary: Application List
      description: Lists all of the applications in the specified account.
      operationId: Application_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplications-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Batch account
      - in: query
        name: maxresults
        description: The maximum number of items to return in the response
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
      responses:
        200:
          description: OK
      tags:
      - Application
  /subscriptions/{subscriptionId}/providers/Microsoft.Batch/locations/{locationName}/quotas:
    get:
      summary: Location Get Quotas
      description: Gets the Batch service quotas for the specified subscription at
        the given location.
      operationId: Location_GetQuotas
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-batchlocationslocationnamequotas-get
      parameters:
      - in: path
        name: locationName
        description: The desired region for the quotas
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Location Quotas
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