# cv

Curriculum Vitae

## Generate Word and PDF Versions

Install [pandoc](http://johnmacfarlane.net/pandoc/).

### Word

    pandoc -s john-walley-cv.md -o john-walley-cv.docx

### PDF

Unfortunately pandoc requires an install of LaTeX to generate pdf documents. I say unfortunately only because I have never seen a small LaTeX install.

    pandoc -s john-walley-cv.md -o john-walley-cv.pdf
    
## Colourful Version

Requires [Adobe InDesign](http://www.adobe.com/uk/products/indesign.html) to edit the ``.indd`` file. In addition there is currently no automated method for importing the text in the markdown version.
