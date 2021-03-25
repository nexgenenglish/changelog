---
title: eTest API
---

# eTest API
Service (API) to manage all the Assements Test (Placement test or the Certification Test) systems on neo.

## [v1.4.15]  on March 12th, 2021
- ETAPI-55 Allow take CT from different UIC (Student transfer)

## [v1.4.14]  on March 05th, 2021
- ETAPI-54 The callback url does not work correctly

## [v1.4.13]  on March 01st, 2021
- ETAPI-52 UD: Report "~Can't Do" statements for missed items on Failed Certification Tests
- ETAPI-53 Curated Post-CT Failure Review Lists

## [v1.4.12]  on February 01st, 2021
- ETAPI-51 Test scores cannot be submitted-----Elite
- ETAPI-48 Create a CT logs per level
- ETAPI-46 Failed move candidate to another UIC using API

## [v1.4.11] on November 26th, 2020
- [ETAPI-41](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-41) Area for improvement not display sequently on PT report
- [ETAPI-43](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-43) Prevent error when Candidate's result is null

## [v1.4.10] on November 11th, 2020
- [ETAPI-32](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-32) Institutional "Can't Do" Statements based on ePT
- [ETAPI-40](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-40) Create an API that generate excel report that include student PT/CT response based on the student email address
- import new Assessment file
- add a new parameter to differentiate the candidate register from etest and dashboard

## [v1.4.9] on October 19th, 2020
- [ETAPI-37](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-37) Added endpoint to query candidates by selected email.

## [v1.4.8] on October 12th, 2020
- [ETAPI-36](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-36) Fixed issue for dial code and phone number that turn to 0 after updating candidate.

## [v1.4.7] on October 06th, 2020
- [ETAPI-33](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-33) eTest api does not work properly.
- [ETAPI-34](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-34) Prevented Admins from getting Student Info from other UICs that are not at the same or below.
- [ETAPI-35](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-35) Added flag for hide or unhide candidate.

## [v1.4.6] on September 29th, 2020
- [ETAPI-30](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-30) Changed data type from string to "0 / 1".
- [ETAPI-31](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-31) Mapping Question Flow based on the Certificate Plan.

## [v1.4.5] on September 22th, 2020
- [ETAPI-28](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-28) Fixed issue about receiving 20 emails  after finishing ept.
- Add config plan name
```
copy the plan.json file to the files directory
```

## [v1.4.4] on September 02nd, 2020
- [ETAPI-25](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-25) Updated searching method by inherintance UIC.
- [ETAPI-24](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-24) Update candidate search method by username, email and level.
- [ETAPI-19](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-19) Added Certification Tests (CTs) for neo Academic courseware.

## [v1.4.3] on August 18th, 2020
- [ETAPI-22](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-22) Send a notification email to student after completion of CT

## [v1.4.2] on August 06th, 2020
- [ETAPI-20](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-20) Added some new field for organization information.

## [v1.4.1] on July 23th, 2020
- [ETAPI-21](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-21) Fixed issue for sending email notification after failed on CT.

## [v1.4.0] on July 13th, 2020
- [ETAPI-14](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-14) Send email notification after complete PT.
- [ETAPI-15](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-15) Add information whether to continue the package or not after completing the Certification Test.
- [ETAPI-18](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-18) Add a flag to identify sending notifications to clients.

## [v1.3.9] on June 06th, 2020
- [ETAPI-16](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-16) Update status CT to pass before issued the certificate.
- [ETAPI-17](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-17) Fixed wrong question for CT PRE A1.

## [v1.3.8] on June 29th, 2020
- [ETAPI-13](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-13) Updated configuration for email that have been registered in NSADB and eTest.

## [v1.3.7] on June 17th, 2020
- [ET-324](https://dyned.myjetbrains.com/youtrack/issue/ET-324) Made a pop up message "Email already registered, please use another email address"
for candidate that used the registered e-mail when taking PT.
- [ET-335](https://dyned.myjetbrains.com/youtrack/issue/ET-335) Improve labelling for some words in generating test token.
- [ETAPI-5](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-5) Improve API to accept user with “support” role.
- [ETAPI-6](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-6) Question numbering on A1+ CT not showing properly.

## [v1.3.6] on May 13th, 2020
- [ET-316](https://dyned.myjetbrains.com/youtrack/issue/ET-316) Fixed API call for student whose PT status is complete.
- [ET-318](https://dyned.myjetbrains.com/youtrack/issue/ET-318) Improved the API with status message.  

## [v1.3.5] on May 05th, 2020
- [ET-311](https://dyned.myjetbrains.com/youtrack/issue/ET-311) Fixed PT result for candidate that registered from Universal Dashboard.

## [v1.3.4] on Apr 16th, 2020
- Store total of correct and incorrect also total answers as result of CT from eTest.
- Update versioning.

## [v1.3.3] on Apr 28th, 2020
- Update feature search candidate by e-mail.
- Update limit paginations to get list of candidates.

## [v1.3.0] on Apr 13th, 2020
- Improve data structuring in backend.

## [v1.3] on Apr 8th, 2020
- Fixed API issue to display actual test time.

## [v1.3] on Apr 8th, 2020
- Fixed API issue to display actual test time.

## [v1.2] on Feb 17th, 2020

## [v1.1] on Feb 6th, 2020
- Assessments test only for Professional Plan.
- Fixing some bugs and improvement features.

## [v1.0] on Nov 21th , 2019
- E-test version V1.0 which only support level score from code.




