# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.0.6]
### Added
- iframe execution environment ([#33](https://github.com/MetaMask/snaps-skunkworks/pull/33))
- Execution environment OpenRPC spec ([#23](https://github.com/MetaMask/snaps-skunkworks/pull/23))

### Changed
- **(BREAKING)** Migrate `CommandEngine` message format to JSON-RPC ([#11](https://github.com/MetaMask/snaps-skunkworks/pull/11))
- **(BREAKING)** Refactor `PluginController` to use `BaseControllerV2` ([#13](https://github.com/MetaMask/snaps-skunkworks/pull/13))
- **(BREAKING)** Use generic execution environment interface ([#19](https://github.com/MetaMask/snaps-skunkworks/pull/19))
- **(BREAKING)** Restore origin parameter to `setupWorkerConnection`, rename to `setupPluginProvider` ([#20](https://github.com/MetaMask/snaps-skunkworks/pull/20))
- **(BREAKING)** Rename some execution environment methods ([#23](https://github.com/MetaMask/snaps-skunkworks/pull/23))

### Fixed
- Ensure that the plugin `isRunning` check always runs when a plugin is started ([#21](https://github.com/MetaMask/snaps-skunkworks/pull/21))

## [0.0.5]
### Uncategorized
- First semi-stable release.

[Unreleased]: https://github.com/MetaMask/snaps-skunkworks/compare/v0.0.6...HEAD
[0.0.6]: https://github.com/MetaMask/snaps-skunkworks/compare/v0.0.5...v0.0.6
[0.0.5]: https://github.com/MetaMask/snaps-skunkworks/releases/tag/v0.0.5