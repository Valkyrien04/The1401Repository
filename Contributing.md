# Contributing to the repository

All contributed programs should be sorted into a seperate folder under a sub folder according to their use case. Each submission should be organized as such:

* <program name\> - Program root folder

  * man.md - documentation explaning expected input, output, and program operation to potential users. This should also include any requirements of operation, e.g. minimum card size, required tape drives/computer features, etc, as well as the expected output from a successful run of the test dataset.

  * <program name\>.cd - a text file consisting of card contents with each card seperated by a newline character. Text should be in either VDC, SIMH new, or SIMH old formats.

  * <program name\>.test.cd - a test dataset (or in the case of compilers, a test program source code) that can be used to check that the program is operating correctly.

Submissions are currently being tested on Rolffsons free emulator "The 1401 Room"

Programs may be submitted under the following categories:

* Compilers
  * Code compilers for early programming languages, such as FORTRAN, COBOL, Autocode, etc
* Utilities
  * Helper programs for use with particular datasets/workloads
* Demonstrations
  * Simple programs for use demonstrating the 1401 to laypeople, such as the CHM's "BigPrint" program, which takes a name via a card and prints a blown up version to the 1403 printer.
