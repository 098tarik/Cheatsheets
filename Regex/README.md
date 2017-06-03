# REGEX


### Character Representations

Character  | Replaces
--- | ---
. | Represents any character
\ | Escapes a character
[] | Matches one char inside bracket
[^] | Matches anything BUT bracket contents


### RANGES

Must be escaped in [] brackets

Range | Character  | Replaces
--- | --- | ---
A-Z | | Uppercase Letters
a-z | | Lowercase Letters
0-9 | \d | Numbers
| | \w | Alphanumeric Characters and Digits
| | \s | Whitespace (\t \n \r)
| | \D | Non-digit
| | \W | Non-alphanumeric
| | \S | Non-whitespace


### Multiplicity

Character  | Replaces
--- | ---
\* | 0 or more
\+ | 1 or more
? | 0 or 1 (optionality)
{n} | n Repitions
{a,b} | anywhere from a to b repitions


### Position

Character | Indicates
--- | ---
^ | Beginning
$ | Ending


### Capture Groups

() Represent a capture group that stores the contained matching metacharacters

Capture Groups can be accessed again by \<n> where n is the number of the capture group ( \1 \2 \3 )

Groups are numbered by the appearance of their openning parenthesis, (. This means that capture groups will function even when nested



### Optional patterns

| between (  ) will match either the pattern on the left or the one on the right

(<pattern>|<pattern>)







