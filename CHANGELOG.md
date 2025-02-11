# Change Log
All notable changes to this project will be documented in this file. This change log follows the conventions of [keepachangelog.com](http://keepachangelog.com/).

## [1-alpha6-SNAPSHOT] - unleased
- plotlylcoth - set default height and width
- plotlycloth - changed default background color (for ggplot compatibility)
- plotlycloth - polar coordinates - WIP

## [1-alpha5-SNAPSHOT] - 2024-08-06
- added the `plotlycloth` API (experimental) generating [Plotly.js plots](https://plotly.com/javascript/)

## [1-alpha4-SNAPSHOT] - 2024-07-12
- breaking change: substitution keys are `:=abcd`-style rather than `:haclo/abcd`-style
- simplified CSV writing
- more careful handling of datasets - avoiding layer data when they can reuse the toplevel data
- related refactoring
- facets support - WIP

## [1-alpha3-SNAPSHOT] - 2024-06-28
- catching common problems
- bugfix (#1) of type inference after stat

## [1-alpha2-SNAPSHOT] - 2024-06-22
- renamed the `hanami` keyword namespace to `haclo` to avoid confusion

## [1-alpha1-SNAPSHOT] - 2024-06-22
- initial version
