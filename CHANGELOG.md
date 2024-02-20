# Changelog

## [2.0.0](https://github.com/cccteam/github-workflows/compare/v1.1.0...v2.0.0) (2024-02-20)


### ⚠ BREAKING CHANGES

* Accept Slack channel ID as secret in golang-security-scan yml ([#16](https://github.com/cccteam/github-workflows/issues/16))

### Features

* Accept Slack channel ID as secret in golang-security-scan yml ([#16](https://github.com/cccteam/github-workflows/issues/16)) ([367894f](https://github.com/cccteam/github-workflows/commit/367894f218454c70ac9b23a5834f69cd64d0a6ce))
* Include scanner output in Issue body ([#13](https://github.com/cccteam/github-workflows/issues/13)) ([6b4613b](https://github.com/cccteam/github-workflows/commit/6b4613b174190dcd05641d00e6d49b459bc73fe9))

## [1.1.0](https://github.com/cccteam/github-workflows/compare/v1.0.1...v1.1.0) (2024-02-09)


### Features

* Add workflow for building and scanning a Docker image ([#14](https://github.com/cccteam/github-workflows/issues/14)) ([89e7e0a](https://github.com/cccteam/github-workflows/commit/89e7e0ada4970ca87320714651a33289dc65f8e9))

## [1.0.1](https://github.com/cccteam/github-workflows/compare/v1.0.0...v1.0.1) (2024-02-03)


### Bug Fixes

* Do not ignore unfixed in security scan ([#11](https://github.com/cccteam/github-workflows/issues/11)) ([141661b](https://github.com/cccteam/github-workflows/commit/141661bb9d1eb3adbfe406b8bf0ee6605baf9933))

## [1.0.0](https://github.com/cccteam/github-workflows/compare/v0.0.1...v1.0.0) (2024-01-30)


### Features

* Add support for golangci-lint timeout ([#7](https://github.com/cccteam/github-workflows/issues/7)) ([c882fce](https://github.com/cccteam/github-workflows/commit/c882fceee8143eb708275654ad02f4ac00228849))


### Bug Fixes

* Execute alert-related jobs even if trivyscan is skipped ([#6](https://github.com/cccteam/github-workflows/issues/6)) ([3b982e9](https://github.com/cccteam/github-workflows/commit/3b982e982ecad4ef1216d1cbed7e671598f04008))
