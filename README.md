# ![LOGO](logo.png) Guest Diagnostic Settings **flow**ground Connector

## Description

A generated **flow**ground connector for the Guest Diagnostic Settings API (version 2018-06-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/monitor-guestDiagnosticSettings_API/2018-06-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:27+03:00

## API Description

API to Add/Remove/List Guest Diagnostics Configuration to Azure Resources

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get a list of all guest diagnostic settings in a subscription.

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `api-version` - _required_ - Client Api Version.

### Get a list of all guest diagnostic settings in a resource group.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `subscriptionId` - _required_ - The Azure subscription Id.
* `api-version` - _required_ - Client Api Version.

### Delete guest diagnostics settings.

*Tags:* `GuestDiagnosticsSettings`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `diagnosticSettingsName` - _required_ - The name of the diagnostic setting.
* `subscriptionId` - _required_ - The Azure subscription Id.
* `api-version` - _required_ - Client Api Version.

### Gets guest diagnostics settings.

*Tags:* `GuestDiagnosticsSettings`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `diagnosticSettingsName` - _required_ - The name of the diagnostic setting.
* `subscriptionId` - _required_ - The Azure subscription Id.
* `api-version` - _required_ - Client Api Version.

### Updates guest diagnostics settings.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `diagnosticSettingsName` - _required_ - The name of the diagnostic setting.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription Id.

### Creates or updates guest diagnostics settings.

*Tags:* `GuestDiagnosticsSettings`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `diagnosticSettingsName` - _required_ - The name of the diagnostic setting.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription Id.

## License

**flow**ground :- Telekom iPaaS / azure-com-monitor-guest-diagnostic-settings-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
