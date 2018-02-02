# Changelog
All notable changes to this project will be documented in this file.

## [1.4] - 2018-02-01
### Added
- Added RPi GPIO libraries

### Changed
- Updated Node-RED to 0.18.0
- Updated node-red-contrib-home-assistant to 0.2.1
- Moved install of node-red-contrib-home-assistant to `/share/node-red`

### Fixed
- No longer get error messages in logs about missing GPIO library
- Allow user updating of node-red-contrib-home-assistant

## [1.3] - 2018-01-11
### Fixed
- Fixed setting the wrong HTTP Password (Issue #3)

## [1.2] - 2017-12-27
### Fixed
- Corrected default settings path

## [1.1] - 2017-12-27
### Changed
- Don't install Node-RED as global package

### Fixed
- Use bcryptjs instead of bcrypt because of build issues
- Fixed bug in string quoting

## [1.0] - 2017-12-26
### Added
- Initial Project

[1.4]: https://github.com/korylprince/hassio-node-red/compare/1.3...1.4
[1.3]: https://github.com/korylprince/hassio-node-red/compare/1.2...1.3
[1.2]: https://github.com/korylprince/hassio-node-red/compare/1.1...1.2
[1.1]: https://github.com/korylprince/hassio-node-red/compare/1.0...1.1