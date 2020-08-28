# M13 Puzzle

Building the puzzle described in Noam Elkies's [paper](https://arxiv.org/pdf/math/0508630.pdf)

## Prototype 1

An intial implementation in SAGEMATH v8.7.

### Issues
- The circular representation of the puzzle.
- Some of the colored puzzle pieces look identical.

## Representation - First choice

Present the puzzle by placing its pieces around a [Roman surface](https://en.wikipedia.org/wiki/Roman_surface) with a hole centered at (0,0,0)
To push a puzzle piece into the hole, hold the edge of the tetrahedron the connects that piece to the hole. Proceed to twist the edge by 180 degrees, until the piece occupies the central location.

### Issues
- How does this representation illustrate the next move?
