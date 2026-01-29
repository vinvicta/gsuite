======================================================================
                       Graal Release Notes
======================================================================

Graal
by Linux Cyberjoueur
Manager: Stéphane Portha (unixmad@graalonline.com)
Technical Director: Stefan Knorr (bomber@graalonline.com)

--------------------------------------
For the latest information and updates
--------------------------------------

Visit the Graal homepage at www.graalonline.com

----------
Copyrights
----------

Graal uses the HawkVoice libraries for encoding/decodoing voice packets.
It is distributed under the LGPL. You find the source code at
http://www.hawksoft.com/hawkvoice/

---------------
Problem solving
---------------

P: My character always moves to the left!
A: Graal just uses the installed joysticks. So try to
calibrate your joysticks or turn off joystick support in
the option window (click on the 'options' button in the
starting window).

P: When I start Graal then it crashes with a dinput.dll error!
A: There are some compability problems between DirectX5 and
DirectX7 joystick drivers. Disable the use of DirectInput
in the options window.

P: I cannot see my own nick name in the online mode!
A: But the other players see your name (type in 'showname'
to see it for 3 secs).

P: When I start Graal it only says "Graal.exe corrupted"!
A: The game checks for the checksum of Graal.exe. If it's
incorrect, then there is a virus on your machine or a similar
program that manipulates executables (some older virus
checkers do so). Remove the virus or turn off the exe
manipulation.
At this time Graal doesn't work with 'drivespace' or other
hard disk compressors because then the exe checksum is wrong.


--------
Controls
--------

Options Window:
  F1

Open Editor:
  F4

Load Level:
  F5

Debug Window (in the script list click left to a command to set a breakpoint):
  F6

Player List:
  F7

Server List:
  F8

End game:
  Escape

Running + Push Stones:
  Player1: joystick1 or arrow keys or 'I'/'J'/'K'/'L'
  Player2: joystick2 or numpad '8'/'5'/'2'/'6'

Item Button (use items/weapons, or hide under carried bush, or (when on horse): spy fire, eat bushes with your horse):
  Player1: joystick1 button 1 or 'D'
  Player2: joystick2 button 1 or numpad '1'

Attack Button (slay sword):
  Player1: joystick1 button 2 or 'S' or space bar
  Player2: joystick2 button 2 or numpad '5'

Action Button (lift objects, pull stones, get down from the horse):
  Player1: joystick1 button 3 or 'A'
  Player2: joystick2 button 3 or numpad '3'

Show Map or Cancel Reading:
  Player1: joystick1 button 4 or 'M'
  Player2: joystick2 button 4 or numpad '+'

Select Item/Weapon:
  Player1: joystick1 button 9 (on Gravis GamePad Pro 'Select') or 'Q'
  Player2: joystick2 button 9 or numpad ','

Pause:
  Player1: joystick1 button 10 (on Gravis GamePad Pro 'Start') or 'P'
  Player2: joystick2 button 10 or numpad '0'

Switch To Chat Field:
  joystick button 5 or TAB

The buttons can be changed in the controls option window
(in the game press F1 then click on 'Controls')

---------------
Special Actions
---------------

Laying Items:
  Select Item: hold Attack Button (S) + press Action Button (A)
  Lay Item: Action Buton (A)

Switching Between Fullscreen And Window mode:
  Alt + Enter/Return

Screenshots (whole level/current screen):
  Alt + 1 / Alt + 2

Turning minimap on/off:
  Alt + 3

Show bytes pers second sent by the server:
  Alt + 4

Making a snapshot of the current level:
  Alt + 5

Starting recording the player movements:
  Alt + 6

Stop recording and save it to levels/recordpos.txt:
  Alt + 7

Zoom in:
  Alt + 8

Zoom out:
  Alt+9

Show an emotion icon:
  Ctrl+A/B/C/D/E/F/G/H/K/L/M/O/P/R/S/T/W/X/Y/Z

Display player ratings:
  R

-------
The End
-------
