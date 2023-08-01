# Extract all function names with their first/last line number in C/C++ source codes

Tested with C source files.

Functions_list_generator.py usage:
- Either specify two input parameters (a) or none to use the default hardcoded parameters (b). <output_file> support .txt and .xlsx format
- Usage (a): python3 Functions_list_generator.py <folder_path> <output_file>
- Usage (b) (hardcoded parameters: <folder_path>=src, <output_file>=Functions_list.xlsx): python3 Functions_list_generator.py

Script will parse all .c/.cpp files from input folder and list all functions found



