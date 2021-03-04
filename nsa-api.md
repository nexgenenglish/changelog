---
title: neo Study App API
---

# neo Study App API
Service (API) to manage neo Study App.

# 1.9.7.1 on March 03rd, 2021
- Handle when lesson type is empty on summary page

# 1.9.7 on March 01st, 2021
- Prevent study when user_et and user_cert_plan is not found
- NSA-2698 iOS&Android: internal server error when going through unit sequences where the last unit has no MT
- NSAAPI-310 Curated Pre-CT Review Lists
- NSAAPI-311 Curated Post-CT Failure Review Lists

# 1.9.6 on February 24th, 2020
- mylesson not saved.

# 1.9.5 on January 18th, 2021
- NSAAPI-306 The 'total days' is always show as 0
- add mna profile field to update
- prepare to split data collection

# 1.9.4 on January 18th, 2021
- add certification.plan_code -> MNA Group

# 1.9.3 on January 06th, 2021
- NSAAPI-303 The progress of students without learning records after learning the course remains unchanged
- NSAAPI-304 Can't download contentt
- NSAAPI-305 Prevent duplicate data study records

# 1.9.2 on January 04th, 2021
- Added session (live) active, session (live) upcoming, percentage points, is trial expired on sp (MNA).
- Save ct logs question per level and attempt.
- [NSAAPI-301](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-301) Fixed issue on student account who got  error on prompt CT.
- Added end point to check student is on db or not.


# 1.9.1 on December, 2020
- Added acl access informastion on sp.
- Disabled alert no saved lessons home screen.

# 1.9.0 on December, 2020
- Compressed file when change the avatar.
- Save point my lesson for 1.9.x versions or more than.

# 1.8.27 on December 16th, 2020
- [NSAAPI-296](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-296) Fixed user et data (b2cp_user_et).
- [NSAAPI-297](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-297) Fixed issue for error message that show after student passed last MT on Level B1. 
- Show alert myLessons only once on Home Screen
- Disabled myLessons when Account is expired, CT passed (buy more package)

# 1.8.26 on December 09th, 2020
- [NSAAPI-288](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-288) Save My Lesson.
- [NSAAPI-289](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-289) Delete My Lesson.
- [NSAAPI-292](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-292) Get My lesson data.
- [NSAAPI-293](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-293) Set to disable when My lesson has played.

# 1.8.25 on December 07th, 2020
- [NSAAPI-295](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-295) Fixed issue for MT that is not open although finishing MT Review.

# 1.8.24 on December 02nd, 2020
- [NSAAPI-294](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-294) Fixed issue for the app which allowing student do MT serveral times (unit case).

# 1.8.23 on December 01st, 2020
- [NSAAPI-285](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-285) Hanlde unit point not enough to pass.
- [NSAAPI-286](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-286) Make Decrypt data collection per lesson.
- [NSAAPI-290](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-290) Fixed issue for button that doesn't change to "review lesson" when CT status is pending.
- [NSAAPI-291](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-291) Fixed issue for ET which status is open although the last MT is unlocked.

# 1.8.22 on Novmber 27th, 2020
- [NSAAPI-287](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-287) Review MT error.
- Added country_admin and region_admin as new admin guard.

# 1.8.21 on Novmber 26th, 2020
- [NSAAPI-282](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-282) Issue on end user who didn't get step completion bonus though interactivity points are over 50.
- [NSAAPI-283](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-283) Fixed issue on can't take CT even though the points are enough.
- [NSAAPI-284](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-284)  MT share review support from multiple studypaths.

# 1.8.20 on Novmber 20th, 2020
- [NSAAPI-276](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-276)  Fixed issue for incorrectly display fields on the Get current progress api.

