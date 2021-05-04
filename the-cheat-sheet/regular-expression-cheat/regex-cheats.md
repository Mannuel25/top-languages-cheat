To import Regex into your python code, kindly used

`import re`

## Functions/Methods and Keywords in Regex
- <b>search()</b>

This is like finding something and it is more powerful when you specify what you are looking.
This is the function that looks and parse through the data looking for the words intended.

- <b>findall()</b>

This is way more powerful, easier and faster than the `search` function. The findall function would not only doing the
searching only but also create an handle for the getting the output.

You might not really understand this but as we move on, you'll get to understand it better.

## Regex Cheats
<details>
<summary>
<strong>Anchors<strong>
</summary>
<ul>
<li>  `^` - Start of string, or start of line in a multi-line pattern </li>
<li> `\A` - Start of a string </li>
<li> `$` - End of a string, or end of line in a multi-line pattern </li>
<li> `\Z` - End of a string </li>
<li> `\b` - Word boundary </li>
<li> `\B` - Not word boundary 
<li> `\<` - Start of a word
<li> `\>` - End of a word
</ul>
</details> 
<details>
<summary>
<strong>Quantifiers<strong>
</summary>
<ul>
<li>  `*` - Used to match 0 or more of the previous (e.g. xy*z could correspond to "xz", "xyz", "xyyz", etc.) </li>
<li> `?` - Matches 0 or 1 of the previous </li>
<li> `+` - Matches 1 or more of the previous </li>
<li> `{3}` - Matches exactly 3 </li>
<li> `{2, 4}` - Matches everything between 2-4 </li>
</ul>
</details>
<details>
<summary>
<strong>Assertions<strong>
</summary>
<ul>
<li>  `?=` - Lookahead assertion </li>
<li> `?!` - Negative lookahead </li>
<li> `?<=` - Lookbehind assertion </li>
<li> `?>` - Once-only Subexpression </li>
<li> `?#` - Comment </li>
<li> `?()|` - Condition [if then else] </li>
<li> `?()` - Condition [if then] </li>  
</ul>
</details>
<details>
<summary>
<strong>Character Classes<strong>
</summary>
<ul>
<li>  `\c` - Control character </li>
<li> `\s` - White space </li>
<li> `\S` - Not white space </li>
<li> `\d` - Digit </li>
<li> `\D` - Not digit </li>
<li>  `\w` - Word </li>
<li> `\W` - Not word </li>
<li> `\x` - Hexadecimal digit </li>
<li> `\O` - Octal digit </li>
</ul>
</details>
<details>
<summary>
<strong>Special Characters<strong>
</summary>
<ul>
<li>  `\n` - New line </li>
<li> `\r` - Carriage return </li>
<li> `\t` - Tab </li>
<li> `\v` - Vertical tab </li>
<li> `\f` - Form feed </li>
<li> `\xxx` - Octal character xxx </li>
<li> `\xhh` - Hex character hh </li>  
</ul>
</details>
<details>
<summary>
<strong>Groups<strong>
</summary>
<ul>
<li>  `(xyz)` - Grouping of characters </li>
<li> `(?:xyz)` - Non-capturing group of characters </li>
<li> `[xyz]` - Matches a range of characters (e.g. x or y or z) </li>
<li> `[^xyz]` - Matches a character other than x or y or z </li>
<li> `[a-d]` - Matches a character from within a specified range </li>
<li> `[0-9]` - Matches a digit from within a specified range </li>  
</ul>
</details>





 

