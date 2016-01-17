uae4all2_AmigaPi
Amiga Emulator that can be started automatically.

Usage: uae4all2 gamefile.conf

gamefile.conf = configuration game file.

If gamefile.conf is present at startup the emulator reads the conf file and
loads the floppies df0-df3 then starts the emulation automatically.

If emulation is running floppies can be swapped using the keyboard.
Press and hold "Esc" then press F1-F4 to swap floppy of DF0-DF3 into DF0.
If emulation is running pressing F12 compeletely exits the Amiga Emulator.

If the game config files are set up correctly there should be no need to use
the gui of the emulator.
With this its possible to completely bypass the gui and use the emulator with
e.g. Emulation-Station.

==========================================
 ORIGINAL README
==========================================
Uae4all2
A fast and optimized Amiga Emulator

Features: AGA/OCS/ECS, 68020 and 68000 emulation, harddisk-support, WHDLoad-support, Chip/Slow/Fast-mem settings, savestates, vsync, most games run fullspeed

Authors:
Chui, john4p, TomB, notaz, Bernd Schneider, Toni Wilen, Pickle, smoku, AnotherGuest, Anonymous engineer, finkel, Lubomyr, pelya
android port by Lubomyr, android libSDL by pelya 

Android-port info

On-screen scheme

4 3 ( YX)
2 1 ( BA)

'1'- <Button A> autofire [HOME]
'2'- <Button B> Right mouse click [END]
'3'- <Button X> joystick fire/left click [PAGEDOWN]
'4'- <Button Y> [PAGEUP]
'5' <Button L> [SDLK_F13]
'6' <Button R> [SDLK_RCTRL]
old textUI vkeybd - '2'+'4'
 
SDL keycode action:
F15 textUI vkeybd
F12 - emulator menu toggle 
F11 - change input method

Please put kickstarts files in android/data/pandora.uae4all.sdl/kickstarts directory.
Files must be named as kick13.rom kick20.rom kick31.rom
