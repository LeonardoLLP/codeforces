# Codeforces
My solutions to the codeforces problems

## Structure of the repository.
The folder named "solved" contains all the problems that will be uploaded. It is divided into many folders, each one represented by the range of problems they contain, in multiples of 100. For example, the file 1732-A.cpp, corresponding to the problem A of the absolute round 1732, will be found at the path "problems/1701-1800/1732-A.cpp".

The folder named "working" contains 


## File format
Every file will start with a two-line comment with the following format:

/*
Date: YYYY-MM-DD
Help: unknown | no | algorithm | solution
*/

Help - Unknown means I uploaded it some time ago and I can't remember. No means no. Algorithm means I used any page that included a description of the algorithm that I wanted to use to program it, but the solution was mainly done by me. Solution means I saw the solution and implemented it.



## How to compile
First, run the bash file named "solved.sh". It will expect a number and a letter. The command ...

$ ./solved.sh 1732 A

... will compile the problem number 1732 letter A. Keep in mind that the number corresponds to the absolute contest number, not the codeforces round.

Similarly, we can compile files under the "working" folder by running the script "working.sh".

## How to contribute
You can't :)