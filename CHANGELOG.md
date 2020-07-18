# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [5.1.0](https://github.com/faceyspacey/extract-css-chunks-webpack-plugin/compare/v4.7.4...v5.1.0) (2020-07-18)


### Features

* update deps ([#262](https://github.com/faceyspacey/extract-css-chunks-webpack-plugin/issues/262)) ([3a73ff5](https://github.com/faceyspacey/extract-css-chunks-webpack-plugin/commit/3a73ff531056d5bea7fa53fffac69ca4f7f9c97b))


### Bug Fixes

* add TS declarations ([#282](https://github.com/faceyspacey/extract-css-chunks-webpack-plugin/issues/282)) ([c3c22f8](https://github.com/faceyspacey/extract-css-chunks-webpack-plugin/commit/c3c22f8d9c5fa63a6293157645f272a597694684))
* docs ([88f2bb1](https://github.com/faceyspacey/extract-css-chunks-webpack-plugin/commit/88f2bb13fa541fe3bac7217675ac2b08c7128bbe))
* restore `insert` option functionality ([#265](https://github.com/faceyspacey/extract-css-chunks-webpack-plugin/issues/265)) ([b164efd](https://github.com/faceyspacey/extract-css-chunks-webpack-plugin/commit/b164efd0a50a3ac587fb4d916dfa0458e1195a58)), closes [faceyspacey/extract-css-chunks-webpack-plugin#264](https://github.com/faceyspacey/extract-css-chunks-webpack-plugin/issues/264)
* **deps:** update dependency loader-utils to v2 ([#251](https://github.com/faceyspacey/extract-css-chunks-webpack-plugin/issues/251)) ([e0fa3e3](https://github.com/faceyspacey/extract-css-chunks-webpack-plugin/commit/e0fa3e32b0a3c23b125e45d34694e0e32075420f))
* **deps:** update dependency webpack to v4.42.0 ([#247](https://github.com/faceyspacey/extract-css-chunks-webpack-plugin/issues/247)) ([24b808f](https://github.com/faceyspacey/extract-css-chunks-webpack-plugin/commit/24b808ff74a8b1fa6a2e184f0c534ebde9177383))
* **deps:** update dependency webpack-external-import to v2 ([#232](https://github.com/faceyspacey/extract-css-chunks-webpack-plugin/issues/232)) ([3ad42db](https://github.com/faceyspacey/extract-css-chunks-webpack-plugin/commit/3ad42db05c417aaa11beb069772d6ce4c9962adc))
* addressing comments from webpack on insert-string ([#226](https://github.com/faceyspacey/extract-css-chunks-webpack-plugin/issues/226)) ([d41bafa](https://github.com/faceyspacey/extract-css-chunks-webpack-plugin/commit/d41bafa3b442c0f36a8aa26fddfa5f158043a4e5))

### [0.9.0](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/compare/v0.8.2...v0.9.0) (2019-12-20)


### Features

* new `esModule` option ([#475](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/475)) ([596e47a](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/596e47a8aead53f9cc0e2b1e09a2c20e455e45c1))

### [0.8.2](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/compare/v0.8.1...v0.8.2) (2019-12-17)


### Bug Fixes

* context for dependencies ([#474](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/474)) ([0269860](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/0269860adb0eaad477901188eea66693fedf7769))

### [0.8.1](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/compare/v0.8.0...v0.8.1) (2019-12-17)


### Bug Fixes

* use filename mutated after instantiation ([#430](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/430)) ([0bacfac](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/0bacfac7ef4a06b4810fbc140875f7a038caa5bc))
* improve warning of conflict order ([#465](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/465)) ([357d073](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/357d073bf0259f2c44e613ad4dfcbcc8354e4be3))
* support ES module syntax ([#472](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/472)) ([2f72e1a](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/2f72e1aa267de23f121441714e88406f579e77b2))

## [0.8.0](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/compare/v0.7.0...v0.8.0) (2019-07-16)


### Features

* Add ignoreOrder option ([#422](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/422)) ([4ad3373](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/4ad3373))



## [0.7.0](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/compare/v0.6.0...v0.7.0) (2019-05-27)


### Bug Fixes

* do not attempt to reload unrequestable urls ([#378](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/378)) ([44d00ea](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/44d00ea))
* fix `publicPath` regression ([#384](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/384)) ([582ebfe](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/582ebfe))
* enable using plugin without defining options ([#393](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/393)) ([a7dee8c](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/a7dee8c))
* downgrading normalize-url ([#399](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/399)) ([0dafaf6](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/0dafaf6))
* hmr do not crash on link without href ([#400](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/400)) ([aa9b541](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/aa9b541))
* hmr reload with invalid link url ([#402](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/402)) ([30a19b0](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/30a19b0))


### Features

* add `moduleFilename` option ([#381](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/381)) ([13e9cbf](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/13e9cbf))



<a name="0.6.0"></a>
# [0.6.0](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/compare/v0.5.0...v0.6.0) (2019-04-10)


### Features

* added error code to chunk load Error ([#347](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/347)) ([b653641](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/b653641))
* adding hot module reloading ([#334](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/334)) ([4ed9c5a](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/4ed9c5a))
* publicPath can be a function ([#373](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/373)) ([7b1425a](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/7b1425a))



<a name="0.5.0"></a>
# [0.5.0](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/compare/v0.4.5...v0.5.0) (2018-12-07)


### Features

* add crossOriginLoading option support ([#313](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/313)) ([ffb0d87](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/ffb0d87))



<a name="0.4.5"></a>
## [0.4.5](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/compare/v0.4.4...v0.4.5) (2018-11-21)


### Bug Fixes

* **index:** allow requesting failed async css files ([#292](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/292)) ([2eb0af5](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/2eb0af5))



<a name="0.4.4"></a>
## [0.4.4](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/compare/v0.4.3...v0.4.4) (2018-10-10)


### Bug Fixes

* **index:** assign empty `module.id` to prevent `contenthash` from changing unnecessarily ([#284](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/284)) ([d7946d0](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/d7946d0))



<a name="0.4.3"></a>
## [0.4.3](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/compare/v0.4.2...v0.4.3) (2018-09-18)


### Bug Fixes

* **loader:** pass `emitFile` to the child compilation (`loaderContext.emitFile`) ([#177](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/177)) ([18c066e](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/18c066e))



<a name="0.4.2"></a>
## [0.4.2](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/compare/v0.4.0...v0.4.2) (2018-08-21)


### Bug Fixes

* use correct order when multiple chunk groups are merged ([#246](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/246)) ([c3b363d](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/c3b363d))



<a name="0.4.1"></a>
## [0.4.1](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/compare/v0.4.0...v0.4.1) (2018-06-29)


### Bug Fixes

* CSS ordering with multiple entry points ([#130](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/issues/130)) ([79373eb](https://github.com/webpack-contrib/extract-css-chunks-webpack-plugin/commit/79373eb))



# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

x.x.x / <year>-<month>-<day>
==================

  * Bug fix -
  * Feature -
  * Chore -
  * Docs -
