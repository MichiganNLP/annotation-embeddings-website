# AnnDisagree

Code for the [AnnDisagree website](https://lit.eecs.umich.edu/anndisagree/).

## Paper page thumbnails.

We used ImageMagick:

```bash
convert $PDF_FILE[0-8] -thumbnail x156 img/thumbs/%d.png
```
