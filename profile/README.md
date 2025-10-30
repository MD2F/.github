# MD2F - Markdown 2 File

![MD2F Banner](https://via.placeholder.com/800x200.png?text=MD2F)

## About the Project

**MD2F** is a tool to convert Markdown files into HTML and other outputs, supporting:

* Full GitHub-flavored Markdown
* Tables, links, and images
* Nested lists, blockquotes, and code blocks
* Multi-page Markdown files
* Automatic fallback when a file fails to load

The goal of the project is to provide a **simple, flexible, and clear** tool for working with Markdown documentation.

## Features

* ✅ Markdown → HTML conversion
* ✅ Support for relative and absolute URLs
* ✅ Fallback file if loading fails
* ✅ Support for nested lists (`1.1`, `a.a`) and mixed `*` / `-` styles
* ✅ Nested blockquotes (`>`) and code blocks (`lang`)
* ✅ Styled outputs with CSS
* ✅ Multi-page Markdown and tabbed HTML views
* ✅ Optimized for quick web Markdown display

## Installation

**Requirements:**

* Python ≥ 3.8
* PyQt5
* Other dependencies listed in `requirements.txt`

```bash
git clone https://github.com/your-username/MD2F.git
cd MD2F
pip install -r requirements.txt
```

## Usage

Run the application:

```bash
python main.py
```

Open a Markdown file via URL:

```
project/?url=path/to/markdown.md
```

If the file cannot be loaded, it will automatically open the fallback Markdown `res/md/404.md`.

## Example

```markdown
# Heading 1

## Heading 2

* List item
  * Sub-item
- Another item

1. Numbered list
   1.1 Sub-item
   1.2 Sub-item

> Blockquote

**Bold text**, *italic text*

[Link](https://github.com)
![Image](https://via.placeholder.com/150)
```

## Contributing

Contributions are welcome! Open a Pull Request or an issue.

## License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

© 2025 Jan Poláček
