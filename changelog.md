# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres
to [Semantic Versioning](https://semver.org/spec/v2.0.0.html) (after version 0.0.5).

## [0.0.5] - 2022-03-17
### Added
- New config: allow surrounding output with mermerd backticks ([PR #4](https://github.com/KarnerTh/mermerd/pull/4))

## [0.0.4] - 2022-03-14
### Added
- Licence

### Fixed
- Do not require a global configuration file

## [0.0.3] - 2022-03-12
### Added
- Possibility to opt in for all tables
- Start mermerd with a predefined run config
- Add version command
- Show version number in intro header

### Changed
- Improved help command output
- Exit with error code 1 on failure
- Fully POSIX-compliant flags (including short & long versions)
- the parameter for the connection string suggestions (previously `connectionStrings`) was renamed to
  `connectionStringSuggestions`
- the flag `-ac` was replaced with `--showAllConstraints`

### Removed
- `.mermerd` configuration file is not automatically created on first use anymore

## [0.0.2] - 2022-01-30
### Added
- Configurable suggestions for connection string input

### Changed
- improved one to many constraint detection for mysql
- improved one to many constraint detection for postgres

## [0.0.1] - 2022-01-17
### Added
- Initial release of mermerd

[0.0.5]: https://github.com/KarnerTh/mermerd/releases/tag/v0.0.5

[0.0.4]: https://github.com/KarnerTh/mermerd/releases/tag/v0.0.4

[0.0.3]: https://github.com/KarnerTh/mermerd/releases/tag/v0.0.3

[0.0.2]: https://github.com/KarnerTh/mermerd/releases/tag/v0.0.2

[0.0.1]: https://github.com/KarnerTh/mermerd/releases/tag/v0.0.1
