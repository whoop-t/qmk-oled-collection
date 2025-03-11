# qmk-oled-animation-collection
A collection of easy to copy animations for your qmk oled

> [!NOTE]
> These are for use with OLEDS and QMK, they WILL NOT work with nice!views without modification

## How to use

1. Pick an animation/image
2. Copy the code from the `.c` files in the folder directly to the end of you `keymap.c` file in your QMK firmware
3. Compile and flash your boards

That's it!

## Add your own!

If you'd like to contribute to this collection please follow these steps:

1. Your addition must contain a single `.c` file and a `README.md`
2. The `.c` file must be able to be copied straight to the end of a `keymap.c` file for ease of use
3. The `README.md` should contain some information about the animation/image and a link to what it looks like on the board.
4. Make sure you add your animation/image to the folder for the oled size it was made for(128x32, etc). If there isnt one, please include the folder creation on your PR
5. Raise a PR and wait for review

Thank you for contributing!
