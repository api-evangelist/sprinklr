# Sprinklr

Sprinklr is a unified customer experience management (Unified-CXM) platform offering REST APIs for social media management, customer service, marketing, and advertising across 30+ digital channels. The platform serves enterprise customers with APIs covering social listening, publishing, reporting, user provisioning, digital asset management, and webhook integrations, all secured via OAuth 2.0.

## APIs

- **Sprinklr API** - RESTful APIs at `https://api3.sprinklr.com` covering:
  - Social listening streams
  - Publishing and engagement
  - Reporting and analytics
  - User provisioning
  - Digital asset management
  - Webhook subscriptions
  - Account management

## Developer Resources

- [Developer Portal](https://dev.sprinklr.com/api-overview)
- [Getting Started](https://dev.sprinklr.com/getting-started)
- [OAuth 2.0 Authentication](https://dev.sprinklr.com/oauth-2-0-for-partners)
- [Webhooks](https://dev.sprinklr.com/sprinklr-webhooks)
- [Error and Status Codes](https://dev.sprinklr.com/rest-api-error-and-status-codes)
- [API Usage Reporting Dashboard](https://www.sprinklr.com/help/articles/api/sprinklr-api-usage-reporting-dashboard/685e92d66862622c54ca0754)

## Authentication

Sprinklr uses OAuth 2.0 for API authentication, invoking Sprinklr's existing user-level governance and security model. To get started:

1. Register at the [Sprinklr Developer Portal](https://dev.sprinklr.com)
2. Create an API Application (or use Developer Tools in the platform as of release 26.1)
3. Generate an API Key and Secret
4. Obtain an access token through the OAuth 2.0 flow

## Pricing and Access

API access is included for Enterprise license holders. Sprinklr discontinued its Self-Serve plans on April 30, 2026. All access is now negotiated through Sprinklr's enterprise sales process. Enterprise contracts typically start at $50,000/year. See [plans/sprinklr-plans-pricing.yml](plans/sprinklr-plans-pricing.yml) for details.

## Rate Limits

Specific rate limit thresholds are not publicly documented and vary by enterprise contract. HTTP 429 responses indicate rate limit exceeded. See [rate-limits/sprinklr-rate-limits.yml](rate-limits/sprinklr-rate-limits.yml) for details.

## Links

- [Website](https://www.sprinklr.com)
- [Blog](https://www.sprinklr.com/blog/)
- [Pricing](https://www.sprinklr.com/pricing/)
- [Status Page](https://status.sprinklr.com/)
- [LinkedIn](https://www.linkedin.com/company/sprinklr)
- [X](https://x.com/sprinklr)

## Maintainer

**Kin Lane** - kin@apievangelist.com
