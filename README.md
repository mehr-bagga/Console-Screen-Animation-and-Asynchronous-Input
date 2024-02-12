built a Marquee Display Banner with the following features:
Upon startup, the program rolls a string of “>><<” across a 20x1 (Columns x Rows) marquee display area from
right to left.
• When the display contents reach the leftmost display boundary, it must wrap around character-by-character to
the rightmost boundary.
• For every alphabet / number pressed on the keyboard, it must be immediately inserted into the string between
the “>>” (header) and “<<” (footer) symbols, and the newly entered character must roll along across the display
with the existing contents between the header and footer
All subsequent inserted contents must be cascaded to the existing contents between the header and footer in
the left-to-right sequential order.
• You may have to set an upper limit to the number of characters that can be inserted to the display string to
prevent overwhelming the display area with too many characters.
• You may want to set up a key to shut down the program.
• Advanced Features (Above and Beyond Activities)
o Implement a key that can toggle the rolling direction of the string movement.
o Implement a marquee display that can roll a string of more than 20 characters across the 20x1 display
window. Think about how.
