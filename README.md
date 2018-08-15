# pdfcrunch

Reduce the size of a PDF by reducing the image quality of the individual pages.

# Installation and dependencies

This is a simple bash script, so either place it somehwere in your PATH, or add the repository to your PATH.
It depends on ``pdftoppm`` and ``convert``, which are provided by the poppler-utils and ImageMagick packages on Fedora.

# Usage

```bash
pdfcrunch INPUT [OUTPUT]
```

Arguments:

1. INPUT  
pdf file to reduce in size
2. OUTPUT  
optional. output filename; defaults to ```INPUT_crunched.pdf```


