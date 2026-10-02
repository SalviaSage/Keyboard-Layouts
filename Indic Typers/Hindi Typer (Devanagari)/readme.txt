Hindi Devanagari Typer;

It is an easy way to type the Devanagari script and it does not require retraining your muscle memory.

You should use the toggleable caps lock script, found here for better typing:
	https://github.com/SalviaSage/Autohotkey-Scripts-Repository/tree/master/Typing%20Scripts/Holdable%20CapsLock

Also, you should have the Hotstrings.exe running in the background with my custom library loaded and enabled there.
This library helps correct and automate some vowel matra mistakes and replace the matra with independent vowels at the start of words:
	https://github.com/SalviaSage/Custom-Libraries/blob/main/Character%20Replacers/Indic/Hindi%20Vowel%20Helper%20(Devanagari).csv

The base keys have consonant letters and the mātra (combining forms) of the vowels.
If you hit shift + vowel key you get mātras for long vowels.
If you want the independent forms of the vowels, then hit the caps lock + vowel key.
Similarly, hit caps lock + shift + vowel key to get independent long vowels.

You have to remember to press caps lock each time a word starts with a vowel.
That is, unless you have the hotstrings.exe program running in the background with my 'Hindi (Devanagari) Vowel Helper' library loaded and running.
It automatically detects mātras at the start of words or after other vowels and appropriately replaces the mātras with independent vowels.
It is working surprisingly well, which bodes well for us.
Otherwise it is difficult to type Indic scripts as the user will have to manually pick between mātras and vowels.

The aspirated consonants are typed by pressing the caps lock key where their base counterparts are.
For example; B(ब), Caps Lock + B = (भ)

The virāma key serves a special purpose, typed by pressing Shift + Space.
It is used to construct "conjunct consonants" which is an important part of Devanagari.
It then disappears and gives us the conjunct consonant.
To type the virāma key, press Shift + Space.
For example: (ज) + (्) + (ञ) = (ज्ञ)
To type the virāma without getting conjunct consonants, press Ctrl + Space.
For example: (ज) + (्) + (ZWNJ) + (ञ) = (ज्‌ञ)
To type the conjunct consonants on their own, press Ctrl + Shift + Space.
For example: (ज) + (्) + (ZWJ) = (ज्‍)

The "Zero-Width-Joiner" is located at Shift + Caps ([) key.
The "Zero-Width-Non-Joiner" is located at Shift + Caps (]) key.

The Rupee sign (₹) can be typed with Right Alt + R key or the Right Alt + (=) key.

The "danda"(।) and the "double danda"(॥) are at the (\) key.
The "danda"(।) serves the same function as the full stop (.) and should preferably be used instead of the Latin full stop.
The "double danda"(॥) should be used at the end of paragraphs (optional use).
This library helps with spacing regarding the danda character:
	https://github.com/SalviaSage/Custom-Libraries/blob/main/Character%20Replacers/Indic/Hindi%20Character%20Replacer%20(Danda%2BHairspace).csv

This keyboard layout has the Sindhi implosive letters, (ॿ), (ॾ), (ॻ), (ॼ).
They are typed with Right Alt + consonant key.

How to type Devanagari abbreviation sign(॰)?
Press AltGr + Space or Shift + Caps (\).

By default, the numbers are typed from the numpad as ०१२३४५६७८९.
Press Right Alt + Numeral to type as 0123456789.

How to type the reph?
	https://en.wiktionary.org/wiki/reph
The reph (र्क) is produced in Unicode by the sequence [ra र ] + [virāma ्] + consonant.
It can be typed with the Ctrl + R key.

How to type eyelash reph?
	https://en.wikipedia.org/wiki/Balbodh#Eyelash_reph_/_raphar
The eyelash reph (र्‍) is produced in Unicode by the sequence [ra र ] + [virāma ्] + [ZWJ].
It can be typed with the Ctrl + Shift + R key.

How to type (र‌ु) or (र‌ू) instead of (रु) and (रू)?
Similar to the Arabic lam-alef character, the computer automatically ligates (र‌ु) into (रु) and (र‌ू) into (रू).
The correct way to prevent this mandatory ligation is to use the zero width non-joiner (U+200C), same as in Arabic.
For example: (र) + (ZWNJ) + (ु) = (र‌ु) | (र)  + (ZWNJ) + (ू) = (र‌ू)

