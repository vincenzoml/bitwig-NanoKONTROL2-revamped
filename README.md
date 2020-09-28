# REVAMPED!!!

This repository contains a fork of the original bitwig script, which will be updated both to bring it up-to-date and to add new functions. 

By now, the following changes have been made:

- The script can control 2 devices even in different tracks! Since there are 8 knobs + 8 sliders = 16 parameters, it makes a lot of sense to do this. It works as follows: first 4 knobs + first 4 sliders = 8 parameters (4 above and 4 below) that follow the selected device in the selected track (and can be pinned in the studio I/O panel). Press the first 4 "S" buttons to change parameter page. Similarly, the last 4 knobs + last 4 sliders control another device. Pin it in the studio I/O panel, or it will control the same device as the first group.

- In mixer mode, the knobs control Send1, not pan. Ask if you would prefer pan, let's see how to make it usable. 

- The script is intended for live usage. As such, I've removed the arranger-related functionality (may be restored upon request). Also, I've removed the preset-change code which is very dangerous in live usage (hit set+marker, bum, you need undo to restore your sound, and it takes time)

Planned functionality:

- add more devices, by using also the "M" and "R" buttons to change track/device. 

- undo/redo via the << and >> buttons

- find good use of the marker buttons (also as modifiers)

- add clip recording / launching via the three rows of "S", "M", "R" buttons

- more mixer pages (e.g. control more sends, master track, tempo)

- Feel free to suggest more (sequencer anyone?)


# NanoKONTROL2-Macro-for-Bitwig
 Script designed to live with two modes , Mixer and Macro for maximum playability.<br />
 <br />
 <h3>HOW TO USE</h3><br />

 Mixer mode is selected first. Switch in Macro mode with cycle button. Toggle mode with the same process.<br />
 You can enter into Macro mode with [set] + [M]ute button for use the good track (cycle button for exit and return in Mixer mode).<br />
 <br />
 <h3>BOTH MODE</h3><br />

 Change selected track with [<]prev or [>]next button<br />
 Switch mode with [cycle] button<br />
 Toggle loop with [set] + [cycle] buttons<br />
 Rewind with [<<] button<br />
 FastForward with [>>] button<br />
 Stop song with [STOP] button<br />
 Play song with [PLAY] button<br />
 Arm Record with [RECORD] button<br />
 <br />
 [S]olo button toggle solo track<br />
 [M]ute button toggle mute track<br />
 [R]ecord button toggle arm track<br />
 <br />
 Slider range to control the volume<br />
 <br />
 <h3>MIXER MODE</h3><br />

 Knob range to control the panoramic<br />
 <br />
 Change the tempo with [<]marker button or [>]marker button for 1 BPM<br />
 Change the tempo with [set] + [<]marker or [set] + [>]marker button for 10 BPM<br />
 <br />
 <h3>MACRO MODE</h3><br />

 Knob[1-8] range to control the macro [1-8]
 
 
 
 
 
 
