
# Changelog (TypeScript Toolchain)
All notable changes to TypeScript Toolchain will be documented in this file. (Delete this section of the log from client packages)

TODO: Fix this to be relevant to cruft package

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Using `importHelpers` and `tslib` to emit smaller bundles from Typescript ([#1](https://github.com/brisberg/typescript-toolchain/pull/1))

### Changed
- Moved repository from @brisberg/typescript-pkg to @brisberg/typescript-toolchain


## [2.0.2] - 2020-06-23

### Changed
- Correctly exporting typings .d.ts files for package consumers


## [2.0.1] - 2020-06-23

### Changed
- ESLint will no longer lint built files
- Packages will be pushed to registry.npmjs.org instead of GPR.


## [1.0.1] - 2020-06-23

### Changed
- Upgrade Jest to latest (v26)


## [1.0.0] - 2020-06-23
### Added
- Added default configurations for all tools:
- [VSCode](https://code.visualstudio.com/) - Hackable IDE
- [TypeScript](https://www.typescriptlang.org/) - TypeScript language compiler
- [Yarn](https://yarnpkg.com/) - Package Manager of choice for node modules
- [Jest](https://jestjs.io/en/) - All-in-one test framework and assertion library
- [ESLint](https://eslint.org/) - Pluggable lint for Javascript/TypeScript
- [clang-format](https://clang.llvm.org/) - Code Formatting library
- [GitHub Actions](https://github.com/features/actions) - CI Pipelines hosted by GitHub
- [Keep-a-Changelog](https://keepachangelog.com/en/1.0.0/) - Guide for maintaining a useful, readable Changelog.


[Unreleased]: https://github.com/brisberg/typescript-toolchain/compare/v2.0.2...HEAD
[2.0.2]: https://github.com/brisberg/typescript-toolchain/releases/tag/v2.0.1...v2.0.2
[2.0.1]: https://github.com/brisberg/typescript-toolchain/releases/tag/v1.0.1...v2.0.1
[1.0.1]: https://github.com/brisberg/typescript-toolchain/releases/tag/v1.0.0...v1.0.1
[1.0.0]: https://github.com/brisberg/typescript-toolchain/releases/tag/v1.0.0
