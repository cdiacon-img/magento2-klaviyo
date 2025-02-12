# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

### [Unreleased]

### Fixed
- Email consent now recorded when Klaviyo list opt-in settings are used

### [2.0.0] - 2021-01-11

#### Added
- Product delete observer webhook to send to Klaviyo catalog
- Webhook secret form field for webhook validation

#### Changed
- Removed csp setting
- Removed csp mode from config.xml
- Added a.fast.klaviyo.com to img-src csp whitelist


### [1.2.4] - 2020-12-01

#### Added
- Create CHANGELOG.md

#### Changed
- Update to README.md to share contribution guidelines
- Use List API V2 for fetching newsletter lists

#### Fixed
- Remove JQuery UI as a dependency since it is unused


### [1.2.3] - 2020-10-09

##### Changed
- Removes unused variable and DI from Reclaim.php
- CSP now uses report-only mode


[Unreleased]: https://github.com/klaviyo/magento2-klaviyo/compare/2.0.0...HEAD
[2.0.0]: https://github.com/klaviyo/magento2-klaviyo/compare/1.2.4...2.0.0
[1.2.4]: https://github.com/klaviyo/magento2-klaviyo/compare/1.2.3...1.2.4
[1.2.3]: https://github.com/klaviyo/magento2-klaviyo/compare/1.2.2...1.2.3

  
#### NOTE
- The CHANGELOG was created on 2020-11-20 and does not contain information about earlier releases
