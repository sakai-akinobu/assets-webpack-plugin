# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning].

This change log follows the format documented in [Keep a CHANGELOG].

[Semantic Versioning]: http://semver.org/
[Keep a CHANGELOG]: http://keepachangelog.com/

## Unreleased

## 3.7.2 - 2018-06-14

### Changed

- Reduces npm package size [#67](https://github.com/kossnocorp/assets-webpack-plugin/issues/67)

## 3.7.1 - 2018-06-13

### Changed

- Fixes a parsing error with the asset path introduced by the fix for [#88](https://github.com/kossnocorp/assets-webpack-plugin/issues/88)

## 3.7.0 - 2018-06-13

### Changed

- Adds all assets to the manifest that aren't in a chunk (kudos to [@Kronuz](https://github.com/Kronuz) see [#65](https://github.com/kossnocorp/assets-webpack-plugin/pull/65))

## 3.6.3 - 2018-06-13

### Changed

- Add support for multiple files of the same extension (kudos to [@aaronatmycujoo](https://github.com/aaronatmycujoo) see [#79](https://github.com/kossnocorp/assets-webpack-plugin/pull/79) and [@Kronuz](https://github.com/Kronuz) see [#64](https://github.com/kossnocorp/assets-webpack-plugin/pull/64))

## 3.6.2 - 2018-06-13

### Changed

- Fixed incorrect concatination of asset file names and directory path see [#88](https://github.com/kossnocorp/assets-webpack-plugin/issues/88)

## 3.6.1 - 2018-06-13

### Changed

- webpack-dev-server (which uses memory-fs) correctly generates the manifest inside the memory file system (kudos to [@Kronuz](https://github.com/Kronuz) see [#90](https://github.com/kossnocorp/assets-webpack-plugin/pull/90))

## 3.6.0 - 2018-05-29

### Changed

- webpack 4 support (kudos to [@ztoben](https://github.com/ztoben) and [@saveman71](https://github.com/saveman71) see [#89](https://github.com/kossnocorp/assets-webpack-plugin/pull/89))

## 3.5.1 - 2017-01-20

### Fixed

- Support for source maps when `includeManifest` option is set.

## 3.5.0 - 2016-10-21

### Added

- `includeManifest` option (kudos to Matt Krick [@mattkrick](https://github.com/mattkrick)).
  [See docs](./README.md#includemanifest) for more details.

## 3.4.0 - 2016-03-09

### Changed

- Do not write to assets file if output hasn't changed.

## 3.2.0 - 2015-11-17

### Added

- `processOutput` option.

## 3.1.0 - 2015-10-24

### Added

- Config now accepts a `fullPath` option.