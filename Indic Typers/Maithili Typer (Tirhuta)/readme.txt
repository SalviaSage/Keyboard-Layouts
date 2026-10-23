Maithili (Tirhuta) Typer;

A script which is very similar to the Bengali script.

You should use the toggleable caps lock script, found here for better typing:
https://github.com/SalviaSage/Autohotkey-Scripts-Repository/tree/master/Typing%20Scripts/Holdable%20Caps%20Lock

Also, you should have the Hotstrings.exe running in the background with my custom library loaded and enabled in there.
This library helps correct and automate some vowel maatra mistakes and replace the maatras with independent vowels at the start of words:
https://github.com/SalviaSage/Custom-Libraries/blob/main/Maatra%20Helpers/(Maatra%20Helper)%20Tirhuta.csv

The base keys have the consonants and the maatra (combining forms) of the vowels.
If you hit the shift key + vowel key you get long maatra vowels instead.

If you want the independent forms of the vowels, then hit the AltGr + vowel key.


You will have to remember to press caps lock each time a word starts with a vowel
unless if you have the hotstrings.exe program running in the background with my 'Bengali Maatra Helper' library loaded and running.

What it does is that it automatically detects where the independent vowel would be used such as at the start of words or after other vowels and appropriately replaces the maatra with the independent vowel.
It is working surprisingly well, which bodes well for us, otherwise it is difficult to type in Indic scripts.

The aspirated consonants are accessed by pressing the caps lock key where their unaspirated counterparts are.

You see, programmatically, the viraam key serves a special purpose.
It is used to construct 'conjunct consonants' which of course is an important part of Bengali.
For this reason, it can not be used at the start or at the middle of words, it just can not be typed if another letter follows it.
It then disappears and instead gives us the conjunct consonant.
Again, this is not an issue if writing by hand, but this means that we can not type the viraam at the start or at the middle of words.

The Rupee sign is where the equals sign is.
The numbers can only be typed on the numpad.
You can also type the western numbers by pressing the AltGr key.

The 'shift+spacebar' key is the "viraam" key and it is also used to make conjunct consonants.
The "Zero-Width Joiner" is located at key '{' key.
The "Zero-Width Non Joiner" is located at key '}' key.
They are supposed to help with the conjunct characters, but the viraam seems to do the job just fine most of the time.

The "danda" and the "double danda" are at the '\' key on top of the enter key.
They serve the same function as the full stop in the Latin alphabet and should preferably be used instead of the Latin full stop.

