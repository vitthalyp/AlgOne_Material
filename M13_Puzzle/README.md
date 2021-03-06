# M13 Puzzle

The idea for this came from Dr. Sebastian Egner's JAVA applet mentioned in this [article](http://www.neverendingbooks.org/the-mathieu-groupoid-1)

The puzzle is labelled as per the scheme provided in Noam Elkies's [paper](https://arxiv.org/pdf/math/0508630.pdf)

## Prototype 1

An intial implementation in SAGEMATH v8.7.

### Issues
- The circular representation of the puzzle.
- Some of the colored puzzle pieces look identical.

## Representation - Roman Surface

Present the puzzle by placing its pieces around a [Roman surface](https://en.wikipedia.org/wiki/Roman_surface) with a hole centered at (0,0,0).

## Prototype 2

Using the Roman surface representation and fixing the hole at the center, the puzzle was implemented in SAGEMATH v9.1. 

The projective space ![equation](https://latex.codecogs.com/gif.latex?%5Cmathbb%7BP%7D%5E%7B2%7D%28%5Cmathbb%7BF%7D_%7B3%7D%29) has 13 lines, we display precisely those lines that intersect the point labelled 'hole' and thus we can fix the hole at the center. 

### Issues
- Visual presentation.

## Representation - Icosahedron

Present the puzzle by placing its pieces at the vertices of an icosahedron with a hole centered at (0,0,0).

## Prototype 3

Using the icosahedron representation the puzzle was implemented in SAGEMATH v9.1. [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vitthalyp/AlgOne_Material/master?filepath=%2FM13_Puzzle%2FDemo_Puzzle.ipynb)

(The puzzle can now be scrambled.)

## Solver

A ![solver](https://github.com/vitthalyp/M13) has been implemented using a ported version of Dr.Sebastian Egner's code. 


