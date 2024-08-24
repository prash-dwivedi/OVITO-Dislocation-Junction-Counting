Junction Identification and Counting Script for OVITO

This Python script is designed for use with OVITO (Open Visualization Tool) to identify and categorize dislocation junctions within crystal structures. It classifies junctions into four types—Binary, Ternary, Quaternary, and Higher Order—based on the number of dislocation segments converging at a point. The script then counts and prints the number of each junction type. This tool is ideal for researchers working on crystallography and dislocation analysis.

Features:

Identifies and categorizes dislocation junctions in crystal structures.
Counts and outputs the number of each type of junction (Binary, Ternary, Quaternary, Higher Order).
Easy integration as a Python script modifier within OVITO.


![junction_final](https://github.com/user-attachments/assets/6da2c7a7-d05e-4e33-98f5-3e4e73cae455)



Requirements:
OVITO software
NumPy library


Usage:
Load your crystal structure data into OVITO.
Add this script as a Python script modifier.
Run the script to see the results in the console.


Citation: If you use this script in your research, please cite the following articles:

https://doi.org/10.1016/j.jnucmat.2024.155289

https://doi.org/10.1016/j.jnucmat.2024.155042

Developed by Prashant Dwivedi.
