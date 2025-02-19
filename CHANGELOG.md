# :arrows_counterclockwise: Microsoft Windows As Built Report Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.5.5] - Unreleased

### Changed

- Increase dbatools module version (v2.1.18)
- Increase Eomm/why-don-t-you-tweet (v2.0)

### Fixed

- Fix DNS Zone table not displaying 'Available For Scavenge' and 'Last Scavenge Time' correctly
- Fix DHCP Infrastructure table not displaying 'Database Logging Enabled' and 'Database Backup Interval' correctly
- Fix [#31](https://github.com/AsBuiltReport/AsBuiltReport.Microsoft.Windows/issues/31)

## [0.5.4] - 2024-05-16

### Changed

- Increase AsBuiltReport.Core module version (v1.4.0)

### Fixed

- Fix [#25](https://github.com/AsBuiltReport/AsBuiltReport.Microsoft.Windows/issues/25)
- Fix [#26](https://github.com/AsBuiltReport/AsBuiltReport.Microsoft.Windows/issues/26)

## [0.5.3] - 2024-03-06

### Added

- Add SQL Server support
  - General Information
  - Security
    - Login
    - Roles
  - Databases
    - User
    - System
  - Server Objects
    - Backup Devices

## [0.5.2] - 2024-02-18

### Added

- Add Local Windows Group Members information @flynngw
- Add more HealthCheck conditions

### Changed

- Improve report readability

### Fixed

- Fix CodeQL security alerts
- Fix FailOver Cluster section
- Fix issue in Get-AbrWinOSHotfix install date logic

## [0.5.1] - 2023-05-16

### Added

- Added Hyper-V per VM configuration reporting @oolejniczak
- Added Hyper-V Management OS Adapters table @rebelinux

## [0.5.0] - 2023-05-08

### Added

- Added FailOver Cluster section

### Changed

- Improved bug and feature request templates
- Changed default logo from Microsoft to the AsBuiltReport logo due to licensing requirements
- Changed default report style font to 'Segoe Ui' to align with Microsoft guidelines
- Changed Required Modules to AsBuiltReport.Core v1.3.0

## [0.4.1] - 2022-10-20

### Fixed

- Fixes [#8](https://github.com/AsBuiltReport/AsBuiltReport.Microsoft.Windows/issues/8)

## [0.4.0] - 2022-10-20

### Added

- Added table to show the pending/missing Windows updates (Health Check)

## [0.3.0] - 2022-01-29

### Added

- Added DHCP Server Section
- Added DNS Server Section

### Changed

- Changed WINRM session authentication from kerberos to negotiate

## [0.2.0] - 2022-01-26

### Added

- Added Windows Logo
- Added table column sorting on primary key
- Added table caption
- Updated project ReadMe file
- Added IIS Web Server section
- Added SMB File Server section
- Added Windows Service Status to OS section

### Changed

- Migrate report to new module structure
- Implemented better error handling (try/catch)

## [0.1.0] - 2021-08-11

### Added

- Added Host Hardware Summary
- Added Host Operating System Section
- Added Host Networking Section
- Added Host Storage Section
  - Added Host ISCSI Section
- Added Hyper-V Configuration Section
- Added Local Users and Groups Section
