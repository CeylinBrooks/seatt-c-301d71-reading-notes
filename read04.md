https://regexr.com/

https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285


Anchors — ^ and $ ^The matches any string that starts with The -> Try it! end$ matches a string that ends with end ^The end$ exact string match (starts and ends with The end) roar matches any string that has the text roar in it

abc* matches a string that has ab followed by zero or more c
abc+ matches a string that has ab followed by one or more c abc? matches a string that has ab followed by zero or one c abc{2} matches a string that has ab followed by 2 c abc{2,} matches a string that has ab followed by 2 or more c abc{2,5} matches a string that has ab followed by 2 up to 5 c a(bc)* matches a string that has a followed by zero or more copies of the sequence bc a(bc){2,5} matches a string that has a followed by 2 up to 5 copies of the sequence bc

Bracket expressions — [] [abc] matches a string that has either an a or a b or a c -> is the same as a|b|c -> Try it! [a-c] same as previous [a-fA-F0-9] a string that represents a single hexadecimal digit, case insensitively -> Try it! [0-9]% a string that has a character from 0 to 9 before a % sign [^a-zA-Z] a string that has not a letter from a to z or from A to Z. In this case the ^ is used as negation of the expression

