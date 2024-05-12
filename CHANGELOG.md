# Changelog

## 4.0.0 - 2024-0053-12

### Changed
- Now requires PHP `8.2.0+`.
- Now requires Craft `5.0.0+`.

## 3.0.3 - 2023-05-10

### Fixed
Fix an issue with Craft 4.4+ and `branchLimit`.

## 3.0.2 - 2023-05-09

### Fixed
Fix an issue with Craft 4.4+ and `source` setting.

## 3.0.1 - 2022-11-30

### Fixed
- Fix fields not migrating to new package name correctly.

## 3.0.0 - 2022-11-24

### Changed
- Now requires PHP `8.0.2+`.
- Now requires Craft `4.0.0+`.

## 2.0.2 - 2022-11-30

### Fixed
- Fix fields not migrating to new package name correctly.

## 2.0.1 - 2022-11-24

### Fixed
- Fix an error when querying via GraphQL.

## 2.0.0 - 2022-11-24

> {note} The plugin’s package name has changed to `verbb/single-cat`. Single Cat will need be updated to 2.0 from a terminal, by running `composer require verbb/single-cat && composer remove elivz/craft-single-cat`.

### Added
- Add GraphQL support for field. (thanks @denisyilmaz).

### Changed
- Migration to `verbb/single-cat`.
- Now requires Craft 3.7+.

### Removed
- Remove CraftQL support.

## 1.2.2 - 2021-11-01

### Fixed
- Show only categories from the current site in field input.

## 1.2.1 - 2019-02-17

### Fixed
- Prevent error when CraftQL plugin is not installed.

## 1.2.0 - 2019-02-16

### Added
- Setting to display a blank initial option in the drop-down, allowing for no category to be selected (thanks to [carlcs](https://github.com/carlcs)).
- CraftQL support. It works the same as with a native Categories field.

### Changed
- If the previously-selected category has since been disabled, editing the entry will result in no category being selected, rather than the first in the list.

## 1.1.0 - 2019-01-26

### Added
- Compatibility with Craft 3.1.

## 1.0.3 - 2018-11-08

### Fixed
- Improved reliability with loading categories.

## 1.0.2 - 2018-11-07

### Fixed
- Bug when multiple category groups exist.

### Added
- Ability to select a different category in each site.

## 1.0.1 - 2018-11-04

### Fixed
- Error when field value is null.

## 1.0.0 - 2018-10-29

### Added
- Initial release.
