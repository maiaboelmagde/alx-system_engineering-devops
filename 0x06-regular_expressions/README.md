# 0x06-regular_expressions Tasks solutions (Alx program)

## Regular_expressions summary:
 - ##### Repetition Token :
    + "{m, n}" -> exact occurance of a      character/token
    + "?"      -> 0 or 1 occurance of a token
    + "+"      -> 1 or more occurance of token
    + "*"     -> 0 or more occurance of a token

- ##### Anchor Token :
    + "^" -> matches the position at the start of line .
    + "$" -> matches the position at the end of line .
    + "\A" -> matches the position at the start of String .
    + "\Z" -> matches the position at the end of String .

- ##### Character Token :
    + "[a-zA-Z0-9]" -> matches one out of several characters .
    + "[^a-zA-Z0-9]" -> matches any character which is not one of those in the character set .
    + "[a-zA-Z0-9]+" -> matches repeating characters .
   + "[1st - [2nd]]" -> matches any one character in first list but not in the second list .

- ##### Shortcut Character Token :
    + "\d" -> matches any digit .
    + "\s" -> matches any whitespace character .
    + "\w" -> matches any word character i.e. letters, numbers,__
    + "\D", "\S", "\W" -> matches opposite of the above character classes .

