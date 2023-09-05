# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Fixed
- Fix comment typos.

## [2.2.2] - 2023-09-05
### Fixed
- Misnamed rule.

## [2.2.1] - 2023-09-05
### Changed
- Sort rules alphabetically.
- Wrap comments at column 100.
- Don't require multi-line arrays to be sorted alphabetically.
- Don't enforce limits on file size, class size or function complexity.

## [2.2.0] - 2023-09-05
### Changed
- Update slevomat/coding-standard to version 8.
- Allow both capturing and non-capturing catch.

## [2.1.2] - 2022-08-01
### Changed
- Don't require an empty line after use if it's the last in class.
- Remove requirement on number literals.

## [2.1.1] - 2022-04-26
### Changed
- Allow empty().

## [2.1.0] - 2021-12-09
### Changed
- Allow arrow functions.
- Require constructor property promotion.
- Require trailing comma in multi-line function declaration.

## [2.0.0] - 2021-12-02
### Changed
- Update slevomat/coding-standard to version 7.

## [1.1.0] - 2020-12-13
### Added
- Dependabot config and running PR tests on Appocular
  repositories.
- This changelog.

### Changed
- Use dealerdirect/phpcodesniffer-composer-installer to ease
  installation.
- Submit to packagist for even easier installation.

## [1.0.3] - 2019-11-17
### Changed
- Slevomat has both rules forbidding ternary operator, and decide
  whether they should be single or multi line. We'll allow them.
- Allow increment and decrement operators.

## [1.0.2] - 2019-11-16
### Changed
- Require an empty (save for the *) line between @ elements of a doc
  comment.

## [1.0.1] - 2019-11-16
### Changed
- Allow {@inheritdoc}. It might be immediately useless, might be
  useless, but it does serve as a hint to the reader that there might
  be better documentation in the parent class/implemented interface.

## [1.0.0] - 2019-11-16
### Added
- Use slevomat/coding-standard and adjust it to adhere to PSR12.
- Also adjust to personal taste.

[Unreleased]: https://github.com/appocular/coding-standard/compare/2.2.2...HEAD
[2.2.0]: https://github.com/appocular/coding-standard/compare/2.2.1...2.2.2
[2.2.0]: https://github.com/appocular/coding-standard/compare/2.2.0...2.2.1
[2.2.0]: https://github.com/appocular/coding-standard/compare/2.1.2...2.2.0
[2.1.1]: https://github.com/appocular/coding-standard/compare/2.1.1...2.1.2
[2.1.1]: https://github.com/appocular/coding-standard/compare/2.1.0...2.1.1
[2.1.0]: https://github.com/appocular/coding-standard/compare/2.0.0...2.1.0
[2.0.0]: https://github.com/appocular/coding-standard/compare/1.1.0...2.0.0
[1.1.0]: https://github.com/appocular/coding-standard/compare/1.0.2...1.1.0
[1.0.3]: https://github.com/appocular/coding-standard/compare/1.0.2...1.0.3
[1.0.2]: https://github.com/appocular/coding-standard/compare/1.0.1...1.0.2
[1.0.1]: https://github.com/appocular/coding-standard/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/appocular/coding-standard/releases/tag/1.0.0
