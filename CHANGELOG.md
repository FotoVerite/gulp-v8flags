# Changelog

## 1.0.0 (2026-10-04)


### ⚠ BREAKING CHANGES

* Drop support for snake_case flags
* Utilize process.allowedNodeEnvironmentFlags ([#63](https://github.com/FotoVerite/gulp-v8flags/issues/63))
* Use SHA-256 for the config file name ([#57](https://github.com/FotoVerite/gulp-v8flags/issues/57))
* Normalize repository, dropping node <10.13 support ([#60](https://github.com/FotoVerite/gulp-v8flags/issues/60))

### Features

* Remove homedir polyfill ([#62](https://github.com/FotoVerite/gulp-v8flags/issues/62)) ([306f970](https://github.com/FotoVerite/gulp-v8flags/commit/306f970119b632b4439df2886f467e7da7662b27))
* Utilize process.allowedNodeEnvironmentFlags ([#63](https://github.com/FotoVerite/gulp-v8flags/issues/63)) ([2240a0f](https://github.com/FotoVerite/gulp-v8flags/commit/2240a0f72f5ee7b87530966178fda8153de43d86))


### Bug Fixes

* Add version to the cache file name ([#50](https://github.com/FotoVerite/gulp-v8flags/issues/50)) ([24622a1](https://github.com/FotoVerite/gulp-v8flags/commit/24622a1a528f0b7dd115e66f769d1ce0c88291c9))
* Always return flags even if the cache file can't be written ([e2e91ca](https://github.com/FotoVerite/gulp-v8flags/commit/e2e91cabc2306d5dba8dc6dd493bc6d2fa8d7297))
* Avoid appending to cache file on concurrent calls ([098e66c](https://github.com/FotoVerite/gulp-v8flags/commit/098e66c20d0cb4e33a43b0dbfc43fadcb32a7d55))
* Avoid polluting globals ([e543d1e](https://github.com/FotoVerite/gulp-v8flags/commit/e543d1efc336cdfec35dd27d2f1a775679fc83d9))
* Avoid throwing when Electron runtime ([dca90be](https://github.com/FotoVerite/gulp-v8flags/commit/dca90be8dd781865f88a69ae925e7ac7011ec80f))
* Correct typo ([1315cf3](https://github.com/FotoVerite/gulp-v8flags/commit/1315cf31b70aa0e380e18120cd963715260b5b19))
* Correct typo in the failure message ([2cd690c](https://github.com/FotoVerite/gulp-v8flags/commit/2cd690c6d940d39dc05b5936cb03a73597f2b4fe))
* Default flags to empty array (fixes [#53](https://github.com/FotoVerite/gulp-v8flags/issues/53)) ([c3b4ff0](https://github.com/FotoVerite/gulp-v8flags/commit/c3b4ff0d3cf0666015fbee6f92b434e75a55a0f9))
* Ensure callback is always called async ([c0d4e29](https://github.com/FotoVerite/gulp-v8flags/commit/c0d4e29f61c81d6fde6074818f6783e84d836466))
* Exclude example flags provided by node ([#66](https://github.com/FotoVerite/gulp-v8flags/issues/66)) ([58f009a](https://github.com/FotoVerite/gulp-v8flags/commit/58f009a2a69365abc2d3af187ef0abdc9e4f5297))
* Hash username to avoid invalid file paths ([#31](https://github.com/FotoVerite/gulp-v8flags/issues/31)) ([e27b29e](https://github.com/FotoVerite/gulp-v8flags/commit/e27b29e95a8e618248cf0fd04a53847982564f6d))
* Improve caching for non-standard environments ([fdc81c9](https://github.com/FotoVerite/gulp-v8flags/commit/fdc81c952280bcaad4f20d3979c3b29c9a95ea4e))
* Improve home directory lookup behavior & fallback (fixes [#41](https://github.com/FotoVerite/gulp-v8flags/issues/41)) ([#42](https://github.com/FotoVerite/gulp-v8flags/issues/42)) ([4d74ca0](https://github.com/FotoVerite/gulp-v8flags/commit/4d74ca0c1b7bc72b211e6a39c9f9f7885e974c3e))
* More work on concurrent config file access & appending issue ([e5976ff](https://github.com/FotoVerite/gulp-v8flags/commit/e5976ff339ee567d03cf7289b8eb0ca6ce4844be))
* Properly handle undefined user & add test ([64cc428](https://github.com/FotoVerite/gulp-v8flags/commit/64cc42823674bd4b02d5754de49bb07ca0c46fcf))
* Properly support new flag format in node 10 ([#49](https://github.com/FotoVerite/gulp-v8flags/issues/49)) ([4b16628](https://github.com/FotoVerite/gulp-v8flags/commit/4b166285a8c465d37b88936dd40a68a3f1040900))
* Revert to 1.0.0 behavior ([17cadd2](https://github.com/FotoVerite/gulp-v8flags/commit/17cadd24168c3bf01d30d3db9aa2b6a0015b5a51))
* Revert to 2.0.5 behavior ([836c75e](https://github.com/FotoVerite/gulp-v8flags/commit/836c75ea6578d60aaf9f1da819c9061ce5fd914b))
* Use node path from process.env._ ([5113f6a](https://github.com/FotoVerite/gulp-v8flags/commit/5113f6ac77db5315c9b311505f86a3dc1e627204))
* Use process.env.NODE to find node executable ([cb4e0e3](https://github.com/FotoVerite/gulp-v8flags/commit/cb4e0e3a06046d3550a449a6a5716251dc4a60ec))
* Use process.execPath to find node executable on Windows ([c2d0f37](https://github.com/FotoVerite/gulp-v8flags/commit/c2d0f37353c6ea1daf5f10c149d01c6e667c3524))
* Use SHA-256 for the config file name ([#57](https://github.com/FotoVerite/gulp-v8flags/issues/57)) ([f30a18e](https://github.com/FotoVerite/gulp-v8flags/commit/f30a18ef545882aba65aa23e3cb9da7d4bc0bbb4))
* Wrap node executable path in quotes ([99399f9](https://github.com/FotoVerite/gulp-v8flags/commit/99399f9fa98b7fb9e943c8eeb8b442c2318bec5c))


### Miscellaneous Chores

* Drop support for snake_case flags ([e5194ca](https://github.com/FotoVerite/gulp-v8flags/commit/e5194ca0b4e5e3d4f28b5a42903a20b477ee3eb9))
* Normalize repository, dropping node &lt;10.13 support ([#60](https://github.com/FotoVerite/gulp-v8flags/issues/60)) ([42ad05f](https://github.com/FotoVerite/gulp-v8flags/commit/42ad05f91336a6e9673313d1d988be0317309262))

### [4.0.1](https://www.github.com/gulpjs/v8flags/compare/v4.0.0...v4.0.1) (2023-09-03)


### Bug Fixes

* Exclude example flags provided by node ([#66](https://www.github.com/gulpjs/v8flags/issues/66)) ([58f009a](https://www.github.com/gulpjs/v8flags/commit/58f009a2a69365abc2d3af187ef0abdc9e4f5297))

## [4.0.0](https://www.github.com/gulpjs/v8flags/compare/v3.2.0...v4.0.0) (2021-11-08)


### ⚠ BREAKING CHANGES

* Drop support for snake_case flags
* Utilize process.allowedNodeEnvironmentFlags (#63)
* Use SHA-256 for the config file name (#57)
* Normalize repository, dropping node <10.13 support (#60)

### Features

* Remove homedir polyfill ([#62](https://www.github.com/gulpjs/v8flags/issues/62)) ([306f970](https://www.github.com/gulpjs/v8flags/commit/306f970119b632b4439df2886f467e7da7662b27))
* Utilize process.allowedNodeEnvironmentFlags ([#63](https://www.github.com/gulpjs/v8flags/issues/63)) ([2240a0f](https://www.github.com/gulpjs/v8flags/commit/2240a0f72f5ee7b87530966178fda8153de43d86))


### Bug Fixes

* Use SHA-256 for the config file name ([#57](https://www.github.com/gulpjs/v8flags/issues/57)) ([f30a18e](https://www.github.com/gulpjs/v8flags/commit/f30a18ef545882aba65aa23e3cb9da7d4bc0bbb4))


### Miscellaneous Chores

* Drop support for snake_case flags ([e5194ca](https://www.github.com/gulpjs/v8flags/commit/e5194ca0b4e5e3d4f28b5a42903a20b477ee3eb9))
* Normalize repository, dropping node <10.13 support ([#60](https://www.github.com/gulpjs/v8flags/issues/60)) ([42ad05f](https://www.github.com/gulpjs/v8flags/commit/42ad05f91336a6e9673313d1d988be0317309262))
