# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0] - 2022-05-20
### Added
- Added support for Guzzle 7
- Added signature validation to examples
### Changed
- Removed bundled Guzzle 6 library
- Guzzle version (6 or 7) is selected automatically depending on the environment
- Payment timestamp accuracy increased in examples

## [1.1.0] - 2022-03-23
### Added
- Added native return type to jsonSerialize()
### Changed
- Allow payment request to be made without providing any items
- Validation rules updated to check if a negative value has been provided for an item

## [1.0.1] - 2021-10-29
### Changed
-  setDeliveryDate is now optional

## [1.0] - 2021-10-06
### Added
-  All initial plugin functionalities
