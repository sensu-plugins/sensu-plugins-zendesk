# Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed [here](https://github.com/sensu-plugins/community/blob/master/HOW_WE_CHANGELOG.md)

## [Unreleased]

## [2.0.0] - 2018-03-04
### Security
- updated rubocop dependency to `~> 0.51.0` per: https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-8418 (@majormoses)

### Breaking Changes
- removed ruby `< 2.1` support (@majormoses)

### Added
- Ruby 2.4.1 testing

### Changed
- updated changelog guidelines location (@majormoses)

### Fixed
- handler-zendesk.rb: fixed print statement with single quotes when it needs to be interpolated (@majormoses)

## [1.0.0] - 2017-03-24
### Added
- Support for Ruby 2.3 (@eheydrick)

### Removed
- Ruby 1.9.3 support (@eheydrick)

### Fixed
- Pin to `activesupport` < 5 so Ruby 2.0, 2.1 are supported (@eheydrick)
- Fix deprecated `timeout` warnings (@eheydrick)

## [0.0.3] - 2015-07-14
### Changed
- updated sensu-plugin gem to 1.2.0

## [0.0.2] - 2015-06-03
### Fixed
- added binstubs

### Changed
- removed cruft from /lib

## 0.0.1 - 2015-05-21
### Added
- initial release

[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-zendesk/compare/2.0.0...HEAD
[2.0.0]: https://github.com/sensu-plugins/sensu-plugins-zendesk/compare/1.0.0...2.0.0
[1.0.0]: https://github.com/sensu-plugins/sensu-plugins-zendesk/compare/0.0.3...1.0.0
[0.0.3]: https://github.com/sensu-plugins/sensu-plugins-zendesk/compare/0.0.2...0.0.3
[0.0.2]: https://github.com/sensu-plugins/sensu-plugins-zendesk/compare/0.0.1...0.0.2
