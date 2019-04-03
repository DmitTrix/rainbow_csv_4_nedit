# rainbow_csv_4_nedit
Use NEdit’s syntax highlighting to color columns in CSV (Comma-Separated Values) files. Adapted from the (much more feature-reach) Vim plugin [rainbow_csv](https://github.com/mechatroner/rainbow_csv).

## Installation
1. Download [RainbowCSV.pats](RainbowCSV.pats), and run `nedit -import path/to/RainbowCSV.pats`
2. Optionally, go to NEdit menu bar, choose Preferences → Default Settings → Language Modes…, find the newly added language modes at the bottom of the list, and move them to the desired location using "Move ^" and "Move v" buttons (e.g. to arrange the language modes alphabetically)
3. In NEdit menu bar, do Preferences → Save Defaults…
4. Optionally, edit `~/.nedit/nedit.rc` file, find the section `nedit.highlightPatterns`, and move the newly added patterns to the desired location (e.g. to arrange the languages alphabetically). Note the "end of line" syntax for all lines except the last line of the section!
