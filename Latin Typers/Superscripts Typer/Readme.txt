Adds the capacity to type superscript letters. they are basically miniscule letters that are written on the top side of a line as opposed to "subscript" letters which is the same thing but written on the bottom side of a line.

a b c d e f g h i j k l m n o p q r s t u v w x y z
ᵃ ᵇ ᶜ ᵈ ᵉ ᶠ ᵍ ʰ ᶦ ʲ ᵏ ˡ ᵐ ᶰ ᵒ ᵖ   ʳ ˢ ᵗ ᵘ ᵛ ʷ ˣ ʸ ᶻ
                ⁱ         ⁿ

Again, just as it is the case with the "Small Caps" letter set, the "Q" is problematic and the superscript "q" doesn't exist in Unicode.
I substituted the letter 'ᵠ` modifier letter small greek phi (U+1D60) at that position because it looks similar to a `q` but it is not satisfactory.
I also made a small change to the letters i and n due to the way they are encoded in unicode separately from the rest of the superscript set, they look bigger than the rest of the superscript letters.
This causes these letters to stand out and look inappropriately, therefore I substituted them with a dotless i and a small capital N at those positions.
But the original letters can still be typed with the shift + caps lock combination.

A B C D E F G H I J K L M N O P Q R S T U V W X Y Z
ᴬ ᴮ   ᴰ ᴱ   ᴳ ᴴ ᴵ ᴶ ᴷ ᴸ ᴹ ᴺ ᴼ ᴾ   ᴿ   ᵀ ᵁ ⱽ ᵂ      
It also has capital letter support for the above letters. 'C, F, Q, S, X, Y, Z' are the capital letters that do not have Unicode designations.

This is something that I can not fix but Unicode can possibly fix it from their end if they choose to do so by adding those characters.
I personally think that the full set should be in Unicode. Right now, neither set is full with the smallcase superscript letters missing the letter "q" and the capital case superscript letters missing 7 letters: C, F, Q, S, X, Y, Z.

Also, it has full number support:

0 1 2 3 4 5 6 7 8 9 - + ( )
⁰ ¹ ² ³ ⁴ ⁵ ⁶ ⁷ ⁸ ⁹ ⁻ ⁺ ⁽ ⁾

UNICODE VERSION 14.0 UPDATE (September 2021):

As of Unicode v14.0, the superscript q (U+107A5 MODIFIER LETTER SMALL Q) is now in Unicode.
However, it is located outside the BMP.
Also, the modifier letter capital Y is now in Unicode.
However, these do not show with the current version of computers and simply are not supported.
They are not included in this program for that reason.