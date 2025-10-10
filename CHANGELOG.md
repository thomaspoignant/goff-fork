# Changelog

## [1.47.1](https://github.com/thomaspoignant/goff-fork/compare/v1.47.0...v1.47.1) (2025-10-10)


### Bug Fixes

* add exclusions ([1101277](https://github.com/thomaspoignant/goff-fork/commit/1101277d3ec26c66cc0f8db561930c2d566e4da5))

## [1.47.0](https://github.com/thomaspoignant/goff-fork/compare/v1.46.1...v1.47.0) (2025-10-10)


### ⚠ BREAKING CHANGES

* Remove deprecated AWS SDK v1 retrievers and exporters ([#3804](https://github.com/thomaspoignant/goff-fork/issues/3804))

### Features

* add evaluation rules name to all the flags evaluations ([#3910](https://github.com/thomaspoignant/goff-fork/issues/3910)) ([5546813](https://github.com/thomaspoignant/goff-fork/commit/554681371a38ae81ff28bf4211aca632218ccfb4))
* add flagset name in logs ([#3882](https://github.com/thomaspoignant/goff-fork/issues/3882)) ([995c9b5](https://github.com/thomaspoignant/goff-fork/commit/995c9b5a3f8e223488637c3fa03955f7507f63d2))
* add pubsubexporterv2 with cloud.google.com/go/pubsub/v2 support ([#3807](https://github.com/thomaspoignant/goff-fork/issues/3807)) ([17f598d](https://github.com/thomaspoignant/goff-fork/commit/17f598d68da6bf3d45f903212352f6fa08eba924))
* Adding static flagset feature ([#3610](https://github.com/thomaspoignant/goff-fork/issues/3610)) ([8b655d2](https://github.com/thomaspoignant/goff-fork/commit/8b655d294efc585c509511eeb1b371008d3807e8))
* blog post to introduce flag sets ([#3692](https://github.com/thomaspoignant/goff-fork/issues/3692)) ([e4c66e6](https://github.com/thomaspoignant/goff-fork/commit/e4c66e66801dcf8ae905780812ace0a0232fbb07))
* Bump go minor ([#3448](https://github.com/thomaspoignant/goff-fork/issues/3448)) ([a098503](https://github.com/thomaspoignant/goff-fork/commit/a098503555355b12560aa5c7c01f56ec5e79c55f))
* First step in-process evaluation ([#3413](https://github.com/thomaspoignant/goff-fork/issues/3413)) ([652e728](https://github.com/thomaspoignant/goff-fork/commit/652e72831000c02e08e99f856297e2281ad131f5))
* **helm:** Add monitoringPort support for relay-proxy Helm chart ([#3803](https://github.com/thomaspoignant/goff-fork/issues/3803)) ([0d4f096](https://github.com/thomaspoignant/goff-fork/commit/0d4f0965993696869c879c2463d8e9d2a652e3e1))
* postgresql retriever - flagset compatible ([#3881](https://github.com/thomaspoignant/goff-fork/issues/3881)) ([2a2ff14](https://github.com/thomaspoignant/goff-fork/commit/2a2ff1437416e372b556bcee0102ab12656ad558))
* reuse retriever config logic from cmd/relayproxy ([#3911](https://github.com/thomaspoignant/goff-fork/issues/3911)) ([b722fae](https://github.com/thomaspoignant/goff-fork/commit/b722faeebb71fb30876412999d60fe845d447a01))
* use pterm in cli output ([#3810](https://github.com/thomaspoignant/goff-fork/issues/3810)) ([7497875](https://github.com/thomaspoignant/goff-fork/commit/7497875b404980626e5da28b3524929bc1fa3929))
* Use static distroless image ([#3449](https://github.com/thomaspoignant/goff-fork/issues/3449)) ([8e0e938](https://github.com/thomaspoignant/goff-fork/commit/8e0e9388d78783635441d36156834422f693765e))


### Bug Fixes

* Add AWS API Gateway base path support for non-root Lambda deployments ([#3661](https://github.com/thomaspoignant/goff-fork/issues/3661)) ([f6fde9a](https://github.com/thomaspoignant/goff-fork/commit/f6fde9ad78443a735d3f0e289e9f6518f5bf8403))
* Admin key only should not enable authentication ([#3956](https://github.com/thomaspoignant/goff-fork/issues/3956)) ([20d0757](https://github.com/thomaspoignant/goff-fork/commit/20d07579b22a8627fb7987bb216084e156773444))
* Blog post link ([21bf493](https://github.com/thomaspoignant/goff-fork/commit/21bf4933eeb0112cc177540787e2e0139908f27b))
* building error in netlifly ([#3916](https://github.com/thomaspoignant/goff-fork/issues/3916)) ([d6116ea](https://github.com/thomaspoignant/goff-fork/commit/d6116eae46ddfea191fb85f8ad24de305ea13b34))
* Bumping things to resolve CVE ([#3948](https://github.com/thomaspoignant/goff-fork/issues/3948)) ([4d5fc9f](https://github.com/thomaspoignant/goff-fork/commit/4d5fc9f49071562dbaf99b796011545fa9fa95d4))
* cache key in python provider should contain flag key ([#3614](https://github.com/thomaspoignant/goff-fork/issues/3614)) ([e8ab15c](https://github.com/thomaspoignant/goff-fork/commit/e8ab15cf47146113a27843d9010286ba02c4ca8d))
* ci sdk version ([#3988](https://github.com/thomaspoignant/goff-fork/issues/3988)) ([81029f6](https://github.com/thomaspoignant/goff-fork/commit/81029f6b6b41df02ad294a7c7366d489543aecb0))
* Error when opening PR on wasm repo ([#3636](https://github.com/thomaspoignant/goff-fork/issues/3636)) ([1e4ac93](https://github.com/thomaspoignant/goff-fork/commit/1e4ac9362cb9f18ce877a7d3fda4582132420c89))
* fix linter ([#3696](https://github.com/thomaspoignant/goff-fork/issues/3696)) ([61ace44](https://github.com/thomaspoignant/goff-fork/commit/61ace44c903a27ecb4d382852fbae40b217b496a))
* improve flaky test around websocket ([#3917](https://github.com/thomaspoignant/goff-fork/issues/3917)) ([01ac94b](https://github.com/thomaspoignant/goff-fork/commit/01ac94be41bda5836a7988c27a3cbd883460c788))
* Pin nikunjy/rules to version with fix for semver bug ([#3618](https://github.com/thomaspoignant/goff-fork/issues/3618)) ([9113431](https://github.com/thomaspoignant/goff-fork/commit/911343117d8fb046f466192a7598c198ec9ebfd4))
* **python:** CI trigger python test ([#3635](https://github.com/thomaspoignant/goff-fork/issues/3635)) ([1dadd38](https://github.com/thomaspoignant/goff-fork/commit/1dadd385192db721d4f3b2506772a34575832292))
* resolve flaky timestamp tests in TestGetFlagStates and TestAllFlagsState ([#3984](https://github.com/thomaspoignant/goff-fork/issues/3984)) ([a541616](https://github.com/thomaspoignant/goff-fork/commit/a541616ccccda62dc5c813d2b3698a7146ee07b3))
* resolve flaky websocket test by implementing proper cleanup and timeouts ([#3915](https://github.com/thomaspoignant/goff-fork/issues/3915)) ([a34d4d4](https://github.com/thomaspoignant/goff-fork/commit/a34d4d4a2547d45682f30daba98cf5b1d38b67d3))
* return flat error in logs ([#3875](https://github.com/thomaspoignant/goff-fork/issues/3875)) ([c867646](https://github.com/thomaspoignant/goff-fork/commit/c8676461a2ab593bd2e822a3989e4e8e47b9bab3))
* website/package.json & website/package-lock.json to reduce vulnerabilities ([#3428](https://github.com/thomaspoignant/goff-fork/issues/3428)) ([1e2719b](https://github.com/thomaspoignant/goff-fork/commit/1e2719b7250a6d13b72bdb84f26d6224f97207e2))


### Miscellaneous Chores

* Remove deprecated AWS SDK v1 retrievers and exporters ([#3804](https://github.com/thomaspoignant/goff-fork/issues/3804)) ([91433b2](https://github.com/thomaspoignant/goff-fork/commit/91433b2d9c85e85735a35fc85c361c956da03f3c))
