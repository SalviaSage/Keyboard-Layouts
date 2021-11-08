# Keyboard-Layouts
This repository contains the installable keyboards that I created for Windows 10/11.

I came up with this idea after I created my own phonetic alphabet. I had a problem, I couldn't type this alphabet on Windows 10.
So, using a computer program, I set out to create a keyboard typable method for my own alphabet based on the QWERTY keyboard layout that was already there on my keyboard. Soon enough, I brought the alphabet to a usable level, then I made even some more tweaks to it and adjusted the positions of the keys in comparison with the letters. After that, I said to myself, well it would be useful to be able to type additional alphabets and characters in support of various languages around the world. I then set out to create such typing systems. 

The interesting thing with my typing systems is that all the letters and the sounds they represent in various different writing systems are supposed to be where the sounds and the letters represented by the QWERTY keyboard layout is. This is necessary in order to preserve the muscle memory retained from the QWERTY keyboard layout, which helps us type faster. Without this, it becomes frustratingly difficult to type and it would be even worse if every typing system we had to use had different layouts with keys scattered in different locations.

I did however create one NON-QWERTY keyboard layout called the "HALMAK" keyboard layout. I am a fan of this keyboard layout as I believe that it is a very efficient keyboard layout with the vowels located on the right side for typing with the right hand which I think would be preferable for people who are right handed such as myself. This is similar in comparison to the DVORAK keyboard layout which has the vowel letters on the left side of the keyboard, which is perhaps better for people who are left handed. This keyboard layout, HALMAK, is also good because it moves some of the punctuation keys (non-letter keys) that are located on the right, bottom side of the QWERTY keyboard to the center of the keyboard layout. This is the only keyboard layout I know that does that. This would help in making sure that the hands are more separate apart from each other and do not stretch out as far and that the letters are closer to one another. That feature itself might have been the idea of the AI that helped place the keys there in that position, which does make sense. It is also the only keyboard layout I know that was designed by an AI. I am not responsible for that project and did not create that layout, however I did create an installable keyboard layout for that layout.

The GitHub page for that project is located here:  
https://github.com/MadRabbit/halmak  
This GitHub page also hosts installable keyboard layouts for this layout:  
https://github.com/pguerin3/halmak4windows#:~:text=Halmak%20maps%20to%20the%20Halmak%20layout%20for%20normal,in%20their%20original%20Qwerty%20positions%20on%20the%20keyboard.  


Although, that layout itself might be better in its key placement, switching from a keyboard layout that is in your muscle memory to something that isn't will slow down your typing speed so very much, to the point that you would have to visually look at the keyboard in order to type. People who make the switch do eventually improve over time as it sets into their muscle memory, which of course takes some time. This makes the switch simply not worth it to so many people including myself. And, even if you do master such a keyboard layout. You will still find the QWERTY keyboard everywhere, as it is the most popular keyboard layout in the world.

Below is a keyboard typing guide and a hotkey guide for Windows 10 21H1 version.
I can not guarantee its correctness in versions below 21H1. It may have been changed.

**CTRL + LEFT SHIFT:** Cycles the keyboard layouts downwards within the same language, does not switch languages.
**CTRL + RIGHT SHIFT:** Cycles the keyboard layouts upwards within the same language, does not switch languages.  

**WINDOWS KEY + SPACE:** Cycles all of the keyboard layouts, across languages as well.  

**ALT + LEFT SHIFT:** Cycles languages downwards, not the keyboard layouts.  
**ALT + RIGHT SHIFT:** Cycles languages upwards, not the keyboard layouts.

**WINDOWS KEY + ;:** Windows key + the semi colon key opens the emoji menu where we can type emojis, kaomojis, emoticons and also various symbols and letters from Unicode.

**WINDOWS KEY + CTRL + O:** Pressing this will turn on the On Screen Keyboard, so the keyboard can be "used" using the mouse.
Pressing it again will turn it off.


**SHIFT KEY, pressed 5 times:** This will trigger a window which will ask you if you want to turn on the "sticky keys" functionality of Windows 10.

