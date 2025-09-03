Challenge
Category: Reverse Engineering  
Author: karan  
Difficulty: Beginner  

Description

This is a  reverse engineering challenge.  
You are given an obfuscated C source file `wikki.c`.  
Compile and run it to reveal the flag.

The code looks confusing with lots of macros, math, and unused functions,  
but the actual flag is hardcoded in the program.



 Provided Files
 `wikki.c`



 Instructions

 1. Compile
bash
gcc -std=gnu89 -w wikki.c -o wikki_bin -lm
 2. Run
./warmup_bin
 3.output
 flag{hi_all_wElcomE_this_task} you got it
