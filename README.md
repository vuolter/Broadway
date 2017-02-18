<p align="center">
<img src="/media/1.bmp" /> <img src="/media/2.bmp" /> <img src="/media/3.bmp" />
<br>
<img src="/media/4.bmp" /> <img src="/media/5.bmp" /> <img src="/media/6.bmp" />
<br>
<img src="/media/7.bmp" /> <img src="/media/8.bmp" /> <img src="/media/9.bmp" />
</p>

Broadway
========

[![Rockbox](https://img.shields.io/badge/Rockbox-3.13-ff69b4.svg?style=flat-square)](http://www.rockbox.org/)
[![Rockbox checkwps](https://img.shields.io/badge/build-passing-brightgreen.svg?style=flat-square)](http://themes.rockbox.org/index.php?themeid=2500&target=sansaclipzip)
[![GitHub release](https://img.shields.io/github/release/vuolter/Broadway.svg?style=flat-square)](https://github.com/vuolter/Broadway/releases/latest)
[![GitHub releases](https://img.shields.io/github/downloads/vuolter/Broadway/latest/total.svg?style=flat-square)](https://github.com/vuolter/Broadway/releases/latest)
[![GitHub issues](https://img.shields.io/github/issues/vuolter/Broadway.svg?style=flat-square)](https://github.com/vuolter/Broadway/issues)
[![License](https://img.shields.io/badge/license-CC%20BY--SA%203.0-blue.svg?style=flat-square)](/LICENSE.md)
[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/WalterPurcaro.svg?style=social)](https://twitter.com/intent/tweet?text=Wow:&url=%5Bobject%20Object%5D)
[![GitHub stars](https://img.shields.io/github/stars/vuolter/Broadway.svg?style=flat-square)](https://github.com/vuolter/Broadway/stargazers)

An impressive theme for [Rockbox](http://www.rockbox.org/),
designed for the **SanDisk Sansa Clip Zip** device, like [Ekaran]
(http://themes.rockbox.org/index.php?themeid=1762&target=sansaclipzip),
but with *few* **extra**...

- Clean and neat source-code rewritten according the latest Rockbox
specifications
- Improved FM Radio Screen and While Playing Screen
- Fully customizationd theme skin featuring brand new menu screens *(menu, recording
screen, time & date screen)*
- New multi-tool status bar
- New big volume bar with audio level and gain indicator
- New song bar with current *Now Playing* track title
- Volume level **in percentage**
- Radio signal strength **in percentage**
- Progress bar set color and behaviour **according the active screen and
playback mode**
- Refreshed icon pack
- New battery screen with **real charging animation** and estimated battery time
left indicator
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
- Charge indicator blinks if connected charger is not charging and warns if low
battery, reporting estimated time left
- Detailed track info in While Playing Screen *(playlist position, more album
info. next track title)*
- *Next track* info in While Playing Screen
- Recording support in FM Radio Screen
- **Custom color support** *(see to the [Customization section](#customization))*
- Fully text translated
- Right-To-Left languages support
- No more bulky title on screen
- **A lot of theme issues now fixed!**


Table of contents
-----------------

- [Installation](#installation)
- [Troubleshooting](#troubleshooting)
- [Notice](#notice)
- [Customization](#customization)
- [Palette](#palette)
- [Licensing](#licensing)


Installation
------------

Take the *Blue pill* or take the *Red pill*:

- **Blue pill:** Use the official [Rockbox Utility]
(http://www.rockbox.org/wiki/RockboxUtility#Download) to automatically download
& install the theme, the story ends.
- **Red pill:** Manually download the [latest released package]
(https://github.com/vuolter/Broadway/releases), unzip it to the root directory
of your device and see how deep the rabbit hole
goes.

> **Note:**
> If you choose the *Red pill*,
> make sure the files of the `.rockbox` directory was copied to the **same
> directory** on your device.

> **Note:**
> **If you clone (or download) this repository DO NOT copy its files directly in
> your device!**
> Look at the [Customization section](#customization) to learn how finalize them
> to correctly install a *customized* theme.


Troubleshooting
---------------

If the screen glitches after enabling the theme in the settings menu, just
restart the device and everything will be fine.


Notice
------

The color tonality of the theme skin you can see in the screenshots may result
*slightly* different on the device screen, due of the display technology of the
device itself.


Customization
-------------

You can change the colors of the theme skin in this way:

1. Clone (or download) the master branch of this repository.
2. Open with a text-editor the following files: `Broadway.sbs`, `Broadway.wps`,
`Broadway.fms`, `Broadway.cfg`.
3. *Replace all* the color **ID codes** with the **HEX codes** you prefer
*([few examples](http://www.color-hex.com/color-palettes/))*.
4. You must replace **all** the *ID codes* you found in these files
**otherwise the theme will not work**!

Description                            | ID code
-------------------------------------- |--------------
Background                             | !P000!
Foreground                             | !P001!
Status bar                             | !P002!
Status low battery                     | !P003!
Status fully charged                   | !P004!
Status recording                       | !P005!
Volume bar                             | !P006!
Volume mute                            | !P007!
Volume level                           | !P008!
Volume gain                            | !P009!
Song bar                               | !P010!
Browser screens foreground             | !P011!
Context screens foreground             | !P012!
Menu items [selected][unselected]      | !P013! !S013!
Sub-menu items [selected][unselected]  | !P014! !S014!
WPS song title                         | !P015!
WPS song artist                        | !P016!
WPS album title                        | !P017!
WPS playlist status [position][time]   | !P018! !S018!
WPS indicators                         | !P019!
WPS progress bar                       | !P020!
Recording screen foreground            | !P021!
FMS current frequency [playing][muted] | !P022! !S022!
FMS RDS name                           | !P023!
FMS RDS text                           | !P024!
FMS scan/preset text [preset][scan]    | !P025! !S025!
FMS indicators                         | !P026! !S026!
FMS progress bar [regular][recording]  | !P027! !S027!
Quick screen foreground                | !P028!
Pitch screen foreground                | !P029!
Time and Date screen foreground        | !P030!
Battery screen foreground              | !P031!
Battery screen charging                | !P032!
Battery screen fully charged           | !P033!

> **Note:**
> _**P** = Primary color_; _**S** = Secondary color_.


Palette
-------

> **Note:**
> Revised palette of the theme skin
> [Clyp-E](http://themes.rockbox.org/index.php?themeid=2259&target=sansaclipzip).

Description                            | HEX code      | *ID code*
-------------------------------------- | ------------- | ---------------
Background                             | 000000        | *!P000!*
Foreground                             | 08E3E7        | *!P001!*
Status bar                             | FFE708        | *!P002!*
Status low battery                     | FF0820        | *!P003!*
Status fully charged                   | 20FF08        | *!P004!*
Status recording                       | FF0820        | *!P005!*
Volume bar                             | B606B3        | *!P006!*
Volume mute                            | FFE708        | *!P007!*
Volume level                           | FFE708        | *!P008!*
Volume gain                            | 0CF2F7        | *!P009!*
Song bar                               | 0CF2F7        | *!P010!*
Browser screens foreground             | 08E3E7        | *!P011!*
Context screens foreground             | FFE708        | *!P012!*
Menu items [selected][unselected]      | FFE708 08E3E7 | *!P013! !S013!*
Sub-menu items [selected][unselected]  | FFE708 08E3E7 | *!P014! !S014!*
WPS song title                         | FFE708        | *!P015!*
WPS song artist                        | 08E3E7        | *!P016!*
WPS album title                        | 0CF2F7        | *!P017!*
WPS playlist status [position][time]   | FFE708 08E3E7 | *!P018! !S018!*
WPS indicators                         | 08E3E7        | *!P019!*
WPS progress bar                       | FFE708        | *!P020!*
Recording screen foreground            | FFE708        | *!P021!*
FMS current frequency [playing][muted] | FFE708 08E3E7 | *!P022! !S022!*
FMS RDS name                           | 08E3E7        | *!P023!*
FMS RDS text                           | 0CF2F7        | *!P024!*
FMS scan/preset text [preset][scan]    | FFE708 08E3E7 | *!P025! !S025!*
FMS indicators                         | 08E3E7 FFE708 | *!P026! !S026!*
FMS progress bar [regular][recording]  | 08E3E7 FF0820 | *!P027! !S027!*
Quick screen foreground                | FFE708        | *!P028!*
Pitch screen foreground                | FFE708        | *!P029!*
Time and Date screen foreground        | FFE708        | *!P030!*
Battery screen foreground              | 08E3E7        | *!P031!*
Battery screen charging                | 08E3E7        | *!P032!*
Battery screen fully charged           | FFE708        | *!P033!*


Licensing
---------

Please refer to the
[![Creative Commons Attribution-ShareAlike 3.0 Unported License]
(https://licensebuttons.net/l/by-sa/3.0/80x15.png)](/LICENSE.md) for the
extended license.


---------------------------------
###### © 2016-2017 Walter Purcaro
