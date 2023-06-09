# @rocket.chat/meteor

## 6.3.0

### Minor Changes

- [#29203](https://github.com/RocketChat/Rocket.Chat/pull/29203) [`56177021d9`](https://github.com/RocketChat/Rocket.Chat/commit/56177021d918d69913d6bcf531a5fda28675fae1) Thanks [@yash-rajpal](https://github.com/yash-rajpal)! - feat: access-marketplace permission

- [#28975](https://github.com/RocketChat/Rocket.Chat/pull/28975) [`9ea8088f06`](https://github.com/RocketChat/Rocket.Chat/commit/9ea8088f0621900fa7a11156a89f7447482e4df8) Thanks [@yash-rajpal](https://github.com/yash-rajpal)! - fix: respect useEmoji preference for messages

- [#29303](https://github.com/RocketChat/Rocket.Chat/pull/29303) [`35aeeed1ca`](https://github.com/RocketChat/Rocket.Chat/commit/35aeeed1cab7875bb622f4c1a33be743ab7e851e) Thanks [@yash-rajpal](https://github.com/yash-rajpal)! - fix: Hide roomLeader padding

- [#29373](https://github.com/RocketChat/Rocket.Chat/pull/29373) [`3109a764bc`](https://github.com/RocketChat/Rocket.Chat/commit/3109a764bc23f7f1912ed45f1ed6908b89a6d4b0) Thanks [@sampaiodiego](https://github.com/sampaiodiego)! - feat: _Enterprise_ Add support for different transporters to connect multiple monolith instances.

  To use that, you can use the `TRANSPORTER` env var adding "monolith+" to the transporter value. To use NATS for example, your env var should be:

  ```bash
  export TRANSPORTER="monolith+nats://localhost:4222"
  ```

- [#28948](https://github.com/RocketChat/Rocket.Chat/pull/28948) [`6a474ff952`](https://github.com/RocketChat/Rocket.Chat/commit/6a474ff952fea793aac3db226d13fd9a0bb4f35a) Thanks [@aleksandernsilva](https://github.com/aleksandernsilva)! - Refactored Omnichannel department pages to use best practices, also fixed existing bugs

- [#29335](https://github.com/RocketChat/Rocket.Chat/pull/29335) [`cebe359d13`](https://github.com/RocketChat/Rocket.Chat/commit/cebe359d1392c50d7cf8979bdf3e4015544ef97d) Thanks [@yash-rajpal](https://github.com/yash-rajpal)! - fix: Room history scrollbar position

- [#29474](https://github.com/RocketChat/Rocket.Chat/pull/29474) [`066cf25f6f`](https://github.com/RocketChat/Rocket.Chat/commit/066cf25f6fa64d3fb77aeade6117dc241410b4ee) Thanks [@yash-rajpal](https://github.com/yash-rajpal)! - Fixed invalid message draft issue.

- [#29255](https://github.com/RocketChat/Rocket.Chat/pull/29255) [`e116d88047`](https://github.com/RocketChat/Rocket.Chat/commit/e116d8804783c91d2f0d1633caea25aeefb67b86) Thanks [@dougfabris](https://github.com/dougfabris)! - chore: Add `roomName` on Composer placeholder

- [#29263](https://github.com/RocketChat/Rocket.Chat/pull/29263) [`40cebcc0f1`](https://github.com/RocketChat/Rocket.Chat/commit/40cebcc0f1ce12b0b0d6fdf497b5399930c713bf) Thanks [@ggazzo](https://github.com/ggazzo)! - ask for totp if the provided one is invalid

- [#29282](https://github.com/RocketChat/Rocket.Chat/pull/29282) [`29556cbba9`](https://github.com/RocketChat/Rocket.Chat/commit/29556cbba9dd2cf7112b8ebfc9f9a7a2d819d64f) Thanks [@yash-rajpal](https://github.com/yash-rajpal)! - Added emoji popup trigger length of 3 characters.

- [#29336](https://github.com/RocketChat/Rocket.Chat/pull/29336) [`6e2f78feea`](https://github.com/RocketChat/Rocket.Chat/commit/6e2f78feea1054feb5581d5793a81ddb719585e2) Thanks [@aleksandernsilva](https://github.com/aleksandernsilva)! - Added ability to see attachments in the contact history message list

- [#29286](https://github.com/RocketChat/Rocket.Chat/pull/29286) [`7e00009ddb`](https://github.com/RocketChat/Rocket.Chat/commit/7e00009ddb2d23995eacf5b176b0ebc8007e4bb6) Thanks [@anikdhabal](https://github.com/anikdhabal)! - fix: Analytics page crash

### Patch Changes

- [#28367](https://github.com/RocketChat/Rocket.Chat/pull/28367) [`b03fcd9c14`](https://github.com/RocketChat/Rocket.Chat/commit/b03fcd9c14170373e0bd6e44b9b7f369945ffbf2) Thanks [@cauefcr](https://github.com/cauefcr)! - fix: broken error messages on room.saveInfo & missing CF validations on omni/contact api

- [#29372](https://github.com/RocketChat/Rocket.Chat/pull/29372) [`ea0bbba8ab`](https://github.com/RocketChat/Rocket.Chat/commit/ea0bbba8abebfa8e0fceac25743b4a9283e223d5) Thanks [@totoi690](https://github.com/totoi690)! - fixed system messages for room role changes

- [#29401](https://github.com/RocketChat/Rocket.Chat/pull/29401) [`7d769b96e3`](https://github.com/RocketChat/Rocket.Chat/commit/7d769b96e3d8c56d1beba306805d741377edab6f) Thanks [@matheusbsilva137](https://github.com/matheusbsilva137)! - fix: Importer crashes when sending the "active status" e-mail notification to users

- [#28814](https://github.com/RocketChat/Rocket.Chat/pull/28814) [`222c8ec5bb`](https://github.com/RocketChat/Rocket.Chat/commit/222c8ec5bb49aa3cd7327d707a957cde592401c6) Thanks [@matheusbsilva137](https://github.com/matheusbsilva137)! - feat: [ENTERPRISE] Add setting to control user merge on LDAP Background Sync

- [#29349](https://github.com/RocketChat/Rocket.Chat/pull/29349) [`c95cda43e6`](https://github.com/RocketChat/Rocket.Chat/commit/c95cda43e69b931cb2c902f9cd031ac064930f6a) Thanks [@ggazzo](https://github.com/ggazzo)! - fix: getActiveLocalUserCount query always returning 0

- [#29245](https://github.com/RocketChat/Rocket.Chat/pull/29245) [`d33f4ebabe`](https://github.com/RocketChat/Rocket.Chat/commit/d33f4ebabee0bc1e49745c8e8ff816a58a3264f6) Thanks [@gabriellsh](https://github.com/gabriellsh)! - fix: OTR session closing after 10 seconds without warning

- [#29174](https://github.com/RocketChat/Rocket.Chat/pull/29174) [`347e206023`](https://github.com/RocketChat/Rocket.Chat/commit/347e2060235fad8b353294501b54a9db809bfbff) Thanks [@gabriellsh](https://github.com/gabriellsh)! - fix: Clicking uploaded file title replaces current tab

- [#29313](https://github.com/RocketChat/Rocket.Chat/pull/29313) [`c9279bfcd3`](https://github.com/RocketChat/Rocket.Chat/commit/c9279bfcd31e7437719c7dc38b80dea0dee84c47) Thanks [@debdutdeb](https://github.com/debdutdeb)! - fix: message deletion fails if has files attached on filesystem storage

- [#29250](https://github.com/RocketChat/Rocket.Chat/pull/29250) [`0c34904b50`](https://github.com/RocketChat/Rocket.Chat/commit/0c34904b5024af34d2e0153d29684e0523d08ae6) Thanks [@aleksandernsilva](https://github.com/aleksandernsilva)! - Fixed omnichannel contact form asynchronous validations

- [#29293](https://github.com/RocketChat/Rocket.Chat/pull/29293) [`1687bfbe3a`](https://github.com/RocketChat/Rocket.Chat/commit/1687bfbe3a6af77614e2c20a0ec9c59a218edc66) Thanks [@debdutdeb](https://github.com/debdutdeb)! - fix: Admins unable to create new users if new users require manual approval

- [#28611](https://github.com/RocketChat/Rocket.Chat/pull/28611) [`b31ccd4a96`](https://github.com/RocketChat/Rocket.Chat/commit/b31ccd4a96a62b25e9612f4e1a3ddfd629506df9) Thanks [@felipe-rod123](https://github.com/felipe-rod123)! - chore: break down helpers.ts and create new files

  🔀 changed `handleAPIError` import in AppDetailsPage.tsx
  🔀 changed `apiCurlGetter` import in AppDetailsAPIs.tsx
  🔀 changed `formatPriceAndPurchaseType` import in AppStatusPriceDisplay.tsx

  ❌ deleted `apiCurlGetter, handleInstallError, handleAPIError, warnAppInstall, warnEnableDisableApp, warnStatusChange, formatPriceAndPurchaseType` and moved them to new files, from helpers.ts

  ✅ created apiCurlGetter.ts file
  ✅ created appErroredStatuses.ts file
  ✅ created formatPrice.ts file
  ✅ created formatPriceAndPurchaseType.ts file
  ✅ created formatPricingPlan.ts file
  ✅ created handleAPIError.ts file
  ✅ created handleInstallError.ts file
  ✅ created installApp.ts file
  ✅ created updateApp.ts file
  ✅ created warnAppInstal.ts file
  ✅ created warnEnableDisableApp.ts file
  ✅ created warnStatusChange.ts file

  🔀 changed `handleAPIError` import in useAppInstallationHandler.tsx
  🔀 changed `handleAPIError` import in useCategories.ts
  🔀 changed `handleAPIError` import in useOpenIncompatibleModal.tsx

- [#29189](https://github.com/RocketChat/Rocket.Chat/pull/29189) [`29452946a5`](https://github.com/RocketChat/Rocket.Chat/commit/29452946a55f093dda7acadd381da4fcb42cf563) Thanks [@KevLehman](https://github.com/KevLehman)! - fix: `queuedForUser` endpoint not filtering by status

- [#29395](https://github.com/RocketChat/Rocket.Chat/pull/29395) [`26db142b10`](https://github.com/RocketChat/Rocket.Chat/commit/26db142b100b6886909b107ca578d11da464e823) Thanks [@ggazzo](https://github.com/ggazzo)! - fix wrong %s translations

- [#28999](https://github.com/RocketChat/Rocket.Chat/pull/28999) [`ebbb608166`](https://github.com/RocketChat/Rocket.Chat/commit/ebbb608166b2c069df3397c8f8f48a965bf157af) Thanks [@hugocostadev](https://github.com/hugocostadev)! - fix: Login Terms custom content
  The custom layout Login Terms did not had any effect on the login screen, so it was changed to get the proper setting effect

- [#29278](https://github.com/RocketChat/Rocket.Chat/pull/29278) [`17024613c5`](https://github.com/RocketChat/Rocket.Chat/commit/17024613c5250fd9a311bd53b623e27bc1001be4) Thanks [@aleksandernsilva](https://github.com/aleksandernsilva)! - fixes the Livechat CSP validation, which was incorrectly blocking access to the widget for all non whitelisted domains

- [#27121](https://github.com/RocketChat/Rocket.Chat/pull/27121) [`c8cdc51799`](https://github.com/RocketChat/Rocket.Chat/commit/c8cdc5179932c23bc1211eb6df1ae602c2772cc7) Thanks [@debdutdeb](https://github.com/debdutdeb)! - fix: unable to upload files in IOS Safari browsers

- [#28081](https://github.com/RocketChat/Rocket.Chat/pull/28081) [`3f58495769`](https://github.com/RocketChat/Rocket.Chat/commit/3f58495769d853a8cee1c4c51161e24350185b0c) Thanks [@LucianoPierdona](https://github.com/LucianoPierdona)! - chore: update room on `cleanRoomHistory` only if any message has been deleted

- [#29128](https://github.com/RocketChat/Rocket.Chat/pull/29128) [`2bcc812fcf`](https://github.com/RocketChat/Rocket.Chat/commit/2bcc812fcfaa570fb814a1484d02a47c006f8562) Thanks [@ggazzo](https://github.com/ggazzo)! - fix: Rocket.Chat.Apps using wrong id parameter to emit settings

- [#28989](https://github.com/RocketChat/Rocket.Chat/pull/28989) [`505b292ba9`](https://github.com/RocketChat/Rocket.Chat/commit/505b292ba90a861ad9bd58b3751018d5016612c5) Thanks [@murtaza98](https://github.com/murtaza98)! - test: add missing omnichannel contact-center tests

- [#29019](https://github.com/RocketChat/Rocket.Chat/pull/29019) [`82194555ea`](https://github.com/RocketChat/Rocket.Chat/commit/82194555ea4569cb1f923f438c87e5cc5e92f072) Thanks [@totoi690](https://github.com/totoi690)! - fix: Editing a room in the admin menu breaks that room's integration

- [#29421](https://github.com/RocketChat/Rocket.Chat/pull/29421) [`585c49f145`](https://github.com/RocketChat/Rocket.Chat/commit/585c49f1459789badfc68b4592b7da129ca263b9) Thanks [@matheusbsilva137](https://github.com/matheusbsilva137)! - fix: Import progress page stuck at 0%

- [#29323](https://github.com/RocketChat/Rocket.Chat/pull/29323) [`f8cd53bc7e`](https://github.com/RocketChat/Rocket.Chat/commit/f8cd53bc7e89ab45c8963d65c99c96d87756d91a) Thanks [@KevLehman](https://github.com/KevLehman)! - fix: Add missing awaits to .count() calls

- [#29489](https://github.com/RocketChat/Rocket.Chat/pull/29489) [`a685a592a9`](https://github.com/RocketChat/Rocket.Chat/commit/a685a592a9cd73bd9639f9e9d95c5995336637de) Thanks [@ggazzo](https://github.com/ggazzo)! - Fix seats counter including apps

- [#29416](https://github.com/RocketChat/Rocket.Chat/pull/29416) [`4513378600`](https://github.com/RocketChat/Rocket.Chat/commit/45133786008e873a4a5a533958491bccd511aa9a) Thanks [@matheusbsilva137](https://github.com/matheusbsilva137)! - fix: Imported messages are not displayed
  fix: Importer agent is added as a member of every imported room

- [#28979](https://github.com/RocketChat/Rocket.Chat/pull/28979) [`8fcb3edb40`](https://github.com/RocketChat/Rocket.Chat/commit/8fcb3edb40159cb1d6a7f881d978ee6043d08faf) Thanks [@aleksandernsilva](https://github.com/aleksandernsilva)! - fix: Remove room from UI when another agent takes it

- [#29378](https://github.com/RocketChat/Rocket.Chat/pull/29378) [`059a92e876`](https://github.com/RocketChat/Rocket.Chat/commit/059a92e8769d86cdb40b748895494cb285550afc) Thanks [@KevLehman](https://github.com/KevLehman)! - Fix visitor's query when both email & phone number are empty

- Updated dependencies [[`4b5a87c88b`](https://github.com/RocketChat/Rocket.Chat/commit/4b5a87c88b132c6899ee5023059d17822766bec7), [`e006013e5f`](https://github.com/RocketChat/Rocket.Chat/commit/e006013e5f1f2e795d1594b4c0ac325b600231c0), [`9ea8088f06`](https://github.com/RocketChat/Rocket.Chat/commit/9ea8088f0621900fa7a11156a89f7447482e4df8), [`ebbb608166`](https://github.com/RocketChat/Rocket.Chat/commit/ebbb608166b2c069df3397c8f8f48a965bf157af), [`6a474ff952`](https://github.com/RocketChat/Rocket.Chat/commit/6a474ff952fea793aac3db226d13fd9a0bb4f35a), [`37c792161f`](https://github.com/RocketChat/Rocket.Chat/commit/37c792161f756c712a4203f36a3e056bfb323258), [`40cebcc0f1`](https://github.com/RocketChat/Rocket.Chat/commit/40cebcc0f1ce12b0b0d6fdf497b5399930c713bf), [`40cebcc0f1`](https://github.com/RocketChat/Rocket.Chat/commit/40cebcc0f1ce12b0b0d6fdf497b5399930c713bf), [`cde2539619`](https://github.com/RocketChat/Rocket.Chat/commit/cde253961940855cbf94ed10a84ddd1b1b9ff613)]:
  - @rocket.chat/web-ui-registration@1.0.0
  - @rocket.chat/api-client@0.1.0
  - @rocket.chat/rest-typings@6.3.0
  - @rocket.chat/gazzodown@1.0.0
  - @rocket.chat/agenda@0.0.2
  - @rocket.chat/omnichannel-services@0.0.2
  - @rocket.chat/presence@0.0.2
  - @rocket.chat/core-services@0.0.2
  - @rocket.chat/ui-contexts@1.0.0
  - @rocket.chat/fuselage-ui-kit@1.0.0
  - @rocket.chat/cron@0.0.2
  - @rocket.chat/ui-theming@0.0.1
  - @rocket.chat/ui-client@1.0.0
  - @rocket.chat/ui-video-conf@1.0.0
  - @rocket.chat/core-typings@6.3.0
  - @rocket.chat/pdf-worker@0.0.2
  - @rocket.chat/model-typings@0.0.2
  - @rocket.chat/models@0.0.2
  - @rocket.chat/instance-status@0.0.2
