# case-casting

This project defines casting form upper case to lower case and vice versa for
the Dutch language. This is of course extremely trivial. However, the list
provided here can be used to do casting or to test casting software.

The casting is defined in the tab-seprated file [case-casting.tsv](https://raw.githubusercontent.com/OpenTaal/case-casting/master/case-casting.tsv)
of which the first line holds the header. For the lines following, the first column holds lower case characters and the second column upper case
characters. This file can be used in a text editor, spreadsheet application or
custom software. A more readable  rendered version can be found [here](https://github.com/OpenTaal/case-casting/blob/master/case-casting.tsv).

For the Dutch language, there are no requirements for casting of characters
which are not in the list provided here. Casting between such characters can be
done by the default behaviour of the used programming language or software
library. This is also trivial for casting between Ł and ł but can prove a
problem for casting between Σ and σ or ς.
