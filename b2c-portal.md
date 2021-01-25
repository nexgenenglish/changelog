---
title: B2C Portal
---

# B2C Portal

## [v1.1.14] on January 25th, 2021
- [MNS-745](https://dyned.myjetbrains.com/youtrack/issue/MNS-745) Added validation to reopen CT and fixed total attempt after reopen CT.
- [MNS-746](https://dyned.myjetbrains.com/youtrack/issue/MNS-746) Changed email service to smtp.
- Added MyLesson video introduction under videos in Bahasa.
- [MNS-747](https://dyned.myjetbrains.com/youtrack/issue/MNS-747) Fixed not showing PT Result animation for neo prep plus.

## [v.1.1.13] on November 17th, 2020
- Retreived subgroup_id and partner_id (create user API).
- Fixed amount of given coin (create user API).
- Fixed error on fetch etest API (create user API).
- Fixed error on reset coin.
- Set default picture on certificate when profile picture file not found.
- Docker version to 1.1.13.

## [v1.1.12] on September 7th, 2020
- [MNS-730](https://dyned.myjetbrains.com/youtrack/issue/MNS-730) Added split Live token.
- [MNS-732](https://dyned.myjetbrains.com/youtrack/issue/MNS-732) Added photo to generate sample certificate API.
- [MNS-739](https://dyned.myjetbrains.com/youtrack/issue/MNS-739) Added admin role authorize for API.
- [MNS-740](https://dyned.myjetbrains.com/youtrack/issue/MNS-740) Updated Planet Payment credentials.
- [MNS-741](https://dyned.myjetbrains.com/youtrack/issue/MNS-741) Fixed certificate font to suit for all languages.

## [v1.1.11] on August 28th, 2020
- Changed PT result to Lottie.
- Eula Page.
- Default trial duration to 14 days.
- Verified token to other server (global and CN).
- Added more accepted roles for API authorize.

## [v1.1.10] on June 22th, 2020
- [MNS-668](https://dyned.myjetbrains.com/youtrack/issue/MNS-668) Added new requirements for Plus plan.
- [MNS-669](https://dyned.myjetbrains.com/youtrack/issue/MNS-669) Added default PT and payment is pro plus plan.
- [MNS-686](https://dyned.myjetbrains.com/youtrack/issue/MNS-686) Hide taking picture (via webcam) button in iOS safari and fixed auto rotate when taking picture with camera.
- [MNS-682](https://dyned.myjetbrains.com/youtrack/issue/MNS-682) Fixed issue about loading picture when the connection is slow.
- [MNS-704](https://dyned.myjetbrains.com/youtrack/issue/MNS-704) Fixed issue for student who cannot activate next level and added clear cache after purchase next level.
- [MNS-708](https://dyned.myjetbrains.com/youtrack/issue/MNS-708) Updated eTest candidate after register account and phone number.
- [MNS-710](https://dyned.myjetbrains.com/youtrack/issue/MNS-710) Fixed error after purchased for next level.
- [MNS-711](https://dyned.myjetbrains.com/youtrack/issue/MNS-711) Replaced wording coins to tokens.
- [MNS-714](https://dyned.myjetbrains.com/youtrack/issue/MNS-714) Added API to get available country.
- Added use live privileges.
- User with live access 0 cannot purchase more token and token will acquired additional token on purchase next level.
- Dockerfile 1.1.10.



## [v1.1.9] on June 3th, 2020
- [NBRG-427](https://dyned.myjetbrains.com/youtrack/issue/NBRG-427) Fixed parsing login; fixed issue for student who cannot take exit test or continue study. 
- [NB2B-240](https://dyned.myjetbrains.com/youtrack/issue/NB2B-240) Fixed trial coin based priority based on request. 
- [DELP-702](https://dyned.myjetbrains.com/youtrack/issue/DELP-702) Fixed change password.
- Updated some translation (receipt / invoice page).
- Dockerfile to 1.1.9.

## [v1.1.8] on May 20th, 2020
- Added Payment Log API.
- [DELP-684](https://dyned.myjetbrains.com/youtrack/issue/DELP-684) Added API: show downloadable certificate.
- [DELP-685](https://dyned.myjetbrains.com/youtrack/issue/DELP-685) Added API: update student account type.
- Updated translation (by gita).
- [DELP-688](https://dyned.myjetbrains.com/youtrack/issue/DELP-688) Fixed Live coin purchasing.
- Added Planet as payment method option of coin purchasing.
- Added Kredivo as payment method option of coin purchasing.
- [DELP-689](https://dyned.myjetbrains.com/youtrack/issue/DELP-689) Updated payment option highlight to red.

## [v1.1.7] on May 12th, 2020
- Fixed audio sound in iOS.
- Updated API privileges for organization admin.
- Fixed cert_studying not writen to DB.
- Fixed sample cert not showing properly.

## [v1.1.6] on May 5th, 2020
- Fixed expired date on create sso (b2c) - dockerfile 1.1.5.1 (dev).
- Hide password as response (create user API) - dockerfile 1.1.5.1(dev).
- Fixed student profile data on create user API.
- Added API for get sudent study record based of organization - dockerfile 1.1.5.2 (dev).
- Added configuration to define price (level or monthly) [delp-672] - dockerfile 1.1.5.4 (dev).
- Takeout design folder and split to different repo.
- Updated dockerfile to 1.1.6.

## [v1.1.5] on April 20th, 2020
- Updated webview PT result background to transparent.
- [NB2B-234](https://dyned.myjetbrains.com/youtrack/issue/NB2B-234) Fixed create user API not written u_profile.
- [DELP-676](https://dyned.myjetbrains.com/youtrack/issue/DELP-676) Prevented add coin for student in another organization.
- Changed default trial duration to 21 days.
- Fixed coin earned if account is trial.
- Updated docker file version to 1.1.5.

## [v1.1.4] on April 13th, 2020
- [DELP-667](https://dyned.myjetbrains.com/youtrack/issue/DELP-667) Make PT on portal disable for China students.
- [DELP-670](https://dyned.myjetbrains.com/youtrack/issue/DELP-670) Created new layout for PT Plus result.
- [DELP-671](https://dyned.myjetbrains.com/youtrack/issue/DELP-671) Change trial duration.
- [DELP-673](https://dyned.myjetbrains.com/youtrack/issue/DELP-673) Fixed PT result when open from mobile.
- Updated CSS.
- Update docker version to 1.1.4.

## [v1.1.4 pre-release] on April 7th, 2020
- First prerelease, including all changes and merge from last version v1.1.3 to this point.

## [v1.1.3] on March 25th, 2020
- Updated Czech translation of video.
- Fixed profile page error.
- Fixed get user information error if not using etest.
- Created student API: remove received organization information, change to received org name and description.
- Manually set certificate send to email option; default is true.
- Changed token -> coin (naming).
- Now exit test sync with etest.
- Update live v2 service url.
- Update docker to docker to 1.1.3.

## [v1.1.2] on March 5th, 2020
- Updated sms provider to twillio.

## [v1.1.1] on February 26th, 2020
- Clean up profile code, now use vue as js, and vue component.
- Clean up register sso code.
- Removed unused code libraries.
- Improved some code.
- Moved resources view profile/sso to sso/_form.
- Updated live api to v2 ft dashboard.
- Moved student to b2c organization after sso if the b2c organization is exist in dashboard.
- Updated trial description.
- Fixed pt result show wrong result.
- Fixed email invoice show month duration wrong.
- Fixed student not move to b2c organization.
- Fixed student not registered in dashboard.
- Fixed certificate to email doesn't produce properly.

## [v1.1.0] on February 13th, 2020
- Updated docker image version to 1.1.0.
- Updated certificate pdf layout.
- Supported academic pplus certificate.
- Deleted assets folder: cert_image, cert_final.
