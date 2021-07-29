| Metacharacters | Meaning |
| ----- | ----- |
| \a | Alert | 
| \b Backspace |
| \n Newline |
| \r | Carriage return |
| \f | Form feed |
| \t | Horizontal tab |
| \octal | Character specified by a three-digit octal code |
| [...] | Range |
| [^...] | Not in range |
| . | Any character except newline |
| \w | Word character [a-zA-Z0-9_] |
| \W | Nonword character [^a-zA-Z0-9_] |
| \d | Digit character [0-9] |
| \D | Nondigit character [^0-9] |
| \s | Whitespace character [\n\r\f\t] |
| \S | Nonwhitespace character [^\n\r\f\t] |
| ^ | Start of string |
| \A | Start of search string, in all match modes |
| $ | End of string |
| \Z | End of string, or the point before a string-ending newline, in any match mode |
| \b | Word boundary |
| \B | Not-word-boundary |
| (?=...) | Positive lookahead |
| (?!...) | Negative lookahead |
| (?<=...) | Positive lookbehind |
| (?<!...) | Negative lookbehind |
| i | Case-insensitive matching |
| m | ^ and $ match next to embedded \n |
| s | Dot (.) matches newline |
| x | Ignore whitespace, and allow comments (#) in pattern |
| (?mode) | Turn list modes on fot the rest of the subexpression |
| (?#...) | Treat substring as a comment |
| #... | Rest of the line is treated as a comment in x mode |
| (...) | Group subpattern and capture submatch into \1, \2, .. |
| \n | Contains the result of nth earlier submatch from a parentheses capture group, or a named 
capture group |
| (?:...) | Groups subpattern, but does not capture submatch |
| * | Match 0 or more times |
| +| Match 1 or more times |
| ? | Match 1 or 0 times |
| {n} | Match exactly n times |
| {x,y} | Match at least x times, but no more than y times |
| *? | Match 0 or more times, but a few times as possible |
| +? | Match 1 or more times, but a few times as possible |
| ?? | Match 0 or 1 times, but as few times as possible |
| {x,y}? | Match at least x times, no more than y times, and as few times as possible |
