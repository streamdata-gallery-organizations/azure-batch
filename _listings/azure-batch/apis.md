---
name: Azure Batch
x-slug: azure-batch
description: Batch processing began with mainframe computers and punch cards. Today,
  it still plays a central role in business, engineering, science, and other areas
  that require running lots of automated tasks&mdash;processing bills and payroll,
  calculating portfolio risk, designing new products, rendering animated films, testing
  software, searching for energy, predicting the weather, and finding new cures for
  disease. Previously, few people had access to the computing power for these scenarios.
  With Azure Batch, that power is available to you when you need it, without any capital
  investment.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
x-kinRank: "10"
x-alexaRank: ""
tags: Azure Batch
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Batch API Batch Account Create
  x-api-slug: azure-batch-api
  description: Creates a new Batch account with the specified parameters. Existing
    accounts cannot be updated with this API and should instead be updated with the
    Update Batch Account API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}
  tags: Batch Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountname-put-openapi.md
- name: Azure Batch API Batch Account Update
  x-api-slug: azure-batch-api
  description: Updates the properties of an existing Batch account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}
  tags: Batch Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountname-patch-openapi.md
- name: Azure Batch API Batch Account Delete
  x-api-slug: azure-batch-api
  description: Deletes the specified Batch account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}
  tags: Batch Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountname-delete-openapi.md
- name: Azure Batch API Batch Account Get
  x-api-slug: azure-batch-api
  description: Gets information about the specified Batch account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}
  tags: Batch Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountname-get-openapi.md
- name: Azure Batch API Batch Account List
  x-api-slug: azure-batch-api
  description: Gets information about the Batch accounts associated with the subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Batch/batchAccounts
  tags: Batch Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidprovidersmicrosoftbatchbatchaccounts-get-openapi.md
- name: Azure Batch API Batch Account List By Resource Group
  x-api-slug: azure-batch-api
  description: Gets information about the Batch accounts associated within the specified
    resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts
  tags: Batch Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccounts-get-openapi.md
- name: Azure Batch API Batch Account Synchronize Auto Storage Keys
  x-api-slug: azure-batch-api
  description: Synchronizes access keys for the auto storage account configured for
    the specified Batch account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/syncAutoStorageKeys
  tags: Batch Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountnamesyncautostoragekeys-post-openapi.md
- name: Azure Batch API Batch Account Regenerate Key
  x-api-slug: azure-batch-api
  description: Regenerates the specified account key for the Batch account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/regenerateKeys
  tags: Batch Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountnameregeneratekeys-post-openapi.md
- name: Azure Batch API Gets the account keys for the specified Batch account.
  x-api-slug: azure-batch-api
  description: This operation applies only to Batch accounts created with a poolAllocationMode
    of 'BatchService'. If the Batch account was created with a poolAllocationMode
    of 'UserSubscription', clients cannot use access to keys to authenticate, and
    must use Azure Active Directory instead. In this case, getting the keys will fail.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/listKeys
  tags: Account Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountnamelistkeys-post-openapi.md
- name: Azure Batch API Application Package Activate
  x-api-slug: azure-batch-api
  description: Activates the specified application package.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/applications/{applicationId}/versions/{version}/activate
  tags: Application Package
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountnameapplicationsapplicationidversionsversionactivate-post-openapi.md
- name: Azure Batch API Application Create
  x-api-slug: azure-batch-api
  description: Adds an application to the specified Batch account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/applications/{applicationId}
  tags: Application
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountnameapplicationsapplicationid-put-openapi.md
- name: Azure Batch API Application Delete
  x-api-slug: azure-batch-api
  description: Deletes an application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/applications/{applicationId}
  tags: Application
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountnameapplicationsapplicationid-delete-openapi.md
- name: Azure Batch API Application Get
  x-api-slug: azure-batch-api
  description: Gets information about the specified application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/applications/{applicationId}
  tags: Application
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountnameapplicationsapplicationid-get-openapi.md
- name: Azure Batch API Application Update
  x-api-slug: azure-batch-api
  description: Updates settings for the specified application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/applications/{applicationId}
  tags: Application
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountnameapplicationsapplicationid-patch-openapi.md
- name: Azure Batch API Application Package Create
  x-api-slug: azure-batch-api
  description: Creates an application package record.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/applications/{applicationId}/versions/{version}
  tags: Application Package
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountnameapplicationsapplicationidversionsversion-put-openapi.md
- name: Azure Batch API Application Package Delete
  x-api-slug: azure-batch-api
  description: Deletes an application package record and its associated binary file.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/applications/{applicationId}/versions/{version}
  tags: Application Package
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountnameapplicationsapplicationidversionsversion-delete-openapi.md
- name: Azure Batch API Application Package Get
  x-api-slug: azure-batch-api
  description: Gets information about the specified application package.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/applications/{applicationId}/versions/{version}
  tags: Application Package
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountnameapplicationsapplicationidversionsversion-get-openapi.md
- name: Azure Batch API Application List
  x-api-slug: azure-batch-api
  description: Lists all of the applications in the specified account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/applications
  tags: Application
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftbatchbatchaccountsaccountnameapplications-get-openapi.md
- name: Azure Batch API Location Get Quotas
  x-api-slug: azure-batch-api
  description: Gets the Batch service quotas for the specified subscription at the
    given location.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Batch/locations/{locationName}/quotas
  tags: Location Quotas
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidprovidersmicrosoftbatchlocationslocationnamequotas-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidprovidersmicrosoftbatchlocationslocationnamequotas-get-openapi.md
- name: Azure Batch API
  x-api-slug: azure-batch-api
  description: Batch processing began with mainframe computers and punch cards. Today,
    it still plays a central role in business, engineering, science, and other areas
    that require running lots of automated tasks&mdash;processing bills and payroll,
    calculating portfolio risk, designing new products, rendering animated films,
    testing software, searching for energy, predicting the weather, and finding new
    cures for disease. Previously, few people had access to the computing power for
    these scenarios. With Azure Batch, that power is available to you when you need
    it, without any capital investment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Azure Batch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/batch/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/batch/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/batch/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/batch/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---