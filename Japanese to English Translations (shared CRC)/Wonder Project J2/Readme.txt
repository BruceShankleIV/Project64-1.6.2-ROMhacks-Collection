****************************************************
* Wonder Project J 2 (N64) Translation Version 1.0 *
*           japanese -> english                    *
****************************************************

This patch is freeware, you may redistribute it
as long as it is accompanied by this readme.
Please don't distribute ROMs where this patch is
already applied, thank you.


This document is best viewed with a fixed width
font such as Fixedsys.



-----------------------------------------------------
 0. Contents
-----------------------------------------------------

 1. Version History
 2. Installation
 3. Emulation
 4. Project 64 ROM Database Entry
 5. Known Issues
 6. Translation Notes
 7. Credits



-----------------------------------------------------
 1. Version History
-----------------------------------------------------

 12.15.2007 - Second Release V1.0

 What has been done:
 Everything with the exception of a few graphics
 is translated.


 01.21.2007 - First Release V0.1

 What has been done:
 The beginning of the game is completely translated.
 Your first, second and third tour around the two
 islands should be in english.
 You can work as a waitress and as a flyer handler.


-----------------------------------------------------
 2. Installation
-----------------------------------------------------

 Use an IPS patcher like LunarIPS to apply the patch.

 It should go without saying, but use the z64 patch
 if you have the z64 version of the ROM, use the
 v64 patch if your ROM is in the v64 format.


 The z64 patch has to be applied to this ROM:

 Good Name: Wonder Project J2 (J) [!].z64
 File Size: 8388608 Bytes
 CRC32: 5E8FC436


 The v64 patch has to be applied to this ROM:

 Good Name: Wonder Project J2 (J) [!].v64
 File Size: 8388608 Bytes
 CRC32: 8AAF74A3


 Once you've applied the patch, the ROMs should
 have the following specs:

 z64 ROM
 File Size: 8912896 Bytes
 CRC32: E1094E29

 v64 ROM
 File Size: 8912896 Bytes
 CRC32: 38401DDB



-----------------------------------------------------
 4. Emulation
-----------------------------------------------------

 Even though it's one of the oldest N64 games,
 Wonder Project J 2 isn't supported as well as one
 might think by N64 emulators.
 It runs on the following emulators to varying
 degrees. Emulators not mentioned here either don't
 run it or I haven't tested them.


 Nemu64:
 ~~~~~~~
 The best emulator for the game, period.
 It runs it out of the box, no special configuration
 needed, no crashes, clean sound, just don't use
 Nemu's own graphic plugin.
 If your system supports this emu, use it.
 You need to take some caution when using a digital
 only input devices, though.
 If you're using a gamepad that doesn't have an
 analog stick, it's recommended to set the cursor
 speed in the game to slow.
 And keyboard users have to take note that the
 default range of the 4 direction buttons is
 something like 60%. In certain situations you need
 100% range, pressing Control plus a direction
 button will get you these 100%.


 Mupen64:
 ~~~~~~~~
 Before you can even run the translated ROM with this
 emulator you need to make a new entry in your ROM
 database file, scroll down to point 4 in this readme
 for the details.
 Once you did that you will get very solid emulation.
 But there are two points in the game where the
 emulator might crash. The first crash can be bypassed,
 the second unfortunately not.
 The first crash occurs right in the intro after you
 read that letter. To bypass this one, simply start
 your game by making a new entry in the diary. Once it
 crashes reboot and load your save, you will resume
 where you left off.
 The second crash occurs during the rather lengthy
 ending of the game, also after a letter. You can beat
 the game, but you won't see the whole ending if the
 crash occurs. Either start playing with Nemu right
 away, or switch to it once you get there.
 Furthermore I recommend using Jabo's DirectInput
 plugin. You can use NRage's Input Plugin as well,
 but the emulator will crash whenever you stop the
 emulation. Also, you will get the best sound when
 using Azimer's HLE Audio v0.56 WIP2 plugin.


 Project64:
 ~~~~~~~~
 Just as with Mupen, you need to make a new entry in
 your ROM database file or else the translated ROM
 won't run with this emulator, scroll down to point 4
 in this readme for the details.
 You will also face the two same possible crashes as
 with Mupen, so read the entry above.
 This emulator is rather picky when it comes to plugins.
 From my experience you will only get good sound out of
 it if you use the following graphic/sound plugin
 combination: Jabo's Direct3D Plugin plus Jabo's Direct
 Sound Plugin. Every other combination will get you
 crackling or other similar issues.


 1964:
 ~~~~~
 I have yet to fully test the game with 1964.
 Regardless of the combination I have tested,
 I didn't manage to get perfect sound out of 1964.
 At least one reason to avoid this emulator.
 If you really have to use 1964, I recommend using
 version 0.8.3 and 0.8.5, not 0.9.9.
 With 0.9.9 you'll get the same crashes as with Mupen
 and PJ64 plus lots of random ones.
 With the other two versions I mentioned you'll "only"
 experience a random crash here and there.




 And now on to the graphic plugins. Your choice here
 is almost as important as the emulator itself.


 Rice's Video Plugin:
 ~~~~~~~~~~~~~~~~~~~~
 My personal favorite.
 It's the only plugin where the face close ups don't
 break up and it's the only plugin that doesn't filter
 the graphics, resulting in almost pixel perfect results.
 You have to do some configuring, though.
 In its standard settings the plugin will filter text
 that's getting close to the right border of the screen,
 which looks really odd.
 To turn this effect off, load up the configuration
 window. Set render engine to DirectX, uncheck
 "Hide Advanced Options", then head to the
 "Texture Filters" tab and change the
 "Force Texture Filter" option to "Force Nearest Filter".
 Also, when using this plugin you might get a problem
 with the view in the last 3D sequence of the game,
 switch to another graphic plugin for this scene if it's
 bothering you.


 Jabo's D3D 8 Plugin:
 ~~~~~~~~~~~~~~~~~~~~
 The graphics don't look that great with this plugin.
 But choosing this one will give you the least problems
 overall.
 If you're under Windows 98, you might want to use
 Jabo's D3D 6 Plugin, it's almost the same.
 I don't think these 2 plugins can be downloaded
 seperately, but they are included in Project64
 releases.


 Direct64:
 ~~~~~~~~~
 Results with this plugin are very similar to
 the ones you get with Jabo's Plugins.
 Just a tad cleaner.
 There's only one real negative aspect here,
 it can get really annoying when using this plugin
 in Nemu64 and playing in window mode.
 No issues with the fullscreen mode, though.


 Glide64:
 ~~~~~~~~
 Almost the same as Jabo's Plugin, but resizing here
 looks a bit ugly. Jabo's isn't already perfect when
 it comes to resizing WPJ2's graphics, but this here
 is even worse.


 Nemu64 Graphics:
 ~~~~~~~~~~~~~~~~
 Has various clipping problems and doesn't render
 the text properly.
 Not recommended!


 glN64:
 ~~~~~~
 Very similar to Nemu64's own plugin, but it also
 causes the game to hang in the intro.
 Not recommended!


 Rice's Daedalus:
 ~~~~~~~~~~~~~~~~
 Huge problems with the 3D graphics and horrible
 text rendering.
 Unplayable!


-----------------------------------------------------
 4. Project 64 ROM Database Entry
-----------------------------------------------------

 Open up the file "Project64.rdb" with a text editor
 and add the following lines somewhere in there:

[4F1E88F7-4A5A3F96-C:4A]
Good Name=Wonder Project J2 (T-Eng)
Internal Name=WONDER PROJECT J2 T-Eng
RDRAM Size=4
Counter Factor=Default
Save Type=First Save Type
CPU Type=Recompiler
Self-modifying code Method=Default
Use TLB=Yes
Linking=On
Reg Cache=On
Use Large Buffer=Yes
Status=Compatible
Delay SI=No
Audio Signal=No
SP Hack=No
Core Note=
Plugin Note=


-----------------------------------------------------
 5. Known Issues
-----------------------------------------------------

 The controller pak management screen that is accessed
 by pressing "Start" during the boot process is not
 translated and probably somewhat broken as well.
 Just use another game to manage your controller paks.

 In main menu, when switching back and forth between
 the two name input screens several times, the game
 might hang. No major problem, you should manage to
 input your name in one go I think.

 When deleting a diary in the main menu, the name
 you've chosen for Josette might not be displayed
 correctly.

 I'm not aware of any other issues, if you find any
 serious ones I wouldn't mind it if you report them.


-----------------------------------------------------
 6. Translation Notes
-----------------------------------------------------

 There is quite a lot I would like to write about,
 but I won't. The patch is ready and I don't want to
 delay it any further.
 Writing this passage would take me a considerable
 amount of time, time that I don't want to spend
 right now.
 The stuff I planned to write here would probably
 boring to most anyway.

 There is just one thing I'd like to mention, a part
 I didn't understand myself for a long time, that
 should probably be explained: In the game you
 might see the name "Daijinma". This is most likely
 a reference to a rather famous japanese movie
 creature named Daimajin. Use your favorite search
 engine to learn more.


-----------------------------------------------------
 7. Credits
-----------------------------------------------------

 So, who's been working on this patch:

 Ryu - That's me. I did the hacking and the
       translation. If you need to contact me for
       some reason use ryu@seiyuu.info.

 Mark Datysgeld - The man responsible for the script
                  editing.

 Garret Greenwood - Proofreading and testing. He also
                    adapted a hard to translate joke.

 CZroe - He tested the translation on a real N64.

 satsu - He helped translating a short text passage.


------------------------------------------------------

The project's homepage is http://www.seiyuu.info/wpj2
Refer to that site for any possible future releases.


