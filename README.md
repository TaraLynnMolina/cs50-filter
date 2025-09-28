# cs50-filter
A C program that applies image filters such as grayscale, sepia, reflect, and blur to bitmap (.bmp) images. Built as part of CS50x (Introduction to Computer Science by Harvard University).

📖 Overview

The program takes a bitmap image as input and applies one of several filters. The implementation manipulates pixel data directly to achieve the effects.

Available filters:
	•	Grayscale – converts the image to shades of gray
	•	Sepia – gives the image a warm, brownish tint
	•	Reflect – flips the image horizontally
	•	Blur – applies a box blur to soften the image

Example:
./filter -g infile.bmp outfile.bmp   # grayscale
./filter -s infile.bmp outfile.bmp   # sepia
./filter -r infile.bmp outfile.bmp   # reflect
./filter -b infile.bmp outfile.bmp   # blur

🛠 Features
	•	Direct manipulation of bitmap image pixels.
	•	Implements four classic filters.
	•	Input/output using .bmp files.
  
🚀 How to Run
	1.	Compile the program: make filter
  2.	Run the program with the desired filter flag (-g, -s, -r, -b):
  ./filter [flag] infile.bmp outfile.bmp
  3.	View the resulting output image in any image viewer.

📂 Files
	•	filter.c – main source code
	•	helpers.c – filter implementations
	•	helpers.h – function prototypes
	•	README.md – project documentation
