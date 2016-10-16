Broadway
========

<p align="center">
<img src="/media/1.bmp" /> <img src="/media/2.bmp" /> <img src="/media/3.bmp" />
<br>
<img src="/media/4.bmp" /> <img src="/media/5.bmp" /> <img src="/media/6.bmp" />
<br>
<img src="/media/7.bmp" /> <img src="/media/8.bmp" /> <img src="/media/9.bmp" />
</p>

An impressive theme for [Rockbox](http://www.rockbox.org/),
designed for the **SanDisk Sansa Clip Zip** device,
like [Ekaran](http://themes.rockbox.org/index.php?themeid=1762&target=sansaclipzip), but with *few* **extra**...

 - Clean and neat source-code rewritten according the latest Rockbox specifications
 - Improved FM Radio Screen and While Playing Screen
 - Fully customized skin featuring brand new menu screens *(menu, recording screen, time & date screen)*
 - New multi-info status bar
 - New big volume bar with audio level and gain indicator
 - New song bar with current *Now Playing* track title
 - Volume level **in percentage**
 - Radio signal strength **in percentage**
 - Progress bar now set color and behaviour **according the active screen and playback mode**
 - Refreshed icon pack
 - New battery screen with **real charging animation**
 - New equalizer indicator in While Playing Screen
 - New repeat mode indicator in While Playing Screen
 - New crossfade indicator in While Playing Screen
 - New dithering indicator in While Playing Screen
 - New replaygain indicator in While Playing Screen
 - New audio channels indicator in FM Radio Screen
 - New audio recording indicator in FM Radio Screen
 - New signal strength indicator in FM Radio Screen
 - New charge indicator in status bar
 - New lock indicator in status bar
 - New sound recording indicator in status bar
 - Time clock supports now the 12 hour format
 - Charge indicator blinks if connected charger is not charging and warns if low battery, reporting estimated time left
 - Detailed track info in While Playing Screen *(playlist position, more album info. next track title)*
 - *Next track* support in While Playing Screen
 - Recording support in FM Radio Screen
 - **Custom color support**
 - Fully text translated
 - RTL languages support
 - No more ugly header titles on screen!
 - **A lot of display issues fixed now**


Table of contents
-----------------

 - [Installation](#installation)
 - [Troubleshooting](#troubleshooting)
 - [Notice](#notice)
 - [Customize](#customize)
 - [Palettes](#palettes)
   - [Broadway](#broadway)
   - [Crayola](#crayola)
   - [Lime](#lime)
   - [Scarlet](#scarlet)
 - [Licensing](#licensing)


Installation
------------

 - Use the official [Rockbox Utility](http://www.rockbox.org/wiki/RockboxUtility#Download) to automatically download & install the theme.
 - Manually download the [latest released package](https://github.com/vuolter/Broadway/releases) and unzip it to the root directory of your device.

> **Note:**
> If you choose the manual procedure,
> make sure the files of the `.rockbox` directory was copied to the **same directory** on your device.

> **Note:**
> **Don't install the files directly in your device if you clone or download the repository!**
> Look at the [Customize section](#customize) to learn how finalize them.


Troubleshooting
---------------

If the screen glitches after enabling the theme in the settings menu,
just restart the device and everything will be fine.


Notice
------

The color tonality of the theme skin you can see in the screenshots may result *slightly* different on the device screen,
due of the display technology of the device itself.


Customize
---------

You can change the colors of the theme skin in this way:
 1. Clone or download the master branch of the repository.
 2. Open the following files with a text-editor: `Broadway.sbs`, `Broadway.wps`, `Broadway.fms`, `Broadway.cfg`.
 3. *Replace all* the **default** color codes with the hex codes you want *([some examples](http://www.color-hex.com/color-palettes/))*.
 4. Again, you must replace **all** the codes in those files **or the theme will not work**!

> **Note:**
> Refer to the [Installation section](#installation) to see how install your theme manually.

### Default

Description                           | Codes
------------------------------------- | -------------
Background                            | !P000!
Foreground                            | !P001!
Status bar                            | !P002!
Status low battery                    | !P003!
Status fully charged                  | !P004!
Status recording                      | !P005!
Volume bar                            | !P006!
Volume mute                           | !P007!
Volume level                          | !P008!
Volume gain                           | !P009!
Song bar                              | !P010!
Browser screens foreground            | !P011!
Context screens foreground            | !P012!
Menu items [selected|unselected]      | !P013! !S013!
Sub-menu items [selected|unselected]  | !P014! !S014!
WPS song title                        | !P016!
WPS song artist                       | !P017!
WPS album title                       | !P018!
WPS playlist status [position|time]   | !P019! !S019!
WPS indicators                        | !P020!
WPS progress bar                      | !P021!
Recording screen foreground           | !P022!
FMS current frequency [playing|muted] | !P024! !S024!
FMS RDS name                          | !P025!
FMS RDS text                          | !P026!
FMS scan/preset text [preset|scan]    | !P027! !S027!
FMS indicators                        | !P028! !S028!
FMS progress bar [regular|recording]  | !P029! !S029!
Quick screen foreground               | !P030!
Pitch screen foreground               | !P031!
Time and Date screen foreground       | !P032!
Battery screen foreground             | !P033!
Battery screen charging               | !P034!
Battery screen fully charged          | !P035!

> **Note:**
> ***P** = Primary color; **S** = Secondary color*.

Palettes
--------

### Broadway

Description                           | Codes         | Default codes
------------------------------------- | ------------- | -------------
Background                            | 000000        | !P000!
Foreground                            | 08E3E7        | !P001!
Status bar                            | FFE708        | !P002!
Status low battery                    | FF0820        | !P003!
Status fully charged                  | 20FF08        | !P004!
Status recording                      | FF0820        | !P005!
Volume bar                            | B606B3        | !P006!
Volume mute                           | FFE708        | !P007!
Volume level                          | FFE708        | !P008!
Volume gain                           | 0CF2F7        | !P009!
Song bar                              | 08E3E7        | !P010!
Browser screens foreground            | 08E3E7        | !P011!
Context screens foreground            | FFE708        | !P012!
Menu items [selected|unselected]      | FFE708 08E3E7 | !P013! !S013!
Sub-menu items [selected|unselected]  | FFE708 08E3E7 | !P014! !S014!
WPS song title                        | FFE708        | !P016!
WPS song artist                       | 08E3E7        | !P017!
WPS album title                       | 0CF2F7        | !P018!
WPS playlist status [position|time]   | FFE708 08E3E7 | !P019! !S019!
WPS indicators                        | 08E3E7        | !P020!
WPS progress bar                      | FFE708        | !P021!
Recording screen foreground           | FFE708        | !P022!
FMS current frequency [playing|muted] | FFE708 08E3E7 | !P024! !S024!
FMS RDS name                          | 08E3E7        | !P025!
FMS RDS text                          | 0CF2F7        | !P026!
FMS scan/preset text [preset|scan]    | FFE708 08E3E7 | !P027! !S027!
FMS indicators                        | 08E3E7 FFE708 | !P028! !S028!
FMS progress bar [regular|recording]  | 08E3E7 FF0820 | !P029! !S029!
Quick screen foreground               | FFE708        | !P030!
Pitch screen foreground               | FFE708        | !P031!
Time and Date screen foreground       | FFE708        | !P032!
Battery screen foreground             | 08E3E7        | !P033!
Battery screen charging               | 08E3E7        | !P034!
Battery screen fully charged          | FFE708        | !P035!

> **Note:**
> Basically, this palette was inspired by the theme
> [Clyp-E](http://themes.rockbox.org/index.php?themeid=2259&target=sansaclipzip).

### Crayola

...

### Lime

...

### Scarlet

...


Licensing
---------

Please refer to the attached [![Creative Commons Attribution-ShareAlike 3.0 Unported License](https://licensebuttons.net/l/by-sa/3.0/80x15.png)](/LICENSE.md) for the extended license.


----------------------------
###### © 2016 Walter Purcaro
