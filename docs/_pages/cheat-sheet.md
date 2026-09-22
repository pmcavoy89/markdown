---
title: Cheat Sheet
subtitle: Quickly reference the syntax to create wonderful Markdown pages
layout: page
featured_image: /images/markdown.jpg
toc: true
---

# Table of Contents

- [Headers](#headers)
- [Italics](#italics)
- [Bold / Emphasis](#bold--emphasis)
- [Blockquote](#blockquote)
- [Code](#code)
- [Code Block](#code-block)
- [Organized Lists](#organized-lists)
- [Unorganized Lists](#unorganized-lists)
- [Checklist](#checklist)
- [Links](#links)
- [Images](#images)
- [Videos](#videos)

### Headers

Headers go in size, typically up to level 5, with each subsequent `#` lowering the level.

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

### Italics

Code:

```markdown
Adding _italics_, useful for titles.
_Programming Pat_
```

Output:
Adding _italics_, useful for titles.

_Programming Pat_

### Bold / Emphasis

Code:

```markdown
Adding **bold/emphasis**, useful for definitions.

**Programming Pat** is a useful website for learning all things tech.
```

Output:
Adding **bold/emphasis**, useful for definitions.

**Programming Pat** is a useful website for learning all things tech.

### Blockquote

Code:

```markdown
> Blockquote
```

Output:

> Blockquote

### Code

Code:

```markdown
Adding `code`, useful for talking about variables.
```

Output:

Adding `code`, useful for talking about variables.

### Code Block

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

### Organized Lists

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

### Unorganized Lists

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

### Checklist

TODO: Fix the CSS or the rendering from the gem.

Code:

```markdown
- [ ] To Do Item 1
- [ ] To Do Item 2
- [ ] To Do Item 3
```

Output:

- [ ] To Do Item 1
- [x] To Do Item 2
- [ ] To Do Item 3

### Links

```markdown
Keep in mind, the `-` creates a list item. You can have an [cool link](https://programmingpat.com/markdown) in your sentence.

- [Next page](/markdown/next-page)
- [Level 1 Header](#level-1-header)
- [Another Website](https://example.com "On Hover Message - Optional")
- [Programming Pat](https://www.programmingpat.com "A Cool Website")
```

Output:

Keep in mind, the `-` creates a list item. You can have an [cool link](https://programmingpat.com/markdown) in your sentence.

- [Next page](/markdown/next-page)
- [Level 1 Header](#level-1-header)
- [Another Website](https://example.com "On Hover Message - Optional")
- [Programming Pat](https://www.programmingpat.com "A Cool Website")

### Images

Code:

```markdown
![Alternate text](./basic-image.png)
![Shown When Image Not Found](./not-found.png)
![Awesome Logo](./images/logo_personal.png)
```

![Alternate text](./basic-image.png)

![Shown When Image Not Found](./not-found.png)

TODO: Edit the size
![Awesome Logo](./images/logo_personal.png)

### Videos

Code:

```

```

Output:
