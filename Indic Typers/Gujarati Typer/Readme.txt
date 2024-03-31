Gujarati Typer;

It is an easy way to type the Gujarati script and it does not require retraining your muscle memory.

You should use the toggleable caps lock script, found here for better typing:
https://github.com/SalviaSage/Autohotkey-Scripts-Repository/tree/master/Holdable%20Caps%20Lock

Also, you should have the Hotstrings.exe running in the background with my custom library loaded and enabled in there.
This library helps correct and automate some vowel maatra mistakes and replace the maatras with independent vowels at the start of words:
https://github.com/SalviaSage/Custom-Libraries/blob/main/Maatra%20Helpers/(Maatra%20Helper)%20Gujarati.csv

The base keys have the consonants and the maatra (combining forms) of the vowels.
If you hit the shift key + vowel key you get long maatra vowels instead.

If you want the independent forms of the vowels, then hit the caps lock key + vowel key.
And similarly, hit caps lock + shift and a vowel key to get independent long vowels.

You will have to remember to press caps lock each time a word starts with a vowel
unless if you have the hotstrings.exe program running in the background with my 'Gujarati Typer Helper' library loaded and running.

What it does is that it automatically detects where the independent vowel would be used such as at the start of words or after other vowels,
and appropriately replaces the maatra with the independent vowel.
It is working surprisingly well, which bodes well for us, otherwise it is difficult to type in Indic scripts.

The retroflex consonants are accessed by pressing the shift key where their dental / alveolar counterparts are.
The aspirated consonants are accessed by pressing the caps lock key where their unaspirated counterparts are.

You see, programmatically, the viraam key serves a special purpose.
It is used to construct 'conjunct consonants' which of course is an important part of Gujarati.
For this reason, it can not be used at the start or at the middle of words, it just can not be typed if another letter follows it.
It then disappears and instead gives us the conjunct consonant.
Again, this is not an issue if writing by hand, but this means that we can not type the viraam at the start or at the middle of words.
Fortunately, I found a character from vedic extensions that look just like the viraam which can be typed by pressing ctrl+spacebar.
This feature allows us to type the viraam where otherwise we can not, it looks identical in most fonts as I checked it.
It should show appropriately on fonts that are designed for Gujarati.

The Rupee sign is also where the dollar sign is.
The numbers can only be typed on the numpad.
You can also type the western numbers by pressing the scroll lock key to go back to the original Latin alphabet keyboard.

The 'shift+spacebar' key is the "viraam" key and it is also used to make conjunct consonants.
The "Zero-Width Joiner" is located at key '{' key.
The "Zero-Width Non Joiner" is located at key '}' key.
They are supposed to help with the conjunct characters, but the viraam seems to do the job just fine most of the time.

The "danda" and the "double danda" are at the '\' key on top of the enter key.
They serve the same function as the full stop in the Latin alphabet and should preferably be used instead of the Latin full stop.

-----

The scroll lock has been given a new job which I call the "Kana Lock".
Press the scroll lock to type in the Latin alphabet, press it again to type in the target alphabet.
This gives us a way to type in different scripts from the same keyboard layout without switching keyboard layouts.
This state is saved and does not reset when switching between keyboard input methods.
