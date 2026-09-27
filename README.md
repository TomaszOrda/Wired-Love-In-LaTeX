# Wired Love: A Romance in Dots And Dashes
A typesetting of Wired Love: A Romance of Dots and Dashes by Ella Cheever Thayer typeset in LaTeX.

The original was written around 1880. It has therefore been in the public domain for a long time in most countries.

The typesetting took a little more than 6 hours and another hour of sewing the book.

To compile copy the `Wired_love_A_Romance_Of_Dots_and_Dashes.tex` file and initials folder to an [Overleaf](https://www.overleaf.com) project. It should compile before timing out, but only just.

Another Overleaf project with `signatures.tex` and compiled `Wired_love_A_Romance_Of_Dots_and_Dashes.pdf` will translate it into print-ready 16 pages A5 signatures.

There are a few options that can be set in the tex file: the initials style, chapter page break and font. Of course anyone with a little bit of TeX knowledge can adjust rendering greatly.

# Changes
Changes compared to the original:
 - Morse code was translated to International Morse Code from American Railroad Dialect.
 - Added morse code table and decoding tree
 - Chapters now break the page.
 - Some minor visual changes, including:
    - Title page was approximated
    - Rules are not exact
    - Page breaks in different places
    - Page size and margins
    - Font is not exact

Those should be most of them
Additionally in the .tex file there is a crude regex method for translating things from/to morse code.