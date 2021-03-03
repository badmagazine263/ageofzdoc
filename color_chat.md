# Using Text Colors and Styles in Age of Z Chat

## Colors

Colors are written as hexadecimal RGBA sequences between square brackets:

[rrggbbaa]

rr = two hexadecimal digits for the intensity of the color Red
gg = two hexadecimal digits for the intensity of the color Green
bb = two hexadecimal digits for the intensity of the color Blue
aa = two hexadecimal digits for the Alpha or opacity of the color

Hexadecimal values for colors go from 00 to FF in hexadecimal, or from 0 to 256 decimal.

So, to write with solid Red, you use:

[ff0000ff]red text

To write with solid Green, you use:

[00ff00ff]green text

To write with solid Blue, you have to use:

[0000ffff]blue text

To write with a color that has a bit of Red, more Green, and even more Blue, you use:

[336699ff]Light-blue text.

## Styles

Bold text is written as: [b]Bold text[/b]

Italic text is written as: [i]Italic text[/i]

Underline text is written as: [u]Underline text[/u]

Strikethrough text is written as: [s]Strikethrough text[/s]

Combinations are possible, for example: [b][i]Bold italic text[/i][/b].

Closing a style tag at the end of the line is optional, for example if the whole line should be bold, the tag may be only opened:

[b]Bold text comment...
