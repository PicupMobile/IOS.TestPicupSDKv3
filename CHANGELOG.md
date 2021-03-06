# Changelog

## [2.4.0]

### Added
- Enable branded opt-in screen before asking user to grant Contacts access.
- show "test version" banner when `testingMode` is 1.
- add `refresh()` function to call from background fetch. 

## [2.3.3]

### Added
- Allow testing silent push notifications in development environment.

## [2.3.2]

### Changed
- Change register() signature to make it clearer and easier to use.

## [2.3.1]

### Fixed
- fix occasional server-side decryption error.

## [2.3.0]

### Added
- support silent push notifications by allowing the app to call `didReceiveMessage()`.
- add contact groups.
- add test server configuration.

## [2.2.3]

### Added
- new card designs and configuration options.
- allow to disable service from either client or server, which will automatically clear all data.
- add `permissionMode` that defaults to `external`. 
- add `isDebugMode` and only print to the console when it's `true`, with "PicUP" prefix.

### Fixed
- fix duplicates.
- prevent possible crash by ensuring host app has contacts usage description.

