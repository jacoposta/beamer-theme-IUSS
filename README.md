# beamer-theme-IUSS

This repository provides a `LaTeX` theme implementation for the `beamer` 'documentclass' adequately consistent with the **IUSS** official graphical design.

## Usage

In order to use the **IUSS** theme, the following files should be included within the same directory where the main `*.tex` file resides:
 * `beamercolorthemeIUSS.sty`
 * `beamerinnerthemeIUSS.sty`
 * `beamerouterthemeIUSS.sty`
 * `beamerthemeIUSS.sty`
 * `iuss_logo.pdf`
 * `watermark.pdf`
 
The **IUSS** theme should be explicitly included in the *preamble* of the main `*.tex` file with the folliwing command:

```TeX
\usetheme{IUSS}
```

You can compile the document with your favourite `LaTeX` engine.
