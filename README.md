# 32wpsdeckbins
Compiled Firmware for our Decks!

# Step 0
Using a [supported browser](https://caniuse.com/?search=webhid), check that you have QMK enabled by going to this url: https://usevia.app/

The webpage should accurately identify the keyboard to be flashed my make and model.

# Step 1
Download the binaries to your machine (does not have to be *nix)
`gh repo clone Enki--/32wpsdeckbins`

# Step 2
Install [QMK toolbox](https://github.com/qmk/qmk_toolbox/releases), open it, and watch for console messages

# Step 3
*For V-series Keychron boards:
        Remove power, remove spacebar, and press and hold exposed reset button while reconnecting power [link to site](https://www.keychron.com/blogs/archived/how-to-factory-reset-or-flash-your-qmk-via-enabled-keychron-v1-keyboard)

Make sure QMK Toolkit picked up the board (console message should mention "DFU device connected")

# Step 4
Open the right firmware in QMK Toolbox our deck, then click flash and watch it work.

# Step 5
Using a [supported browser](https://caniuse.com/?search=webhid), check that QMK VIA no longer works by going to this url: https://usevia.app/
