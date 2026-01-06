# Examples Context

Collection of TouchOSC examples demonstrating various scripting techniques, control interactions, and interface patterns.

## Recent Updates
- **bpm_tap**: Improved robustness, TAP now blinks in sync with onset
- **fade_example**: Updated fade scripts
- **master_fader_mix**: Added relative master fader mix example

## Examples by Category

### Control Addressing & Navigation
- **address_controls**: Demonstrates parent/children addressing in Lua
- **find&findAll**: Shows find() and findAll() functions for locating controls
- **group_iterator**: Single and recursive iteration over groups

### Faders & Values
- **fader_incdec**: Increment/decrement fader in 127 MIDI steps
- **fader_two_value_responsefactor**: Dynamic response factor for faders
- **master_fader_mix**: Control multiple faders relatively via master fader
- **copy_value**: Copy value between controls

### Animation & Timing
- **fade_example**: Automatic fades between values (0-1 or stored value-0)
- **delayed_and_repetitive_actions**: Timer-based delayed/repetitive actions using getMillis() and update()
- **bpm_tap**: BPM counter with ring buffer, button blinks in sync with onset

### Grid & Layout
- **grid_label**: GRID scripting tutorial, iterating children, setting labels
- **multitoggle_1d**: Multitoggle examples with radio grid functionality

### Randomization & Iteration
- **randomizer**: Randomize control values using tag property
- **shuffle_table**: Shuffle table functionality

### Properties & Configuration
- **simple_properties**: Set properties via local messages and Lua (size, color, position)
- **many_properties**: Example with many configurable properties

### Hardware Integration
- **accelerometer_xy**: Use device accelerometer to control XY values with smoothing
- **battery_level**: Display device battery level
- **midi_pgm_incdec**: MIDI program increment/decrement with Lua

### Utilities
- **date_time**: Date/time clock display
- **copy_value**: Copy value functionality

## Common Patterns
- Local messages for control communication
- Lua scripting for dynamic behavior
- Tag property for data storage/communication
- Parent/children relationships for control addressing
- Timer-based updates using getMillis() and update() function
- find() and findAll() for control discovery
