Hi, I am Rahul Chaky. I am just trying out Github.

# Markdown Reference Sheet

### Escape Characters
Escape a Character: ( \\ char ) \
Also note that: \
\\ <- Newline

## Headings
Large Heading ( \# text ) \
Medum Heading ( \## text ) \
Small Heading ( \### text ) 

## Text Styling
Bold Text ( \*\*text\*\* ) \
**Winter is here, and it's BOLD**

Italic Text ( \*text\* ) \
*Example Text*

Blockquote ( \> text )
> "You have eyes but failed to see Mt. Tai."

Code ( \` text \` ) \
`print(Hello World!)`

Strikethrough ( \~ text \~ ) \
~The world is flat.~

Subscript ( \<sub\> text \<\/sub\> ) \
H<sub>2</sub>O

Superscript ( \<sup\> text \<\/sup\> ) \
X<sup>2</sup>

## Lists
Ordered List ( 1. text )
1. This
2. is
3. an
4. ordered
5. list

Unordered List ( \- text )
- This
- is
- an
- unordered
- list

Task List ( \- \[ \] text ) and (  \- \[x\] text )

- [x] Cope
- [ ] Cope some more
- [ ] Cope even harder


## Horizontal Rule
Type 1: ( \-\-\- )
---
Type 2: ( \*\*\* )
***
Type 3: ( \_\_\_ )
___
Note: Horizontal Rules affect text size.

## Links
Notation: ( \[text for hyperlink\](url) ) \
[Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

## Images
Notation: ( !\[alt text\](image.jpg) ) \
![Wormhole Tutorial](meme.jpg)

## Tables
Syntax : \
\| Table \| Description \| \
\| ----------- \| ----------- \| \
\| Header \| Title \| \
\| Paragraph \| Text \|

| Column1 | Column2 |
| ----------- | ----------- |
| Row1 | x |
| Row2 | y |

## Fenced Code Block
This has code over multiple lines. ( \`\`\` text \`\`\` )

```
{
  "firstName": "Rahul",
  "lastName": "Chaky",
  "age": 21
}
```

## Footnote
Syntax Pt.1: ( \[\^text\] ) \
Use the syntax where you would like to have a marker for the footnote in the text. \
Syntax Pt.2: ( \[\^text\]: ) \
Use the syntax where you would like to write the footnote. \

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.


