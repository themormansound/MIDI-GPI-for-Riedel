# MIDI-GPI-for-Riedel
Raspberry Pi pico code for connecting Rode Rodecaster Pro to Riedel comms panel

Receives MIDI data on ALL channels, closes relay on NOTE-ON, opens on NOTE-OFF

Attach relay via transistor to pin 4.

To enable remote control of Riedel comms panel from RODE Rodecaster PRO.

You'll need the Adafruit 'TinyUSB' library and  MIDI Library by Forty Seven Effects (https://github.com/FortySevenEffects/arduino_midi_library)