# 1.8.19 on Novmber 19th, 2020
- Implemented acctual point capped on summary screen.
- Added goal name.
- [NSAAPI-273](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-273)  Add a new actual point capped on summary response.
- [NSAAPI-275](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-275)  Android: neoPrep+>B1>EFS U10>step1: Fixed issue for showing 'Mastery Test Failed". The MT should be open.
- [NSAAPI-277](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-277)  neoPrep+>A1+: error message showed while reviewing lessons after failing an MT.
- [NSAAPI-278](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-278)  iOS: 1.8.1(2011101459000): issues when going through unit sequences of neoPrep+ > C1.
- [NSAAPI-279](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-279)  iOS V1.8.1 & Android V1.8.2: Issues on various pages before an MT is unlocked.
- [NSAAPI-280](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-280)  iOS V1.8.2(201118114500): Issues about points on summary screen in A1.

# 1.8.18 on Novmber 13th, 2020
- Set env assets files location.
- Updated MT review page.

# 1.8.17 on Novmber 09th, 2020
- Fixed summary point [role tester].

# 1.8.16 on Novmber 04th, 2020
- [NSAAPI-270](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-270) iOS&Android: improvement showing "Mastery Test Open" instead of "0 points to next test".
- [NSAAPI-271](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-271) Fixed issue for the differences points.
- [NSAAPI-272](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-272) neoPrep+>A1: Fixed issue for target point and rocket animation.

## [v1.8.15] on October 19th, 2020
 - Updated condition point interactivity.
 - Updated review unlocked CT.
 - Updated CT pending screen.

## [v1.8.14] on October 14th, 2020
-[NSAAPI-269](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-269) Handled if the Live Session completed is more than minimum to pass.

## [v1.8.13] on October 06th, 2020
- [NSAAPI-266](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-266) coach scores are not added.
- [NSAAPI-268](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-266) Added Step Completion Bonus to "Review lessons".

## [v1.8.12] on September 29th, 2020
- [NSAAPI-262](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-262) Access student information in dashboard error, prompt 500.
- [NSAAPI-263](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-263) No data of student who certified on untiversal dashboard.

## [v1.8.11] on September 14th, 2020
- [NSAAPI-262](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-262) Fixed error when access student information.
- [NSAAPI-263](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-263) Fixed issue for student data who already passed ET in student summary.

## [v1.8.10] on September 10th, 2020
- [NSAAPI-260](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-260) Failed to update avatar with Admin mode
- [NSAAPI-261](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-261) Cannot change level when all levels have passed

## [v1.8.9] on September 08th, 2020
- [NSAAPI-250](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-250) Allowed update Phone Number from MNA Apps.
- [NSAAPI-253](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-253) Reset live token after change level.
- [NSAAPI-254](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-254) Added a validation for student to changes the avatar and fullname by limited time.
- [NSAAPI-255](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-255) Fixed issue for Master Test lessons that not found for internal testing after changing certificate packages.
- [NSAAPI-256](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-256) Fixed a mismatch  between Student page and student detail.
- [NSAAPI-258](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-258) Save Certificate Levels and Plan in SSO.
- [NSAAPI-259](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-259) Updated calculation token balance scheme.

## [v1.8.8] on September 02nd, 2020
- [NSAAPI-245](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-245) Updated student search method.
- [NSAAPI-242](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-242) Fixed wrong study steps issue sequence.
- [NSAAPI-247](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-247) Fixed issue for level information after a change.
- [NSAAPI-248](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-248) Fixed issue for student certification test data which does not appear.
- [NSAAPI-249](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-249) Fixed CT for C1-Bridge issue that still locked after finished certification test review.
- [NSAAPI-251](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-251) Fixed double data when change level to previous level.

## [v1.8.7] on August 19th, 2020
- [NSAAPI-240](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-240) [summary] Shared token for multiple server

## [v1.8.6] on August 18th, 2020
- [NSAAPI-236](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-236) Add new key to search report summary data.
- [NSAAPI-239](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-239) Fixed repeating study the same lesson for review.  

## [v1.8.5] on August 12th, 2020
- [NSAAPI-237](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-237) Fixed issue for app which ask student to do MT repeatly.
- [NSAAPI-238](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-238) Updated the repeat and next button requirements.

