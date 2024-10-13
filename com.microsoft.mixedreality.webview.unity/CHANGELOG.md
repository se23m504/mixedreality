# Changelog

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [0.22.7-pre.1] - 2024-07-02

## [0.22.6] - 2024-06-06 [DEPRECATED]

### Fix

- Minor issue related to error hanlding for missing WebView2 runtime.

## [0.22.5] - 2024-05-29 [DEPRECATED]

### Added

- Added support for SSO
- Added new permission-related APIs:
    - `GetNonDefaultPermissionSettings()`
    - `SetPermissionState()`
    - `PermissionRequested` event
- Added new events:
    - `NavigationStarting`
    - `NavigationCompleted`
    - `DocumentTitleChanged`
- Added improved error handling for missing WebView2 runtime.
