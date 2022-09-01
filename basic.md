### String Methods
- Match: return an array of matches just like exec on RegExp
- Search: return an index of the matched string
- Replace: replaces matches with astring
- Split: splits a string into an array. The division is based on the regular expression pattern

```.js
let text = "yes, this is the text."

let regex1 = /yes/;
let regex2 = /word/;

console.log(text.match(regex1));
```
### Regular Expressions Flags
- /pattern/flags; or new RegExp("pattern", "flags");
- g - global, match more than one occurance
- i - case insensitive match, case doesn't matter
- m - multi-line match
```.js
let text = "yes, this is the text."

let regex1 = /\s/g;
let regex2 = /word/;

console.log(text.match(regex1));
// ["s ", "s "]
```

### Using Regexpal
- Try the test at this website.
  - https://www.regexpal.com/
    - Flag
    - Top regular expressions
    - Cheat Sheet  

### Control Characters
- \t tab
- \v vertical tab
- \n newline
- \r carriage return
