# FNAA

Five Nights at Arnold's - Fan based game mod by Martin Eesmaa

## Requirements

You need to mod or/and develop the fan mod game by

- Clickteam Fusion 2.5 (paid developer for executable applications, free only for HTML5 export) 
- Perspective.mfx extension module installed
- HDiffPatch
- Original MFA source project file

## Installation

Please grab a free edition copy of Clickteam Fusion 2.5 on Steam.

Also original MFA source file and HDiffPatch needs to be downloaded:

https://mega.nz/folder/nhMWkbqT#kizq4xCzbipP1EDqgY2qMQ

https://github.com/sisong/HDiffPatch/releases

If you want to distribute exporting to applications, it is a expensive to pay, but you can find on Internet Archive that has available for Clickteam Fusion 2.5 Developer Edition.

Once you have installed Clickteam Fusion 2.5 on your PC, copy Perspective.mfx from [extension](extension) folder into Clickteam Fusion 2.5 files.

Example path:

```
C:\Program Files\Clickteam Fusion Developer 2.5\Extensions\Unicode\
```

Patch the file by applying mod modified changes:

```
hpatchz FiveNights-55-original.mfa FNAA-MartinEesmaa.diff FNAA-MartinEesmaa.mfa
```

After that, run the developer or free edition of Clickteam Fusion 2.5 application and go File->Open... (open MFA file).

## Patches mod

Patches are available on [mod](mod) folder with diff files.

Diff files can copy differ between original and modded diff file into complete source project file (.MFA) used by Clickteam Fusion 2.5.

- Martin Eesmaa