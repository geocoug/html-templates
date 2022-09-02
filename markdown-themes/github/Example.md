# Markdown Guide

![The Ultimate Guide to Markdown](http://blog.ghost.org/content/images/2015/03/markdown-guide-1.jpg)

## Basic Markdown Formatting

### Headings

```md
# This is an <h1> tag
## This is an <h2> tag
### This is an <h3> tag
#### This is an <h4> tag
##### This is an <h5> tag
###### This is an <h6> tag
```

### Emphasis

```md

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

```

### Lists

```md
**Inordered:**

* Milk
* Bread
    * Wholegrain
* Butter
```

Result:

* Milk
* Bread
  * Wholegrain
* Butter

**Ordered:**

```md
1. Tidy the kitchen
1. Prepare ingredients
1. Cook delicious things
```

Result:

1. Tidy the kitchen
1. Prepare ingredients
1. Cook delicious things

### Images

```md
![Alt Text](url)
```

Result:

![m'lady](http://i.imgur.com/v8IVDka.jpg)

### Links

```md
[link](http://example.com)
```

Result:

[link](http://example.com)

### Blockquotes

```md
As Kanye West said:

> We're living the future so
> the present is our past.
```

Result:

As Kanye West said:
> We're living the future so
> the present is our past.

### Horizontal Rules

```md
---
```

Result:

---

### Reference Lists & Titles

```md

**The quick brown [fox][1], jumped over the lazy [dog][2].**

[1]: https://en.wikipedia.org/wiki/Fox "Wikipedia: Fox"
[2]: https://en.wikipedia.org/wiki/Dog "Wikipedia: Dog"

```

Result:

**The quick brown [fox][1], jumped over the lazy [dog][2].**

[1]: https://en.wikipedia.org/wiki/Fox "Wikipedia: Fox"
[2]: https://en.wikipedia.org/wiki/Dog "Wikipedia: Dog"

### Embedding HTML

```html

<button class="button-save large">Big Fat Button</button>

```

## Advanced Markdown

Note: Some syntax which is not standard to native Markdown. They're extensions of the language.

### Strike-throughs

```md

~~deleted words~~

```

Result:

~~deleted words~~

### Markdown Footnotes

Work in [Ghost](https://ghost.org/):

```md

The quick brown fox[^1] jumped over the lazy dog[^2].
[^1]: Foxes are red
[^2]: Dogs are usually not red

```

Result:

The quick brown fox[^1] jumped over the lazy dog[^2].

[^1]: Foxes are red
[^2]: Dogs are usually not red

## GitHub Flavored Markdown

### Syntax Highlighting

```md

```javascript
function fancyAlert(arg) {
    if(arg) {
    $.facebox({div:'#foo'})
    }
}

```

Result:

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

### Task Lists

```md
* [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
* [x] list syntax required (any unordered or ordered list supported)
* [x] this is a complete item
* [ ] this is an incomplete item
```

### Tables

You can create tables by assembling a list of words and dividing them with hyphens `-` (for the first row), and then separating each column with a pipe `|`:

```md
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```

### Username @mentions

Typing an `@` symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.

### Emoji

GitHub supports emoji! Check out the [Emoji Cheat Sheet](http://www.emoji-cheat-sheet.com/).

## References

* [http://blog.ghost.org/markdown/](http://blog.ghost.org/markdown/)
* [https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)
