# Privacy Policy

**Effective Date:** April 9, 2026
**Last Updated:** April 9, 2026

***

## 1. Overview

This Privacy Policy describes how this application ("App") handles information in connection with its operation. This App is a content scheduling and automation tool that enables content creators to publish video content to their TikTok accounts via the TikTok Content Posting API. It operates via a desktop application and n8n workflow integration.

**This App does not collect, store, or share personal data from any third-party users.** No user registration, login, or data submission is available to the public.

***

## 2. Information We Do Not Collect

The following data is **NOT** collected from any user:

- Personal identification information of third parties
- Email addresses, phone numbers, or contact information from users
- Payment or financial information
- Location data
- Browsing history or behavioral analytics
- Cookies from third-party visitors

***

## 3. Information Used Internally

The App may handle the following data solely for operational purposes:

| Data Type | Purpose | Stored? |
|-----------|---------|---------|
| TikTok API Access Token | Authenticate API requests to TikTok | Locally only |
| TikTok Client Key & Secret | API integration credentials | Locally only |
| Video files and metadata | Content to be published to TikTok | Temporarily, during upload |
| App usage logs | Debugging and error tracking | Locally only |

All data is stored **locally on the user's own machine** or within private automation tools (e.g., n8n self-hosted instance). No data is transmitted to external servers beyond what is required by the TikTok API itself.

***

## 4. TikTok API Data Usage

This App uses the TikTok Content Posting API to publish videos to authorized TikTok accounts. By using the TikTok API, the App is subject to TikTok's own privacy practices. TikTok may collect data as described in their Privacy Policy available at:
[https://www.tiktok.com/legal/privacy-policy](https://www.tiktok.com/legal/privacy-policy)

The App only requests the minimum API scopes necessary to perform video uploads. Specifically:
- `video.publish` — to post videos directly to the authorized TikTok account
- `video.upload` — to handle video file transfers to TikTok's servers
- `user.info.basic` — to identify and authenticate the authorized user

No other TikTok user data is accessed, stored, or processed.

***

## 5. Third-Party Tools

This App may integrate with the following tools for automation and workflow management:

- **n8n** (workflow automation) — used locally or on a private server
- **Custom desktop application** — developed for content creators, not distributed to third parties

Neither tool is used to collect or transmit user data to any external party.

***

## 6. Data Security

All API credentials and tokens are stored securely on the user's local machine or private environment. No credentials are shared, published, or transmitted beyond authenticated API calls to TikTok's official endpoints.

***

## 7. Children's Privacy

This App is not directed at children under the age of 13, and no data from minors is knowingly collected or processed.

***

## 8. Changes to This Privacy Policy

This Privacy Policy may be updated from time to time to reflect changes in the App's functionality or applicable regulations. The "Last Updated" date at the top of this document will reflect any revisions.

***

## 9. Contact

For any questions or concerns about this Privacy Policy, please contact the developer directly through the App's associated TikTok account or registered developer email.

***

*This Privacy Policy was last updated on April 9, 2026.*
