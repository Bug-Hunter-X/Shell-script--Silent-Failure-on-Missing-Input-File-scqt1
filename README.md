# Shell Script: Silent Failure on Missing Input File

This repository demonstrates a common error in shell scripting: the silent failure when an input file is missing.

The script `bug.sh` attempts to process a file, but does not check if the file exists before proceeding. This leads to a silent failure if the file is not found.

The `bugSolution.sh` file provides a corrected version that checks for the file's existence and handles the case where the file is missing appropriately, providing a user-friendly error message.