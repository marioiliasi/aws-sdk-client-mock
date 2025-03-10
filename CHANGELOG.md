# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [4.1.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v4.1.0-beta.0...v4.1.0) (2024-10-15)


### Features

* add commandCall method to AwsStub ([#241](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/241)) ([4f11d4c](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/4f11d4ce587ba989aa53e70d13f2cbc0a1ef3d96))

## [4.1.0-beta.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v4.0.2...v4.1.0-beta.0) (2024-10-11)


### Features

* **jest:** add support for vitest ([#231](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/231)) ([3ed37a9](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/3ed37a9404f5385e50dcd157f8fa6962e22452ab))


### Bug Fixes

* **jest:** import path in types test ([750605b](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/750605b68a2b11057e1977cbdd6e219030144550))

### [4.0.2](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v4.0.2-beta.0...v4.0.2) (2024-09-23)

### [4.0.2-beta.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v4.0.1...v4.0.2-beta.0) (2024-06-20)


### Bug Fixes

* **jest:** allow "toHaveReceivedCommandWith" partial match without required Command fields ([79929ae](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/79929ae03339be734f04012dc8faa86a1a0f3eb7))

### [4.0.1](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v4.0.1-beta.0...v4.0.1) (2024-06-01)

### [4.0.1-beta.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v4.0.0...v4.0.1-beta.0) (2024-06-01)


### Bug Fixes

* **jest:** match input type accepting @jest/globals asymmetric matchers ([644a603](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/644a6030ebe86446389c8d3ca18239501e848241))

## [4.0.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v4.0.0-beta.0...v4.0.0) (2024-03-17)

## [4.0.0-beta.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v3.1.0...v4.0.0-beta.0) (2024-03-17)


### ⚠ BREAKING CHANGES

* Correct expect.assertions() count on CommandWith commands (#209)

### Bug Fixes

* Correct expect.assertions() count on CommandWith commands ([#209](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/209)) ([65d53a7](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/65d53a724f36910d0b7cb75169e3f0121369bd41))

## [3.1.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v3.1.0-beta.1...v3.1.0) (2024-03-17)

## [3.1.0-beta.1](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v3.1.0-beta.0...v3.1.0-beta.1) (2024-01-15)


### Features

* support toHaveReceivedAnyCommand matcher ([#202](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/202)) ([ba5eedb](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/ba5eedb167968c0e3d6968aded0287c8493ed460))

## [3.1.0-beta.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v3.0.1...v3.1.0-beta.0) (2024-01-01)


### Features

* **core:** ability to use custom Sinon Sandbox ([#200](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/200)) ([31ff180](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/31ff180f58a16d61a38d65fc97d35d1af5d9ff5b))
* **jest:** fail if more than expected matcher arguments are passed ([#199](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/199)) ([6f7bb59](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/6f7bb5940ed3f568f54e7d8800520ea1be9641a3)), closes [#191](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/191)
* migrate Jest matchers to @jest/globals types ([#198](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/198)) ([8f14cbb](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/8f14cbbde2dae020500444b9cf9f315d6476ef5a)), closes [#180](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/180)

### [3.0.1](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v3.0.0...v3.0.1) (2024-01-01)

### Fixes

* bump sinon version ([7ccfdca](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/7ccfdcaada4916df4c530179d19e1f05b4cc75e9))

## [3.0.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v3.0.0-beta.0...v3.0.0) (2023-07-01)

## [3.0.0-beta.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v2.2.0...v3.0.0-beta.0) (2023-07-01)


### ⚠ BREAKING CHANGES

* support AWS SDK v3.363.0

### Features

* support AWS SDK v3.363.0 ([0865065](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/0865065290b77fcfbfc6cf4a7db7c43448d1fcc1))

## [2.2.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v2.2.0-beta.0...v2.2.0) (2023-06-26)


### Features

* allow throwing errors in callsFake() ([67c37e6](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/67c37e6d812c704c4a15e50fd53505805f88fc6b)), closes [#8](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/8)

## [2.2.0-beta.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v2.1.1...v2.2.0-beta.0) (2023-05-30)


### Features

* access Client configuration in callsFake ([#164](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/164)) ([020735a](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/020735a205a18efaa7226049d64bf4e7bab9ecec))

### [2.1.1](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v2.1.0...v2.1.1) (2023-03-11)

## [2.1.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v2.0.1...v2.1.0) (2023-03-06)


### Features

* add Jest matcher for nth specific Command ([#146](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/146)) ([89ef933](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/89ef93388eae31c599aec626de7d074accf04484))

### [2.0.1](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v2.0.0...v2.0.1) (2022-11-27)


### Bug Fixes

* Bump Sinon version ([#133](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/133)) ([0a513a1](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/0a513a12dbb3ebd0a7f121fa272c000e45011d0b))

## [2.0.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v2.0.0-beta.2...v2.0.0) (2022-08-29)

## [2.0.0-beta.2](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v2.0.0-beta.1...v2.0.0-beta.2) (2022-08-21)


### ⚠ BREAKING CHANGES

* move Jest matchers to a separate package (#112)

### Features

* support Jest asymmetric matchers ([#111](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/111)) ([3bf23ef](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/3bf23eff752e8cc9814fa44b95ad809baafe8aac))


### Bug Fixes

* move Jest matchers to a separate package ([#112](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/112)) ([05a3a51](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/05a3a51046b7076deaabdff96d4ead62145e08de))

## [2.0.0-beta.1](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v2.0.0-beta.0...v2.0.0-beta.1) (2022-06-27)


### Bug Fixes

* add @types/jest as a regular dependency ([c51c9d9](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/c51c9d903a0e55285b93947b38ef6f1b0e06331e))

## [2.0.0-beta.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v1.0.0...v2.0.0-beta.0) (2022-06-26)


### ⚠ BREAKING CHANGES

* remove libStorage helper to remove incompatibilities (#105)

### Bug Fixes

* remove libStorage helper to remove incompatibilities ([#105](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/105)) ([097d29f](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/097d29f1cbcd55f21ceb8a1718af3c7e55eb9a6f))

## [1.0.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v0.6.2...v1.0.0) (2022-06-14)


### ⚠ BREAKING CHANGES

* remove @aws-sdk types and client-s3 from peer dependencies (#57)

### Features

* introduce jest matchers ([#97](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/97)) ([b5f2c10](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/b5f2c100075ad0d30856ec611bed739812b4a872))


### Bug Fixes

* remove [@aws-sdk](https://github.com/aws-sdk) types and client-s3 from peer dependencies ([#57](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/57)) ([c66e050](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/c66e050ba87895120277af3b4739f761c1ed231a))

### [0.6.2](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v0.6.1...v0.6.2) (2022-03-06)


### Features

* chained behaviors for consecutive command calls ([#80](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/80)) ([fe131a9](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/fe131a92afedd653ad576d7ac415d24a1984d6c1))

### [0.6.1](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v0.6.0...v0.6.1) (2022-03-05)


### Bug Fixes

* bump typescript to 4.6.2 ([5c29961](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/5c29961e2c0e93e23d0cac705aad8cbcb8ec406d)), closes [#79](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/79)

## [0.6.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v0.5.6...v0.6.0) (2022-02-12)


### ⚠ BREAKING CHANGES

* recreate mock on reset() (#76)

### Bug Fixes

* recreate mock on reset() ([#76](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/76)) ([9e1a873](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/9e1a873e0dbd2c969a7f164d9dca4ebf50a5db51)), closes [#1572](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/1572) [#1572](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/1572)

### [0.5.6](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v0.5.5...v0.5.6) (2021-11-06)


### Features

* getting mock calls with command type and payload filter ([#61](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/61)) ([b3f3250](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/b3f32507162e7e0054e40807c9119faf5266f969))

### [0.5.5](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v0.5.4...v0.5.5) (2021-09-19)


### Bug Fixes

* not requiring @aws-sdk/client-s3 installed if not using lib-storage mock ([#51](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/51)) ([67d55d2](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/67d55d2bd83c89d61d609a2eb30978a028b89b50))

### [0.5.4](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v0.5.3...v0.5.4) (2021-09-16)


### Features

* helper to mock @aws-sdk/lib-storage Upload ([#47](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/47)) ([10780e8](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/10780e821be9d6ef497579beb02f96ba222f6e62))

### [0.5.3](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v0.5.2...v0.5.3) (2021-06-24)


### Features

* **src:** enable types as peer dependencies to get around bumping wi… ([#35](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/35)) ([2150567](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/215056733f44cfca19242a4456fcaa6d188abf6d))

### [0.5.2](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v0.5.1...v0.5.2) (2021-06-14)

### [0.5.1](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v0.5.0...v0.5.1) (2021-06-13)


### Bug Fixes

* move tslib to dependencies ([#31](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/31)) ([df8bd27](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/df8bd2743e4da1ad97935fede5c930d0db59bcc9))

## [0.5.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v0.4.0...v0.5.0) (2021-05-31)


### ⚠ BREAKING CHANGES

* bump Sinon to v11 (#27)

### Bug Fixes

* make compatibility test project dir ([2aef307](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/2aef3077089ab39d6185cfdec6a13ecf139bdd11))


* bump Sinon to v11 ([#27](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/27)) ([2edad51](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/2edad513c4788ab137e1348c13e53ae0b891a68f)), closes [#24](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/24) [#22](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/22)

## [0.4.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v0.3.0...v0.4.0) (2021-05-06)


### ⚠ BREAKING CHANGES

* partial payload matching by default (#16)

### Features

* partial payload matching by default ([#16](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/16)) ([3bdc6bb](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/3bdc6bb3be4a3b2e95be7c7093c8cd5a5625d656))

### [0.3.1](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v0.3.0...v0.3.1) (2021-05-01)

### [0.3.0](https://github.com/m-radzikowski/aws-sdk-client-mock/compare/v0.2.0...v0.3.0) (2021-04-11)


### Features

* DynamoDB DocumentClient mocking ([#11](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/11)) ([a1de5fe](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/a1de5fefaae2d5bfe0a8dadb5a7468f0c4d56790))

## 0.2.0 (2021-03-06)


### ⚠ BREAKING CHANGES

* type-checking of resolved responses (#2)

### Features

* type-checking of resolved responses ([#2](https://github.com/m-radzikowski/aws-sdk-client-mock/issues/2)) ([da31c40](https://github.com/m-radzikowski/aws-sdk-client-mock/commit/da31c40329fd53c4b5d9debd34413662ddbdc26e))

## 0.1.1 (2021-02-18)

Initial release
