# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- Something here


## [2.0.5] - 2021-02-14
### Fixed
- This thing please

## [2.0.4] - 2021-02-14
### Added
- doctrine/dbal dependency for editing migrations
- Logout function for UserAuthentication
- UserRepository::getWhereEmail function to retrieve a user via email
- UserRepository::getFromControlId function to retrieve a user via control ID
- UserRepository::getFromRememberToken function to get by remember token
- Functions to get the control user from the database user

## [2.0.3] - 2020-02-05
### Added
- doctrine/dbal dependency for editing migrations
- Logout function for UserAuthentication
- UserRepossssitory::getWhereEmail function to retrieve a user via email
- UserRepository::getFromControlId function to retrieve a user via control ID
- UserRepository::getFromRememberToken function to get by remember token
- Functions to get the control user from the database user

### NotValid
- Some test

## [2.0.2] - 2020-02-04
### Added
- doctrine/dbal dependency for editing migrations
- Logout function for UserAuthentication
- UserRepository::getWhereEmail function to retrieve a user via email
- UserRepository::getFromControlId function to retrieve a user via control ID
- UserRepository::getFromRememberToken function to get by remember token
- Functions to get the control user from the database user

### Removed
- Forename, surname, email and student ID columns from database user model.
- UserRepository::getWhereIdentity function

## [2.0.1] - 2020-02-04
### Added
- doctrine/dbal dependency for editing migrations
- Logout function for UserAuthentication
- UserRepository::getWhereEmail function to retrieve a user via email
- UserRepository::getFromControlId function to retrieve a user via control ID
- UserRepository::getFromRememberToken function to get by remember token
- Functions to get the control user from the database user

### Removed
- Forename, surname, email and student ID columns from database user model.
- UserRepository::getWhereIdentity function


## [2.0.0] - 2020-02-04
### Added
- doctrine/dbal dependency for editing migrations
- Logout function for UserAuthentication
- UserRepository::getWhereEmail function to retrieve a user via email
- UserRepository::getFromControlId function to retrieve a user via control ID
- UserRepository::getFromRememberToken function to get by remember token
- Functions to get the control user from the database user

### Removed
- Forename, surname, email and student ID columns from database user model.
- UserRepository::getWhereIdentity function

### Fixed

## [1.1.0] - 2020-01-31
### Changed
- Bumped the control dependency to version 1 (stable)
- Allow Module Instance Setting values to be null
- Refresh the module builder instance in the factory

### Added
- Laravel Session Authentication

### Removed
- Laravel Web Authentication

## [1.0.3] - 2020-01-17
### Added
- Initial Release

## [1.0.2] - 2020-01-15
### Added
- Initial Release

## [1.0.1] - 2020-01-13
### Changed
- Generate a new module builder each time the module factory is used
- Make module instance setting values nullable
- Connection ID attribute is now fillable for a module instance service
- Prefer stable dependencies

## [1.0.0] - 2020-01-01
### Added
- Initial Release

[Unreleased]: https://github.com/tobytwigger/test-release-package/compare/v2.0.5...HEAD
[2.0.5]: https://github.com/tobytwigger/test-release-package/compare/v2.0.4...2.0.5
[2.0.4]: https://github.com/tobytwigger/test-release-package/compare/v2.0.3...2.0.4
[2.0.3]: https://github.com/tobytwigger/test-release-package/compare/v2.0.2...v2.0.3
[2.0.2]: https://github.com/tobytwigger/test-release-package/compare/v2.0.1...v2.0.2
[2.0.1]: https://github.com/tobytwigger/test-release-package/compare/v2.0.0...v2.0.1
[2.0.0]: https://github.com/tobytwigger/test-release-package/compare/v1.1.0...v2.0.0
[1.1.0]: https://github.com/tobytwigger/test-release-package/compare/v1.0.3...v1.1.0
[1.0.3]: https://github.com/tobytwigger/test-release-package/compare/v1.0.2...v1.0.3
[1.0.2]: https://github.com/tobytwigger/test-release-package/compare/v1.0.1...v1.0.2
[1.0.1]: https://github.com/tobytwigger/test-release-package/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/tobytwigger/test-release-package/tag/v1.0.0
