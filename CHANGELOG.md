# Changelog

All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

<!-- EasyBuild: START -->
<!-- last_commit_released: 2d8589520fcff3892dcf2df50b416efd1b19c05f -->
<!-- EasyBuild: END -->

## 2.0.0 - 2024-12-02

### 🏗️ Breaking changes

* Add `perf`, `revert` and `build` commit type to be on par with Angular convention (most common one) ([9bba64c](https://github.com/easybuild-org/commit-linter/commit/9bba64cf4315a574403e3ba7b8c51f6160ccef91))

<strong><small>[View changes on Github](https://github.com/easybuild-org/commit-linter/compare/703531d83302632ddbfdf698a0bf7c0f05afb95a..2d8589520fcff3892dcf2df50b416efd1b19c05f)</small></strong>

## 1.1.0

### 🚀 Features

- Upgrade `EasyBuild.CommitParser` to ignore line starting with `#` at the end of the body or footer ([703531d](https://github.com/easybuild-org/EasyBuild.CommitLinter/commit/703531d83302632ddbfdf698a0bf7c0f05afb95a))

## 1.0.1

### 🐞 Bug Fixes

- Upgrade `EasyBuild.CommitParser` to support parsing footer with trailing lines ([729ff4f](https://github.com/easybuild-org/EasyBuild.CommitLinter/commit/729ff4f0cef9e338b31551ca1327ec3c631b9643))

## 1.0.0

### 🚀 Features

- Upgrade EasyBuild.CommitParser moving to a commit convention 100% compliant with Conventional Commit spec ([3ad6687](https://github.com/easybuild-org/EasyBuild.CommitLinter/commit/3ad66877d2bab41ed429cbf801a75f75cb386e18))

## 0.1.1

### 🐞 Bug Fixes

- Use `EasyBuild.CommitParser` instead of a custom inline parser ([c2dcbd6](https://github.com/easybuild-org/EasyBuild.CommitLinter/commit/c2dcbd693a9f079361f88ea877db4b754376c3e4))

## 0.1.0

### 🚀 Features

- Add a top level description for the CLI app ([e60ab34](https://github.com/easybuild-org/EasyBuild.CommitLinter/commit/e60ab349637d7bc602542b5f378d465e93423960))
- Allows to provide relative or absolute path for the config / commit file ([9cc4622](https://github.com/easybuild-org/EasyBuild.CommitLinter/commit/9cc46228b09823ff4a7d0f43d2b649910bb599b2))
- Initial implementation ([94e97b5](https://github.com/easybuild-org/EasyBuild.CommitLinter/commit/94e97b5b06bc351d9419235df3e4af13cb45f121))
### 🐞 Bug Fixes

- Improve formatting in case of invalid format ([b511088](https://github.com/easybuild-org/EasyBuild.CommitLinter/commit/b5110881d905234aef41b12c96efd307909f99dc))
- Include FSharp.Core in the generated tool ([2c3d605](https://github.com/easybuild-org/EasyBuild.CommitLinter/commit/2c3d605e12e2bced3a01333fc14513f135e05d5a))
