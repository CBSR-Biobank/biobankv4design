# Notes

## PDF

Use the following command to generate the PDF document:

    /usr/bin/rubber --pdf main

Requires the `rubber` package which is an automated system for building LaTeX documents.

## Figures

All figures are created with LibreOffice Draw and kept in file (images/images.odg). Each image was
then exported as a PNG file and included in the LaTeX document. In LaTeX, cropping is used to remove
extra white space in the images.
