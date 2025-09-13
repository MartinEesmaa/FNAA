# FNAA

Five Nights at Arnold's - Fan based game mod by Martin Eesmaa

## Requirements

You need to mod or/and develop the fan mod game by

- Latest version copy of Five Nights at Freddy's (v1.132)
- Clickteam Fusion 2.5 (paid developer for executable applications, free only for HTML5 export) 
- Perspective.mfx extension module installed
- HDiffPatch
- Original MFA source project file

## Run the game

Ensure you have original Five Nights at Freddy's for Windows executable version and make sure MD5 checksum is matched of v1.132:

```
MD5: d926fee3666c1c854a475a9766ad7ff7
```

Link of [archive.org](https://archive.org/details/five_nights_at_freddys_windows) for Windows version

Reminder: If you love the game, please consider support, purchase the game or/and donate to Scott Cawthon for his hard work.

If the file is identical, then it is ready to go. 

Otherwise, if the file is different. It may be:

- Wrong version/copy or different checksum
- Size is too small
- Disk space full

Please try again and if the problem persists, please feel free to create an issue.

[Link of releases](https://github.com/MartinEesmaa/FNAA/releases) contains prezipped executable file with encrypted passphrase and patch diff file from original FNAF game of Windows version for update mod.

The password of zipped file is: `heyarnold-MartinEesmaa`.

Diff patch file can be applied from original FNAF game to modded game:

```
hpatchz "Five Nights at Freddy's.exe" FNAA-MartinEesmaa-Windows.diff FNAA-MartinEesmaa.exe
```

## Source project

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