# tibia-knight-training-script
a MacOS script to train knigts (apple script)

> **Important: DO NOT CHANGE YOUR SCREEN AWAY FROM TIBIA, THIS SCRIPT NEEDS TIBIA TO BE THE ACTIVE WINDOW**

## How to run

1. Download the `tbamcr.scpt` and open it with the default macos code edior
2. Adds your food to the hotkey `0`
3. Add your heal spell to hotkey `3`
4. Attack the creature that you want train (Mad Sheep)
5. Start the code clicking on the `Play` button on your code editor


## Advanced options

You can costumize the hotkeys as you wish, inside the code you can define new hotkeys.

Check the complete key codes here: https://eastmanreference.com/complete-list-of-applescript-key-codes

Example, you can change the heal spell and the food hotkeys.

Into the script, change the lines:
```
set heal_spell to 20
set food to 290
```
- 20 is the key "0" on the keyboard
- 290 is the key "3" on the keyboard

to

```
set heal_spell to 109
set food to 103
```
- 109 is the F10 key on the keyboard
- 103 is the key "F11" on the keyboard
