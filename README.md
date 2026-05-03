# TikTok for Developers

TikTok for Developers provides a suite of REST APIs enabling third-party platforms to integrate with TikTok's social video ecosystem. Products include Login Kit, Display API, Content Posting API, Research API, and the TikTok API for Business, supporting use cases from user authentication and video publishing to advertising campaign management and academic research.

**Human URL:** https://developers.tiktok.com/

## APIs

| Name | Description |
|---|---|
| [TikTok Display API](https://developers.tiktok.com/doc/display-api-overview) | Access user profile information and video metadata |
| [TikTok Content Posting API](https://developers.tiktok.com/doc/content-posting-api-get-started) | Publish videos directly to user TikTok accounts |
| [TikTok Research API](https://developers.tiktok.com/doc/research-api-get-started) | Access public data for academic research |
| [TikTok Login Kit](https://developers.tiktok.com/doc/login-kit-web) | OAuth 2.0 authentication via TikTok |

## OpenAPI Specifications

| Specification | Description |
|---|---|
| [TikTok Display API](openapi/tiktok-display-openapi.yml) | User info and video listing endpoints |
| [TikTok Content Posting API](openapi/tiktok-content-posting-openapi.yml) | Video upload and publish endpoints |
| [TikTok Research API](openapi/tiktok-research-openapi.yml) | Research data query endpoints |
| [TikTok Login Kit API](openapi/tiktok-login-kit-openapi.yml) | OAuth token management endpoints |

## Capabilities

Workflow-oriented Naftiko capabilities combining TikTok APIs for common integration patterns.

| Capability | APIs Used | Description |
|---|---|---|
| [Content Creation](capabilities/content-creation.yaml) | Display API, Content Posting API | Full content lifecycle for app developers and media tools |
| [Social Research](capabilities/social-research.yaml) | Research API | Video, user, comment, and social graph data for researchers |

### Shared API Definitions

| Shared Definition | Description |
|---|---|
| [display-api.yaml](capabilities/shared/display-api.yaml) | TikTok Display API consumed definition |
| [content-posting-api.yaml](capabilities/shared/content-posting-api.yaml) | TikTok Content Posting API consumed definition |
| [research-api.yaml](capabilities/shared/research-api.yaml) | TikTok Research API consumed definition |

## Rules

| Ruleset | Description |
|---|---|
| [tiktok-for-developers-rules.yml](rules/tiktok-for-developers-rules.yml) | Spectral ruleset enforcing TikTok API conventions |

## Schemas

| Schema | Description |
|---|---|
| [tiktok-for-developers-video-schema.json](json-schema/tiktok-for-developers-video-schema.json) | JSON Schema for TikTok video objects |
| [tiktok-for-developers-user-schema.json](json-schema/tiktok-for-developers-user-schema.json) | JSON Schema for TikTok user profiles |

## Structures

| Structure | Description |
|---|---|
| [tiktok-for-developers-video-structure.json](json-structure/tiktok-for-developers-video-structure.json) | Video object field structure |

## JSON-LD

| Context | Description |
|---|---|
| [tiktok-for-developers-context.jsonld](json-ld/tiktok-for-developers-context.jsonld) | JSON-LD context mapping to schema.org |

## Examples

| Example | Description |
|---|---|
| [Get User Info](examples/tiktok-display-getUserInfo-example.json) | Example request/response for user info |
| [Init Video Publish](examples/tiktok-content-posting-initVideoPublish-example.json) | Example video publish initiation |
| [Query Research Videos](examples/tiktok-research-queryResearchVideos-example.json) | Example research video query |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [tiktok-for-developers-vocabulary.yml](vocabulary/tiktok-for-developers-vocabulary.yml) | TikTok developer platform vocabulary |

## Common Properties

- **Website:** https://www.tiktok.com/
- **Developer Portal:** https://developers.tiktok.com/
- **Documentation:** https://developers.tiktok.com/doc/overview
- **GitHub:** https://github.com/tiktok
- **Change Log:** https://developers.tiktok.com/doc/changelog
- **Terms of Service:** https://developers.tiktok.com/doc/tiktok-api-terms-of-service

## Maintainers

**Kin Lane** (kin@apievangelist.com)
