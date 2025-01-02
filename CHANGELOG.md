# Changelog

## [1.0.4] - 01-01-25

- Removed "Basic Chair" component from bot station, which may have prevented station events from being seen

## [1.0.3] - 04-27-24

- PortalManager takes a ZoneTrigger instead of AudioOverrideZone for bot zone
- Stream control checks for zones before using them, exposes zone properties
- Added PortalAudioConfig to dynamically set audio zones on stream control

## [1.0.2] - 02-15-24

- Removed empty Editor assembly definition that caused harmless warning in console

## [1.0.1] - 09-29-23

- Removed dependency on UdonSharp package to prepare for SDK 3.4.0
