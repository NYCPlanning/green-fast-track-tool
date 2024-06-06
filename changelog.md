# Changelog
## Fast Tracker Application

All notable changes to this project will be documented in this file.

## [0.2.1] - 2024-06-06
- Update of survey and report data version information
### Added
### Fixed
- Added missing point features to Legend widget
### Changed
- Replaced dataset version table at end of report with a single data source version number in report header, and a corresponding contextual footnote
- Removed version number text in application header, and replaced it with a title text hyperlink to the application changelog
  - Allows re-publication of survey and report without having to fully re-publish the Experience Builder application
### Removed

## [0.2.0] - 2024-06-03
- Broad beta release of Fast Tracker application
### Added
- Search by BBL functionality added to search widget on Lot Selector page
- Close with "X" button to Legend
- Point select tool from Select widget
- Layer control widget
### Fixed
- Hyperlink behavior within app sidebar - links will now open the PDF or web page in a new tab, and not within the sidebar itself
### Changed
- Incorporated various beta testing feedback into survey language
- Filtered CATS permit dataset to only include `ApplicationID` values prefixed with "PA" or "PB"
- Make all survey questions required, with the exception of questions covering personal identifiers such as Project ID and Company Name
- Added size adjustment functionality to data table widgets
- Changed map/data hierarchy within app and survey
  - Combined HazMat with Noise
  - Moved Natural, Historic, and Shadows to separate application views
- Output CSV name from `Tax Lots.csv` to `Fast Tracker Lots.csv`
- Behavior of Legend and Layer windows - windows now open in sidebar on left side of screen, not as windows anchored to button
### Removed
- Search widget from all maps besides the Lot Selector map
- Polygon select tool from Select widget

## [0.1.0] - 2024-05-06
- Limited beta release of Fast Tracker application
### Added
### Fixed
### Changed
### Removed

----
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/)