**RIGHT SHIFT KEY, held down for 8 seconds:** This will trigger a window which will ask you if you want to turn on the "filter keys" functionality of Windows 10. If you hit yes, the "FilterKeys" icon will appear as a tray icon in the taskbar. If you want to turn it off again, you can again hold down the right shift key for 8 seconds.

**NUM LOCK KEY, held down for 5 seconds:** This will trigger a window which will ask you if you want to turn on the "toggle keys" functionality of Windows 10. This makes it so that a sound is played by windows when the caps lock, num lock or scroll lock keys are pressed.

Personally, I would recommend that the shortcut keys for these should be turned off as they can be toggled unintentionally, which is how I learned of these shortcuts in Windows 10. It can be turned off by holding the right shift key for 8 seconds and clicking "Disable this keyboard shortcut in Ease of Access keyboard settings".

There is also the "MouseKeys" feature, which basically allow us to use the mouse through the keyboar NumPad. This however, makes it so that the numpad can not be used when it is turned on.

If you have the "UnicodeInput" program running in the background, then you can type Unicode characters very easily.  
**ALT + Numpad+ :** Enter Unicode "code" and hit enter to type that unicode character.


***How to uninstall / remove keyboard layouts?***  
Click on the name of the language on the language bar such as "ENG US"
Then, click on "Language Preferences"
There, select the language that that keyboard layout is associated with and click on "Options"
There, you will see a list of keyboards that are available for that language.
Just click on the keyboard layout that you want to remove, then you will get a button that says "Remove".

The keyboard layout should then be deleted immediately and you won't see it anymore in the language bar.

Also, it seems you have to restart the computer to be able to use newly installed keyboard layouts.

***What does the "scroll lock" key do?***  
This key is used by certain programs to make it so that horizontal scrolling is triggered.
A good example is the LibreOffice Calc and the Microsoft Excel programs. I
If scroll lock is turned on, we scroll horizontally when we hit the arrow keys on the keyboard.
if it is turned off, we go to the next cells by using the arrow keys on the keyboard.

***How to lock the keyboard or the mouse keys?***  
This free program is definitely what you are looking for:
https://www.sordum.org/7921/bluelife-keyfreeze-v1-4-block-keyboard-and-mouse/

***What is a faster way to switch between keyboard layouts?***  
You can skip choosing a layout from the menu by directly switching to that keyboard layout by setting up a shortcut to that layout.
This won't give you any visuals, but it will immediately switch to that layout upon hitting those hotkeys. It is the fastest way of going between different layouts.
To set up such hotkeys, openm the settings window from the start menu or by hitting WIN KEY + I and go to "Time & Language", then click on "Language" on the menu to the left.
Then, click on "keyboard", then click on "Input language hot keys". There, you can see a list of all the keyboard layouts that are installed.
Select a layout and click on "Change Key Sequence" and pick which key keys you want to associate with that layout. I recommend using the CTRL + ~ key for your default keyboard layout, likely the US QWERTY layout, and the CTRL + # keys for fast switching to other layouts.
These seem to not interfere with other programs when pressed and yet quickly switch between keyboard layouts.

***What is the definitive way to delete custom keyboard layouts?***
The keyboard layouts that I make with the program KBDEdit all have to start with the string KBDEdit.
Once installed, these keyboard layouts are located in the C:\Windows\System32 and C:\Windows\SysWOW64 folders as dll files.
So, find the layout that you want to delete, and delete from there.

Make sure to delete them from both the System32 and the SysWOW64 folders.
Then, sign out and back in or restart the computer.
Same is true when we install the new keyboard layouts, you will have to sign out and back in or restart in order to use them.
You can also install, uninstall or reinstall from the .exe file.

How to set up the Text Services and Input Languages?
Open the settings window and click "Time & Language", then click "language"
then click "Spelling, typing & keyboard settings", then click "Advanced keyboard settings"
then, click "Input language hot keys", then choose the "Advanced Key Settings" tab, then click
"Change Key Sequence".
Here, Switch Input Language should be set to "Left Alt + Shift" and Switch Keyboard Layout should be set to
"Not Assigned", It should not be set to anything else because we already use the grave accent and the ctrl+shift
for other things, the keyboard can already be changed wwith winkey+spacebar anyway, so it doesn't have to be set.
