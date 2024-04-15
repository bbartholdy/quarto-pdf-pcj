# Peer Community Journal Submission Formatting

This is a Quarto extension that can be used to format a manuscript for submission to the Peer Community Journal.
I am in the process of submitting a paper myself, but for now I **cannot** confirm whether the extension
sufficiently adheres to the [format requirements](https://peercommunityjournal.org/page/instructions/).

To format a preprint for submission to one of the thematic PCIs, I highly recommend the
[Quarto typst extension](https://github.com/alxsimon/typst-pci) created by [Alexis Simon](https://github.com/alxsimon).

## Installing

New repository

```bash
quarto use template bbartholdy/quarto-pdf-pcj
```

Existing repository/project

```bash
quarto add bbartholdy/quarto-pdf-pcj
```

Updating extension

```bash
quarto update bbartholdy/quarto-pdf-pcj
```

## Usage

```bash
quarto render <yourdocument>.qmd --to pci-pdf
```

## Example PDF

![Screenshot of the rendered template.qmd](pdf.png)
