# Changelog

All notable changes to this project will be documented in this file.

## [0.4.0] - 2023-06-22

### Bug Fixes

- Add missing cleanup for parameter deletion

### Features

- Allow initialization to continue without crashing if no region is set
- Verify commit message structure in workflow
- Merge non-namespaced params with namespaced params
- Add NamespaceFilter
- Optionally load default environment keys

### Miscellaneous Tasks

- Add pull_from_env_or_obj utility function
- Update README.rst
- More details on configuration variables
- Change logger name and use warn instead of exception level
- Guard against non-string type for DEFAULT_ENV_FOR_DYNACONF

### Refactor

- Unify exception handling style
- Unify environment parameter naming scheme

## [0.3.2] - 2023-06-07

### Miscellaneous Tasks

- New metadata fields in pyproject.toml
- Introduce git-cliff for generating CHANGELOG
- Add CHANGELOG.md for 0.3.2

<!-- generated by git-cliff -->
