# Randomized Algorithms - Spring 2022

This repository contains the homework assignments and solutions for the "Randomized Algorithms" course, taught at the University of Tehran during the Spring 2022 semester.

## Repository Contents

The repository is structured as follows:

*   `.tex` files: These are the LaTeX source files for the homework assignments. The text is written in Persian.
*   `pdf/` directory: This directory contains the compiled PDF versions of the homework assignments.
*   `Photos/` directory: This contains images that are included in the homework documents.
*   `.ttf` files: These are font files (specifically, the "XB Yas" font) used in the LaTeX documents to render the Persian text.
*   `neurips.sty`: A LaTeX style file used for formatting the documents.
*   `LICENSE`: The license for the repository.
*   `README.md`: This file.

## Homework Assignments

Here is a list of the available homework assignments in PDF format:

*   [Homework 4](pdf/HW4.pdf)
*   [Homework 5](pdf/HW5.pdf)
*   [Homework 6](pdf/HW6.pdf)
*   [Homework 7](pdf/HW7.pdf)

The corresponding LaTeX source files are also available in the root directory.

## Building from Source

To compile the `.tex` files into PDFs yourself, you will need a working LaTeX distribution that includes the `xelatex` compiler. `xelatex` is required for documents that use modern fonts and Unicode, which is necessary for the Persian text in these assignments.

### Dependencies

*   A LaTeX Distribution (e.g., [TeX Live](https://www.tug.org/texlive/), [MiKTeX](https://miktex.org/)).
*   The `xepersian` package.
*   The font files (`.ttf`) included in this repository should be available to your system's font manager or placed in the same directory as the `.tex` files.

### Compilation Steps

1.  **Install a LaTeX distribution:** If you don't have one, install one of the distributions mentioned above.
2.  **Compile with `xelatex`:** Open a terminal or command prompt, navigate to the repository's root directory, and run the following command for the desired homework file:

    ```bash
    xelatex HW1.tex
    ```
    (Replace `HW1.tex` with the file you wish to compile).

    You may need to run the command twice to ensure all cross-references are correctly generated.

## Missing Source Code

Several of the LaTeX documents refer to source code files that are not included in this repository. These files were likely part of the original homework submissions but were not committed to this repository. The missing files are:

*   `perm.cpp`: Mentioned in `HW2.tex`. This file contains C++ code for generating permutations.
*   `mst_kruskal.cpp`: Mentioned in `11.6. Exploratory Assignment.tex`. This file contains a C++ implementation of Kruskal's algorithm for finding a Minimum Spanning Tree.
*   `conclusion.ipynb`: Mentioned in `11.6. Exploratory Assignment.tex`. This is a Jupyter Notebook file used for analyzing and plotting the results of the MST algorithm.
