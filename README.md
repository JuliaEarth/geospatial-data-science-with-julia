# Geospatial Data Science with Julia

This repository hosts the source code of the
book *Geospatial Data Science with Julia*.

The book is available online for free at
[https://juliaearth.github.io/geospatial-data-science-with-julia](https://juliaearth.github.io/geospatial-data-science-with-julia)

## Build instructions

To build this book, you need:

- Julia v1.11 (or a later release)
- Quarto

1. Open the Julia REPL and instantiate the environment in this folder:

   ```julia
   import Pkg
   Pkg.activate(".")
   Pkg.instantiate()
   ```

2. Open the terminal, choose any `*.qmd` file (e.g., `index.qmd`) and preview it:

   ```sh
   quarto preview index.qmd
   ```

3. Render the entire book to different output formats:

   ```sh
   quarto render # default to html
   ```

   ```sh
   quarto render --to pdf
   ```

If you prefer to work with VSCode, install the Quarto VSCode extension.
Edit the files and press the `render` button. All changes to the files
are automatically tracked by the extension.
