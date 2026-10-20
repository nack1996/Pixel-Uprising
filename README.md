# Pixel-Uprising-0.1.0
Pixel Uprising is an unofficial, non-commercial fan-made engine that lets you play again a 2010 iOS game on Mac and Windows.

This item contains ONLY the engine. It does not include any graphics, music, sound effects, videos, texts or data from the original game. To play, you need your own copy of the original iOS game file (.ipa), version 1.4.5. The first time you open the app, drag the .ipa into its window: the app extracts the game's resources once, locally, and nothing is uploaded anywhere.

Files:
- Pixel Uprising-0.1.0-mac-AppleSilicon.zip: Mac with M1/M2/M3/M4 chips
- Pixel Uprising-0.1.0-mac-Intel.zip: Mac with Intel processors
- Pixel Uprising-0.1.0-win-portable.exe: Windows 10/11, single file
- Pixel Uprising-0.1.0-win-x64.zip: Windows 10/11, folder version

Not affiliated with, endorsed by or connected to the original developer, publisher, or any band, artist or brand that appears in the original game. Includes FFmpeg (GPL), used only to convert the original videos.

PIXEL UPRISING 0.1.0
====================

An unofficial, fan-made engine that lets you play again a 2010 iOS game on Mac and Windows.

This package contains ONLY the engine. It does not include any graphics, music, sound effects,
videos, texts or data from the original game. You need your own copy of the original game file.


WHAT YOU NEED
-------------
- The original iOS game file, version 1.4.5 (other versions are not supported), in .ipa format.
- macOS 12 or newer (Apple Silicon or Intel), or Windows 10/11 (64-bit).

The first time you open the app, drag the .ipa file into its window (or click to choose it).
The app reads the game's graphics, sounds and data from it and converts them once; after that,
the game starts directly. Nothing is uploaded anywhere: everything stays on your computer.


WHICH FILE TO DOWNLOAD
----------------------
Mac
- Mac/Pixel Uprising-0.1.0-mac-AppleSilicon.zip   for Macs with M1, M2, M3, M4... chips
- Mac/Pixel Uprising-0.1.0-mac-Intel.zip          for older Macs with Intel processors

Windows
- Windows/Pixel Uprising-0.1.0-win-portable.exe   single file, just run it
- Windows/Pixel Uprising-0.1.0-win-x64.zip        same app as a folder: unzip it and run "Pixel Uprising.exe"


FIRST LAUNCH
------------
The apps are not signed with a paid developer certificate, so the system asks for confirmation once:
- Mac: unzip, move "Pixel Uprising" to Applications, then right-click it > Open > Open.
  If macOS still blocks it: System Settings > Privacy & Security > "Open Anyway".
- Windows: if SmartScreen appears, click "More info" > "Run anyway".


CONTROLS
--------
Keyboard (all keys can be changed in Menu > Options > Keyboard)
  W A S D / arrows   move
  J / Space          attack, continue dialogue
  E / Enter          talk, enter doors
  R                  run on/off
  M                  map
  Q                  current mission
  Tab / Esc          menu, close windows

Mouse: click where you want to walk, click characters, doors, buttons and objects.
Game controllers (PlayStation, Xbox and compatible) are supported.

The on-screen attack, run and talk buttons can be made transparent or hidden
in Menu > Options > Buttons (set them to 0% to play with mouse and keyboard only).


SAVES
-----
- Mac:      ~/Library/Application Support/Pixel Uprising/save.json
- Windows:  %APPDATA%\Pixel Uprising\save.json
A backup copy (save.backup.json) is kept next to it. You can also export/import a save as text
from Menu > Options.


LEGAL
-----
This is a non-commercial fan project. It is not affiliated with, endorsed by or connected to the
original developer, publisher, or any band, artist or brand that appears in the original game.
All original content belongs to its respective owners and is NOT distributed here: the app only
reads the copy of the game provided by the user.

The app includes FFmpeg (https://ffmpeg.org), licensed under the GNU GPL, used only to convert
the original videos into a format the app can play. Electron and the other open-source
components keep their own licenses, included inside the app packages.
