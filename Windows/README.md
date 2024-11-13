
# Keyboard Layouts for Windows:

 * [English (Phonemic)](Phonemic/README.md) - for writing in phonemic English using traditional IPA notation
 * [Writer (QWERTY)](Writer/README.md) - standard QWERTY with extra symbols on AltGr and AltGr+Shift layers
 * [Writer+ (QWERTY)](Writer+/README.md) - similar Writer(QWERTY) but with extra IPA symbols on AltGr and AltGr+Shift layers
 * [Writer+ (ASERTH)](WriterASERTH/README.md) - Writer+ with most frequently used letters on the home row (QWERTY-flip-twist)
 * [Shavian (QWERTY)](ShavianQWERTY/README.md) - standard Shavian(QWERTY) layout
 * [Shavian+ (QWERTY)](ShavianQWERTY+/README.md) - Shavian(QWERTY) with extra symbols on AltGr and AltGr+Shift layers
 * [Shavian (Imperial)](ShavianImperial/README.md) - slightly modified layout of the **Model 6** Shavian typewriter


#### Example screenshots (Phonemic layout):

![](Phonemic/img/1-unshifted.png)
![](Phonemic/img/2-shifted.png)

#### Download

To download pre-compiled binaries go to resources section of this project.

----- 

## How to compile .klc files

If you'd like to modify the layout you want to use so it better suits your needs, download the KLC file and follow the steps below to compile and install:

1. Download the `.klc` file of your choice from this repository
2. Download MSKLC v1.4 (Microsoft Keyboard Layout Creator version 1.4) from Microsoft website:
    - [Description & download](https://www.microsoft.com/en-us/download/details.aspx?id=102134)
    - [Direct link to binaries](https://download.microsoft.com/download/6/f/5/6f5ce43a-e892-4fd1-b9a6-1a0cbb64e6e2/MSKLC.exe>)
3. Install MSKLC on your PC
4. Open the `.klc` file in MSKLC
5. Build binaries `Project › Build DLL and Setup Package`

![Building Layout](./MSKLC.png "Building Keyboard Layout with MSKLC")

-----

## Installation and configuration

When compilation of the KLC file is complete, simply open the binaries folder and run `setup.exe` to install.

### Configuration steps:

1. Open Windows Setup (WinKey + I)
2. Go to `Time & Language`
3. Select `Language`
4. At the bottom of the screen click on `English (United States)` — the `Options` button will appear, click it
5. At the bottom you should see a list of keyboard layouts
    - if there is only `US QWERTY`, then click `Add a keyboard` and install additional layout
6. Go back to `Settings › Language`
7. Click on `Keyboard`
    - you may select your favorite layout as a default keyboard
	- you may set a different input method for each app window
8. Click on `Language bar options`
    - recommended: on `Language Bar` tab select `Docked in the taskbar`
9. On `Advanced Key Settings` you may:
    - set up a hotkey for switching languages/layouts (default is `Left Alt+Shift`
	- assign hotkeys to switch directly to your favorite layout
	- remember: if you leave it unchanged the default switch to `English (United States) QWERTY` is **Ctr+1**
	- remember: second default hotkey for switching languages/layouts (aka “input methods”) is **WinKey+Space**
10. You may need to reboot Windows to see the Language Bar next to the system clock icon — in this respect Windows is waaaaaaay behind Linux.

-----

## On-Screen Keyboards

When learning new keyboard layout it may be helpful to use an On-Screen Keyboard.

Microsoft Windows provides two On‑Screen Keyboards:

 * Old **OSK.exe** (`c:\Windows\System32\osk.exe`) — to start, press `WinKey+Ctrl+O`
 * New **TabTip.exe** (`c:\Program Files\Common Files\microsoft shared\ink\TabTip.exe`) - TabTip stands for **Tab**let **T**ext **I**nput **P**anel — part of the Inking feature (WinKey+I › Devices › Pen & Windows Ink)

To start either one:

 * osk.exe — `WinKey+Ctrl+o`
 * tabtip.exe — right‑click system clock, select `Show touch keyboard button`. Click the keyboard button.

Please note: **NONE of these supports Unicode**, so instead of Shavian symbols you'll see blank rectangles.

The only layout from this project that semi‑works with OSK.exe is the **English (Phonemic)** — but only in the *Unshifted* and *Shifted* layers.

Alternatives you may find on the Internet:

* [Free Virtual keyboard](https://freevirtualkeyboard.com/) — available as portable and as installer, but doesn't allow to change font, so Shavian is displayed as blocks.
* On-Screen Keyboard Portable from PortableApps.com — not really portable (installer). It is only a launcher for native Windows OSK.exe. Don't even bother.
* [Keyman](https://keyman.com/) — nice but takes over 200MB of space.


-----
Copyright (c) 2024 Neil Raiden (AGPL v3)
