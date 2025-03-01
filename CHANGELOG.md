# Change Log

All notable changes to this project will be documented in this file.

## [Unreleased](https://github.com/idealista/postgresql_role/tree/develop)

## [2.1.0](https://github.com/idealista/postgresql_role/tree/2.1.0)

[Full Changelog](https://github.com/idealista/postgresql_role/compare/2.0.0...2.1.0)

### Added

- *Support for PostgreSQL 17* @ultraheroe

### Updated

- *Updated ansible tasks to use FQCN* @ultraheroe
- *Updated test-requirements* @ultraheroe
- *Updated Goss version to v0.4.9 and adjusted architecture detection* @ultraheroe
- *Updated travis* @ultraheroe
- *Dropped support for old versions of PostgreSQL (EOL reached)* @ultraheroe

## [2.0.0](https://github.com/idealista/postgresql_role/tree/2.0.0)

[Full Changelog](https://github.com/idealista/postgresql_role/compare/1.4.2...2.0.0)

### Added

- *[#35](https://github.com/idealista/postgresql_role/issues/35) Adding support for Debian 12* @ledepedro
- *[#35](https://github.com/idealista/postgresql_role/issues/35) Adding support for Postgresql 13,14,15,16* @ledepedro

### Changed

- *Changed the default version of PostgreSQL to 16* @ledepedro

## [1.4.2](https://github.com/idealista/postgresql_role/tree/1.4.2)

[Full Changelog](https://github.com/idealista/postgresql_role/compare/1.4.1...1.4.2)

- *[#28] Adding support for Debian 11* @plozano94

## [1.4.1](https://github.com/idealista/postgresql_role/tree/1.4.1)

[Full Changelog](https://github.com/idealista/postgresql_role/compare/1.4.0...1.4.1)

- *[#23] Some integer variables are beign rendered wrongly on templates* @vsuarez

## [1.4.0](https://github.com/idealista/postgresql_role/tree/1.4.0)

[Full Changelog](https://github.com/idealista/postgresql_role/compare/1.3.0...1.4.0)

### Added

- *[#15](https://github.com/idealista/postgresql_role/issues/15) Add tags to included_tasks* @vicsufer

## [1.3.0](https://github.com/idealista/postgresql_role/tree/1.3.0)

[Full Changelog](https://github.com/idealista/postgresql_role/compare/1.2.0...1.3.0)

### Fixed

- *[#12](https://github.com/idealista/postgresql_role/issues/12) Fixed service mess when custom data dir is defined* @frantsao
- *Updated test dependencies because security warnings* @frantsao

### Added

- *[#9](https://github.com/idealista/postgresql_role/issues/9) Added tag to database management tasks* @frantsao

## [1.2.0](https://github.com/idealista/postgresql_role/tree/1.2.0)

[Full Changelog](https://github.com/idealista/postgresql_role/compare/1.1.0...1.2.0)

### Added

- *[#10](https://github.com/idealista/postgresql_role/issues/10) Allow custom values in postgresql.conf*

## [1.1.0](https://github.com/idealista/postgresql_role/tree/1.1.0)

[Full Changelog](https://github.com/idealista/postgresql_role/compare/1.0.1...1.1.0)

### Added

- *[#4](https://github.com/idealista/postgresql_role/issues/4) Adding support to manage users and databases* @dortegau
- *[#4](https://github.com/idealista/postgresql_role/issues/4) Upgraded to molecule 3 (fixes python interpreter issues in Centos 8)* @frantsao

## [1.0.1](https://github.com/idealista/postgresql_role/tree/1.0.1)

[Full Changelog](https://github.com/idealista/postgresql_role/compare/1.0.0...1.0.1)

### Fixed

- *Removed no longer needed postgresql.conf files used to create and check templates* @frantsao
- *Updated travis configuration* @frantsao

## [1.0.0](https://github.com/idealista/postgresql_role/tree/1.0.0)

### Added

- *First version* @frantsao
