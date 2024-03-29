# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html). However, eLux packages also include a -X identifier, which represents the version of the eLux package

## 1.4.2-0 - 2023-06-16

### Fixed
- Compatibility issue with Citrix Workspace App for Linux 2209 and up

## 1.4.1-0 - 2021-04-14

### Fixed
- Compatibility issue with Citrix Workspace App for Linux 2101 and up

## 1.4.0-0 - 2020-03-20

### Added
- More robust messaging protocol between the Kandy HID Driver for VDI and Kandy HID SDK

## 1.3.1-0 - 2020-02-28

### Added
- A 64-bit (RP6) version of this package is available

## 1.3.1-0 - 2020-01-31

### Added
- In Citrix VDI, filtering of known / supported devices has been removed. All HID devices found by the Kandy HID Driver for VDI are sent up to the Kandy HID SDK for filtering and processing

## 1.2.0-2 - 2020-01-17

### Changed
- Rebuild of 1.2.0-1 to address a bug in the VDI Toolkit, which was built using the wrong version of Kandy HID Driver for VDI

## 1.2.1-0 - 2020-01-10

### Added
- Ability to disable the Kandy HID Driver for VDI (killswitch)

## 1.2.0-1 - 2019-11-04

### Added
- One of each supported type of HID device may now be connected to a Thin Client simultaneously

## 1.1.0-1 - 2019-08-16

### Added
- Support for the Jabra Speak 710 in VDI mode

<!-- changelog possible fields:
### Added
### Changed
### Removed
### Deprecated
### Fixed
### Security
>
