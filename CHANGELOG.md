# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.3.0] - 2022-06-16
### Added
- Added suppport for jinja3

## [2.2.1] - 2022-05-30
### Fixed
- Minor fixes

## [2.2.0] - 2022-05-30
### Added
- Fixed deletion of valid distros, profiles and systems.
- Fixed performance problems.
### Fixed
- Fix tag problems.

## [2.1.0] - 2022-04-26
### Added
- Add complete selinux enforced compatibility

## [2.0.0] - 2022-04-26
### Added
- Refactorize to upgrade cobbler to version 3.X
- Any version of systems based on redhat prior to 8 is no longer supported
- Force selinux to permissive

## [1.4.2] - 2022-04-04
### Fixed
- Adapted for CentOS derived distros. Related to ansible/main#263

## [1.4.1] - 2022-02-14
### Fixed
- Fixed changelog.

## [1.4.0] - 2022-02-14
### Added
- Added cobbler_module_* variables.

### Changed
- Migrated tests to molecule.
