# Marvin's Change Log

## [2.0.5] - not yet released
### Added:
- Added netrc configuration to installation documentation.

### Fixed:
- Added mask to model spaxel.
- Bug in Cube tool when a galaxy loaded from db does not have NSA info; no failure with redshift
- Two bugs in index.py on KeyErrors: Sentry issues 181369719,181012809
- Bug on plate web page preventing meta-data from rendering

## [The dark ages] - multiple versions not logged.

## [1.90.0]
### Changed
- Full refactoring of Marvin 1.0
- Refactored web

### Added
- Marvin Tools
- Queries (only global properties, for now)
- Point-and-click for marvin-web
- RESTful API
- Many more changes

### Fixed
- Issue albireox/marvin#2: Change how matplotlib gets imported