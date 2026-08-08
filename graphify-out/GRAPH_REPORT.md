# Graph Report - .  (2026-08-08)

## Corpus Check
- 66 files · ~234,321 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 826 nodes · 1457 edges · 72 communities (62 shown, 10 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS · INFERRED: 1 edges (avg confidence: 0.75)
- Token cost: 244,721 input · 0 output

## Community Hubs (Navigation)
- f-members Service Dependency Graph
- domain-events Events Dependency Graph
- mentions Service Dependency Graph
- settings Service Dependency Graph
- url Service Dependency Graph
- auth Service Dependency Graph
- email-service Service Dependency Graph
- ff-mail Service Dependency Graph
- themes Service Dependency Graph
- posts Service Dependency Graph
- events Events Dependency Graph
- comments Service Dependency Graph
- f-stripe Service Dependency Graph
- email-analytics Service Dependency Graph
- adapter-manager Service Dependency Graph
- f-limits-js Service Dependency Graph
- f-email-suppression-list Service Dependency Graph
- f-jobs Service Dependency Graph
- mentions-email-report Service Dependency Graph
- offers Service Dependency Graph
- route-settings Service Dependency Graph
- settings-helpers Service Dependency Graph
- staff Service Dependency Graph
- api-version-compatibility Service Dependency Graph
- collections Service Dependency Graph
- f-member-attribution Service Dependency Graph
- f-link-tracking Service Dependency Graph
- milestones Service Dependency Graph
- newsletters Service Dependency Graph
- recommendations Service Dependency Graph
- custom-redirects Service Dependency Graph
- segment Service Dependency Graph
- tiers Service Dependency Graph
- webhooks Service Dependency Graph
- members-events Service Dependency Graph
- mentions-jobs Service Dependency Graph
- permissions Service Dependency Graph
- public-config Service Dependency Graph
- Readme
- audience-feedback Service Dependency Graph
- explore Service Dependency Graph
- f-lexical-multiplayer Service Dependency Graph
- f-link-redirection Service Dependency Graph
- media-inliner Service Dependency Graph
- oembed Service Dependency Graph
- i18n-js Service Dependency Graph
- invites Service Dependency Graph
- mail-events Service Dependency Graph
- posts-public Service Dependency Graph
- slack-js Service Dependency Graph
- slack-notifications Service Dependency Graph
- tags-public Service Dependency Graph
- xmlrpc-js Service Dependency Graph
- custom-theme-settings-js Service Dependency Graph
- donations Service Dependency Graph
- model-to-domain-event-interceptor Service Dependency Graph
- stats Service Dependency Graph
- frontend-data-service Service Dependency Graph
- invitations Service Dependency Graph
- notifications Service Dependency Graph
- websockets Service Dependency Graph
- announcement-bar-service Service Dependency Graph
- users-js Service Dependency Graph
- domain-events Events Dependency Graph
- domain-events Events Dependency Graph
- domain-events Events Dependency Graph
- Navigation Demo Navigation Demo
- comments Service Dependency Graph
- comments Service Dependency Graph
- comments Service Dependency Graph
- integrations Service Dependency Graph
- webhooks Service Dependency Graph

## God Nodes (most connected - your core abstractions)
1. `ghost/domain-events/index.js` - 38 edges
2. `ghost/core/core/server/services/members/service.js` - 23 edges
3. `ghost/core/core/server/services/email-service/EmailServiceWrapper.js` - 23 edges
4. `ghost/core/core/server/services/members/api.js` - 20 edges
5. `ghost/core/core/server/lib/common/events.js` - 19 edges
6. `ghost/core/core/server/services/mail/index.js` - 17 edges
7. `index.js` - 17 edges
8. `ghost/core/core/server/models/index.js` - 16 edges
9. `ghost/core/core/shared/url-utils.js` - 15 edges
10. `ghost/core/core/shared/url-utils.js` - 15 edges

## Surprising Connections (you probably didn't know these)
- `Architecture Diagrams README` --conceptually_related_to--> `Service Dependency Maps README`  [INFERRED]
  README.md → service-dep-maps/README.MD

## Communities (72 total, 10 thin omitted)

### Community 0 - "f-members Service Dependency Graph"
Cohesion: 0.11
Nodes (53): ghost/core/core/boot.js, ghost/core/core/frontend/web/site.js, ghost/core/core/server/data/db/index.js, ghost/core/core/server/data/importer/importers/data/RevueSubscriberImporter.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/auth/members/index.js, ghost/core/core/server/services/comments/index.js, ghost/core/core/server/services/email-analytics/EmailAnalyticsServiceWrapper.js (+45 more)

### Community 1 - "domain-events Events Dependency Graph"
Cohesion: 0.05
Nodes (40): ghost/collections/test/collections.test.ts, ghost/core/core/frontend/services/sitemap/SiteMapManager.js, ghost/core/core/frontend/web/site.js, ghost/core/core/server/services/collections/service.js, ghost/core/core/server/services/comments/CommentsService.js, ghost/core/core/server/services/email-analytics/EmailAnalyticsServiceWrapper.js, ghost/core/core/server/services/email-suppression-list/MailgunEmailSuppressionList.js, ghost/core/core/server/services/jobs/job-service.js (+32 more)

### Community 2 - "mentions Service Dependency Graph"
Cohesion: 0.13
Nodes (30): ghost/core/core/boot.js, ghost/core/core/server/lib/common/events.js, ghost/core/core/server/lib/request-external.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/mail/index.js, ghost/core/core/server/services/mentions/BookshelfMentionRepository.js, ghost/core/core/server/services/mentions-email-report/index.js, ghost/core/core/server/services/mentions-email-report/job.js (+22 more)

### Community 3 - "settings Service Dependency Graph"
Cohesion: 0.21
Nodes (30): boot.js, events.js, index.js, run-update-check.js, index.js, index.js, index.js, EmailServiceWrapper.js (+22 more)

### Community 4 - "url Service Dependency Graph"
Cohesion: 0.16
Nodes (30): app.js, boot.js, bridge.js, router.js, author-url.js, url.js, proxy.js, events.js (+22 more)

### Community 5 - "auth Service Dependency Graph"
Cohesion: 0.14
Nodes (27): ghost/constants/index.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/adapter-manager/index.js, ghost/core/core/server/services/api-version-compatibility/index.js, ghost/core/core/server/services/auth/api-key/admin.js, ghost/core/core/server/services/auth/api-key/content.js, ghost/core/core/server/services/auth/api-key/index.js, ghost/core/core/server/services/auth/authenticate.js (+19 more)

### Community 6 - "email-service Service Dependency Graph"
Cohesion: 0.21
Nodes (27): ghost/core/core/boot.js, ghost/core/core/server/adapters/storage/utils.js, ghost/core/core/server/data/db/index.js, ghost/core/core/server/lib/image/index.js, ghost/core/core/server/lib/lexical.js, ghost/core/core/server/lib/mobiledoc.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/audience-feedback/index.js (+19 more)

### Community 7 - "ff-mail Service Dependency Graph"
Cohesion: 0.27
Nodes (25): ghost/core/core/boot.js, ghost/core/core/server/data/importer/import-manager.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/api-version-compatibility/index.js, ghost/core/core/server/services/auth/passwordreset.js, ghost/core/core/server/services/auth/setup.js, ghost/core/core/server/services/comments/index.js, ghost/core/core/server/services/invites/index.js (+17 more)

### Community 8 - "themes Service Dependency Graph"
Cohesion: 0.21
Nodes (22): boot.js, bridge.js, LocalStorageBase.js, CustomThemeSettingsImporter.js, index.js, custom-theme-settings.js, limits.js, activate.js (+14 more)

### Community 9 - "posts Service Dependency Graph"
Cohesion: 0.17
Nodes (21): ghost/core/core/boot.js, ghost/core/core/server/data/db/index.js, ghost/core/core/server/lib/common/events.js, ghost/core/core/server/lib/lexical.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/adapter-manager/index.js, ghost/core/core/server/services/collections/index.js, ghost/core/core/server/services/email-service/index.js (+13 more)

### Community 10 - "events Events Dependency Graph"
Cohesion: 0.10
Nodes (20): ghost/core/core/bridge.js, ghost/core/core/frontend/services/routing/RouterManager.js, ghost/core/core/frontend/services/sitemap/SiteMapManager.js, ghost/core/core/server/adapters/scheduling/post-scheduling/index.js, ghost/core/core/server/lib/common/events.js, ghost/core/core/server/models/base/listeners.js, ghost/core/core/server/models/base/plugins/events.js, ghost/core/core/server/services/i18n.js (+12 more)

### Community 11 - "comments Service Dependency Graph"
Cohesion: 0.18
Nodes (19): ghost/core/core/boot.js, ghost/core/core/server/data/db/index.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/comments/CommentsController.js, ghost/core/core/server/services/comments/CommentsService.js, ghost/core/core/server/services/comments/CommentsServiceEmails.js, ghost/core/core/server/services/comments/CommentsStatsService.js, ghost/core/core/server/services/comments/index.js (+11 more)

### Community 12 - "f-stripe Service Dependency Graph"
Cohesion: 0.29
Nodes (19): ghost/core/core/boot.js, ghost/core/core/server/lib/common/events.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/donations/index.js, ghost/core/core/server/services/explore/index.js, ghost/core/core/server/services/members/api.js, ghost/core/core/server/services/members/index.js, ghost/core/core/server/services/members/service.js (+11 more)

### Community 13 - "email-analytics Service Dependency Graph"
Cohesion: 0.20
Nodes (18): ghost/core/core/boot.js, ghost/core/core/server/data/db/index.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/email-analytics/EmailAnalyticsServiceWrapper.js, ghost/core/core/server/services/email-analytics/events/StartEmailAnalyticsJobEvent.js, ghost/core/core/server/services/email-analytics/index.js, ghost/core/core/server/services/email-analytics/jobs/fetch-latest/index.js, ghost/core/core/server/services/email-analytics/jobs/index.js (+10 more)

### Community 14 - "adapter-manager Service Dependency Graph"
Cohesion: 0.17
Nodes (16): ghost/adapter-manager/index.js, ghost/core/core/server/adapters/cache/index.js, ghost/core/core/server/adapters/scheduling/scheduling-base.js, ghost/core/core/server/adapters/scheduling/utils.js, ghost/core/core/server/adapters/sso/SSOBase.js, ghost/core/core/server/adapters/storage/index.js, ghost/core/core/server/lib/image/index.js, ghost/core/core/server/services/adapter-manager/config.js (+8 more)

### Community 15 - "f-limits-js Service Dependency Graph"
Cohesion: 0.17
Nodes (15): ghost/core/core/boot.js, ghost/core/core/server/data/db/index.js, ghost/core/core/server/data/importer/importers/data/UsersImporter.js, ghost/core/core/server/models/integration.js, ghost/core/core/server/models/invite.js, ghost/core/core/server/models/post.js, ghost/core/core/server/models/user.js, ghost/core/core/server/services/auth/api-key/admin.js (+7 more)

### Community 16 - "f-email-suppression-list Service Dependency Graph"
Cohesion: 0.21
Nodes (14): ghost/core/core/boot.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/email-suppression-list/index.js, ghost/core/core/server/services/email-suppression-list/InMemoryEmailSuppressionList.js, ghost/core/core/server/services/email-suppression-list/MailgunEmailSuppressionList.js, ghost/core/core/server/services/email-suppression-list/service.js, ghost/core/core/server/services/members/api.js, ghost/core/core/server/services/members/middleware.js (+6 more)

### Community 17 - "f-jobs Service Dependency Graph"
Cohesion: 0.26
Nodes (14): ghost/core/core/boot.js, ghost/core/core/server/data/importer/import-manager.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/email-analytics/jobs/index.js, ghost/core/core/server/services/email-service/EmailServiceWrapper.js, ghost/core/core/server/services/jobs/index.js, ghost/core/core/server/services/jobs/job-service.js, ghost/core/core/server/services/media-inliner/service.js (+6 more)

### Community 18 - "mentions-email-report Service Dependency Graph"
Cohesion: 0.26
Nodes (14): ghost/core/core/boot.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/mail/index.js, ghost/core/core/server/services/mentions-email-report/index.js, ghost/core/core/server/services/mentions-email-report/job.js, ghost/core/core/server/services/mentions-email-report/service.js, ghost/core/core/server/services/mentions-email-report/StartMentionEmailReportJob.js, ghost/core/core/server/services/mentions/index.js (+6 more)

### Community 19 - "offers Service Dependency Graph"
Cohesion: 0.31
Nodes (13): ghost/core/core/boot.js, ghost/core/core/frontend/web/site.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/members/api.js, ghost/core/core/server/services/offers/index.js, ghost/core/core/server/services/offers/OfferBookshelfRepository.js, ghost/core/core/server/services/offers/service.js, ghost/core/core/shared/config/index.js (+5 more)

### Community 20 - "route-settings Service Dependency Graph"
Cohesion: 0.23
Nodes (13): ghost/core/core/boot.js, ghost/core/core/bridge.js, ghost/core/core/frontend/services/routing/config.js, ghost/core/core/server/services/route-settings/DefaultSettingsManager.js, ghost/core/core/server/services/route-settings/index.js, ghost/core/core/server/services/route-settings/RouteSettings.js, ghost/core/core/server/services/route-settings/SettingsLoader.js, ghost/core/core/server/services/route-settings/validate.js (+5 more)

### Community 21 - "settings-helpers Service Dependency Graph"
Cohesion: 0.44
Nodes (13): index.js, EmailServiceWrapper.js, index.js, service.js, posts-service.js, index.js, SettingsHelpers.js, settings-service.js (+5 more)

### Community 22 - "staff Service Dependency Graph"
Cohesion: 0.42
Nodes (13): boot.js, index.js, index.js, index.js, service.js, index.js, index.js, service.js (+5 more)

### Community 23 - "api-version-compatibility Service Dependency Graph"
Cohesion: 0.35
Nodes (12): ghost/api-version-compatibility-service/index.js, ghost/core/core/boot.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/api-version-compatibility/index.js, ghost/core/core/server/services/api-version-compatibility/legacy-api-path-match.js, ghost/core/core/server/services/api-version-compatibility/mw-version-rewrites.js, ghost/core/core/server/services/auth/api-key/admin.js, ghost/core/core/server/services/mail/index.js (+4 more)

### Community 24 - "collections Service Dependency Graph"
Cohesion: 0.30
Nodes (12): ghost/collections/build/index.js, ghost/core/core/boot.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/collections/BookshelfCollectionsRepository.js, ghost/core/core/server/services/collections/index.js, ghost/core/core/server/services/collections/PostsRepository.js, ghost/core/core/server/services/collections/service.js, ghost/core/core/server/services/posts/posts-service.js (+4 more)

### Community 25 - "f-member-attribution Service Dependency Graph"
Cohesion: 0.50
Nodes (12): ghost/core/core/boot.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/email-service/EmailServiceWrapper.js, ghost/core/core/server/services/member-attribution/index.js, ghost/core/core/server/services/members/api.js, ghost/core/core/server/services/staff/index.js, ghost/core/core/server/services/url/index.js, ghost/core/core/shared/config/index.js (+4 more)

### Community 26 - "f-link-tracking Service Dependency Graph"
Cohesion: 0.35
Nodes (11): ghost/core/core/boot.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/email-service/EmailServiceWrapper.js, ghost/core/core/server/services/link-redirection/index.js, ghost/core/core/server/services/link-tracking/index.js, ghost/core/core/server/services/link-tracking/LinkClickRepository.js, ghost/core/core/server/services/link-tracking/PostLinkRepository.js, ghost/core/core/shared/url-utils.js (+3 more)

### Community 27 - "milestones Service Dependency Graph"
Cohesion: 0.24
Nodes (11): ghost/core/core/boot.js, ghost/core/core/server/data/db/index.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/milestones/BookshelfMilestoneRepository.js, ghost/core/core/server/services/milestones/index.js, ghost/core/core/server/services/milestones/MilestoneQueries.js, ghost/core/core/server/services/milestones/service.js, ghost/core/core/shared/config/index.js (+3 more)

### Community 28 - "newsletters Service Dependency Graph"
Cohesion: 0.29
Nodes (11): ghost/core/core/server/models/index.js, ghost/core/core/server/services/limits.js, ghost/core/core/server/services/mail/index.js, ghost/core/core/server/services/members/api.js, ghost/core/core/server/services/members/SingleUseTokenProvider.js, ghost/core/core/server/services/newsletters/emails/verify-email.js, ghost/core/core/server/services/newsletters/index.js, ghost/core/core/server/services/newsletters/NewslettersService.js (+3 more)

### Community 29 - "recommendations Service Dependency Graph"
Cohesion: 0.31
Nodes (11): ghost/core/core/boot.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/mentions/index.js, ghost/core/core/server/services/recommendations/index.js, ghost/core/core/server/services/recommendations/RecommendationEnablerService.js, ghost/core/core/server/services/recommendations/RecommendationServiceWrapper.js, ghost/core/core/server/services/settings/index.js, ghost/core/core/shared/config/index.js (+3 more)

### Community 30 - "custom-redirects Service Dependency Graph"
Cohesion: 0.31
Nodes (10): ghost/core/core/boot.js, ghost/core/core/frontend/web/site.js, ghost/core/core/server/services/custom-redirects/CustomRedirectsAPI.js, ghost/core/core/server/services/custom-redirects/index.js, ghost/core/core/server/services/custom-redirects/utils.js, ghost/core/core/server/services/custom-redirects/validation.js, ghost/core/core/shared/config/index.js, ghost/core/core/shared/url-utils.js (+2 more)

### Community 31 - "segment Service Dependency Graph"
Cohesion: 0.27
Nodes (10): ghost/core/core/boot.js, ghost/core/core/server/lib/common/events.js, ghost/core/core/server/services/segment/DomainEventsAnalytics.js, ghost/core/core/server/services/segment/index.js, ghost/core/core/server/services/segment/ModelEventsAnalytics.js, ghost/core/core/shared/config/index.js, ghost/core/core/shared/sentry.js, ghost/domain-events/index.js (+2 more)

### Community 32 - "tiers Service Dependency Graph"
Cohesion: 0.33
Nodes (10): boot.js, index.js, run-update-check.js, api.js, service.js, index.js, service.js, TierRepository.js (+2 more)

### Community 33 - "webhooks Service Dependency Graph"
Cohesion: 0.24
Nodes (10): index.js, boot.js, events.js, index.js, limits.js, index.js, listen.js, payload.js (+2 more)

### Community 34 - "members-events Service Dependency Graph"
Cohesion: 0.31
Nodes (9): ghost/core/core/boot.js, ghost/core/core/server/data/db/index.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/members-events/index.js, ghost/core/core/server/services/members/index.js, ghost/core/core/shared/labs.js, ghost/core/core/shared/settings-cache/index.js, ghost/domain-events/index.js (+1 more)

### Community 35 - "mentions-jobs Service Dependency Graph"
Cohesion: 0.39
Nodes (9): ghost/core/core/boot.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/mentions-email-report/service.js, ghost/core/core/server/services/mentions-jobs/index.js, ghost/core/core/server/services/mentions-jobs/job-service.js, ghost/core/core/server/services/mentions/service.js, ghost/core/core/shared/sentry.js, ghost/domain-events/index.js (+1 more)

### Community 36 - "permissions Service Dependency Graph"
Cohesion: 0.39
Nodes (9): ghost/core/core/boot.js, ghost/core/core/server/models/index.js, ghost/core/core/server/models/user.js, ghost/core/core/server/run-update-check.js, ghost/core/core/server/services/permissions/actions-map-cache.js, ghost/core/core/server/services/permissions/can-this.js, ghost/core/core/server/services/permissions/index.js, ghost/core/core/server/services/permissions/parse-context.js (+1 more)

### Community 37 - "public-config Service Dependency Graph"
Cohesion: 0.33
Nodes (9): ghost/core/core/server/data/db/info.js, ghost/core/core/server/services/explore/index.js, ghost/core/core/server/services/public-config/config.js, ghost/core/core/server/services/public-config/index.js, ghost/core/core/server/services/public-config/site.js, ghost/core/core/shared/config/index.js, ghost/core/core/shared/labs.js, ghost/core/core/shared/settings-cache/index.js (+1 more)

### Community 38 - "Readme"
Cohesion: 0.25
Nodes (8): Architecture Diagrams README, Copyright & License, ghost.draw.io diagram file, Quickstart Install, VS Code draw.io extension (hediet.vscode-drawio), Service Dependency Maps README, dependency-cruiser (depcruise), How these are generated

### Community 39 - "audience-feedback Service Dependency Graph"
Cohesion: 0.43
Nodes (8): ghost/audience-feedback/index.js, ghost/core/core/boot.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/audience-feedback/FeedbackRepository.js, ghost/core/core/server/services/audience-feedback/index.js, ghost/core/core/server/services/email-service/EmailServiceWrapper.js, ghost/core/core/server/services/url/index.js, ghost/core/core/shared/url-utils.js

### Community 40 - "explore Service Dependency Graph"
Cohesion: 0.29
Nodes (8): ghost/core/core/server/models/index.js, ghost/core/core/server/services/explore/ExploreService.js, ghost/core/core/server/services/explore/index.js, ghost/core/core/server/services/members/index.js, ghost/core/core/server/services/posts/posts-service.js, ghost/core/core/server/services/public-config/index.js, ghost/core/core/server/services/stats/index.js, ghost/core/core/server/services/stripe/index.js

### Community 41 - "f-lexical-multiplayer Service Dependency Graph"
Cohesion: 0.32
Nodes (8): ghost/core/core/boot.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/auth/session/express-session.js, ghost/core/core/server/services/lexical-multiplayer/index.js, ghost/core/core/server/services/lexical-multiplayer/service.js, ghost/core/core/server/services/lexical-multiplayer/y-websocket.js, ghost/core/core/server/services/settings/SettingsBREADService.js, ghost/core/core/shared/labs.js

### Community 42 - "f-link-redirection Service Dependency Graph"
Cohesion: 0.50
Nodes (8): ghost/core/core/boot.js, ghost/core/core/frontend/web/site.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/link-redirection/index.js, ghost/core/core/server/services/link-redirection/LinkRedirectRepository.js, ghost/core/core/server/services/link-tracking/index.js, ghost/core/core/shared/url-utils.js, ghost/link-redirects/index.js

### Community 43 - "media-inliner Service Dependency Graph"
Cohesion: 0.36
Nodes (8): ghost/core/core/boot.js, ghost/core/core/server/adapters/storage/index.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/jobs/index.js, ghost/core/core/server/services/media-inliner/index.js, ghost/core/core/server/services/media-inliner/service.js, ghost/core/core/shared/config/index.js, ghost/external-media-inliner/index.js

### Community 44 - "oembed Service Dependency Graph"
Cohesion: 0.29
Nodes (8): ghost/core/core/server/lib/request-external.js, ghost/core/core/server/services/mentions/WebmentionMetadata.js, ghost/core/core/server/services/oembed/index.js, ghost/core/core/server/services/oembed/NFTOEmbedProvider.js, ghost/core/core/server/services/oembed/service.js, ghost/core/core/server/services/oembed/TwitterOEmbedProvider.js, ghost/core/core/shared/config/index.js, ghost/oembed-service/index.js

### Community 45 - "i18n-js Service Dependency Graph"
Cohesion: 0.43
Nodes (7): ghost/core/core/boot.js, ghost/core/core/server/lib/common/events.js, ghost/core/core/server/services/i18n.js, ghost/core/core/server/services/members/api.js, ghost/core/core/shared/labs.js, ghost/core/core/shared/settings-cache/index.js, ghost/i18n/index.js

### Community 46 - "invites Service Dependency Graph"
Cohesion: 0.48
Nodes (7): ghost/core/core/server/services/invites/index.js, ghost/core/core/server/services/invites/Invites.js, ghost/core/core/server/services/mail/index.js, ghost/core/core/server/services/settings-helpers/index.js, ghost/core/core/shared/settings-cache/index.js, ghost/core/core/shared/url-utils.js, ghost/security/index.js

### Community 47 - "mail-events Service Dependency Graph"
Cohesion: 0.43
Nodes (7): ghost/core/core/boot.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/mail-events/BookshelfMailEventRepository.js, ghost/core/core/server/services/mail-events/index.js, ghost/core/core/shared/config/index.js, ghost/core/core/shared/labs.js, ghost/mail-events/build/index.js

### Community 48 - "posts-public Service Dependency Graph"
Cohesion: 0.38
Nodes (7): ghost/core/core/boot.js, ghost/core/core/server/lib/common/events.js, ghost/core/core/server/services/adapter-manager/index.js, ghost/core/core/server/services/posts-public/index.js, ghost/core/core/server/services/posts-public/service.js, ghost/core/core/shared/config/index.js, ghost/event-aware-cache-wrapper/index.js

### Community 49 - "slack-js Service Dependency Graph"
Cohesion: 0.48
Nodes (7): boot.js, events.js, index.js, slack.js, index.js, index.js, url-utils.js

### Community 50 - "slack-notifications Service Dependency Graph"
Cohesion: 0.43
Nodes (7): boot.js, index.js, service.js, index.js, url-utils.js, index.js, index.js

### Community 51 - "tags-public Service Dependency Graph"
Cohesion: 0.38
Nodes (7): boot.js, events.js, index.js, index.js, service.js, index.js, index.js

### Community 52 - "xmlrpc-js Service Dependency Graph"
Cohesion: 0.52
Nodes (7): boot.js, events.js, index.js, xmlrpc.js, index.js, sentry.js, index.js

### Community 53 - "custom-theme-settings-js Service Dependency Graph"
Cohesion: 0.47
Nodes (6): ghost/core/core/boot.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/custom-theme-settings.js, ghost/core/core/server/services/themes/activation-bridge.js, ghost/core/core/shared/custom-theme-settings-cache.js, ghost/custom-theme-settings-service/index.js

### Community 54 - "donations Service Dependency Graph"
Cohesion: 0.47
Nodes (6): ghost/core/core/boot.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/donations/DonationServiceWrapper.js, ghost/core/core/server/services/donations/index.js, ghost/core/core/server/services/stripe/service.js, ghost/donations/build/index.js

### Community 55 - "model-to-domain-event-interceptor Service Dependency Graph"
Cohesion: 0.40
Nodes (5): ghost/core/core/boot.js, ghost/core/core/server/lib/common/events.js, ghost/core/core/server/services/model-to-domain-event-interceptor/index.js, ghost/domain-events/lib/DomainEvents.js, ghost/model-to-domain-event-interceptor/build/index.js

### Community 56 - "stats Service Dependency Graph"
Cohesion: 0.40
Nodes (5): index.js, index.js, index.js, service.js, index.js

### Community 57 - "frontend-data-service Service Dependency Graph"
Cohesion: 0.67
Nodes (4): ghost/core/core/boot.js, ghost/core/core/server/models/index.js, ghost/core/core/server/services/frontend-data-service/FrontendDataService.js, ghost/core/core/server/services/frontend-data-service/index.js

### Community 58 - "invitations Service Dependency Graph"
Cohesion: 0.50
Nodes (4): ghost/core/core/server/models/index.js, ghost/core/core/server/services/invitations/accept.js, ghost/core/core/server/services/invitations/index.js, ghost/security/index.js

### Community 59 - "notifications Service Dependency Graph"
Cohesion: 0.50
Nodes (4): ghost/core/core/server/models/index.js, ghost/core/core/server/services/notifications/index.js, ghost/core/core/server/services/notifications/Notifications.js, ghost/core/core/shared/settings-cache/index.js

### Community 60 - "websockets Service Dependency Graph"
Cohesion: 0.50
Nodes (4): boot.js, index.js, service.js, labs.js

### Community 61 - "announcement-bar-service Service Dependency Graph"
Cohesion: 0.67
Nodes (3): ghost/announcement-bar-settings/index.js, ghost/core/core/server/services/announcement-bar-service/index.js, ghost/core/core/shared/settings-cache/index.js

## Knowledge Gaps
- **258 isolated node(s):** `VS Code draw.io extension (hediet.vscode-drawio)`, `ghost.draw.io diagram file`, `Copyright & License`, `dependency-cruiser (depcruise)`, `ghost/core/core/bridge.js` (+253 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **10 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What connects `VS Code draw.io extension (hediet.vscode-drawio)`, `ghost.draw.io diagram file`, `Copyright & License` to the rest of the system?**
  _258 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `f-members Service Dependency Graph` be split into smaller, more focused modules?**
  _Cohesion score 0.10595065312046444 - nodes in this community are weakly interconnected._
- **Should `domain-events Events Dependency Graph` be split into smaller, more focused modules?**
  _Cohesion score 0.05384615384615385 - nodes in this community are weakly interconnected._
- **Should `mentions Service Dependency Graph` be split into smaller, more focused modules?**
  _Cohesion score 0.12643678160919541 - nodes in this community are weakly interconnected._
- **Should `auth Service Dependency Graph` be split into smaller, more focused modules?**
  _Cohesion score 0.1396011396011396 - nodes in this community are weakly interconnected._
- **Should `events Events Dependency Graph` be split into smaller, more focused modules?**
  _Cohesion score 0.1 - nodes in this community are weakly interconnected._