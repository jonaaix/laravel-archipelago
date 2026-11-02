# Changelog

All notable changes to `aaix/laravel-archipelago` will be documented in this file.

## [1.0.2] - 2026-11-02

### Added

- An `archipelago-development` skill for Laravel Boost that names the skill of each package. Boost
  reads skills only from packages a `composer.json` requires directly, so the package skills were
  out of reach through this package.

### Changed

- Package type `library` instead of `metapackage`: a metapackage installs no files, so it could not
  ship the skill.

## [1.0.1] - 2026-11-02

### Changed

- README lists the packages with full-size logos.

## [1.0.0] - 2026-11-02

First release.

### Added

- Installs `aaix/laravel-islands`, `aaix/laravel-islands-datagrid`, `aaix/laravel-islands-search`,
  `aaix/laravel-islands-gallery` and `aaix/laravel-islands-filemanager`, each with `^1.0`.
