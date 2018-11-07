# MIDICON-TO-MPC
This code translates midi commands from a MIDIcon and translates it to OSC for use with ONYX
First of all I have to give a shoutout to Arne Böckmann because of his help making this and since it's based on his original BCF2000 file.
Please read how to make this script work here:
https://frickeln.github.io/

To use the midiCON you'll have to install some aditional programs. These programs are loopmidi and midiox.
To install these programs, follow the following link:
http://controllerforum.elationlighting.com/t/two-identical-midi-devices-not-working-cant-select-the-second-one-in-the-list-solved/2408/3
You don't need to use the midi out since the midiCON doesn't need the feedback.
The fader feedback (for use with motorised faders) is still in there for use with the midiCON PRO.

Please note that this is currently V1 so there are some things still missing:
Currently the following things aren't working (correctly):
    Encoder wheels: these are kind of working but there are some weird issues I'll have to sort out.
    Page switching: currently you can't switch the pages of the faders in the software.
    
The faders and buttons above them are working correctly.
The playback buttons (on the right) are completely working, switching pages here actually changes the page in the software.
The special buttons are currently assigned to specific functions, these are the following:
  S1 = Page Up
  S2 = Page Down
  S3 = Clear
  S4 = Move
  S5 = Delete
  S6 = Record
I'm planning to make S3 through S6 user assignable. S1 and S2 might be more difficult but I'm planning on making those assignable as well.

Please check it out, if you have anything to add or requests please contact me and I'll try to make this possible.
