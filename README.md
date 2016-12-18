<!---
IMPORTANT
=========
This README.md is displayed in the WebStore as well as within Jarvis app
Please do not change the structure of this file
Fill-in Description, Usage & Author sections
Make sure to rename the [en] folder into the language code your plugin is written in (ex: fr, es, de, it...)
For multi-language plugin:
- clone the language directory and translate commands/functions.sh
- optionally write the Description / Usage sections in several languages
-->
## Description
Ce plugin permet de controler les clef USB Blink1 (https://github.com/todbot/blink1)

Les commandes suivantes sont supportées:
 - allume led
 - eteint led
 - led bleue
 - led verte
 - led blanche
 - led jaune
 - led orange

## Installation
Attention: le pugin est configuré pour une utilisation sur RPI, si vous voulez l'utiliser sur un system X86/64 il faut modifier le fichier commands et remplacer la valeur 'blink1-tool-armv7l' par 'blink1-tool-x86_64'

## Usage
```
You: allume led
Jarvis: led allumée
You: regle led avec la couleur bleue
Jarvis: led bleue
```

## Authors
[Byackee](https://github.com/byackee)
