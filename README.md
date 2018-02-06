This repository contains a [conda][conda] recipe for building [Alex Herbert's
SBG tools][sbg-tools]. These tools include a loop modeller, maxcluster and
fragment libraries.

## Prerequisites

1. You will need an installation of [conda][miniconda].

2. Your root conda installation must have the `conda-build` installed.

## Building

You should be able to build this package by simply running `conda build .`.
Potentials will be installed to `$PREFIX/share/sbg/potentials/`.

[conda]: https://conda.io
[sbg-tools]: https://github.com/StefansM/sbg-alex
[miniconda]: https://conda.io/miniconda.html
