# Changelog

## [1.0.0](https://github.com/CroudTech/croudtech-python-gcp-otel/compare/v0.3.1...v1.0.0) (2026-01-19)


### ⚠ BREAKING CHANGES

* Extras are no longer available; all instrumentations are always installed.

### Features

* include all instrumentations by default ([bff1505](https://github.com/CroudTech/croudtech-python-gcp-otel/commit/bff1505b848d4f7c1ed04a2604cea5d93400776f))

## [0.3.1](https://github.com/CroudTech/croudtech-python-gcp-otel/compare/v0.3.0...v0.3.1) (2026-01-19)


### Bug Fixes

* sync version in __init__.py with release-please ([062992b](https://github.com/CroudTech/croudtech-python-gcp-otel/commit/062992be3ccf5fd7efcc244d8e8c8ae1cf39794a))

## [0.3.0](https://github.com/CroudTech/croudtech-python-gcp-otel/compare/v0.2.1...v0.3.0) (2026-01-19)


### Features

* add PyPI publishing to release workflow ([18cc12f](https://github.com/CroudTech/croudtech-python-gcp-otel/commit/18cc12fff3a126e61a7123fe6681cb78a25cd7cb))


### Bug Fixes

* check for existing TracerProvider before configuration ([75c524a](https://github.com/CroudTech/croudtech-python-gcp-otel/commit/75c524ad5bee331a7cefad42e39a919feeed2e53))
* handle TracerProvider already set exception gracefully ([8286d98](https://github.com/CroudTech/croudtech-python-gcp-otel/commit/8286d9861a4b38441ac8b8e77d34d940d4faff2b))
* improve trace context extraction from non-recording spans ([18d13db](https://github.com/CroudTech/croudtech-python-gcp-otel/commit/18d13db15da7cefa0c2e27a1e80bf591e7bf285e))

## [0.2.1](https://github.com/CroudTech/croudtech-python-gcp-otel/compare/v0.2.0...v0.2.1) (2026-01-15)


### Bug Fixes

* extras configuration for optional instrumentations ([e0ffb44](https://github.com/CroudTech/croudtech-python-gcp-otel/commit/e0ffb44c9a704d11f25408f5597b83da24cd7f33))

## [0.2.0](https://github.com/CroudTech/croudtech-python-gcp-otel/compare/v0.1.0...v0.2.0) (2026-01-15)


### Features

* add release-please GitHub Actions workflow ([fd0f025](https://github.com/CroudTech/croudtech-python-gcp-otel/commit/fd0f025467f6ac7158f224ddd3564fac2142dc38))


### Documentation

* update installation instructions for GitHub ([115b48d](https://github.com/CroudTech/croudtech-python-gcp-otel/commit/115b48daf410bb04a4568b979a6d35b6a67bf465))
