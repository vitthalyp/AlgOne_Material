# M13 Puzzle

Building the puzzle described in Noam Elkies's [paper](https://arxiv.org/pdf/math/0508630.pdf)

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
