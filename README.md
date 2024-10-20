# Sudoku Solver from Image

This project implements a Sudoku solver that can recognize and solve a Sudoku puzzle from an input image. It uses Computer Vision techniques to extract the puzzle from the image, applies Optical Character Recognition (OCR) to identify the digits, and then solves the puzzle using a backtracking algorithm. The solution is then displayed in the form of an image.

## Features

- Image processing to detect and isolate the Sudoku grid.
- Optical Character Recognition (OCR) to identify digits.
- Sudoku puzzle solving using a backtracking algorithm.
- Visual representation of the original puzzle and its solution.

## Project Overview

The notebook demonstrates the following steps:

1. **Image Preprocessing**: The input image is preprocessed to detect the Sudoku grid using techniques like thresholding, edge detection, and contour detection.
2. **Digit Recognition**: Each cell is processed, and digits are recognized using OCR.
3. **Sudoku Solver**: A backtracking algorithm is used to solve the recognized Sudoku puzzle.
4. **Result Display**: The original puzzle and the solved puzzle are displayed side by side for comparison.

## Installation

To run this project, you need the following libraries:

```bash
pip install numpy opencv-python matplotlib pytesseract
```

## How to Use

1. Upload an image of a Sudoku puzzle.
2. Run the notebook, and the Sudoku solver will automatically process the image and return the solution.

## Code Structure

- **Image Preprocessing**: Prepares the image by resizing, converting to grayscale, and applying filters.
- **Grid Detection**: Detects the edges and finds the Sudoku grid using contours.
- **OCR for Digits**: Uses Tesseract OCR to recognize digits in each cell.
- **Sudoku Solver**: Implements the backtracking algorithm to solve the puzzle.
- **Solution Display**: Displays both the original and solved Sudoku puzzle.

## Example

The project takes an image of a Sudoku puzzle like this:

| Original Image | Solved Sudoku |
|----------------|---------------|
| (Image Input)  | (Solution)    |

## Demonstration
The example having an image of a Sudoku puzzle and the generated solution:
<img src="https://raw.githubusercontent.com/Mayankgbrc/Sudoku-Solver-from-Image/refs/heads/main/images/temp.png" />


## Contributing

Feel free to fork this repository and make improvements. Pull requests are welcome.
