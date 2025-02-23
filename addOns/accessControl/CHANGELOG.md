# Changelog
All notable changes to this add-on will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## Unreleased
### Changed
- Update minimum ZAP version to 2.13.0.
- Maintenance changes.

## [8] - 2022-10-28
### Changed
- Maintenance changes.
- Update minimum ZAP version to 2.12.0.

## [7] - 2021-10-07
### Changed
- Don't set the font color for inherited entries (Issue 6397).
- Update minimum ZAP version to 2.11.0.
- Maintenance changes (some changes impact the visibility of variables and add getters/setters, which may impact third party add-ons or scripts).
- Change to no longer rely on core report classes, which are going to be deleted.

## [6] - 2020-10-06

### Added
- Add API support.
- Add info and repo URLs.

### Changed
- Update minimum ZAP version to 2.9.0.

## 5 - 2018-11-02

- Respect the current mode and react to changes.
- Dynamically unload the add-on.
- Inform of running tests (e.g. on session change, add-on uninstall).
- Improve error handling during test.
- Tweak alerts to use Other Info field instead of Attack/Evidence.

## 4 - 2017-11-28

- Updated for 2.7.0.

## 3 - 2017-11-24

- Fix exception that occurred with Java 9 (Issue 3934).
- Allow to copy multiple results and copy correct value from the result column.
- Display correct message when the table is sorted.

## 2 - 2016-06-02

- Fix an exception when cancelling the "Save" access control report dialogue.
- Do not allow to dynamically uninstall, not yet supported.

## 1 - 2015-04-13

- Initial version

[8]: https://github.com/zaproxy/zap-extensions/releases/accessControl-v8
[7]: https://github.com/zaproxy/zap-extensions/releases/accessControl-v7
[6]: https://github.com/zaproxy/zap-extensions/releases/accessControl-v6
