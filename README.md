# MC8 Midi Controller
Firmware for the MC8 Midi Controller

## Important
Please read the release notes before updating, so you are aware of any breaking changes, or feature changes that may affect your workflow.

[Release notes](https://morningstarengineering.atlassian.net/wiki/spaces/MMS/pages/917045253/Firmware+Release+Notes)


## How to update your firmware
[Firmware Upload Instructions](https://morningstarengineering.atlassian.net/wiki/spaces/MMS/pages/946307073/Updating+your+Firmware)

[Firmware Upload Video Walk through](https://www.youtube.com/watch?v=wtvX8Y9LzXo)

## What firmware to download
There are 2 firmware versions available for each model. One firmware exposes a MIDI + Keyboard USB Interface, while the other exposes just a MIDI Interface. The firmware version suffixed with `A` indicates that it is a MIDI-only USB interfaec.

For example
- `2021-12-21_MC8_Firmware_v3_9_6.hex`
  - MIDI + Keyboard USB Interface 
- `2021-12-21_MC8_Firmware_v3_9_6A_NO_KEYBOARD_INTERFACE.hex`
  - MIDI-only Interface 

## Naming convention for firmware numbers

##### Example: v3.2.1A
- 3: Current architecture. Requires a total reset if switching to a different version
- 2: New features and bug fixes have been made
- 1: Critical bug fixes are made in this version. 0 = Beta version.
- A: If the `A` character is present, the firmawre exposes a MIDI-only USB Interface.
