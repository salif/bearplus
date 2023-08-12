+++
title = "Markdown Syntax Guide"
date = "2023-08-12"
description = "Sample article showcasing basic Markdown syntax and formatting for HTML elements."
taxonomies.tags = [
    "markdown",
    "syntax",
]
+++

This article offers a sample of basic Markdown syntax that can be used in Zola content files,
also it shows whether basic HTML elements are decorated with CSS in a Zola theme.

## Headings

The following HTML `<h1>`—`<h6>` elements represent six levels of section
headings. `<h1>` is the highest section level while `<h6>` is the lowest.

# H1
## H2
### H3
#### H4
##### H5
###### H6

## Paragraph

Xerum, quo qui aut unt expliquam qui dolut labo. Aque venitatiusda cum,
voluptionse latur sitiae dolessi aut parist aut dollo enim qui voluptate ma
dolestendit peritin re plis aut quas inctum laceat est volestemque commosa as
cus endigna tectur, offic to cor sequas etum rerum idem sintibus eiur? Quianimin
porecus evelectur, cum que nis nust voloribus ratem aut omnimi, sitatur?
Quiatem. Nam, omnis sum am facea corem alique molestrunt et eos evelece arcillit
ut aut eos eos nus, sin conecerem erum fuga. Ri oditatquam, ad quibus unda
veliamenimin cusam et facea ipsamus es exerum sitate dolores editium rerore
eost, temped molorro ratiae volorro te reribus dolorer sperchicium faceata
tiustia prat.

Itatur? Quiatae cullecum rem ent aut odis in re eossequodi nonsequ idebis ne
sapicia is sinveli squiatum, core et que aut hariosam ex eat.

## Blockquotes

The blockquote element represents content that is quoted from another source,
optionally with a citation which must be within a `footer` or `cite` element,
and optionally with in-line changes such as annotations and abbreviations.

#### Blockquote without attribution

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.
> **Note** that you can use *Markdown syntax* within a blockquote.

#### Blockquote with attribution

> All men by nature desire to know.<br>
> ― <cite>Aristotle[^1]</cite>

## Tables

Tables aren't part of the core Markdown spec, but Zola supports them
out-of-the-box.

   Name | Age
--------|------
    Bob | 27
  Alice | 23

#### Inline Markdown within tables

| Italics   | Bold     | Code   |
| --------  | -------- | ------ |
| *italics* | **bold** | `code` |

## Code Blocks

#### Code block with backticks

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```

#### Code block indented with four spaces

    <!doctype html>
    <html lang="en">
    <head>
      <meta charset="utf-8">
      <title>Example HTML5 Document</title>
    </head>
    <body>
      <p>Test</p>
    </body>
    </html>

## List Types

#### Ordered List

1. First item
2. Second item
3. Third item

#### Unordered List

- List item
- Another item
- And another item

#### Nested list

- Fruit
  - Apple
  - Orange
  - Banana
- Dairy
  - Milk
  - Cheese

## Math Formulas

#### Inline Math

The Pythagorean theorem is $a^2 + b^2 = c^2$.

#### Display Math

$$
\begin{aligned}
\sin\alpha &= \frac{a}{c} \\\\
\sin\beta  &= \frac{b}{c} \\\\
       c   &= b\sin\beta+a\sin\alpha=\frac{b^{2}}{c}+\frac{a^{2}}{c} \\\\
      c^2  &= a^2 + b^2
\end{aligned}
$$

## Other Elements — abbr, sub, sup, kbd, mark

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> to end the
session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and
other small creatures.[^2]

---
<!-- Note: There must be a blank line between every two lines of the footnote difinition.  -->
[^1]: Aristotle. "Metaphysics". Translated by W. D. Ross. The Internet Classics Archive, 350 B.C.E. <https://classics.mit.edu/Aristotle/metaphysics.html>. Accessed 12 August 2023.

[^2]: The Editors of Encyclopaedia Britannica. "salamander". Encyclopedia Britannica, 23 Jun. 2023, <https://www.britannica.com/animal/salamander>. Accessed 12 August 2023.