# JetBrains' Darcula theme in CSS for code highlight

## Description

This CSS file is an attempt at recreating JetBrains' Darcula theme from PyCharm for Chroma code highlighter.

## Usage in Hugo

Copy the file into your theme's 'static/css/darcula.css'

Then add the below to your config.toml:

```toml
pygmentsUseClasses = true
pygmentsCodefences = true

[Params]
  css = ["css/darcula.css"]
```
