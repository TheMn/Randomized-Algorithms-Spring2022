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

This repository contains the following homework assignments. Descriptions are provided for assignments where the LaTeX source file is available.

*   **Homework 1** (`./HW1.tex`)
    *   A set of problems covering foundational probability theory concepts, including dice rolls, conditional probability, and dependent events.

*   **Homework 2** (`./HW2.tex`)
    *   Explores topics such as reservoir sampling, group testing for disease, the St. Petersburg paradox, and the implementation of different permutation algorithms.

*   **Homework 3** (`./HW3.tex`)
    *   A deep dive into probability theory, covering Markov's inequality, variance calculations, expected values, Chernoff bounds, and Chebyshev's inequality.

*   **Homework 4** (`./pdf/HW4.pdf`)
    *   *Description unavailable: The source `.tex` file for this assignment is not present in the repository.*

*   **Homework 5** (`pdf/HW5.pdf`)
    *   *Description unavailable: The source `.tex` file for this assignment is not present in the repository.*

*   **Homework 6** (`./pdf/HW6.pdf`)
    *   *Description unavailable: The source `.tex` file for this assignment is not present in the repository.*

*   **Homework 7 / Final Project** (`./11.6. Exploratory Assignment.tex` and `./pdf/HW7.pdf`)
    *   An exploratory assignment on finding the Minimum Spanning Tree (MST) in a complete graph with random edge weights. It involves implementing and optimizing Kruskal's algorithm.

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

Several of the LaTeX documents refer to source code files that are not included in this repository, but are available at the `randomized-algorithms-implementations` repository.
