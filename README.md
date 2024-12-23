# Reveal JS Catppuccin Template

This is a template project for [reveal.js](https://revealjs.com/) that uses [Catppuccin](https://catppuccin.com/) for the slide theme. It also uses [Panda Syntax](https://highlightjs.org/demo#lang=&v=1&theme=panda-syntax-dark-min&code=IyB0aGlzIGlzIGEgY29tbWVudApkZWYgZ3JlZXQobmFtZSk6CglwcmludChmIkhlbGxvLCB7xBh9Iik%3D) and [Dank Mono](https://philpl.gumroad.com/l/dank-mono) for code highlighting.

## How to use

1. Download the zip file for this repo.
2. Use a web server to serve the index.html page. Python's built in `http.server` is ideal for this.

    ```shell
    python -m http.server
    ```

    This will serve the page on http://localhost:8000 by default.

3. Change the contents of the [slides.md](./slides.md) file as required.

## Adjusting light/dark mode

The template will automatically switch between light and dark mode based on the browser settings. To force one or the other mode, either change the browser setting or comment out the lines that bring in the slide theme and/or code theme.
