# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- Dependabot config and running PR tests on Appocular
  repositories.
- This changelog.

### Changed
- Use dealerdirect/phpcodesniffer-composer-installer to ease
  installation.

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

[Unreleased]: https://github.com/appocular/coding-standard/compare/1.0.2...HEAD
[1.0.3]: https://github.com/appocular/coding-standard/compare/1.0.2...1.0.3
[1.0.2]: https://github.com/appocular/coding-standard/compare/1.0.1...1.0.2
[1.0.1]: https://github.com/appocular/coding-standard/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/appocular/coding-standard/releases/tag/1.0.0
