# GitHub Training Kit Slide Framework

This is the official courseware slide-generating framework for the [GitHub Training Team's Training Kit](http://training.github.com/kit).

## File Format

The majority of the site materials are written in [Markdown](http://whatismarkdown.com), a [lightweight markup language](http://en.wikipedia.org/wiki/Lightweight_markup_language) supported in the GitHub web application user interface. There is a syntax guide to the original [Markdown format](http://daringfireball.net/projects/markdown/syntax) and also [GitHub Flavored Markdown](http://github.github.com/github-flavored-markdown/).  This repository is based on [Hydeslides](https://github.com/jordanmccullough/HydeSlides). That project offers additional information on the file and directory structure.

## Build

The build of this repository is fully automated through several shell scripts. To perform a build of the materials identical to that of our continuous integration server, from the top directory of this project, run `./_buildscripts/cibuild` and then inspect the output in the `_site` directory.

The `_buildscripts/makerelease` script produces a zip bundle for offline use of these materials. Pre-built releases are available at https://github.com/github/training-kit/releases
