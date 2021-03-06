# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [6.7.0] - 2018-01-24

### Added
- New CMake module "CommonBuildFlags", which allows to easily set the same compilation flags to all KMS modules.

### Changed
- Debian: Align all version numbers of KMS-related modules.
- Debian: Remove version numbers from package names.

## [1.4.0] - 2017-07-24

### Added
- New CMake module "DpkgBuildFlags", which allows to query the `dpkg-buildflags` command and retrieve the compilation flags that will be used to generate Debian packages. All projects now compile with these compilation flags.

### Changed
- Old ChangeLog.md moved to the new format in this CHANGELOG.md file.
- Full review of all CMake files to tidy up and homogenize code style.

## [1.3.2] - 2016-09-30

## [1.3.1] - 2016-05-27

## [1.3.0] - 2016-02-24

## 1.2.2 - 2015-11-25

[6.7.0]: https://github.com/Kurento/kms-cmake-utils/compare/1.4.0...6.7.0
[1.4.0]: https://github.com/Kurento/kms-cmake-utils/compare/1.3.2...1.4.0
[1.3.2]: https://github.com/Kurento/kms-cmake-utils/compare/1.3.1...1.3.2
[1.3.1]: https://github.com/Kurento/kms-cmake-utils/compare/1.3.0...1.3.1
[1.3.0]: https://github.com/Kurento/kms-cmake-utils/compare/1.2.2...1.3.0
