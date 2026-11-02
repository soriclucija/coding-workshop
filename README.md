# coding-workshop

Source code for the [Workshop on Data Extraction and Coding for Meta-Analysis](https://soriclucija.github.io/coding-workshop/) website, a single-page guide with embedded slides for students and research assistants joining our meta-analysis coding team at Tilburg University.

Built with [Quarto](https://quarto.org) and hosted on GitHub Pages.

## Getting started

### Prerequisites

- [Quarto](https://quarto.org/docs/get-started/)
- RStudio (optional)

### Installation

```bash
git clone https://github.com/soriclucija/coding-workshop.git
cd coding-workshop
```

### Usage

Preview the page locally:

```bash
quarto preview index.qmd
```

Build the page and the slides:

```bash
quarto render index.qmd
quarto render slides/01-intro.qmd
quarto render slides/02-zotero.qmd
```

The output (`index.html` and the slide `.html` files) is written next to the source files, which GitHub Pages serves from the root of the `main` branch.

## License

[MIT](LICENSE)

## Author

Lucija Sorić, Tilburg University
