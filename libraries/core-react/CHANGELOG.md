# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.6.1] - 2020-09-04

### Fixed 🐛

- Loosened up on Tabs & TabsPanel typechecking for children ([#539](https://github.com/equinor/design-system/issues/539))

## [0.6.0] - 2020-09-02

### Added

- `<Menu>` component
- `<Pagination>` component

### Fixed 🐛

- Changed background color on `<Tabs>` to transparent ([#533](https://github.com/equinor/design-system/pull/533))
- Improved tooltip inconsistencies when used inside a table ([#488](https://github.com/equinor/design-system/pull/488))
- Fixed Tooltip triggering on some disabled elements ([#479](https://github.com/equinor/design-system/pull/479))
- Fixed misplaced text when using `<Button>` as link or upload ([#482](https://github.com/equinor/design-system/issues/482))
- Fixed wrong color on action buttons in snackbar ([#535](https://github.com/equinor/design-system/issues/535))
- Fixed elevation for dialog ([#534](https://github.com/equinor/design-system/issues/517))

## [0.5.1] - 2020-07-15

### Changed

- Font-weight has been increased to medium in all cases where the font-size is below 16px for improved legibility. This change is most notable in table cells and labels.
- Font-size has been increased and line-height decreased for `<helper>` and `<label>`
- `<Icon>` now uses `currentColor` for its fill value – which means it inherits its fill colour from its parents `color` value
- `<Typography>` now accepts any value for its color property

## [0.4.1] - 2020-07-13

### Added

- `<Typography>` can now limit the number of visible lines, render any typography style in EDS, change the underlying html element and override/extend tokens used for a particular variant
- `<Table>` can now have headers in columns in the table body

### Fixed 🐛

- Fixed horizontal alignment of icons and unintended border-color in `<Button>` in Safari ([#465](https://github.com/equinor/design-system/issues/465))
- Fixed the “off”-colour in `<Switch>`([#466](https://github.com/equinor/design-system/issues/466))
- Fixed an alignment bug in `<Tooltip>`([#408](https://github.com/equinor/design-system/issues/408))
- Fixed alignment of headers in `<Table>`([#407](https://github.com/equinor/design-system/issues/407))

## [0.4.0] - 2020-06-25

### Added

- Breadcrumbs
- Progress
- Snackbar
- `<Button>` can now be rendered as an `<a>` by providing an `href` attribute
- Support for left/right icons inside `<Button`

### Fixed

- Fixed an overflow bug in `<Popover>`([#375](https://github.com/equinor/design-system/issues/375))

### Changed

- Increased `<Button>` icon size to 24px (up from 16px) for greater legibility
- README
  - Moved Progress indicator, Breadcrumbs, Snackbar and Button variations with icons to «Available»
  - Moved Pagination to «In progress»

## [0.3.1] - 2020-06-16

### Fixed

- Fixed a bug where `<Tabs>` steals focus from interactive controls in tab panels. ([#369](https://github.com/equinor/design-system/issues/369))

## [0.3.0] - 2020-06-08

### Added

- Banner
- Popover
- Slider
- Selection controls
- Option to control the `<Search>` component. ([#342](https://github.com/equinor/design-system/issues/342))

### Fixed 🐛

- Fixed a bug where `<Tooltip>` did not close as expected. ([#339](https://github.com/equinor/design-system/issues/339))

### Changed

- README
  - Moved Banner, Popover, Selection controls and Slider to «Available»
  - Moved Progress indicator and Snackbar to «In progress»

## [0.2.2] - 2020-06-02

### Fixed 🐛

- Fixed bug where `<Tabs>` component focused automatically on the active tab on render. ([#329](https://github.com/equinor/design-system/issues/329))

## [0.2.1] - 2020-05-29

### Fixed 🐛

- Fixed bug where `<Search>` component ignored `onFocus` & `onBlur` functions. ([#330](https://github.com/equinor/design-system/issues/330))

## [0.2.0] - 2020-04-30

### Added

- Card
- Tooltip

### Fixed

- `<Button>` component property `type` can now correctly be overridden

### Changed

- README
  - Moved Card and Tooltip to «available»
  - Moved Slider and Popover to «in progress»

## [0.1.4] - 2020-04-20

### Fixed

- Republished with pnpm to fix "workspace:\*" pointers in package.json

## [0.1.3] - 2020-04-16

### Added

- Accordion
- Search
- Table of contents
- Dialog
- Scrim
- Polyfill for :focus-visible

### Changed

- README
  - Moved Accordion, Search, Table of contents, Dialog and Scrim to «available»
  - Moved Tooltip, Navigation Drawer, Menu to «in progress»

## [0.1.2] - 2020-03-23

### Added

- Chips
- Sidesheet

### Changed

- README
  - Moved Chips and Side sheet to «available»
  - Moved Cards, Table of contents, Search and Scrim to «in progress»

## [0.1.1] - 2020-03-11

### Added

- Tabs

### Changed

- README
  - Sorted components alphabetically
  - Moved Tabs to «available»
  - Moved Chips, Dialog and Side Sheet to «in progress»

## [0.1.0] - 2020-02-24

### Added

New components

- Button
  - Ghost icon variant
- List
- TopBar
- Icon
- Tabs

### Changed

- Updated README to me abit more clearer
- Adjustments to to `package.json` to be more in line with our other packages
- New versioning of packages

## [0.0.1-alpha.10] - 2020-01-22

### Fixed

- Faulty build configuration forcing use of umd modules for
- Missing package settings and deprecated npm-script commands
- Malformed changelog

## [0.0.1-alpha.9] - 2020-01-13

### Added

- Textfield alpha component

## [0.0.1-alpha.8] - 2020-01-10

### Changed

- Updated build (wups)

## [0.0.1-alpha.7] - 2020-01-10

### Added

New alpha components:

- Divider
- Table
- Typography

## [0.0.1-alpha.6] - 2019-08-12

### Fixed

- Typo in changelogs

## [0.0.1-alpha.5] - 2019-08-12

### Added

- `@equinor/eds-tokens` as a dependency for tokens

## [0.0.1-alpha.4] - 2019-07-09

### Changed

- Update README

## [0.0.1-alpha.3] - 2019-07-08

### Changed

- Update README

## [0.0.1-alpha.2] - 2019-07-08

### Changed

- Update README
- Add CHANGELOG

## [0.0.1-alpha.1] - 2019-07-08

### Changed

- Publish alpha-version of library
- Copy tokens temporarily to src/tokens
