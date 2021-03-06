# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [0.4.2] - 2018-08-23
### Fixed
- [Fix false positive on value(included_in:) matcher](https://github.com/bloom-solutions/dry-validation-matchers/pull/10)

## [0.4.1] - 2018-06-01
### Fixed
- [Fix date_time type error message](https://github.com/bloom-solutions/dry-validation-matchers/pull/9)
- [Fix false positive checks missmatch between type check and other checks](https://github.com/bloom-solutions/dry-validation-matchers/pull/9)
- [Fix gemspec dependencies context](https://github.com/bloom-solutions/dry-validation-matchers/pull/8)
- [Fix warning on `@check_filled`](https://github.com/bloom-solutions/dry-validation-matchers/pull/7)
- Description messages for pass and fail do not leave artifacts if there are no details
- Make messages consistent with "Subject predicate noun"

## [0.4.0] - 2016-11-10
### Added
- Add support for checking that the value is included_in

## [0.3.0] - 2016-11-09
### Added
- Add support for float, decimal, bool, date, time, date_time, array, hash

## [0.2.0] - 2016-11-08
### Added
- failure_message

### Fixed
- Updated description

## [0.1.0] - 2016-11-08
### Added
- Initial working version
