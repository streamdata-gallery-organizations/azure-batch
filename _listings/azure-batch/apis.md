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
x-alexaRank: "0"
tags: Azure Batch
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/apis.md
specificationVersion: "0.14"
apis:
- name: BatchManagement - Batch Account Create
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountname-put
  description: Creates a new Batch account with the specified parameters. Existing
    accounts cannot be updated with this API and should instead be updated with the
    Update Batch Account API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountname-put-openapi.md
- name: BatchManagement - Batch Account Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountname-patch
  description: Updates the properties of an existing Batch account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountname-patch-openapi.md
- name: BatchManagement - Batch Account Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountname-delete
  description: Deletes the specified Batch account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountname-delete-openapi.md
- name: BatchManagement - Batch Account Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountname-get
  description: Gets information about the specified Batch account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountname-get-openapi.md
- name: BatchManagement - Batch Account List
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-batchbatchaccounts-get
  description: Gets information about the Batch accounts associated with the subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidprovidersmicrosoft-batchbatchaccounts-get-openapi.md
- name: BatchManagement - Batch Account List By Resource Group
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccounts-get
  description: Gets information about the Batch accounts associated within the specified
    resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccounts-get-openapi.md
- name: BatchManagement - Batch Account Synchronize Auto Storage Keys
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnamesyncautostoragekeys-post
  description: Synchronizes access keys for the auto storage account configured for
    the specified Batch account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnamesyncautostoragekeys-post-openapi.md
- name: BatchManagement - Batch Account Regenerate Key
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameregeneratekeys-post
  description: Regenerates the specified account key for the Batch account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameregeneratekeys-post-openapi.md
- name: BatchManagement - Gets the account keys for the specified Batch account.
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnamelistkeys-post
  description: This operation applies only to Batch accounts created with a poolAllocationMode
    of 'BatchService'. If the Batch account was created with a poolAllocationMode
    of 'UserSubscription', clients cannot use access to keys to authenticate, and
    must use Azure Active Directory instead. In this case, getting the keys will fail.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnamelistkeys-post-openapi.md
- name: BatchManagement - Application Package Activate
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationidversionsversionactivate-post
  description: Activates the specified application package.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationidversionsversionactivate-post-openapi.md
- name: BatchManagement - Application Create
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-put
  description: Adds an application to the specified Batch account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-put-openapi.md
- name: BatchManagement - Application Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-delete
  description: Deletes an application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-delete-openapi.md
- name: BatchManagement - Application Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-get
  description: Gets information about the specified application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-get-openapi.md
- name: BatchManagement - Application Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-patch
  description: Updates settings for the specified application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-patch-openapi.md
- name: BatchManagement - Application Package Create
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationidversionsversion-put
  description: Creates an application package record.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationidversionsversion-put-openapi.md
- name: BatchManagement - Application Package Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationidversionsversion-delete
  description: Deletes an application package record and its associated binary file.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationidversionsversion-delete-openapi.md
- name: BatchManagement - Application Package Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationidversionsversion-get
  description: Gets information about the specified application package.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationidversionsversion-get-openapi.md
- name: BatchManagement - Application List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplications-get
  description: Lists all of the applications in the specified account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplications-get-openapi.md
- name: BatchManagement - Location Get Quotas
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-batchlocationslocationnamequotas-get
  description: Gets the Batch service quotas for the specified subscription at the
    given location.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidprovidersmicrosoft-batchlocationslocationnamequotas-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-batch/master/_listings/azure-batch/subscriptionssubscriptionidprovidersmicrosoft-batchlocationslocationnamequotas-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.automation.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.batch.stack.network
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