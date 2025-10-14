# Markdown Cheatsheet

## Headers

```txt
# H1

## H2

### H3

#### H4

##### H5

###### H6
```

# H1

## H2

### H3

#### H4

##### H5

###### H6

## Emphasis

```txt
Emphasis, aka italics, with _underscores_.

Strong emphasis, aka bold, with **asterisks**.

Combined emphasis with **asterisks and _underscores_**.
```

Emphasis, aka italics, with _underscores_.

Strong emphasis, aka bold, with **asterisks**.

Combined emphasis with **asterisks and _underscores_**.

## Lists (Unordered)

```txt
- List item 1
  - Sub-list item 1
    - Sub-sub-list item 1
  - Sub-list item 2
- List item 2
  - Sub-list item 2
- List item 3
```

- List item 1
  - Sub-list item 1
    - Sub-sub-list item 1
  - Sub-list item 2
- List item 2
  - Sub-list item 2
- List item 3

## Lists (Ordered)

```txt
1. List item 1
   1. Sub-list item 1
      1. Sub-sub-list item 1
   1. Sub-list item 2
1. List item 2
   1. Sub-list item 2
1. List item 3
```

1. List item 1
   1. Sub-list item 1
      1. Sub-sub-list item 1
   1. Sub-list item 2
1. List item 2
   1. Sub-list item 2
1. List item 3

## Links

[Local link](./README.md)

[Local link to Lists (Unordered)](#lists-unordered)

[External link](https://www.google.com/)

[External link with Title (hover to see the title)](https://www.google.com/ 'This is known as the title attribute')

## Images

![Local image alt text](./static/img/favicon.ico)

![External image alt text](https://www.gstatic.com/images/branding/searchlogo/ico/favicon.ico)

## Quotes

> This is
> a blockquote
>
> > Nested
> > Blockquote

## Tables

| Column 1 Heading | Column 2 Heading |
| ---------------- | ---------------- |
| Some content     | Other content    |

## Code

`inline code`

```
fenced codeblock.
these can be multiple lines.
```

```js
codeFences.withLanguage();
codeFences.addsLanguageSyntaxHighlighting;
```

    4 space indent also makes a fenced codeblock

## Horizontal line

---

## Comments

```txt
<!-- This is a comment that will not be shown in the rendered output -->

<!--
  These are the same as HTML comments.
  You can do them in multiple lines.
-->
```

<!-- This is a comment that will not be shown in the rendered output -->

<!--
  These are the same as HTML comments.
  You can do them in multiple lines.
-->

## VSCode Snippets

There are some built-in VSCode snippets for common Markdown syntax. See snippets via `Ctrl+Space` or `Cmd+Space` in a Markdown file. A snippet has an empty looking square on the left side of the suggestion. Press `Tab` to insert the snippet.
