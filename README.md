# Learn OCaml by reading ocaml-tiff

A zero-to-hero guide to OCaml, taught entirely from the source code of
[geocaml/ocaml-tiff](https://github.com/geocaml/ocaml-tiff), a pure OCaml TIFF reader and writer.

New to OCaml? Start with sections A–D:

- A. What OCaml is
- B. Installing opam, dune and utop
- C. First steps in utop, including how to read a type error
- D. TIFF in one picture

Then each level teaches one OCaml idea using a real piece of the library, and most end with a small exercise:

0. Repo map and dune
1. `let`, functions, optional arguments, `|>`
2. Variants and pattern matching
3. Records, `option`, `when` guards
4. Lists and folds
5. Recursion and tail calls
6. Mutation, loops and arrays
7. Modules, `.mli` files and abstract types
8. Functions as values and labelled arguments
9. Exceptions and `Result`
10. Bytes, bits and Bigarrays
11. GADTs
12. Testing with OUnit2
13. C stubs with `external`

It finishes with a short note on functors, a trace of one `Tiff.data` call through the whole library, and a glossary.

## How to use it

Open `index.html` in a browser, or read it online at
https://six-shot.github.io/six-shot-ocaml-tiff-zero-to-hero/ once GitHub Pages is on.

Type every example yourself, try each exercise before opening the answer, and read
the compiler's error messages carefully. That is how the language sticks.

## Credits

Code excerpts come from ocaml-tiff, © 2025 geocaml developers, MIT License.
