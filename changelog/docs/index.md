# Changelog

All notable changes to this project will be documented in this file.

--- 

## Unreleased
- Cards that show both activity and attendance

---

## Known Issues
- None

---

## [0.5.0] - 2021-03-12
### Added
- User emails now show up on cards for results page
- Activity log auto converts to the viewers local timezone

### Changed
- Results page now shows attendance & activity
- Now properly pulling all data into one view
- "Left Early" is now greyed out if user hasn't clocked out yet
- Rearranged the results page to fit cards and activity logs better

### Fixed
- Attendance data is dynamic now

---

## [0.4.0] - 2021-03-05
### Added
- Merged activity and attendance data
- Created new database models for holding entries of both
- Created "setters & getters" for accessing saved data

### Changed
- We now discard AT time data

---

## [0.3.0] - 2021-02-12
### Added
- Integrated ROTACloud API
- Prototype of "cards" model

---

## [0.2.0] - 2021-02-05
### Added
- You can now select from pre-set date ranges

---

## [0.1.0] - 2021-01-22
### Added
- Pulls activity logs for the current day