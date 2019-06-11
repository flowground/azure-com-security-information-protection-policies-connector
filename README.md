# ![LOGO](logo.png) Security Center **flow**ground Connector

## Description

A generated **flow**ground connector for the Security Center API (version 2017-08-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/security-informationProtectionPolicies/2017-08-01-preview/swagger.json<br/>
Generated at: 2019-06-11T18:14:15+03:00

## API Description

API spec for Microsoft.Security (Azure Security Center) resource provider

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Information protection policies of a specific management group.

*Tags:* `InformationProtectionPolicies`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
* `scope` - _required_ - Scope of the query, can be subscription (/subscriptions/0b06d9ea-afe6-4779-bd59-30e5c2d9d13f) or management group (/providers/Microsoft.Management/managementGroups/mgName).

### Details of the information protection policy.

*Tags:* `InformationProtectionPolicies`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
* `scope` - _required_ - Scope of the query, can be subscription (/subscriptions/0b06d9ea-afe6-4779-bd59-30e5c2d9d13f) or management group (/providers/Microsoft.Management/managementGroups/mgName).
* `informationProtectionPolicyName` - _required_ - Name of the information protection policy.
    Possible values: effective, custom.

### Details of the information protection policy.

*Tags:* `InformationProtectionPolicies`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
* `scope` - _required_ - Scope of the query, can be subscription (/subscriptions/0b06d9ea-afe6-4779-bd59-30e5c2d9d13f) or management group (/providers/Microsoft.Management/managementGroups/mgName).
* `informationProtectionPolicyName` - _required_ - Name of the information protection policy.
    Possible values: effective, custom.

## License

**flow**ground :- Telekom iPaaS / azure-com-security-information-protection-policies-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
