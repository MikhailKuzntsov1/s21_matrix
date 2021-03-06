# S21_Matrix

## Table of contents
* [General info](https://github.com/MikhailKuzntsov1/s21_matrix/tree/main#general-info)
* [Goal & requirements](https://github.com/MikhailKuzntsov1/s21_matrix/tree/main#goal--requirements)
* [Key learnings](https://github.com/MikhailKuzntsov1/s21_matrix/tree/main#key-learnings)
* [Build](https://github.com/MikhailKuzntsov1/s21_matrix/tree/main#build)
* [Library docs](https://github.com/MikhailKuzntsov1/s21_matrix/tree/main#library-docs)
* [Credits](https://github.com/MikhailKuzntsov1/s21_matrix/tree/main#credits)

## General info 

Implementation of matrices processing library in C. 

## Goal & requirements

The goal of this project was to become familiar with major matrices processing routines and
implement them. The library had to be covered with unit-tests using Check framework.

## Key learnings
- Got familiar with basic matrices processing functions & their implementation
- Became more confident with using recursion (used for `determinant`, `calc_complements`, `inverse_matrix`)
- Discovered [GSL](https://www.gnu.org/software/gsl/) & used it for testing my functions
- Tried out Python & [Numpy](https://github.com/numpy/numpy) for testing correctness of my calculations

## Build

```
$ git clone git@github.com:MikhailKuzntsov1/s21_matrix.git
$ cd repo/src/
$ make
```

## Library docs

// maybe see GSL for example of docs (?)

``` c
/* s21_matrix.h */

// add description of enums & error codes 

```

### s21_create_matrix

``` c
int s21_create_matrix

```

<!-- write docs to my functions -->

## Credits
- Developer: [Mikhail Kuznetsov (@posidoni)](https://github.com/MikhailKuzntsov1)
- [GSL](https://www.gnu.org/software/gsl/) is used for unit testing. GSL is distributed under the terms of the [GNU General Public License (GPL)](https://www.gnu.org/licenses/gpl-3.0.html).
I greatly appreciate the work of Free Software Foundation & GSL developers.
- SC21 for providing this task as a part of our curriculum 🙂💚
