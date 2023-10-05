# Geospatial Data Science with Julia

This repository hosts the source code of the
book *Geospatial Data Science with Julia*.

The book is available online for free at
[https://juliaearth.github.io/geospatial-data-science-with-julia](https://juliaearth.github.io/geospatial-data-science-with-julia)

## Build instructions

To build this book, you need:

- Julia v1.9
- IJulia (>= v1.24)
  ```julia
  import Pkg
  Pkg.add("IJulia")
  ```
- Quarto VSCode extension

1. Open the Julia REPL and instantiate the environment in this folder:

    ```julia
    import Pkg
    Pkg.activate(".")
    Pkg.instantiate()
    ```

2. Go to any `*.qmd` file and press `render` on VSCode.
   Alternatively, run the following in the terminal:

    ```sh
    quarto preview index.qmd
    ```

Your web browser will open a tab with the book rendered.
