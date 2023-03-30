---
title: SSO API
---

# SSO API

## 1.3.13 on March 29th, 2023
- [SSO-63](https://dyned.myjetbrains.com/youtrack/issue/SSO-63) Changed email account to lowercase (u_profile -> email) when new registration is requested.

## 1.3.12 on March 21st, 2023
- [SSO-62](https://dyned.myjetbrains.com/youtrack/issue/SSO-62) Accept SSO change/update available in UD students tab from admin token that has write acces for student acl.

## 1.3.11 on February 14th, 2023
- [SSO-61](https://dyned.myjetbrains.com/youtrack/issue/SSO-61) Add is_active org status in user profile.

## 1.3.10 on November 25th, 2022
- [SSO-59](https://dyned.myjetbrains.com/youtrack/issue/SSO-59) Fixed incorrect deactivated log naming.

## 1.3.9 on November 15th, 2022
- [SSO-58](https://dyned.myjetbrains.com/youtrack/issue/SSO-58) Add timezone ORG in profile user.

## 1.3.8 on October 24th, 2022
- [SSO-55](https://dyned.myjetbrains.com/youtrack/issue/SSO-55) Add the configuration "Allow Students to Download Own Certificates" from Org.
- [SSO-56](https://dyned.myjetbrains.com/youtrack/issue/SSO-56) Fixed issue after deactivating students, student's profile is still active.
- [SSO-57](https://dyned.myjetbrains.com/youtrack/issue/SSO-57) Fixed bulk import issue: an account failed when insert into MYSQL database.

## 1.3.7 on August 22nd, 2022
- [SSO-54](https://dyned.myjetbrains.com/youtrack/issue/SSO-54) Check the org expiration date to determine student expiration date.

## 1.3.6 on August 8th, 2022
- Add redis for SSO.

## 1.3.5 on July 29th, 2022
- [SSO-53](https://dyned.myjetbrains.com/youtrack/issue/SSO-53) Added the CT lock status read from organization or class.

## 1.3.4 on June 28th, 2022
- [SSO-50](https://dyned.myjetbrains.com/youtrack/issue/SSO-50) Provide endpoitns to retrieve teacher and organization admins.
- [SSO-52](https://dyned.myjetbrains.com/youtrack/issue/SSO-52) Endpoint to activated student status.

## 1.3.3 on May 25th, 2022
- [SSO-48](https://dyned.myjetbrains.com/youtrack/issue/SSO-48) Allowed expired date to none and UD send expired date as string empty.
- [SSO-49](https://dyned.myjetbrains.com/youtrack/issue/SSO-49) Store class configuration value to SSO.

## 1.3.2 on April 27th, 2022
- [SSO-47](https://dyned.myjetbrains.com/youtrack/issue/SSO-47) Added use live and mna into organization settings.

## 1.3.1 on April 12th, 2022
- [SSO-45](https://dyned.myjetbrains.com/youtrack/issue/SSO-45) Make the SSO validate for email/u_name already registered when create a new sso users.

## 1.3.0 on April 12th, 2022
- [SSO-44](https://dyned.myjetbrains.com/youtrack/issue/SSO-44) Show Register Date

## 1.2.9 on July 26th, 2021
- [NSAAPI-352](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-352) Profile picture does not show when I log in and I am prompted to provide picture.

## 1.2.8 on June 11th, 2021
- [SSO-42](https://dyned.myjetbrains.com/youtrack/issue/SSO-42) Add a Organization setup from UD

## 1.2.7 on April 11th, 2021
- [SSO-41](https://dyned.myjetbrains.com/youtrack/issue/SSO-41) Make soft delete data

## 1.2.6
- [SSO-40](https://dyned.myjetbrains.com/youtrack/issue/SSO-40) Support edit user data cross server

## 1.2.5
- [SSO-39](https://dyned.myjetbrains.com/youtrack/issue/SSO-39) SSO-39 Log the activity ip address when editing user's data.

## [1.2.4] on November 26th, 2020
- [SSO-38](https://dyned.myjetbrains.com/youtrack/issue/SSO-38) Log the password chnages in u_log in SSO database

## [1.2.3] on September 08th, 2020
- [SSO-37](https://dyned.myjetbrains.com/youtrack/issue/SSO-37) Added log to see the changes of levels and plans on SSO.

## [1.2.2] on August 19th, 2020
- [SSO-36](https://dyned.myjetbrains.com/youtrack/issue/SSO-36) Shared token for multiple server.

## [1.2.1] on August 06th, 2020
- [SSO-34](https://dyned.myjetbrains.com/youtrack/issue/SSO-34) Created a new SSO middleware authentication model for other services.
- [SSO-35](https://dyned.myjetbrains.com/youtrack/issue/SSO-35) Add new an endpoint to get a list of all admins by UIC and ACL.

## [1.2.0] on June 17th, 2020
- [SSO-32](https://dyned.myjetbrains.com/youtrack/issue/sso-32) Added a log for any user's changes and display it in Get User Profile API. 
- [SSO-33](https://dyned.myjetbrains.com/youtrack/issue/sso-33) Added versioning to check API version.
- [SSO-31](https://dyned.myjetbrains.com/youtrack/issue/sso-31) Created a log for any user's changes.