---
name: Bug
about: Something is wrong with proffer.
title: ''
labels: 'type: bug'
assignees: r-prof
---

## Prework

- [ ] Read and abide by `proffer`'s [code of conduct](https://github.com/r-prof/proffer/blob/master/CODE_OF_CONDUCT.md).
- [ ] Search for duplicates among the [existing issues](https://github.com/r-prof/proffer/issues), both open and closed.
- [ ] Advanced users: verify that the bug still persists in the current development version (i.e. `remotes::install_github("r-prof/proffer")`) and mention the [SHA-1 hash](https://git-scm.com/book/en/v1/Getting-Started-Git-Basics#Git-Has-Integrity) of the [Git commit you install](https://github.com/r-prof/proffer/commits/master).

## Description

Describe the bug clearly and concisely. 

## Reproducible example

Provide a minimal reproducible example with code and output that demonstrates the problem. The `reprex()` function from the [`reprex`](https://github.com/tidyverse/reprex) package is extremely helpful for this.

To help us read your code, please try to follow the [tidyverse style guide](https://style.tidyverse.org/). The `style_text()` and `style_file()` functions from the [`styler`](https://github.com/r-lib/styler) package make it easier.

## Expected result

What should have happened? Please be as specific as possible.

## Session info

End the reproducible example with a call to `sessionInfo()` in the same session (e.g. `reprex(si = TRUE)`) and include the output.
