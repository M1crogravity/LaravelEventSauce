# Changelog

This changelog follows [the Keep a Changelog standard](https://keepachangelog.com).

## [Unreleased](https://github.com/EventSaucePHP/LaravelEventSauce/compare/0.2.0...master)


## [0.2.0](https://github.com/EventSaucePHP/LaravelEventSauce/compare/0.1.0...0.2.0)

### Changed
- Laravel 7 is now the minimum supported version
- PHP 7.4 is now the minimum supported version
- Aggregate root id cannot be null ([37eec03](https://github.com/EventSaucePHP/LaravelEventSauce/commit/37eec039172ce12a6875ca099d6ea0ff080a0c73))
- Rename `aggregate_root_id` column to `event_stream` ([f5682b3](https://github.com/EventSaucePHP/LaravelEventSauce/commit/f5682b39b23f4857512273b81561c381c91570d8))

### Fixed
- Protect from non-aggregate root ([89d5a7b](https://github.com/EventSaucePHP/LaravelEventSauce/commit/89d5a7b63ec46b04e7535f199bca645cc6b09352))


## 0.1.0 (2019-08-29)

Initial release.
