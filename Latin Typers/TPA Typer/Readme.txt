Updated: 2022-02-27

TPA Keyboard Layout for the Translingual Phonetic Alphabet typable method on Windows 10/11.

This is the typable keyboard layout for the phonetic alphabet which I created, which is hosted here: https://github.com/SalviaSage/Translingual-Phonetic-Alphabet

It was really difficult to develop this alphabet and at first it wasn't easy to type with. This is because it has about 20 vowel letters and maybe over 100 consonant letters. It has to have that many letters plus many different combining diacritics to support aditional functions.

It is okay if this readme.txt is long because this project certainly deserves it. The idea behind this keyboard layout is
that it is different than the other ones in the sense that it is independent of any specific language and that instead it aims to be able to type any utterance in any language accurately without regards to spelling.

(1) Basically, the TPA is a caseless alphabet. So, the caps lock in its traditional sense is useless. Since the TPA has a lot of letters, we need to use the caps lock key as a modifier key in addition to the shift key. I avoid using the CTRL key alone as a modifier in my layouts because they tend to be used by programs as hotkeys.

I developed an AutoHotkey script for switching the Caps Lock key into holdable instead of toggleable. It basically makes Caps Lock work just like the shift key, it turns it into a modifier key while preserving its own functioning.
(It doesn't turn it into a shift key)

https://github.com/SalviaSage/Autohotkey-Scripts-Repository/tree/master/Holdable%20Caps%20Lock

I recommend running this script in the background when typing the TPA with this keyboard layout. It definitely makes things easier. It is turned on by default but it can be suspended by right clicking its tray icon and hitting suspend. It also retains the toggle feature of caps lock but you need to hit the caps lock key twice within 100-125 milliseconds instead of hitting it once.

(2) The number keys above the letter keys are also being used to type additional letters. Because the TPA has upwards of about 150 letters, those keys have been assigned for this purpose. The F keys above those are left alone and can not be modified anyway. So, the digits / numbers can not be typed with this layout and that serves no purpose here anyway.

(3) The numpad is exclusively being used to type the combining diacritics of the TPA. Because the TPA has and needs so many combining diacritics that go both above the individual letters and below the individual letters, the numpad has to be occupied for this purpose.

a̾ ạ a͚ a͐ a̱ å a̅ á â

(4) This layout contains superscript letters as well.

(5) The "retroflex" letters are accessed with the caps lock key just as it is in my Devanagari keyboard layout.
The "alveolo-palatal" letters are accessed with the shift + caps lock key.

(6) Access aditional letters by hitting shift. The vowel letters on the keyboard give you additional vowel letters, while the consonant letters give you additional consonant letters.

(7) The numpad is being used for typing the combining diacritics of the TPA. This allows us to show various different co-articulations and phenomena.

(8) Other than these main differences, the base small case letters are exactly the same as in the QWERTY English US layout and are found at the same locations except for the i and the j which are there but without the dots (tittle) on top of them.

This is because the TPA makes use of "above combining diacritics" as it is shown above.
The dotted versions can also be typed and they represent the same sounds.

(9) Also, the letter g is changed from U+0067 to "script g" U+0261. That is 'g' into 'ɡ' to prevent it from being shown as the double story g as seen here. Outside of those three differences, the other letters are the same on the base layout.

(10) Shift + vowel letter gives you other vowels, while hitting the Caps Lock key + vowel gives you another more broad vowels of the same vowels.

(11) The font you are supposed to use with this alphabet is a font called CODE2000. Which you can find it, being hosted by me, here: https://github.com/SalviaSage/Fonts-Repository

The Brill font also seems to work well, which can be found here:
https://brill.com/page/290?language=en

(12) You also get a whole set of brackets, where the bracket keys normally are. And even more punctuation characters where the punctuation characters are located.

(13) The ejective, ingressive and implosive markers are located at the question mark key.

(14) There are three more "r" themed keys above the "r" key.
