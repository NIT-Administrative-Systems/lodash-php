# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [v3.0.0] - 2025-08-29
### Changed
- Support for PHP 8.2 has been dropped.
- Added support for `sebastian/comparator` ^7

## [v2.0.0] - 2025-01-28
### Changed
- Support for PHP 8.4 added, and PHP 8.1 dropped.
- Fixups for PHP 8.4 implicit nullable type declarations have been made.
  - This is a breaking change if you were extending the `ListCache` or `MapCache` classes and overriding their constructors.
  - All other fixups impact functions and should not have an impact.
- The `_` base class has been renamed `_Lodash`, as `_` as a class name has been deprecated.
  - The *namespace* `_` remains, so invocations of the functions as `\_\map()` will continue to function.
  - The `_` *constant* remains, so accessing the `_` class with that via the constant will continue to work.

## [v1.1.1] - 2024-05-15
### Changed
- Added support for `sebastian/comparator` ^6

## [v1.1.0] - 2024-06-26
### Changed
- Added support for `sebastian/comparator` ^5

## [v1.0.0] - 2023-03-22
### Changed
- Fixups for PHP 8.2 string interpolation deprecations.
