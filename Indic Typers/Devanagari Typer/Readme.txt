Devanagari Typer;

I created this keyboard layout after having created the same kind of thing for the Greek alphabet.
It is an easy way to type the Devanagari script and it does not require retraining your muscle memory.

You should use the toggleable caps lock script, found here for better typing:
https://github.com/SalviaSage/Autohotkey-Scripts-Repository/tree/master/Holdable%20Caps%20Lock

Also, you should have the Hotstrings.exe running in the background with my custom library loaded and enabled in there.
This library helps correct and automate some vowel maatra mistakes and replace the maatras with independent vowels at the start of words:
https://github.com/SalviaSage/Custom-Libraries/tree/main/Devanagari%20Typer%20Helper

The base keys have the consonants and the maatra (combining forms) of the vowels.
If you hit the shift key + vowel key you get long maatra vowels instead.

If you want the independent forms of the vowels, then hit the caps lock key + vowel key.
And similarly, hit caps lock + shift and a vowel key to get independent long vowels.

You will have to remember to press caps lock each time a word starts with a vowel
unless if you have the hotstrings.exe program running in the background with my 'Devanagary Typer Helper' library loaded and running.

What it does is that it automatically detects where the independent vowel would be used such as at the start of words or after other vowels,
and appropriately replaces the maatra with the independent vowel.
It is working surprisingly well, which bodes well for us, otherwise it is difficult to type in Indic scripts.

Of course, one would not have to deal with that and would not make that mistake of writing the maatra if the word starts with a vowel.
However, that is not the case when it comes to typing and normally the typist would have to pick between the two forms.
It is only due to the computer programmer who made the program Hotstrings.exe that I was able to remedy this problem.

The retroflex consonants are accessed by pressing the shift key where their dental / alveolar counterparts are.
The aspirated consonants are accessed by pressing the caps lock key where their unaspirated counterparts are.

The "Q" and the "w" keys are not mapped to letters due to the fact that they are not letters in Devanagari anyway.
Instead, those two keys have been assigned to important diacritical markings of Devanagari

The 'Q' key is the "anusvaar" and the "shift+Q" key is the "nukta".
The 'W' key is the "viraam" (halant) and the "shift+W" key is a vedic sign that looks just like the viraam.
The reason why it is included there alongside the regular viraam has to do with the way conjunct consonants work.

You see, programmatically, the viraam key serves a special purpose.
It is used to construct 'conjunct consonants' which of course is an important part of Devanagari.
For this reason, it can not be used at the start or at the middle of words, it just can not be typed if another letter follows it.
It then disappears and instead gives us the conjunct consonant.
Again, this is not an issue if writing by hand, but this means that we can not type the viraam at the start or at the middle of words.
Fortunately, I found a character from vedic extensions that look just like the viraam which can be typed by pressing shift+w.
This feature allows us to type the viraam where otherwise we can not, it looks identical in most fonts as I checked it.
It should show appropriately on fonts that are designed for Devanagari.

The Rupee sign is also where the dollar sign is. Also if you hit caps lock + 6 you get "Rs" which is rupees in letters.

You can type the Devanagari digits by pressing the number keys on the keyboard, but not on the numpad!
This is because the numpad now houses some common conjunct consonants, they can be hard to type, so I put them there for single key typing.
The numbers can only be typed on the top part of the keyboard and not at numpad.
You can also type the western numbers

The 'w' key is the "viraam" key and it is also used to make conjunct consonants.
The "Zero-Width Joiner" is located at key "shift+F".
It is supposed to help with the conjunct characters, but the viraam seems to do the job just fine most of the time.

The "danda" and the "double danda" are at the period key. Caps lock and shift caps lock.
They serve the same function as the full stop in the Latin alphabet and should preferably be used instead of the Latin full stop.

This keyboard layout also has the Sindhi implosive letters (voiced letters with a line under them).
They are located at the 7 to 0 keys, typed with caps lock + shift.

-----

The scroll lock has been given a new job which I call the "Kana Lock".
Press the scroll lock to type in the Latin alphabet, press it again to type in the target alphabet.
This gives us a way to type in different scripts from the same keyboard layout without switching keyboard layouts.
This state is saved and does not reset when switching between keyboard input methods.

-----

How to type the eyelash reph? 
https://en.wikipedia.org/wiki/Balbodh#Eyelash_reph_/_raphar

The eyelash reph / raphar (र्‍) is produced in Unicode by the sequence [ra र ] + [virāma ्] + [ZWJ] and [rra ऱ ]+ [virāma ्] + [ZWJ].

-----

I am very proud as to where I was able to bring this program.
It has opened the doors for developing programs for typing in other Indic scripts.

-- November  05, 2022