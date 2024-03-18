# Robot Writeup 2024

[![Compile LaTeX and Release PDF](https://github.com/Team-1280/tech-binder-2024/actions/workflows/release.yml/badge.svg)](https://github.com/Team-1280/tech-binder-2024/actions/workflows/release.yml)

Writeup for Team 1280's robot for the 2024 Crescendo season.

Web version coming soon.

Or download the PDF from [our releases page (automatically kept up to date)](https://github.com/Team-1280/robot-writeup-2024/releases/tag/main).

## How to compile locally

This will repository is configured to automatically compile and release a PDF to its releases page on any push to the main branch. However, if you
want to compile and edit it locally (eg. to test out LaTeX formatting), you should compile it using `latexmk`, targetting `root.tex`,
preferably from the TeX Live software distribution. This will ensure you have all the prerequisite tools like `biber` and packages like `BibLaTeX`
to build the document properly. 
