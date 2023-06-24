# catproof_keyboard
quick script to turn keyboard off to kittenproof

In Ubuntu or Ubuntu derivatives

Copy keyboard.sh and the two image files to the location of your choice

In a terminal window

```$ xinput --list```

Look for a line similar to 

```↳ AT Translated Set 2 keyboard              id=12   [slave  keyboard (3)]```

Enter the "id" number into keyboard.sh

You can then toggle the keyboard on and off by running the script.

This can be done with the .desktop file, changing the location to the location of the script. 

Or for example, added to your taskbar

![image](https://github.com/dm2912/catproof_keyboard/assets/25871666/817e20fe-5bd4-420a-b5e5-76a443f2be61)
