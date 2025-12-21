# Changelog

All notable changes to the TGB-Seq project will be documented in this file.

## [0.1.2] - 2024-12-21

### Fixed
- Updated NumPy dependency constraint from `<2.0` to `>=2.0` to support NumPy 2.0+ installations
- Fixed package build configuration to properly declare dependencies using PEP 517/518 standards
- Resolved dependency conflict that prevented installation in environments with NumPy 2.0+ (Issue #4)

### Changed
- Migrated from Poetry-only configuration to dual Poetry/setuptools configuration for better PyPI compatibility
- Bumped package version from 0.1.1 to 0.1.2

## [0.1.1] - Previous Release

Initial release of TGB-Seq benchmark package.