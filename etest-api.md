---
title: eTest API
---

# eTest API
Service (API) to manage all the Assements Test (Placement test or the Certification Test) systems on neo.

## [v1.6.8] on November 10th, 2022
- [ETAPI-126](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-126) Fixed issue for could not get the ept result of neo Pro by API.

## [v1.6.7] on October 17th, 200
- [ETAPI-123](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-123) Fixed issue for cannot take CT because neo notice this email was registered.
- [ETAPI-124](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-124) Prevent test Tokens from being duplicated with the same type.

## [v1.6.6] on September 22nd, 2022
- [ETAPI-121](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-121) Store PT Level after take the Assessment

## [v1.6.5 ]on July 29th, 2022
- Downloaded flow test PT and CT download.
- Imported flow PT /files/test/v2/flow_pt_neojr.json.
- Imported flow CT /files/test/v2/flow_et_neojr.json.
- Imported the Assessment and Certficates Contents.
- Docker-compose up -d.

## [v1.6.4] on July 22nd, 2022
- [nSO-865](https://dyned.myjetbrains.com/youtrack/issue/NSO-865) Error: student is getting the prompt he has earned the Pre A1 Certificate.

## [v1.6.3] on July 20th, 2022
- Updateed CT Score Pre A1 to minumums 60 (neo+ and neoPrep+).

## [v1.6.2] on July 20th, 2022
- Added token reset admin mode.

## [v1.6.1] on July 8th, 2022
- [ETAPI-115](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-115) Fixed issue for not showing PT Result after taking PT.
- [ETAPI-116](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-116) Change the name of Placement Test to Assessment Test.

## [v1.6.0] on July 8th, 2022
- [ETAPI-107](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-107) Import PT assessment neoJR.
- [ETAPI-111](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-111) Disable Student After PT.
- [ETAPI-112](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-112) Endpoint to retrieve single PT result.

## [v1.5.6] on May 30th, 2022
- [ETAPI-108](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-108) Generate selective PT reports based on organization code.
- [ETAPI-109](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-109) Fixed issue for unable to open the "Cer Test Review List" excel file.

## [v1.5.5.1] on April 26th, 2022
- [ETAPI-96](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-96) Collected the agent info when starting the etest.
- [ETAPI-99](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-99) Fixed the Get candidates that missing uic value in its response. 
- [ETAPI-106](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-106) Fixed Fest API with query that is not working.

## [v1.5.5] on April 26th, 2022
- [ETAPI-94](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-94) Rename PT Result Pre-A1 to Pre A1.
- [ETAPI-97](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-97) Optimized context API.
- [ETAPI-98](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-98) Added Bugsnag to eTest API.
- [ETAPI-102](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-102) Deleted CT token that show more than 1 in Tests tab.
- [ETAPI-103](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-103) Make loading to the next question faster.

## [v1.5.4] on January 20th, 2022
- [ETAPI-93](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-93) Changed Certification Test Pass/Fail scoring from 80 to 70.

## [v1.5.3] on November 25th, 2021
- [ETAPI-88](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-88) Make validation for expired organization from SSO.
- [ETAPI-91](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-91) Updated total in_correct in response CT details.
- [ETAPI-92](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-92) Fixed issue for privileges that cannot be inherited when running the fetch ept API

## [v1.5.2] on November 3rd, 2021
- [ETAPI-86](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-86) Make eTest API cross authenticate to ROW and CN.

## [v1.5.1] on November 3rd, 2021
- [ETAPI-87](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-87) Updated config database global.

## [v1.4.22] on October 12th, 2021
- [ETAPI-84](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-84) Include Student Bulk type in PT Report
- [ETAPI-85](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-85) Update Auth Management


## [v1.4.21] on September 29th, 2021
- [ETAPI-82](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-82) Add a date range based on date PT was taken
- [ETAPI-83](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-82) certificate is not sent automatically after student pass ct

## [v1.4.20] on September 22th, 2021
- [ETAPI-78](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-78) Check email when taking PT whether it already registered in SSO/Live_dev
- [ETAPI-79](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-79) Make the default logo configurable trough config
- [ETAPI-80](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-80) User report the study level will be changed back automatically -- DE

## [v1.4.19] on September 08th, 2021
- [ETAPI-77](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-77) support take force ePT from Cloud and Widget

## [v1.4.18] on August 03rd, 2021
- [ETAPI-71](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-71) made a possible candidate for the ePT once onboard
- [ETAPI-74](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-74) separate notification configuration after ePT

## [v1.4.17]  on April 10th, 2021
- [ETAPI-58](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-58) The etest cant be loaded (Improvement)
- [ETAPI-65](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-65) A 404 error will appear when you submit your score--------ZiJie
- [ETAPI-66](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-66) student report when doing ept, serveral questions always appear again and again
- [ETAPI-67](https://dyned.myjetbrains.com/youtrack/issue/ETAPI-67) There will be some duplicated question when start over the test

## [v1.4.16]  on March 12th, 2021
- ETAPI-58 The etest cant be loaded

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




