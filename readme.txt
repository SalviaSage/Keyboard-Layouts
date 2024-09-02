Keyboard Layouts — Help Documentation; 

These are the computer programs that I make using a keyboard layout editor program.
These programs re-arrange the letters on the keyboard with other letters.
They are useful for typing in other languages and alphabets.
The way my keyboard layouts work is that I try to assign the letters found in the alphabet to where they would be on the keyboard.

For example, in the Arabic Typer, the letter 'ل' (lām) is located at the same key where the letter 'L' is.
In the Cyrillic Typer, pressing the same key will give the letter 'л'.
This is a necessary step to facilitate typing; this kind of mnemonics is what allows a QWERTY keyboard user to type fast and without errors across different writing systems.
This allows us to type different alphabets and languages from a retained muscle memory.
I make a separate computer program for every Unicode block.

For example, Russian, Belarusian, and Ukrainian are all written in Cyrillic.
I do not make separate programs for each if I don't have to.
I make one computer program that types Cyrillic without any missing letters.
Then, of course, it does not cover all the letters and letter variants used in writing for example, Serbian.
To address this issue, I either have to develop another program which will cover the needs of that particular language or create IMEs (Input Method Editors).
Input Method Editors are the only viable method for writing systems where there are too many characters that can not fit on a 104-key keyboard.

The idea here is that I do not make only keyboard layout programs but also other programs that work in tandem with these programs to give the typist the best typing experience.

Below is a keyboard typing guide and a hotkey guide for the Windows 10 21H1 version.
I can not guarantee its correctness in versions below 21H1. It may have been changed.

CTRL + LEFT SHIFT: Cycles the keyboard layouts downwards within the same language, and does not switch languages.
CTRL + RIGHT SHIFT: Cycles the keyboard layouts upwards within the same language, does not switch languages.

WINDOWS KEY + SPACE: Cycles all of the keyboard layouts, across languages as well.

ALT + LEFT SHIFT: Cycles languages downwards, not the keyboard layouts.
ALT + RIGHT SHIFT: Cycles languages upwards, not the keyboard layouts.

WINDOWS KEY + ; : Windows key + the semicolon key opens the emoji menu where we can type emojis, kaomojis, emoticons and also various symbols and letters from Unicode.

WINDOWS KEY + CTRL + O: Pressing this will turn on the On-Screen Keyboard, so the keyboard can be utilised using the mouse.
Pressing it again will turn it off.

SHIFT KEY, pressed 5 times: This will trigger a window which asks you if you want to turn on the "sticky keys" functionality of Windows 10.

RIGHT SHIFT KEY, held down for 8 seconds:
This will trigger a window which asks you if you want to turn on the "filter keys" functionality of Windows 10.
If you hit yes, the "FilterKeys" icon will appear as a tray icon in the taskbar.
If you want to turn it off again, you can again hold down the right shift key for 8 seconds.

NUM LOCK KEY, held down for 5 seconds:
This will trigger a window which asks you if you want to turn on the "toggle keys" functionality of Windows 10.
This makes it so that a sound is played by windows when the caps lock, num lock or scroll lock keys are pressed.

I recommend that these shortcut keys should be turned off as they can be toggled unintentionally.
That is how I learned of these shortcuts in Windows 10.
It can be turned off by holding the right shift key for 8 seconds and clicking "Disable this keyboard shortcut" in the "Ease of Access" keyboard settings".

There is also the "MouseKeys" feature, which allows us to use the mouse through the keyboard numpad.
This, however, makes it so that the numpad can not be used when it is turned on.

	How to uninstall / remove keyboard layouts?
1) Click on the name of the language on the language bar such as "ENG US" Then, click on "Language Preferences".
There, select the language that that keyboard layout is associated with and click on "Options".
There, you will see a list of keyboards available for that language.
Just click on the keyboard layout that you want to remove, then you will get a button that says "Remove".
The keyboard layout should then be deleted immediately and you won't see it anymore in the language bar.

2) Run the KBDEdit installer which used to install the keyboard layout and click "uninstall".

3) Also, search and find the keyboard layouts .dll file in the folders "System32" and "SysWOW64" and delete those .dll files.

That should be all that is necessary to delete a keyboard layout.
Never delete any system .dll files or other files related to keyboard layouts that come with Windows.
Never modify any registry entries that relate to keyboard layouts.
In this context, we are only interested in deleting the custom keyboard layouts made with KBDEdit.
They are easily identified as such because they start with the filename "KBDEdit".

	How to uninstall keyboard layouts if the installer file is missing?
4) Search the registry for the keyboard layout ID such as 'b0070409' using the program, Registry Finder.
Delete the entries that are found and restart the computer.

5) Only after the uninstallation, install the new keyboard layout.
Don't install duplicates.

Also, it seems you have to restart the computer to use the newly installed keyboard layouts.

	What does the "scroll lock" key do?
This key is used by certain programs to trigger horizontal scrolling.
A good example is the LibreOffice Calc and the Microsoft Excel programs.
If the scroll lock is turned on, we scroll horizontally when we hit the arrow keys on the keyboard.
If it is turned off, we go to the next cell by using the arrow keys on the keyboard.

	How to lock the keyboard or the mouse keys?
This free program is definitely what you are looking for:
https://www.sordum.org/7921/

	What is a faster way to switch between keyboard layouts?
You can skip choosing a layout from the language menu by directly switching to that keyboard layout by setting up a shortcut for that layout.
This won't give you any visuals, but it will immediately switch to that layout upon hitting those hotkeys.
It is the fastest way of going between different layouts.
To set up such hotkeys, open the settings window from the start menu or by hitting WinKey+I and go to "Time & Language", then click "Language" on the menu to the left.
Then, click on "keyboard", then click on "Input language hot keys". There, you can see a list of all the keyboard layouts that are installed.
Select a layout and click on "Change Key Sequence" and pick which key keys you want to associate with that layout.
I recommend using the CTRL + ~ key for your default keyboard layout, likely the US QWERTY layout, and the CTRL + # keys for fast switching to other layouts.
These seem to not interfere with other programs when pressed and yet quickly switch between keyboard layouts.

	How to set up the Text Services and Input Languages?
Open the settings window and click "Time & Language", then click "Language" then click "Spelling, typing & keyboard settings".
Then click "Advanced keyboard settings" then, click "Input language hot keys", then choose the "Advanced Key Settings" tab.
Then click "Change Key Sequence". Here, Switch Input Language should be set to "LeftAlt+Shift" and Switch Keyboard Layout should be set to "Not Assigned".
It should not be set to anything else because we already use the grave accent and the "Ctrl+Shift" for other assignments.
The keyboard can already be changed with winkey+space anyway, so it doesn't have to be set.

Signed ﻿;  
	𝓞.﻿ ﻿𝓞𝔃𝓽𝓮𝓴𝓲𝓷
