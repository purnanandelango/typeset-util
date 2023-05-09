---
layout: home
---

# Utilities for Typesetting

- The LaTeX package `custom` specifies:
  - macros for commonly used symbols in trajectory optimization literature. 
  - page formatting in `article` class with math fonts from `mathpazo` package.
  - behavior of hyperlinks via `\hypersetup`.
  
- The style file [`preview.css`](preview.css) specifies [Latin Modern Sans](https://tug.org/FontCatalogue/latinmodernroman/) typeface for VS Code preview of markdown file. Add the following to the workspace settings file `.vscode\settings.json` to modify the markdown preview:
  ```json
  {
      "markdown.styles": ["https://www.purnaelango.com/typeset-util/preview.css"]
  }
  ```
  See the example provide in `.vscode` directory of this repo. Opening this repository in VS Code will apply the style to this preview of this readme file. See the rendered HTML version [here](README.html).
