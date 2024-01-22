# Vite Changelog

All notable changes to this project will be documented in this file.

## 5.0.0-beta.2 - UNRELEASED
### Added
* If the `devServer` is running, the `ViteService::fetch()` method will try to use the `devServerInternal` URL first, falling back on the `devServerPublic` so that `craft.vite.inline()` can pull from the `devServer` if it is running ([#22](https://github.com/nystudio107/craft-plugin-vite/issues/22))

## 5.0.0-beta.1 - 2024.01.21
### Added
- Initial beta release
