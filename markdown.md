## 1. Syntax Cheat Sheet

| Element | Markdown Syntax | Result |
|---------|-----------------|--------|
| Heading 1 | `# Heading` | Largest heading |
| Heading 2 | `## Heading` | Second level |
| Heading 3 | `### Heading` | Third level |
| Bold | `**bold text**` | **bold text** |
| Italic | `*italic text*` | *italic text* |
| Bold and italic | `***both***` | ***both*** |
| Strikethrough | `~~deleted~~` | ~~deleted~~ |
| Inline code | `` `code` `` | `code` |
| Link | `[Text](https://example.com)` | Clickable link |
| Image | `![Alt text](image.png)` | Shows an image |
| Quote | `> quoted text` | Indented quote |
| Bullet list | `- item` | Bulleted list |
| Numbered list | `1. item` | Numbered list |
| Task list | `- [ ] todo` / `- [x] done` | Checkboxes |
| Horizontal line | `---` | Divider line |

## 2. Examples

### Headings

````markdown
# Heading 1
## Heading 2
### Heading 3
````

Add a space after the `#` symbols. Use one `#` heading per page as the title.

### Text Formatting

````markdown
This is **bold**, this is *italic*, and this is ~~strikethrough~~.
````

### Lists

````markdown
- Item one
- Item two
  - Nested item (indent with 2 spaces)

1. First
2. Second
3. Third
````

### Links and Images

````markdown
[Visit GitHub](https://github.com)
![Logo](images/logo.png)
````

To link to another file in the same repo, use a relative path: `[Guide](docs/guide.md)`.

### Code Blocks

Use three backticks. Add the language name for colors (syntax highlighting).

````markdown
```python
name = "Sam"
print(f"Hello {name}")
```
````

Common language names: `python`, `bash`, `json`, `yaml`, `javascript`, `dockerfile`.

### Tables

````markdown
| Name  | Age | City  |
|-------|-----|-------|
| Sam   | 20  | Delhi |
| Riya  | 22  | Pune  |
````

Alignment: `:---` left, `:---:` center, `---:` right.

````markdown
| Left | Center | Right |
|:-----|:------:|------:|
| a    |   b    |     c |
````

### Blockquote

````markdown
> This is a quote.
> It can span multiple lines.
````

### Task List

````markdown
- [x] Learn Git basics
- [ ] Learn Docker
- [ ] Learn Kubernetes
````

### Collapsible Section (GitHub)

````markdown
<details>
<summary>Click to expand</summary>

Hidden content goes here.

</details>
````

## 3. Useful Tricks

| Need | How |
|------|-----|
| New line inside a paragraph | End the line with two spaces, or leave a blank line between paragraphs |
| Show a special character literally | Put a backslash before it, e.g. `\*not italic\*` |
| Comment (not shown) | `<!-- this is a comment -->` |
| Link to a heading | `[Go to Tables](#tables)` (lowercase, spaces become hyphens) |
| Badge image | `![Python](https://img.shields.io/badge/python-3.12-blue)` |

## 4. Special Files on GitHub

| File | Purpose |
|------|---------|
| `README.md` | Shown automatically on the repo home page |
| `CONTRIBUTING.md` | Rules for people who want to contribute |
| `LICENSE.md` | License information |
| `CHANGELOG.md` | List of changes between versions |