## [v1.8.4] on August 05th, 2020
- [NSAAPI-231](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-231) Changed live session points condition.
- [NSAAPI-232](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-232) Handled student when active (submit) on two different devices.
- [NSAAPI-233](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-233) Show the maximum points per unit in the summary report if students get more.
- [NSAAPI-234](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-234) Added First and Last name list on the student summary report.

## [v1.8.3] on July 24th, 2020
- [NSAAPI-228](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-228) Fixed set to unlock CT after Review a Lesson.
- Set disable the Reminder Live feature for tester account

## [v1.8.2] on July 20th, 2020
- [NSAAPI-226](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-226) Fixed issue for zero point of student in UD Organization does not matched with point in MNA.

## [v1.8.1] on July 15th, 2020
- [NSAAPI-147](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-147) Reminder to book a coaching session.
- [NSAAPI-224](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-224) Fix review share MT lesson
- [NSAAPI-225](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-225) display token information when a student hasn't started studies.
- [MNA-242](https://dyned.myjetbrains.com/youtrack/issue/MNA-242) Update Status code 400 when token is expired to handle user stuck

## [v1.8.0] on July 14th, 2020
- Add version name to mobile
  ### add new keys with names are VERSION_NAME_ANDROID and VERSION_NAME_IOS

## [v1.7.9] on July 03th, 2020
- [NSAAPI-50](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-50) Update student cert_exit_exam_complete to 1 when students pass CT

## [v1.7.8] on June 20th, 2020
- [NSAAPI-216](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-216) Fixing get study progress with custom date.
- [DSA-1671](https://dyned.myjetbrains.com/youtrack/issue/DSA-1671) Exit PT Information needs improvement.
- [DSAAPI-210](https://dyned.myjetbrains.com/youtrack/issue/DSAAPI-210) change lowercase when the first character (Change Password)
- [NSAAPI-47](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-47) Gets the last study record for a student.
- [NSAAPI-217](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-217) Add token balance info (Profile)
- [NSAAPI-161](https://dyned.myjetbrains.com/youtrack/issue/NSAAPI-161) Return records of multi-students in one API call.

## [v1.7.7] on May 27th, 2020
- [NB2B-241](https://dyned.myjetbrains.com/youtrack/issue/NB2B-241) update format date SSO
- change lowercase when the first character (Update Profile SSO)

## [v1.7.6] on May 27th, 2020
- [DSAAPI-162](https://dyned.myjetbrains.com/youtrack/issue/DSAAPI-162) Fixed issue to set expired date greater than today's date

## [v1.7.5] on May 27th, 2020
- [DSAAPI-158](https://dyned.myjetbrains.com/youtrack/issue/DSAAPI-158) Update study progress for Coach
- [DSA-2308](https://dyned.myjetbrains.com/youtrack/issue/DSA-2308) Fixed study points and function to get to regular lesson
- [DSAAPI-159](https://dyned.myjetbrains.com/youtrack/issue/DSAAPI-159)Improved pagination function
- [DSAAPI-160](https://dyned.myjetbrains.com/youtrack/issue/DSAAPI-160)Fixed issued to retrieve records in API


## [v1.7.4] on May 05th, 2020
- [DSAAPI-150](https://dyned.myjetbrains.com/youtrack/issue/DSAAPI-150) Add some fileds to summary report for all students under an org
- [DSAAPI-156](https://dyned.myjetbrains.com/youtrack/issue/DSAAPI-156) Add data to the value returned from dsa/report/student-summary-report used by dashboard

## [v1.7.3] on May 04th, 2020
- Improvement data CT from ETest
- [DSAAPI-154](https://dyned.myjetbrains.com/youtrack/issue/DSAAPI-154) Points and button changes after passed CT for Single Package
- [DSAAPI-155](https://dyned.myjetbrains.com/youtrack/issue/DSAAPI-155) Add some filed result of CT
- [NBRG-407](https://dyned.myjetbrains.com/youtrack/issue/NBRG-407) Update SP when level is passed.