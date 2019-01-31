# psyc161-nbackseq

## Description

A mini project to generate balanced sequences

A simple utility

    > nbackseq n l w1 w2 w3 ...

and output comma-separated sequences of words from the provided set
(w1, w2, ...) of length `l` so that for any entry there is no
repetition of words n items back (n includes the item)

e.g.

    > nbackseq 2 2 a b

    a,b
    b,a

    > nbackseq 3 12 house face shoe

    house,face,shoe,house,face,shoe,house,face,shoe,house,face,shoe
    ...


The goal will be to implement and test (unit-tests) two solutions for
the problem.  Initial one will be based on a simple permutation with
selection of solutions which satisfy needed criterion.  We will make
sure that it works correctly, implement some timing of the execution
and then go on to optimize it by adopting the eight queen puzzle
solution, which was implemented via
[backtracking depth-first search](https://en.wikipedia.org/wiki/Backtracking).


## TODOs

- Yarik will initiate
  - new repository on github
  - README.md and nbackseq script prototype
  - basic tests
- You will fork repository on github, and implement permutation-based
  solution, commit, and then submit a PR
- Yarik meanwhile will be adding more tests and assessments, so you
  will need to merge new additions
- You will implement the optimized solution

## Extras

- verify that all input words unique
