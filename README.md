# Error culture and management how Aviation does it

Live version: https://afoeder.github.io/slidedeck-error-culture/ (deployed automatically via GitHub Actions on every push to `main`).

This is a [reveal.js](https://revealjs.com/) slide deck. After cloning you have to `git submodule init && git submodule update` in order to make the reveal.js assets available.

The base file is `index.html`, open it in a web browser. Reveal.js dependencies will be fetched from `reveal.js/dist/…` which is the git submodule you've fetched earlier.

Note that there are speaker notes, you can display them by pressing the `S` key.

## Render as PDF

[Decktape](https://github.com/astefanutti/decktape) can be used to render it as PDF, which in turn can then be [converted to PPTX](https://www.adobe.com/acrobat/online/pdf-to-ppt.html).

```bash
$ npm install decktape
$ http-server
$ `npm bin`/decktape http://127.0.0.1:8080 deck.pdf
```

Note that when experiencing layout inconsistencies it is advised to set `--size 1024x768`.
