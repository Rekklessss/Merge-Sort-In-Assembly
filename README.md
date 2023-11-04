# Merge Sort Implementation for ARM

## Author
Divyanshu Pabia - RA2111003011373

## Program Report - Stage 3

### Objective
The goal of this stage is to implement a function to merge sort a list of strings. The sorting algorithm is designed to run on an ARM simulator.

### Assumptions
- ARMSim version - 2.0.1(4), with output displayed through stdout using Angel SWI Instructions.
- Users adhere to the provided input instructions.

### Instructions to Run
1. Load all the files (`main.s`, `io.s`, `math.s`, `merge.s`, `print.s`, `compare.s`, `case.s`, `input_stage2.s`) in ARMSim# by selecting the 'Load Multiple' option.
2. Ensure `main.s` is loaded first.
3. After the successful loading of the file, click on the 'Run' button.
4. In the stdin/stdout window, enter the values as prompted and press the ENTER key after each line.
5. Avoid using backspaces as they may cause errors.
6. The output will be the sorted list.
7. When the 'remove duplicates' option is selected, do not enter duplicate values in the same list. If duplicates are required, enter them in different lists.

### Output
The program outputs a sorted list of strings based on the user's input, with an option to remove duplicates.

## File Descriptions
- `main.s`: Main assembly file for the merge sort program.
- `io.s`: Input/output handling.
- `math.s`: Mathematical functions and utilities.
- `merge.s`: Merge sort logic.
- `print.s`: Printing utilities.
- `compare.s`: String comparison functions.
- `case.s`: Case conversion utilities.
- `input_stage2.s`: Input handling for stage 2 of the project.

## Contributing
Contributions to this project are welcome. Please follow the contributing guidelines outlined in the CONTRIBUTING.md file.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

We hope this repository serves as a helpful reference for those interested in ARM assembly programming and merge sort algorithms.
