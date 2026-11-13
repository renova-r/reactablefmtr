# reactablefmtr

Functions that streamline the styling and formatting of interactive `reactable` tables: conditional formatters (data bars, color scales, color tiles, icon sets), sparklines, table themes, embedded images, and ways to save tables as HTML or images.

Compatibility updates by Renova.

Version 2.0.0.9001 fixes Rd markup in 10 help pages: literal `{reactable}`, `{reactablefmtr}`, `{scales}` and `{dataui}` in descriptions, which R reports as "Lost braces", are written as `\code{...}` (or plain text in two titles). No R function was changed.

## Install

```r
install.packages("reactablefmtr", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or install this exact release from its tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/reactablefmtr@renova-2.0.0.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

reactablefmtr is by Kyle Cuilla, with contributions from Greg Lin, June Choe and Kent Russell; the original project is at <https://github.com/kcuilla/reactablefmtr>. License: MIT; see [LICENSE](LICENSE) (Copyright 2021 Kyle Cuilla).
