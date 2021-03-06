## [0.2.2] - 2019-11-21
### Added
- Device list now sorts correctly when using diactrics in friendly names
- Some logging features for MQTT and Autodiscovery process
- Toolbar actions now available in device list context menu (#55)
- Preferences dialog: console word-wrap setting and font size and version formatting option for device list
- Clear obsolete LWTs dialog added in MQTT menu
- Save/Clear functions to console

### Fixed
- Power ALL was sending true/false instead of 0/1 (#53)

## [0.2.1] - 2019-11-16
### Fixed
- forced sorting of POWER\<x\> keys when generating toggle actions and drawing state icons
- exception catching when SetOption parsing fails in older Tasmota versions 

## [0.2.0] - 2019-10-02
### Added
- consoles for each device, with colored output to ease reading (needs some polishing), command completion and history
- buttons, switches and relays configuration dialog
- custom widgets in the redesigned device list, including different views

### Changed
- most of the codebase rewritten