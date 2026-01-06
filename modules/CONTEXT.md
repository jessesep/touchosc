# Modules Context

Reusable TouchOSC control modules ready for integration into projects. These are community-made controls with extended functionality.

## Available Modules

### Dropdown Menus
- **dropdown_scroll**: Scrollable dropdown menu (up to 10 elements, configurable unfold size, two output modes)
- **dropdown_static**: Static dropdown menu (up to 10 elements, two output modes, auto-scales)

Both dropdowns:
- Support local messages, MIDI, and OSC
- Use tag property for communication
- Configurable via script (no scripting knowledge required to use)
- Elements set via Lua list syntax

### Multitoggle
- **multitoggle**: 4 variations of exclusive multitoggles (MIDI and OSC versions)
- Can send individual messages when button is turned on, superseded, or turned off
- Can send additional message when ANY button changes state
- Messages and target connections configurable in script

### Numpad
- **numpad**: Foldable integer numberpad with:
  - User-definable range
  - Delete single digits
  - Clear function
  - Variable hide functionality (shrinks to small/big button)
  - Supports local messages, MIDI, and OSC via tag property

## Module Interface Pattern
All modules use a consistent interface:
- **Tag property**: Stores result/state for communication
- **Touch value**: Triggers events in local messages
- **Direct MIDI/OSC**: Can send messages directly using touch as trigger and tag as source
- **Script-based configuration**: Parameters set in script, no scripting knowledge needed to use

## Integration
Modules can be copied/pasted from their .tosc template files into your own projects. They're designed to work standalone or integrated with other controls via local messages.
