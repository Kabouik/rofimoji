# ⮆ [Project migrated to teknik.io](https://git.teknik.io/matf/rofimoji) ⮄

### rofimoji (an emoji picker for rofi) with unicode search

This repository is a fork of [rofimoji by fdw](https://github.com/fdw/rofimoji) with the addition of unicode characters from [/u/fe80c0ffee](https://www.reddit.com/r/unixporn/comments/7zqkov/oc_i_mad_a_rofi_emoji_picker_and_i_feel_bad_about/duqls53?utm_source=share&utm_medium=web2x). Unicode characters are sorted to be shown first when invoking rofimoji. A .txt file with Awesome font from [/u/Delearyus](https://www.reddit.com/r/unixporn/comments/7zqkov/oc_i_mad_a_rofi_emoji_picker_and_i_feel_bad_about/duvrlla?utm_source=share&utm_medium=web2x) is supplied too, but not included in rofimoji by default.

[![Screenshot of rofimoji-fork](https://git.teknik.io/matf/rofimoji/media/branch/master/screenshot-fork.png?raw=true/media/branch/master/screenshot-fork.png?raw=true)](https://git.teknik.io/matf/rofimoji)

The theme used in the above screenshot is *sidebar by qball*, which can be selected as default using `rofi-theme-selector` in terminal.

### Alternative with rofi scripts: rofiemoji-rofiunicode (preferred)

Inspired by [nkoehring/rofiemoji](https://github.com/nkoehring/rofiemoji), the rofi script version of the above emoji-unicode-picker, [**matf/rofiemoji-rofiunicode**](https://git.teknik.io/matf/rofiemoji-rofiunicode) is the combination of two rofi scripts to search emojis or unicode characters directly in rofi. Unicode characters and emojis show up as separate tabs when rofi is invoked. [rofiemoji-rofiunicode](https://git.teknik.io/matf//rofiemoji-rofiunicode) does not allow multiple selection and requires using the clipboard, but the window can be customized further and it offers a solution unified with regular rofi. This is the version I use and therefore it is more likely to be updated.

![rofiemoji-rofiunicode](https://git.teknik.io/matf/rofiemoji-rofiunicode/media/branch/master/unicode.png?raw=true/media/branch/master/screenshot-fork.png?raw=true)
