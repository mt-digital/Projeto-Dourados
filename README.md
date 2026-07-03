# institutodourados.org

> Author: Matt Turner
> Date: April 21, 2026


## Instituto Dourados's Internet Home

The Instituto Dourados is an educational and research exchange program to
promote Indigenous public health in Dourados and the Dourados Indigenous
Reserve, state of Mato Grosso do Sul, Brazil, and beyond.

This website was built with [Quarto](https://quarto.org). Quarto provides a
system for writing content in a single format, which can be used to publish in a
variety of formats.

The website structure is defined in [`_quarto.yml`](/_quarto.yml). Quarto provides useful [tools for multilingualism](https://quarto.org/docs/authoring/language.html).

The following `languages` specification block in `_quarto.yml` specifies how to
"route" the website for different languages.

```{yaml}
languages:
  pt:
    default: true
    name: Português
    dir: pt
  en:
    name: English
    dir: en
```

There are a few more pieces we need for the custom navbar.


### Use as a Template for Multilingual Organization Sites

I would be thrilled for others to use this as a template for their own
innovative institutional websites.

To use this as a template, simply swap out
our Instituto Dourados information and branding for your own, starting with the
name of the organization in [`_quarto.yml`](/_quarto.yml).

To change font colors or changing the
background image in the header, modify the "cascading style sheet" that
specifies web site styling, [`styles.scss`](/styles.scss).




