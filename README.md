# ![LOGO](logo.png) Diagnostics API Client **flow**ground Connector

## Description

A generated **flow**ground connector for the Diagnostics API Client API (version 2018-02-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/web-Diagnostics/2018-02-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:22+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List Hosting Environment Detector Responses

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Site Name
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get Hosting Environment Detector Response

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - App Service Environment Name
* `detectorName` - _required_ - Detector Resource Name
* `startTime` - _optional_ - Start Time
* `endTime` - _optional_ - End Time
* `timeGrain` - _optional_ - Time Grain
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### List Site Detector Responses

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get site detector response

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `detectorName` - _required_ - Detector Resource Name
* `startTime` - _optional_ - Start Time
* `endTime` - _optional_ - End Time
* `timeGrain` - _optional_ - Time Grain
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get Diagnostics Categories

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get Diagnostics Category

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `diagnosticCategory` - _required_ - Diagnostic Category
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get Site Analyses

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `diagnosticCategory` - _required_ - Diagnostic Category
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get Site Analysis

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `diagnosticCategory` - _required_ - Diagnostic Category
* `analysisName` - _required_ - Analysis Name
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Execute Analysis

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `diagnosticCategory` - _required_ - Category Name
* `analysisName` - _required_ - Analysis Resource Name
* `startTime` - _optional_ - Start Time
* `endTime` - _optional_ - End Time
* `timeGrain` - _optional_ - Time Grain
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get Detectors

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `diagnosticCategory` - _required_ - Diagnostic Category
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get Detector

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `diagnosticCategory` - _required_ - Diagnostic Category
* `detectorName` - _required_ - Detector Name
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Execute Detector

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `detectorName` - _required_ - Detector Resource Name
* `diagnosticCategory` - _required_ - Category Name
* `startTime` - _optional_ - Start Time
* `endTime` - _optional_ - End Time
* `timeGrain` - _optional_ - Time Grain
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### List Site Detector Responses

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `slot` - _required_ - Slot Name
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get site detector response

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `detectorName` - _required_ - Detector Resource Name
* `slot` - _required_ - Slot Name
* `startTime` - _optional_ - Start Time
* `endTime` - _optional_ - End Time
* `timeGrain` - _optional_ - Time Grain
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get Diagnostics Categories

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `slot` - _required_ - Slot Name
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get Diagnostics Category

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `diagnosticCategory` - _required_ - Diagnostic Category
* `slot` - _required_ - Slot Name
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get Site Analyses

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `diagnosticCategory` - _required_ - Diagnostic Category
* `slot` - _required_ - Slot Name
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get Site Analysis

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `diagnosticCategory` - _required_ - Diagnostic Category
* `analysisName` - _required_ - Analysis Name
* `slot` - _required_ - Slot - optional
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Execute Analysis

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `diagnosticCategory` - _required_ - Category Name
* `analysisName` - _required_ - Analysis Resource Name
* `slot` - _required_ - Slot Name
* `startTime` - _optional_ - Start Time
* `endTime` - _optional_ - End Time
* `timeGrain` - _optional_ - Time Grain
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get Detectors

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `diagnosticCategory` - _required_ - Diagnostic Category
* `slot` - _required_ - Slot Name
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get Detector

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `diagnosticCategory` - _required_ - Diagnostic Category
* `detectorName` - _required_ - Detector Name
* `slot` - _required_ - Slot Name
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Execute Detector

*Tags:* `Diagnostics`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `siteName` - _required_ - Site Name
* `detectorName` - _required_ - Detector Resource Name
* `diagnosticCategory` - _required_ - Category Name
* `slot` - _required_ - Slot Name
* `startTime` - _optional_ - Start Time
* `endTime` - _optional_ - End Time
* `timeGrain` - _optional_ - Time Grain
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

## License

**flow**ground :- Telekom iPaaS / azure-com-web-diagnostics-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
