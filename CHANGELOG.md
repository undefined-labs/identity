# Changelog

All notable changes to this project are documented in this file.

## [0.0.1] - 2026-09-16

First release under `@undefined-labs/identity`. This project is a fork of the
unmaintained `@open-core/identity` (last published upstream as 1.3.0); the
entries below summarise the inherited history up to the fork point, so version
numbers mentioned in them refer to the upstream package.

### Features

- Add generic type parameters to identity stores and services
- Add lifecycle hooks and default role auto-creation support
- Add findByName method to RoleStore and improve onReady hook

### Refactor

- Change role and account identifiers to support string or number types
- Improve type safety and consistency in store contracts
- Remove unused IdentityOptions dependency from services

### Documentation

- Restructure README to focus on documentation index and DI pattern

### Miscellaneous

- Bump version to 1.2.1 and add identity-auth provider file
- Replace bcrypt with bcryptjs dependency
- Bump version to 1.2.3
- Bump version to 1.2.4 and refactor account/role identifiers
- Bump version to 1.2.5
- Upgrade @open-core/framework to v0.2.6 and enhance identity management
- Bump version to 1.2.6 and update @open-core/framework to ^0.2.7


