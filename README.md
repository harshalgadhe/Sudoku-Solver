# Sudoku-Solver

We solve the sudoku by extracting the box from the image using morphological operations, flood fill algorithm,etc. The box is later passed to OCR model which was a pretrained model on mnist dataset. The model detects the digits and then pass the detected grid to the backtracking algorithm. After solving we superimpose the digits on the image.
