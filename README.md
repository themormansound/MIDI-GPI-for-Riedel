# MIDI-GPI-for-Riedel
Raspberry Pi pico code for connecting Rode Rodecaster Pro to Riedel comms panel

Receives MIDI data on ALL channels, closes relay on NOTE-ON, opens on NOTE-OFF

Attach relay via transistor to pin 4.

To enable remote control of Riedel comms panel from RODE Rodecaster PRO.

Installation:

Download the rp2040.rp2040.rpipico.zip file, copy the UF2 file to your pico board.

To compile:

You'll need the Adafruit 'TinyUSB' library and  MIDI Library by Forty Seven Effects (https://github.com/FortySevenEffects/arduino_midi_library)

Also: Had some dramas using latest libs/boards, but success with 'Raspberry Pi Pico/RP2040' by Earle F Philhower V3.6.3 and 'Adafruit TinyUSB' V2.3.2
