# Basic Library Documentation

> Please follow the [Requirements](https://github.com/rizo/ocaml-by-example/blob/main/README.md#requirements) instructions first.

This demonstrates a simple project with a library and an executable. The
library module has an interface file with documentation.

Run the program:
```
# From the current directory:
$ dune exec -- ./Main.exe

# From the root directory:
$ dune exec -- ./basic-lib-doc/Main.exe
```

Build the documentation:
```
# Go to the root of the project.
$ cd ..  # relative to the current directory
$ dune build @doc
# Find the generated HTML files
$ ls _build/default/_doc/_html/ocaml-by-example/index.html
$ ls _build/default/_doc/_html/ocaml-by-example/Basic_lib_doc/index.html
```
