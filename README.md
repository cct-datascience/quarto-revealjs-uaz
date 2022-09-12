
# quarto-revealjs-uaz

<!-- badges: start -->
<!-- badges: end -->

The goal of quarto-revealjs-uaz is to make a template for Quarto revealjs slides with University of Arizona branding (fonts, colors, logos, images, etc.)

## Installation

To use this Quarto theme, first install it from GitHub using the Quarto command line interface:

``` bash
quarto install cct-datascience/quarto-revealjs-uaz
```

Use the theme in your own reveal.js slides like so:

```yml
---
title: "Presentation"
author: "Your Name"
format: uaz-revealjs
---
```


## Notes on how to do this:

- [Making Quarto extensions](https://quarto.org/docs/extensions/formats.html)
- [Rladies theme extension](https://github.com/beatrizmilz/quarto-rladies-theme)
- [Customizing Scss for slide themes](https://quarto.org/docs/presentations/revealjs/themes.html#creating-themes)
- [Creating an R-Ladies quarto format](https://www.visibledata.co.uk/posts/2022-07-29_creating-an-r-ladies-quarto-format/)

- [UA powerpoint template](https://arizona.app.box.com/s/lldw3idupv0fqrlb464mi95z3r75ld0p)

- You can check the theme as you go, simply by rendering template.qmd.  Next step is to edit stuff in _extensions/uaz/theme.scss to match things in the official branding here: https://brand.arizona.edu/
- Might be cool to add an image for the title slide (see [example](https://quarto.org/docs/extensions/formats.html#format-components))

