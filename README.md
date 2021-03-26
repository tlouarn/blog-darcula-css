# JetBrains' Darcula CSS for Chroma

## Description

This CSS file is an attempt at recreating JetBrains' Darcula theme from PyCharm for [Chroma](https://github.com/alecthomas/chroma) code highlighter.

Works well for Python except the __magic_functions__ that do not seem implemented.

## Usage in Hugo

Since the theme is not included by default with Chroma, you need to tell Hugo to _not_ write inline styling but to write CSS classes instead, and add the CSS file to the static resources.

Copy the file into your theme's 

```shell
static/css/darcula.css
```

Then add the below to your config.toml:

```toml
pygmentsUseClasses = true
pygmentsCodefences = true

[Params]
  css = ["css/darcula.css"]
```

## Example

Theme is used throughout by [blog](https://tlouarn.com/blog).
