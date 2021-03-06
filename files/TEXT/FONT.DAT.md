| Version(s) |
| ---------- |
| * Saturn (original) |

## Description

Contains copies of the game's fonts.
These files are missing from the second Saturn revision and the PlayStation port, and unused in the iOS port.

While these fonts appear to be mostly identical to the fonts used in game, they're not actually used. The game runs and displays text just fine if these files are deleted from the disc altogether.

### FONT.DAT

Contains 16x16 tiles in 4-colour 2bpp.
Has a full set of kana along with various punctuation, non-text symbols, and a large number of kanji; contains a total of 2370 characters.
Does *not* have a full English font; only has a few English characters, enough for the few bits of English used in the game such as "HP" or "MP".

While the English PlayStation version uses an 8x16 font for its dialogue, all Japanese dialogue uses this 16x16 font.

### FONT8.DAT

Contains a mix of 8x8 tiles and 8x16 tiles in 4bpp.
The 8x8 tiles comprise two different fonts, while the 8x16 tiles comprise a single font.
One 8x8 font and the 8x16 font contain a full set of numbers, but otherwise none of the three fonts is complete; they contain only enough characters for what the game needs.
Some of the text in one of the 8x8 fonts and in the 8x16 font spans multiple tile, e.g. is treated as an image rather than as a font.
The 8x8 fonts are used for status text and character names in the menu at the bottom of the screen.
The 8x16 font is used in menus.

## Palette

The primary palette is as follows:

0 - transparent
1 - #D8D8D8
2 - #8080B0
3 - #001040

This palette applies to all fonts in both files, but in-game the 8x8 fonts are sometimes rendered in different colours (for example, green to indicate full health, orange to indicate status effects, etc.)
