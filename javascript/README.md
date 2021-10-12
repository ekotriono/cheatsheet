# Javascript Cheat Sheet

| Character | Meaning | Example  |
| --- | --- | --- |
^ | the beginning of the string	
$ | the end of the string	
\b | whole word only | \babc\b matches 'abc', but not 'abcc '
\B | if the pattern is fully surrounded by word | \Babc\B mathes 'aabcc', but not 'abc'
. | anything	
\d | single digit in 0-9	
\D | single non-digit	
\w | single word character	
\W | single non-word	
\s | white space(space, tab, return, new line)	
\S | non-whitespace	
\t | tab	
\r | return	
\n | new line	
\g | global search, which means it doesn't stop at the first match	
* | zero or more of the previous | abc* matches a string that has ab followed by zero or more c
+ | one or more of the previous | abc+ matches a string that has ab followed by one or more c
? | zero or one of the previous | abc? matches a string that has ab followed by zero or one c
?: | non-capturing group	
X{m} | number of X === m	
X{m,} | m < number of X	
X{m, n} | m < number of X < n	
(X | Y) | X or Y	
[...] | any of characters in the class | [abcd] matches a string that has one of the char (a, b, c, d)
- | range | [a-d] same as above