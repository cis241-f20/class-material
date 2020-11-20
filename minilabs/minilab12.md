## Minilab 12

This minilab will help you get experience using
multidimensional arrays.

For this minilab, we'll look at terrain elevation
maps as 2d arrays and compute how many peaks there
are in a given map.

A peak is defined as a cell where all eight
neighboring cells (N,NE,E,SE,S,SW,W,NW)
are strictly lower.  

For this minilab, assume that a peak cannot be a
cell on the edge of the map.  (Note, more commonly
"boundary conditions" would be assumed about the
cells outside of the map).

Create a program that:
1. Reads in an elevation map from stdin.  The input
   format will be a single line with 2 integers,
   nrows and ncols, respectively.  The following
   lines will contain the elevation for a specific
   cell in the map, input one per line in row major
   format.  Example:
   ```
   3 4
   1
   5
   3
   2
   2
   8
   4
   1
   0
   6
   1
   3
   ```
2. Check whether each cell is a peak, keeping track
   of the total number of peaks found.
3. Print the number of peaks.
