# About this repository

This is my personal resume, based on Adrien Friggeri resume tex template. I did
change some of the fonts to use fonts freely available (FiraSans). There is an
option to render the resume in black and white and revert the header to dark on
light. This is useful if printing on paper is needed.

# Requirements

The following requirements are needed in your system to compile this project.
These are the names of Fedora packages, as of Fedora 29. If you need/have the
package names for other systems (e.g., Debian), you will need to figure out the
correct package names (patches are welcome).

* poppler-utils
* biber
* mozilla-fira-sans-fonts
* texlive-textpos
* texlive-xetex
* aspell

# Useful commands

* `make`: build resume
* `make cover`: build resume with cover letter
* `make cover-nocolors`: build resume with cover letter. Everything in black and white
* `make nocolors`: build resume in black and white
* `make check`: Use `aspell` to check for typos
* `make clean`: (:

# License

Copyright (C) 2017, Athos Ribeiro

The license information regarding the LateX template used for this resume can
be found on friggeri-cv.cls. See https://github.com/afriggeri/CV

The letter was created by Matthew Davis, based on Adrien Friggeri's code.  See
https://github.com/mlda065/friggeri-letter

All the other files available in this repository are licensed under a [Creative
Commons Attribution 4.0 International
License](https://creativecommons.org/licenses/by/4.0/).
