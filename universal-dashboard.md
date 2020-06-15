---
title: Universal Dashboard
---

# neo Universal Dashboard
An universal dashboard to manage neo ecosystem.

## [v1.0.28] on June 2nd, 2020
- Add some conditional for billing report exemption.
- Sync account type (trial and regular) with Live system.
- Update the ACL format for enabled/disabled account.
- Remove some dummy text on some page.

## [v1.0.27] on May 19th, 2020
- Add some conditional for billing report exemption. 
- Change dial code label to country code.
- Fixed the checkbox for “Issues certificate automatically after Certification Test?”  to be able to edit by user. The edit means (check or uncheck the checkbox).
- Fixed period date picker when generate study record.
- Fixed the total student list in download report and in the list on dashboard.

## [v1.0.26] on May 6th, 2020
- Added new feature/button to download student’s summary report in Student page.

## [v1.0.25] on May 6th, 2020
- Fix error when changing student expired date. 
- Fix error when download PT report. 
- Fix error when download trial student report. 
- Fix can’t load the student list in Candidate menu.
- Hide options that available only for Super Admin role.
- Fixed date picker issue in Safari.
- Add local system font.
- Fix register student that doesn’t take Placement Test.

## [v1.0.24] on April 28th, 2020
- Optimize system load by using local system fonts.
- Allow super admin to set trial duration more than 21 days for student.
- Added configuration for client to send certificate by e-mail manually or automatically by system. 

## [v1.0.23] on April 20th, 2020
- Enable C1 candidate to onboard in organization with Plus Plan
- Prevent clear cache on browser for new updated assets
- Allow user to insert 0 amount of token when create organization

## [v1.0.22] on April 14th, 2020
- Fix empty user name on billing report 

## [v1.0.21] on April 14th, 2020
- Add additional condition rule for generating billing report 

## [v1.0.20] on April 14th, 2020
- Optimize the engine code

## [v1.0.19] on April 14th, 2020
- Added token for create user 
- Fix pagination for candidate list
- Added configuration for client to send certificate by e-mail manually (client download the certificate and send to student’s separately)  or automatically by system. 
- Added student trial duration configuration per organization from 14 days to 21 days and more than 21 days is allowed if granted by super admin. 
- Fix register student for Plus level plan
- Fix billing rules for student whose account already expired wouldn’t be charged for billing
- Fix for 403 response on update organization