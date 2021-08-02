# About

Custom Latex template for generating CV

## Usage

Run `make pdf` to create the PDF (`cv.pdf`). See `make help` for an overview of available targets.

This custom template needs the following dependencies:

-   XeTex and fontspec (custom fonts)
-   biblatex/biber (for publications)
-   TikZ (header)
-   textpos (aside)

## Options

-   `print`: renders in black and white, and reverts the header to dark on light
-   `nocolors`: no colors in section headers (but still use dark header)
