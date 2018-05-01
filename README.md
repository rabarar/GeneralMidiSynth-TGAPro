# GeneralMidiSynth-TGAPro
General MIDI Synth for the TGAPro and Teensy 3.6


## GeneralMidiSynth for TGAPro with teensy3.6

### I took the Wavetable-Synthesis library's GeneralMidiSynth sketch and modified it so you can use a MidiKeyboard connected to the TGAPro's MIDI input port. I use MidiKeys on OSX for example and when I play a key on a channel, I get the voice out to the output jack on the TGAPro.

I also use the Yamaha UX16 for my USB to MIDI adapter and plugging the output of the Yamaha into the input of the TGAPro and selecting the Yamaha as the destination on MidiKeys renders sound

## Debugging output

### You can open the serial monitor and see the notes being received on the input MIDI port.

## Gotchas

### Be certain that you select "Serial + MIDI" on the USB Type in arduino.
