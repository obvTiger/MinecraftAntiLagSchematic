# Minecraft Anti Lag Schematic

This script reads a Minecraft schematic file and counts the number of each material used in the schematic. It then checks if more than 30% of the blocks are any blocks from the Minecraft redstone category (including redstone wire, repeaters, comparators, observers, redstone blocks, redstone repeaters, redstone comparators, target blocks, pistons, sticky pistons, and sticks), and if so, sends an error message that lists the redstone blocks found in the schematic.
# Requirements

    Python 3.x
    nbtlib Python library (can be installed using pip)
    Some kind of Webserver
    PHP7.4 or later installation

# Usage

    Install the nbtlib library using pip: pip install nbtlib
    Clone this repository
    Make the cloned directory accessable from the Internet with the Webserver.
    POST an .schematic file to calculate.php as data.

# License

This script is licensed under the MIT License. See the LICENSE file for more information.
Credits

This project was created by [obvTiger](https://obvtiger.ch).