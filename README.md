Go Status Flashcards by Chloe Adeline
=====================================
I wanted to know the statuses of common corner and side Go shapes without thinking. These 3x5" flashcards will help commit them to memory!

Description
-----------
Since the inside shape is what is being drilled and since black stands out in sharper contrast than white, black is always used for the inside shape. Each shape is "dead," "alive," or "undecided." I will eventually add shapes with "ko" statuses as well.

The front of each card shows the shape. The back has the name of the shape [e.g. "6 Stone One Space Notcher on the Side"], its status [e.g. "Undecided."], the shape's "proverb" [e.g. "4 Die, 7 Live."], and how black and white can or cannot live or kill as applicable.

The Shapes So Far
-----------------
- 6-8 Stone Rows on the Side
- 4-6 Stone Rows in the Corner
- 4-6 Stone Rows Around the Corner
- 4-7 Stone One Space Notcher on the Side
- 4-5 Stone One Space Notcher in the Corner [Skipped a few from book.]
- And more to come...

Tools and Sources
-----------------
This is done with TeX and the [psgo](http://www.ctan.org/tex-archive/graphics/pstricks/contrib/psgo/) package.

I run this command in Vim to compile the pdf:
    :w|!latex go-status-cards.tex && dvipdf go-status-cards.dvi

Most but not all of the shapes are taken from **Life and Death** by James Davies. I've stuck with the most identifiable and common shapes, and expanded upon them to include the most common alive, dead, and unsettled variations.
