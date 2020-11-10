# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

## [v0.3.0] - 2020-11-10

### Changed

- Convert the crate to be compatible with the I3G4250D gyroscope.

## [v0.2.0] - 2018-05-12

### Changed

- [breaking-change] moved to v0.2.0 of the `embedded-hal` traits. This crate now compiler on beta
  and stable.

## [v0.1.2] - 2018-02-19

### Added

- Methods to set and read the Output Data Rate (ODR) of the gyroscope.
- Methods to set and read the bandwidth (low pass filter) of the gyroscope.
- Methods to set and read the scale (sensitivity) of the gyroscope.
- Method to read the status register of the gyroscope.

## [v0.1.1] - 2018-01-17

### Changed

- Tweaked the crate level documentation to point to examples and to point back to the `embedded-hal`
  crate.

## v0.1.0 - 2018-01-17

Initial release

[Unreleased]: https://github.com/japaric/l3gd20/compare/v0.2.0...HEAD
[v0.2.0]: https://github.com/japaric/l3gd20/compare/v0.1.2...v0.2.0
[v0.1.2]: https://github.com/japaric/l3gd20/compare/v0.1.1...v0.1.2
[v0.1.1]: https://github.com/japaric/l3gd20/compare/v0.1.0...v0.1.1
