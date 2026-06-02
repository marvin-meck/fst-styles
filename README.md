# fst-styles

A collection of LaTeX style files developed to typeset my PhD thesis and to create plots consistent with the style conventions of the Fluid Systems group at TU Darmstadt.

This package consists of three components intended for direct use in LaTeX documents:

* `fstdiss.sty`: Provides title page definitions and additional macros for front matter elements such as copyright pages and affidavits.
* `fstglossaries.sty`: Provides glossary style definitions for use with `glossaries-extra` (e.g. notation lists).
* `fstplot.sty`: Provides style settings for FST-style plotting using `pgfplots`.

Examples and documentation may be added in the future.

## Licensing and Acknowledgements

The `fst-styles` package is distributed under the LaTeX Project Public License (LPPL), version 1.3c or later.

This package was developed over several years and may contain small code fragments inspired by publicly available discussions in the LaTeX community, including Stack Overflow, package documentation, mailing-list archives, and other community resources. 
Where specific sources are known, they are acknowledged in the corresponding source files and documentation.

### Third-Party Influences

The package includes components that build upon existing LaTeX ecosystem conventions and extension mechanisms.

* `fstmaketitle.sty` contains code derived from KOMA-Script's implementation of `\maketitle` in the `scrbook` class. The code was adapted to expose the title-page implementation via `\@maketitle`, allowing custom title pages while preserving KOMA-Script features such as `firstiscover`, `extratitle`, and `dedication`.

* `fstglossaries.sty` defines glossary styles for use with `glossaries-extra`. The style definitions were adapted from documented examples provided in the `glossaries-extra` documentation by Nicola Talbot.

Unless otherwise stated, all original code in this repository is Copyright (c) 2026 Marvin Meck.

### Maintenance

This work has the LPPL maintenance status `author-maintained`.

The Current Maintainer of this work is Marvin Meck.
