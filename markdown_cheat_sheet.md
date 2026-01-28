# Markdown Cheat Sheet

Quick reference for common Markdown features (CommonMark + GitHub Flavored Markdown).

---

## Headings

# H1
## H2
### H3
#### H4
##### H5
###### H6

## Emphasis

- *Italic* — `*italic*` or `_italic_`
- **Bold** — `**bold**` or `__bold__`
- ***Bold italic*** — `***text***`
- ~~Strikethrough~~ — `~~strikethrough~~`

## Lists

Unordered:
- Dash: `- Item`
- Asterisk: `* Item`
- Plus: `+ Item`

Nested:
- Parent
  - Child (indent by two spaces or a tab)

Ordered:
1. First
2. Second
3. Third

Task list (GitHub):
- [x] Done
- [ ] To do

## Links & Images

Inline link: [GitHub](https://github.com "GitHub") — `[GitHub](https://github.com "GitHub")`

Reference-style link:

[example]: https://example.com "Example Site"
Use: [Example][example]

Image: ![Alt text](https://via.placeholder.com/150 "Optional title") — `![Alt text](url "title")`

## Code

Inline code: `inline()` — wrap with backticks.

Fenced code block:

```js
// JavaScript example
function greet(name) {
  return `Hello, ${name}!`;
}
```

Indented code blocks (4 spaces) also work but fenced blocks are preferred.

## Tables (GitHub Flavored Markdown)

| Column A | Column B | Centered |
|:-------- |:-------:|:-------:|
| left     | centered| right   |
| 1        | 2       | 3       |

## Blockquotes

> This is a blockquote.
> 
> Use `>` at the start of the line for quoting.

Nested blockquote:
> Quote
>> Nested quote

## Horizontal Rule

Use three or more hyphens, asterisks, or underscores:

---

## Footnotes (GitHub)

Here's a sentence with a footnote.[^1]

[^1]: This is the footnote content.

## Escaping

Use a backslash to escape special characters: `\*escaped\*` → \*escaped\*

## HTML in Markdown

You can include inline HTML for elements not available in Markdown:

<kbd>Ctrl</kbd>+<kbd>C</kbd>

Use with care — some renderers sanitize HTML.

## Definition List (not standard in CommonMark; supported by some renderers)

Term
: Definition of the term.

## KaTeX / Math (supported by some renderers)

Inline math: $e^{i\pi} + 1 = 0$

Block math:

$$
\int_0^1 x^2 \,dx = \frac{1}{3}
$$

(Requires renderer support for KaTeX/MathJax.)

## Misc

- Emoji (GitHub): `:smile:` → :smile:
- Mention: `@username` (platform-specific)
- Table of contents: generated automatically on some platforms or via plugins

## Quick Reference — CommonSyntax

- Header: `# Header`
- Bold: `**bold**`
- Italic: `*italic*`
- Code inline: `` `code` ``
- Code block: ```` ```lang ... ``` ````
- Link: `[text](url)`
- Image: `![alt](url)`
- Quote: `> quote`
- List: `- item` or `1. item`

---

If you want this tailored for a specific renderer (GitHub, GitLab, Hugo, Jekyll, etc.), tell me which one and I can adjust examples.
