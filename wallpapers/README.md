# Wallpapers

Here are several wallpapers for quick reference — might be helpful for beginners learning new keyboard layout.

| Keyboard Layout | 1366x768 | 1920x1080 |
|:----------------|:--------:|:---------:|
| English (Phonemic) | [1366x768](1366x768/EnglishPhonemic-full_1366x768.png) | [1920x1080](1920x1080/EnglishPhonemic_1920x1080.png) |
| Shavian (Imperial) | [1366x768](1366x768/ShavianImperial-full_1366x768.png) | [1920x1080](1920x1080/ShavianImperial_1920x1080.png) |
| Shavian+ (QWERTY)  | [1366x768](1366x768/ShavianQWERTY-full_1366x768.png)   | [1920x1080](1920x1080/ShavianQWERTY_1920x1080.png)   |
| Writer+ (ASERTH)   | [1366x768](1366x768/WriterASERTH-full_1366x768.png)    | [1920x1080](1920x1080/WriterASERTH_1920x1080.png)    |
| Writer+ (QWERTY)   | [1366x768](1366x768/WriterPlus-altgr_1366x768.png)     | [1920x1080](1920x1080/WriterPlus_1920x1080.png)      |
| Writer (QWERTY)    | [1366x768](1366x768/WriterQWERTY-altgr_1366x768.png)   | [1920x1080](1920x1080/WriterQWERTY_1920x1080.png)    |

### How to use it

* Set any of the above as your desktop wallpaper
* You may need to move your desktop icons away
* When typing, a quick **Win+D** will show your desktop
* Another **Win+D** should restore your app (at least on Linux)

### Customizing wallpapers

These wallpapers were created in a very crude way (_unfortunately ImageMagick renders text in 72dpi then converts the image to font size, eg 12dpi, making the image blurry_), by following steps:

1. Open a terminal emulator that allows switching to full screen with **F11** (for example [GNOME Terminal](https://wiki.gnome.org/Apps/Terminal))
2. Goto Preferences or Settings and adjust font size, background color, disable scroll bar and blinking cursor, etc
3. Open a text file in VIM
4. Switch to full screen with **F11**
5. Take a screenshot

#### Customizing colors

For colors edit one of the `vimrc` files (or create your own) using the `highlight` and `syntax match`.

For example `vrcASERTH`:
```
highlight punctuations cterm=bold ctermfg=cyan
syntax match punctuations "[§©®℗°±´·«»×÷ˈˌ‐‑–—‘’“”•…‹›⁃←↑→↓√≈≠⋯⌜⌝⌞⌟○◦☐☑☒☺⟨⟩⟮⟯ː¢⁰₀´¹¹₁²₂³₃⁴₄⁵₅⁶₆⁷₇⁸₈⁹₉æɑɒðʤəɛɜɪɫŋɔʃ™ʧʊʌʍʒθµπ]"

highlight asertold cterm=bold ctermfg=blue
syntax match asertold " [ertniERTNI] "

highlight asertnew cterm=bold ctermfg=red
syntax match asertnew " [dfgjkDFGJK] "

highlight asertrotate cterm=bold ctermfg=magenta
syntax match asertrotate " [pol;POL:] "

set nonumber
set textwidth=0
```

Then start VIM with the `-u custom_vimrc` option, for example:
```
vim -u vrcASERT WriterPlusASERTH-full.txt
```

-----
Copyright © 2024 by Neil Raiden (AGPL v3)








