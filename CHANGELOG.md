# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.4.0] - 2020-07-01

### Added

* `github_owner` is now added in the main terragrunt.hcl as well.

## [1.3.2] - 2020-07-01

### Fixed

* secrets can not start with `GITHUB`. Therefore change it to `ADMIN_TOKEN_GITLAB`.

## [1.3.1] - 2020-07-01

### Fixed

* Wrong tag for release

## [1.3.0] - 2020-07-01

### Added

* The github_token will be places in a github action secret as well.

## [1.2.0] - 2020-07-01

### Added

* billing_account will be used for creating the initial terragrunt.hcl file as well.

## [1.1.0] - 2020-07-01

### Added

* Org_id and domain will be used for creating the initial terragrunt.hcl file.

## [1.0.0] - 2020-07-01

This release contains the first version of this Dockerfile with basic tooling:

### Added

* Main module to configure a github repository.
