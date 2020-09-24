
# Changelog (TypeScript Toolchain)
All notable changes to TypeScript Toolchain cruft template will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
- N/a



## [1.1.0] - 2020-09-24
### Changed
- Renamed repository from `@brisberg/typescript-pkg-cruft`.


## [1.1.0] - 2020-09-24
### Added
- Using `importHelpers` and `tslib` to emit smaller bundles from TypeScript ([#1](https://github.com/brisberg/typescript-toolchain/pull/1))

### Changed
- ESLint will no longer lint built files
- Packages will be pushed to registry.npmjs.org instead of GPR.
- Correctly exporting typings .d.ts files for package consumers


## [1.0.0] - 2020-09-24
### Added
- Added default configurations for all tools:
- [VSCode](https://code.visualstudio.com/) - Hackable IDE
- [TypeScript](https://www.typescriptlang.org/) - TypeScript language compiler
- [Yarn](https://yarnpkg.com/) - Package Manager of choice for node modules
- [Jest](https://jestjs.io/en/) - All-in-one test framework and assertion library
- [ESLint](https://eslint.org/) - Pluggable lint for JavaScript/TypeScript
- [clang-format](https://clang.llvm.org/) - Code Formatting library
- [GitHub Actions](https://github.com/features/actions) - CI Pipelines hosted by GitHub
- [Keep-a-Changelog](https://keepachangelog.com/en/1.0.0/) - Guide for maintaining a useful, readable Changelog.

### Changed
- Migrated to a [Cookiecutter](https://github.com/cookiecutter/cookiecutter) template from [@brisberg/typescript-toolchain](https://github.com/brisberg/typescript-toolchain)


[Unreleased]: https://github.com/brisberg/cruft-typescript-pkg/compare/v1.1.1...HEAD
[1.1.1]: https://github.com/brisberg/typescript-toolchain/compare/v1.1.0...v1.1.1
[1.1.0]: https://github.com/brisberg/typescript-toolchain/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/brisberg/cruft-typescript-pkg/compare/v0.0.0...v1.0.0
[0.0.0]: https://github.com/brisberg/cruft-typescript-pkg/releases/tag/v0.0.0
