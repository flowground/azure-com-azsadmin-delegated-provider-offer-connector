# ![LOGO](logo.png) SubscriptionsManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the SubscriptionsManagementClient API (version 2015-11-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-DelegatedProviderOffer/2015-11-01/swagger.json<br/>
Generated at: 2019-06-11T18:13:34+03:00

## API Description

The Admin Subscriptions Management Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get the list of delegated provider offers.

*Tags:* `DelegatedProviderOffers`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.The subscription ID forms part of the URI for every service call.
* `delegatedProviderSubscriptionId` - _required_ - Delegated provider subscription identifier.
* `api-version` - _required_ - Client Api Version.

### Get the specified delegated provider offer.

*Tags:* `DelegatedProviderOffers`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.The subscription ID forms part of the URI for every service call.
* `delegatedProviderSubscriptionId` - _required_ - Delegated provider subscription identifier.
* `offer` - _required_ - Name of an offer.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-delegated-provider-offer-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
