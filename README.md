## Laboratory Assignment #3: Program Style, Compilation, and Math with Integers  

**Points**: 100 pts

*Purpose: gain some familiarity with program style, fixing compilation errors in a program and arithmetic operations.*

---
## Fixing Style and Compilation Errors

For information on how to fix the coding style within the provided files, please use this [reference](https://github.com/chelberg/cs2400/blob/master/docs/coding-style.md). Please **make sure** that each **code** file you make edits to follows this coding style
#### Problem 1 (30 points)
1. Compile `prog1.cc` by typing the command `g++ -Wall prog1.cc` while are you are in the `lab3` directory
2. Run the executable by typing `./a.out`
3. Note that the program and output are almost unreadable due to bad formatting. Reformat the program to fix this issue. Please make sure to add introductory header comments (a block including your name and lab # and any general comments you have)
#### Problem 2 (15 points)
1. Compile `prog2.cc` by typing the command `g++ -Wall prog2.cc` while are you are in the `lab3` directory
2. **Answer questions 1 - 3 on the lab answer document**
3. Use an editor (VS Code, nano, vim) to make the correction
4. Recompile `prog2.cc`
5. Run the executable by typing `./a.out`
6. Use I/O redirection to save the results of this command as follows. The command is shown below. Note that the > causes the output to be redirected to a file called prog2.out
```
./a.out > prog2.out
```
7. Type `more prog2.out` to make sure that the file contains the correct output

#### Problem 3 (15 points)
1. Compile `prog3.cc` by typing the command `g++ -Wall prog3.cc` while are you are in the `lab3` directory
2. **Answer questions 4 & 5 on the answer document**
3. Use an editor (VS Code, nano, vim) to make the correction
4. **Answer question 6 on the answer document
5. Recompile `prog3.cc`
6. Run the executable by typing `./a.out`
7. Use I/O redirection to save the results of this command as follows. The command is shown below. 
```
./a.out > prog3.out
```
7. Type `more prog3.out` to make sure that the file contains the correct output

#### I/O Redirection (10 points)
1. Compile `prog4.cc` by typing the command `g++ -Wall prog4.cc` while are you are in the `lab3` directory
2. Run the program `a.out` by issuing the command `./a.out`
3. Type the following at the Keyboard. Note: Control-D means to press control and d together to generate an EOF signal from the keyboard.
```
10
3
8
Control-D
```
4. **Answer question 7 on the answer document**
5. Issue the command `./a.out < input.txt`. Note that `<` is causing input to be redirected to come from a file called input.txt
6. Save the results of this command by issuing the command 
   `./a.out < input.txt > prog4.out`
7. Type `more prog4.out` to make sure that the correct output was produced
8. **Answer question 8 on the answer document**
#### Arithmetic Operations with Integers (30 points)
1. Compile `prog5.cc` by typing the command `g++ -Wall prog5.cc` while are you are in the `lab3` directory
2. Run the program `a.out` by issuing the command `./a.out`
3. **Answer questions 9-13 on the answer document**
