# 109 Python Problems for CCPS 109

This repository contains the problem specifications and the automated tester for the graded lab problems for the course [CCPS 109 Computer Science I](https://docs.google.com/document/d/1xj3_jehCEMB0las9o6OWgDFB8HuC47hCVYW4UNByFGo/edit?usp=sharing), as taught by [Ilkka Kokkarinen](http://www.scs.ryerson.ca/~ikokkari/) for the Chang School of Continuing Education, Ryerson University, Toronto, Canada.

Write the specified functions one by one into the same file `labs109.py` so that the automated tester `tester109.py` can find them. The automated tester will test only those functions that you have implemented so far, and run the tests in the order in which your functions appear in the file.

Each function is tested by giving it a large number of pseudorandomly generated arguments, and a checksum of all answers is compared to the checksum produced by the instructor's private model solution. This allows the students to work at home and check if their function is correct without the need to release the private model solutions. Furthermore, the file `record.zip` contains the prerecorded expected results for the first 300 test cases for each problem. The automated tester will compare these recorded expected results to those produced by the student solution, and in the case of a discrepancy, terminate that particular test and report the failed test case for the student to examine and help the debugging work.

For the instructors in some corner case situation where the first 300 recorded test cases are not enough to explain why the student solution does not pass the checksum test, the tester script also contains a handy `discrepancy` function to find the discrepancies between the student solution and the private model solution for the instructor to debug a solution that fails the test with a checksum error.

The file `ilkkaresults.txt` contains the running times of these functions for the private model solutions, measured on a 2020 Mac desktop with 3.6GHz processor.

Everyone who wishes to teach or learn Python is welcome to use and adapt these problems for their own purposes as they see fit. The author welcomes feedback by email at `ilkka.kokkarinen@gmail.com` from computer science instructors who use these problems in their courses.

The lab specification document and the automated tester software `tester109.py` are released under the [GNU General Public License v3](https://www.gnu.org/licenses/gpl-3.0.txt), with no warranties implied by the author.

Wordlist `words_sorted.txt` adapted from [dwyl/english-words](https://github.com/dwyl/english-words).
