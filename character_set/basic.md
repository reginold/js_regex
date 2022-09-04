### Match exmaple
- gray or grey
    - /gr[ae]y/

### Specify the range -> think the character as a single one
- /[1-4]/
- /[a-e]/

### Exclude a character set
- /0x[^0-9A-F] [^0-9A-F] ^\ / -> exception 0xF89F^

### Escape charater in a dataset
- Metacharacter you need to escape
    - "-"
    - "^"
    - "\"
    - "]

### Shorthand for character sets
- \d = [0-9]
- \w = [a-zA-Z0-9_] not hyphen but underscore including
- \s = [ \t\r\n] white space, tab, carriage return, a new line feed
#### On the opposite
- \D = [^0-9]
- \W = [^a-zA-Z0-9__] 
- \S = [^ \t\r\n] exclude white space, tab, carriage return, a new line feed