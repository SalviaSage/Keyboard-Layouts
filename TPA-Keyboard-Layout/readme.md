Layout v3.0 for the TPA typable method on Windows 10.

This is the typable keyboard layout for the phonetic alphabet which I created which can be found here:
https://github.com/SalviaSage/Translingual-Phonetic-Alphabet

It was really difficult to develop this alphabet and at first it wasn't easy to type it with.
Then, I improved the placement of the keys and now it functions quite well.

(1) Basically, the TPA is a caseless alphabet, so hitting caps lock gives us additional letters.
which is needed because the TPA has a lot of letters.

Also, I developed an AutoHotkey script for switching the Caps Lock key into holdable instead of toggleable.
It basically makes Caps Lock work just like the shift key, it turns it into a modifier key.

https://github.com/SalviaSage/Autohotkey-Scripts-Repository/tree/master/Holdable%20Caps%20Lock

I recommend running this script in the background when typing the TPA. It definitely makes things easier.
Toggle it on and off with Ctrl+Alt+T.

(2) The number keys above the letter keys are also being used to type additional characters

They type these namely:

θ ʃ ʒ ɾ ɹ ɼ ə ʰ ʸ ˠ - ⧖

If you shift press those, you get:
ð ʆ ʓ ᵳ ɻ ɽ

(3) The numpad is being used for typing the combining diacritics of the TPA.
This allows us to show various different co-articulations and phenomena.

a̾ ạ a͚ a͐ a̱ å a̅ á â

(4) Other than these main differences, the base small case letters are exactly the same as in English, except for the i and the j which have their dots removed.
This is because the TPA makes use of "above combining diacritics" as it is shown above and the letter g is changed from U+0067 to "script g" U+0261.
That is '` g '` into ' ɡ ' to prevent it from being shown as the double story g as seen here. Outside of those three differences, the other letters are the same.
