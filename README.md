
## Word Reconstruction from Coordinate Table

## Description
This project reads a set of points containing `(x-coordinate, character, y-coordinate)` from a table, places the characters correctly in a 2D grid, and prints the hidden word or shape.

The characters can include:
- `█` (filled block)
- `░` (light block)

## Algorithm
1. Input Parsing: Read the list of (x, character, y) tuples.

2. Determine Grid Dimensions: Find the min/max x and y values to define the grid size.

3. Initialize 2D Grid: Create an empty 2D grid based on the dimensions.

4. Place Characters: For each tuple, place the character in the appropriate grid position.

5. Print the Grid: Print the grid row by row from top to bottom.

## Notes
1. Rows are printed from top to bottom (flipping the y-axis) to match regular (x, y) graph coordinates.

2. No external libraries are required — pure Python!

3. This implementation is based on hard-coded input but can be adapted for other input formats.

This tool is useful for visualizing hidden words or shapes stored in coordinate form and is a fun way to reveal hidden messages!

## How to Run
1. Make sure you have Python installed (version 3.x).
2. Save the provided Python code into a file, for example `reconstruct_word.ipypb`.
3. Run it using:

```bash
python reconstruct_word.ipypb
