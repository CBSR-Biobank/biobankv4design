# Notes

## PDF

Use the following commands to generate the PDF document:

```shell
/usr/bin/biber main
/usr/bin/rubber --pdf main
```

Requires the `biber` and `rubber` Ubuntu packages. [Biber](http://biblatex-biber.sourceforge.net/)
is a BibTeX replacement for users of BibLaTeX
[Rubber](http://manpages.ubuntu.com/manpages/hardy/man1/rubber.1.html) is an automated system for
building LaTeX documents.


## Figures

All figures are created with LibreOffice Draw and kept in file (images/images.odg). Each image was
then exported as a PNG file and included in the LaTeX document. In LaTeX, cropping is used to remove
extra white space in the images.
