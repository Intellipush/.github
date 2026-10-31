# Welcome to Intellipush

Intellipush is a Norwegian SMS platform for businesses of all sizes. Send reminders, customer updates and consent-based marketing through the web portal, or connect messaging to your software through our REST API.

## Get started

- [Explore Intellipush](https://www.intellipush.com/)
- [Open the web portal](https://portal.intellipush.com/)
- [View pricing](https://www.intellipush.com/en/pricing/)
- [Read the current REST API documentation](https://api.intellipush.com/restv2/developer/)

## For developers and integration partners

Build SMS into your applications, SaaS products and business workflows. Start with the current API documentation for authentication, supported operations and account-specific capabilities.

The current REST API uses OAuth 2.0 client credentials for server-to-server integrations. Request an access token from `/restv2/token` with `grant_type=client_credentials`, authenticating with your API ID and Secret through HTTP Basic. Use the token in the `Authorization: Bearer <access_token>` header for protected operations. Tokens last 3,600 seconds and have no refresh token. Keep credentials and tokens on the server, out of browser code, URLs and logs.

## Usage-based pricing

Get started with no setup cost and no monthly platform fee. Buy prepaid SMS credits when you are ready to send; credits remain valid for 24 months. Larger credit packages offer lower per-SMS pricing. Actual cost depends on destination and message segments, and one credit is not necessarily one SMS. Optional services such as keywords and short numbers may carry recurring rental charges. [See current pricing and packages](https://www.intellipush.com/en/pricing/).

## SDKs and compatibility

- [PHP SDK](https://github.com/Intellipush/intellipush-php-sdk-v2)
- [Python SDK](https://github.com/Intellipush/intellipush-python-sdk)
- [.NET SDK](https://github.com/Intellipush/intellipush-.net-sdk-v2)

These are legacy SDKs. Review their compatibility with the current REST API before using them in a new integration. SDK modernization is planned; updated support and release details will be documented in the individual repositories.
