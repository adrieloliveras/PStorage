
# [Pokémon Storage]

Pokemon Storage is a homebrew which allows to manage a local bank for XY and ORAS Pokémon games, just like the Pokébank, but as a free offline service.
This homebrew is just a storage solution.

The source code is available under the [GPLv3 license](https://github.com/gocario/PHBank/blob/master/LICENSE) on [github](https://github.com/gocario/PHBank), and the resources are available on [github](https://github.com/gocario/PKBrew) too.


## What this Homebrew can do:
* Work on o3ds and n3ds!
* Navigate through the PC boxes of a XY/ORAS save and the Bank boxes.
* Display a more specific resume per Pokémon (like IVs/EVs).
* Select one Pokémon (with stylus or buttons) and move it to another slot/box.
* Select some Pokémon (with buttons) and move them to another box.
* Swap an entire box content to another one (pc <-> bank).
* Autocomplete the Pokédex when importing Pokémon to a gamesave.
* Prompt a dialog to save/exit/backup during the homebrew execution.
* Export/Import the savedata directly to/from the game, without the need of external tools (/main).
* Load/Save the bankdata to/from the bank, located in the SD card (/pk/bank/bank).

## How to install it:
* Just extract the archive at (to?) the root of your SD card.
* It must contains:
* The homebrew files /3ds/PHBank/[PHBankFiles].
* The cia installer in /cia/PHBank.cia
* The data files /pk/[DataFiles].

## Controls

### Everywhere
* DPad/CPad: Move the cursor inbox, change box, change pc/bank.
* L/R: Change the current box.
* LZ/RZ: Switch from PC to Bank and vice versa (can be done with Pad and/or stylus too).
* Start: Open the savexit menu, for exiting or backing up.
* Select: Switch the selection mode (Single -> Quick -> Multiple).

### Touchscreen
* Move the cursor inbox.
* Change the current box.
* Switch PC/Bank.
* Drag & Drop Pokémon.
* Change the selection mode.

### In Single selection mode (Red):
* A: Select Pokémon / Move Pokémon if one is already selected.
* B: Cancel selection.
### In Quick selection mdoe (Blue):
* A: Select Pokémon / Move Pokémon if one is already selected.
* B: Cancel selection.
* Y: Swap the current PC box content with the current Bank box content.

### In Multiple selection mdoe (Blue):
* Y: Activate the box selector (TODO: transform it as a button on screen).

## Todo List
* Add SM/USUM support
* Wonder box ;)
* Display more specific information per Pokémon (Tabs for contest/met/etc).
* Enhance more the GUI.
* When moving Pokémon with the DPad/A, switch the held Pokémon.

## Note
Original Project was only tested with Pokémon Alpha Sapphire on a cartridge on a n3ds.
Not cheat, no kidding. Besides this being a fork, I'm also stupid.

## Credits
Thanks to original creators!

__Disclaimer: I'm not responsible if you lose or corrupt your save by using this homebrew. It mays contain bugs even within the normal intended use. Use it at your own risk.__

****ALWAYS MAKE A BACKUP!**** __(Just use Checkpoint)__
