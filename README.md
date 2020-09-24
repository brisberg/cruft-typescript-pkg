# TypeScript Npm Package (Template)

Standard project configuration template for @brisberg TypeScript NPM packages.

This is an opinionated toolchain configuration for TypeScript packages published to NPM Registry.
Powered by [Cookiecutter](https://github.com/cookiecutter/cookiecutter) template engine, meant to be distributed with [Cruft](https://github.com/cruft/cruft).

## Usage

### Besure to install cruft:

```bash
pip3 install cruft
```

### Setup
#### In a new repository:
```bash
cruft create https://github.com/brisberg/cruft-typescript-pkg/
```

#### In an existing repository:
```bash
# Link the repo to the bare template
cruft link https://github.com/brisberg/cruft-typescript-pkg -c v0.0.0
# Update to desired release to apply all the changes
cruft update (-c v1.1.0)
```

Be sure to keep any project specific config changes.

### Update
#### Check if there are updates upstream:
```bash
cruft check
```

#### Update to latest:
```bash
# Update to latest commit
cruft update
# Update to specific release tag
cruft update -c v1.1.0
```

Resolve merge conflicts, keeping project specific overrides and deletions.

Verify tests still pass before committing:
```bash
yarn test
# Tests pass
git add .
git commit
```

## Tools

- [VSCode](https://code.visualstudio.com/) - Hackable IDE
- [TypeScript](https://www.typescriptlang.org/) - TypeScript language compiler
- [Yarn](https://yarnpkg.com/) - Package Manager of choice for node modules
- [Jest](https://jestjs.io/en/) - All-in-one test framework and assertion library
- [ESLint](https://eslint.org/) - Pluggable lint for Javascript/TypeScript
- [clang-format](https://clang.llvm.org/) - Code Formatting library

## CI

- [GitHub Actions](https://github.com/features/actions) - CI Pipelines hosted by GitHub

## Best Practices

- [Keep-a-Changelog](https://keepachangelog.com/en/1.0.0/) - Guide for maintaining a useful, readable Changelog.
