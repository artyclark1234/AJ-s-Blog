SLUM
================

The *slum* theme for Hugo is an adaptation Yihue Xie’s *Xmin* theme that
borrows stylistic elements from the Tufte R Markdown theme and from the
*academic* Hugo theme. I’m not really convinced it’s useful for much,
hence the name; this is a *somewhat-light unhelpfully-minimal* Hugo
theme. In truth, my main goal in putting this theme together was to make
sure I understand the basics of how Hugo works.

## Getting started

To create the example site using the slum template into a fresh
directory:

``` r
blogdown::new_site(
  dir = "~/../Desktop/slum", 
  theme = "djnavarro/hugo-slum",
  theme_example = TRUE,
  sample = FALSE
)
```

By setting `theme_example = TRUE` (the default) it installs the example
site, and by setting `sample = FALSE` it prevents Hugo from
automatically including the default content.

To serve an existing site, assuming that R the working directory is set
to the home directory for the site:

``` r
blogdown::serve_site()
```

The example site serves as a tutorial in how to use the theme, and you
can see it at:

<https://djnavarro.github.io/hugo-slum/>
