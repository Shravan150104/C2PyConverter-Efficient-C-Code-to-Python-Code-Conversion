# C2PyConverter-Efficient-C-Code-to-Python-Code-Conversion
we took a C source code file as input, converted it into an intermediate format called ideal syntax and then determined LineType for every line in the ideal syntax source code. The final step is translating each line. We created translation functions for each type of line, and we call that function referencing the LineType array, give proper indentation and then the final output is ready i.e., Python code file which gives same output as Source C code file having same logic and structure
