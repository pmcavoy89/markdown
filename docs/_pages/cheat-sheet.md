---
title: Cheat Sheet
subtitle: Quickly reference the syntax to create wonderful Markdown pages
layout: page
featured_image: /images/markdown.jpg
---

# Table of Contents

- [Headers](#headers)
- [Horizontal Rule](#horizontal-rule)
- [Italics](#italics)
- [Bold / Emphasis](#bold--emphasis)
- [Blockquote](#blockquote)
- [Code](#code)
- [Code Block](#code-block)
- [Organized Lists](#organized-lists)
- [Unordered Lists](#unordered-lists)
- [Links](#links)
- [Images](#images)
- [Videos](#videos)
- [GitHub-Flavor Markdown](#github-flavor-markdown)
  - [Checklist](#checklist)
  - [Tables](#tables)
  - [Strikethrough](#strikethrough)

## Headers

Headers decrease in size, typically up to level 5, with each subsequent `#` lowering the level.

Code:

```markdown
# Level 1

## Level 2

### Level 3

#### Level 4

##### Level 5
```

Output:

# Level 1 Header

## Level 2

### Level 3

#### Level 4

##### Level 5

## Horizontal Rule

Code:

```markdown
---

The dashes above create the Horizontal Rule.
```

Output:

---

The dashes above create the Horizontal Rule.

## Italics

Code:

```markdown
Adding _italics_, useful for titles.
_Programming Pat_
```

Output:
Adding _italics_, useful for titles.

_Programming Pat_

## Bold / Emphasis

Code:

```markdown
Adding **bold/emphasis**, useful for definitions.

**Programming Pat** is a useful website for learning all things tech.
```

Output:
Adding **bold/emphasis**, useful for definitions.

**Programming Pat** is a useful website for learning all things tech.

## Blockquote

Code:

```markdown
> Blockquote
>
> > Double Blockquote
```

Output:

> Blockquote
>
> > Double Blockquote

## Code

Code:

```markdown
Adding `code`, useful for talking about variables.
```

Output:

Adding `code`, useful for talking about variables.

## Code Block

````markdown
```markdown
This is a _markdown code block_.
```

```javascript
const another = "language";
let index = 0;

index++;

console.log("Hello Programmer");
```
````

Output:

```markdown
This is a _markdown code block_.
```

```javascript
const another = "language";
let index = 0;

index++;

console.log("Hello Programmer");
```

## Organized Lists

Code:

```markdown
1. Item One
1. Item Two
1. Item Three
1. Item N...
```

Output:

1. Item One
1. Item Two
1. Item Three
1. Item N...

## Unordered Lists

Code:

```markdown
- List Item
- Another List Item
- Last List Item
```

Output:

- List Item
- Another List Item
- Last List Item

## Links

```markdown
Keep in mind, a hyphen, `-`, creates a list item. You can have a [cool link](https://programmingpat.com/markdown) in your sentence.

- [Next page](/markdown/next-page)
- [Level 1 Header](#level-1-header)
- [Another Website](https://example.com "On Hover Message - Optional")
- [Programming Pat](https://www.programmingpat.com "A Cool Website")
```

Output:

Keep in mind, a hyphen, `-`, creates a list item. You can have a [cool link](https://programmingpat.com/markdown) in your sentence.

- [Next page](/markdown/next-page)
- [Level 1 Header](#level-1-header)
- [Another Website](https://example.com "On Hover Message - Optional")
- [Programming Pat](https://www.programmingpat.com "A Cool Website")

## Images

Code:

```markdown
![Alternate text](./not-found.png)
![Shown When Image Not Found](./not-found.png)
![Personal Logo](./images/personal_logo.png)
```

![Alternate text](./not-found.png)

![Shown When Image Not Found](./not-found.png)

![Personal Logo](/markdown/images/personal_logo.png)

> **Note**: The above image of `./images/not-found.png` is not in my project. It is to show you the example of "Alternate text." Depending on the browser, the user may or may not see the text on the page.

> **Fun Fact**: Using alternate text is a great way to afford accessibility for screen readers. Check out [Section 508](https://www.section508.gov/training/alt-text/what-is-alternative-text/).

## Videos

Code:

```
<a href="https://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="https://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg"
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

<a href="https://www.youtube.com/watch?feature=player_embedded&v=FDAsGmiSgVQ
" target="_blank"><img src="https://img.youtube.com/vi/FDAsGmiSgVQ/0.jpg"
alt="Red Black Tree Example Part 1" width="240" height="180" border="10" /></a>
```

Output:

<a href="https://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="https://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg"
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

> **Note**: The above video is the broken YouTube link as it has the `YOUTUBE_VIDEO_ID_HERE` which you can find in the URL, such as; `https://www.youtube.com/watch?v=FDAsGmiSgVQ`.

<a href="https://www.youtube.com/watch?feature=player_embedded&v=FDAsGmiSgVQ
" target="_blank"><img src="https://img.youtube.com/vi/FDAsGmiSgVQ/0.jpg"
alt="Red Black Tree Example Part 1" width="240" height="180" border="10" /></a>

## GitHub-Flavor Markdown

This markdown is supported on GitHub and many other web apps (but not all). This allows to extend on the regular markdown you know and make it even more useful for organizing and sharing thoughts or tasks.

### Checklist

Code:

```markdown
- [ ] To Do Item 1
- [ ] To Do Item 2
- [x] To Do Item 3
```

Output:

- [ ] To Do Item 1
- [ ] To Do Item 2
- [x] To Do Item 3

### Tables

Code:

```markdown
| Table | Column 1  | Column 2  |
| ----- | --------- | --------- |
| Row 1 | Value 1,1 | Value 1,2 |
| Row 2 | Value 2,1 | Value 2,2 |
```

Output:

| Table | Column 1  | Column 2  |
| ----- | --------- | --------- |
| Row 1 | Value 1,1 | Value 1,2 |
| Row 2 | Value 2,1 | Value 2,2 |

> **Note**: Please read `Value 1,2` as the value for the `Value RowNumber,ColumnNumber`.

### Strikethrough

Code:

```markdown
~~Don't read.~~ Read all the things.
```

Output:

~~Don't just read.~~ Enjoy.
