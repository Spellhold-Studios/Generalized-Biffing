<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Spellhold-Studios/Spellhold-Studios.github.io/main/assets/images/shs-corner-logo.png" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Spellhold-Studios/Spellhold-Studios.github.io/main/assets/images/shs-corner-logo.png" />
  <img align="right" alt="SHS logo" src="https://raw.githubusercontent.com/Spellhold-Studios/Spellhold-Studios.github.io/main/assets/images/shs-corner-logo.png" width="22%">
</picture>

[![Release](https://img.shields.io/github/v/release/Spellhold-Studios/Generalized-Biffing?include_prereleases&color=%2392403a)](https://github.com/Spellhold-Studios/Generalized-Biffing/releases/latest)
[![Published](https://img.shields.io/github/release-date/Spellhold-Studios/Generalized-Biffing?display_date=published_at&label=published&color=%2392403a)](https://github.com/Spellhold-Studios/Generalized-Biffing/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Spellhold-Studios/Generalized-Biffing/total?color=%2392403a)](https://github.com/Spellhold-Studios/Generalized-Biffing/releases)
[![Views](https://badges.pufler.dev/visits/Spellhold-Studios/Generalized-Biffing?label=views&color=%2392403a)](https://github.com/Spellhold-Studios/Generalized-Biffing/releases)
<br>
[![Platform](https://img.shields.io/badge/platform-Windows%20%a0%20macOS%20%a0%20Linux%20%a0%20Project%20Infinity-%2392403a)](https://github.com/Spellhold-Studios/Generalized-Biffing/releases)
[![Language](https://img.shields.io/badge/language-en%20%a0%20fr%20%a0%20it%20%a0%20pl%20%a0%20pt--BR-%2392403a)](https://github.com/Spellhold-Studios/Generalized-Biffing/releases)
[![Games](https://img.shields.io/badge/games-BG1%20%a0%20BG2%20%a0%20BGT%20%a0%20BG%3AEE%20%a0%20SoD%20%a0%20BG2%3AEE%20%a0%20EET%20%a0%20IWD1%20%a0%20IWD2%20%a0%20IWD%3AEE%20%a0%20PST%20%a0%20PST%3AEE-%2392403a)](https://github.com/Spellhold-Studios/Generalized-Biffing/releases)

<!--
Badges white space separator: %20%a0%20
Badges ":" (colon) symbol: %3A
Badges "-" (hyphen) symbol: --
Games full list: BG1 BG2 BGT BG%3AEE SoD BG2%3AEE EET IWD1 IWD2 IWD%3AEE PST PST%3AEE
IETF language tags: https://spellhold-studios.github.io/readmes/template-basic/ietf-lang-tags.pdf
Why some badges update slowly: https://github.com/pujux/badge-it/issues/78
-->

# Generalized Biffing

*A Spellhold Studios tool for Infinity Engine games*

<br>

[<img alt="Download" src="https://raw.githubusercontent.com/Spellhold-Studios/Spellhold-Studios.github.io/main/assets/buttons/download.svg" height="28">](https://github.com/Spellhold-Studios/Generalized-Biffing/releases/latest)&nbsp;
[<img alt="Readme" src="https://raw.githubusercontent.com/Spellhold-Studios/Spellhold-Studios.github.io/main/assets/buttons/readme.svg" height="28">](https://spellhold-studios.github.io/readmes/generalized-biffing/generalized_biffing-readme-english.html)&nbsp;
[<img alt="Webpage" src="https://raw.githubusercontent.com/Spellhold-Studios/Spellhold-Studios.github.io/main/assets/buttons/webpage.svg" height="28">](https://spellhold-studios.github.io/)&nbsp;
[<img alt="Discord" src="https://raw.githubusercontent.com/Spellhold-Studios/Spellhold-Studios.github.io/main/assets/buttons/discord-blue.svg" height="28">](https://discord.gg/pE2Njbdb2a)

## Introduction

This WeiDU tool allows you to biff the content of the override folder for improved performance; that means the files are converted into the BIF file format and moved into the data folder. This works natively under OSX and Linux (if you use the correct executable) and is compatible with the common WeiDU stack un-install operation. The game thereby loads much faster again and the performance is running pretty smoothly without jerking.

<hr>

:spiral_notepad: **Note:** Recent user reports have indicated that Generalized Biffing is unnecessary for Enhanced Edition games.

<hr>

:warning: **Warning: As of WeiDU v247, some functions operating on the Latin-1 (8859-1) character set have been depracated and now use only US-ASCII characters. Biffing files with non-ASCII characters in their filenames may cause the game to crash.**

 It has been confirmed that the following mods may suffer from this issue if the affected files are biffed:

- **Infinity Animations (all versions 5.x.x and below)**

<br>

If you also want to install any of the above mods, please follow these steps before installing Generalized Biffing at the end of your mod install order: 

1. Remove all `setup-modname.exe` files from your game directory.
2. Download [Generalized Biffing v2.7](https://github.com/Spellhold-Studios/Generalized-Biffing/releases/tag/v2.7) (warning: this version does not support EEex).
3. Extract Generalized Biffing into the game directory, but don't install it.
4. Download [WeiDU v246](https://github.com/WeiDUorg/weidu/releases/tag/v246.00).
5. Rename `weidu.exe` from the v246 package to `setup-generalized_biffing.exe` and put it in the game directory overwriting the existing one.
6. Install Generalized Biffing with WeiDU v246.

<br>

Alternatively, if you need EEex compatibility, install the latest Generalized Biffing with [WeiDU v249-x86-legacy](https://github.com/WeiDUorg/weidu/releases/tag/v249.00) (requires an OS with 32-bit application support.)
<hr>

*Please check the complete [Readme](https://spellhold-studios.github.io/readmes/generalized-biffing/generalized_biffing-readme-english.html) to learn more about this tool before installation.*

## Credits

<!-- double space after each credits **Heading** if you don't need lists -->

**Author**  

- the bigg

**Contributors**  

- Argent77 &nbsp;&ndash;&nbsp; Enhanced Edition and EEex compatibility patches
- Gwendolyne &nbsp;&ndash;&nbsp; maintenance (versions 2.3&ndash;2.5)
- AL|EN &nbsp;&ndash;&nbsp; maintenance (versions 2.6&ndash;2.7)
- skellytz &nbsp;&ndash;&nbsp; maintenance (versions 2.8&ndash;2.9)

**Translators**  

- Felipe &nbsp;&ndash;&nbsp; Brazilian Portuguese
- Isaya &nbsp;&ndash;&nbsp; French

**Special thanks**  

- Everyone else from [The Gibberlings Three](https://www.gibberlings3.net/), [Spellhold Studios](http://www.shsforums.net/), and other Infinity Engine gaming and modding communities who offered their help and support.
