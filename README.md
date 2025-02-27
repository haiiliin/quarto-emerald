# quarto-emerald

A [Quarto](https://quarto.org/) template for Emerald journals.

## Creating a New Article

To create a new article using this format:

```bash
quarto use template haiiliin/quarto-emerald
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:

```bash
quarto add haiiliin/quarto-emerald
```

Then, add the format to your document options:

```yaml
format:
  emerald-pdf: default
```

## Options

- `journal.linenumbers`: Add line numbers to the document.
- `journal.linespread`: The line spread factor for the document, by default `1.5`.

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd), see the [PDF output](template.pdf).
