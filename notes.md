# Learn-C
My purpose for this repository is to store and organize my notes and examples as I go about learning C. I wish to improve my skill to code in C to eventually write code for embedded systems. Up to this moment I have only programmed in Arduino in regards to writing software that runs in some specific hardware.
I will probably approach this challenge through trial and error. For example, if I write a simple "Hello, World!" program, I will try to take note of what happens if I change some minor things.

## Index


### Learning the basics
Following [this website](https://www.learn-c.org/) the first topics to cover include

- Variables and Types
- Arrays
- Multidimensional arrays
- Conditions
- Strings
- For Loops
- While loops 
- Functions
- Static

#### My First Program
As tradition dictates [my first program](./Hello.c) will be a "Hello, World!" program. 

To compile this program i will use the command "gcc Hello.c -o Hello"
And to run it "./Hello"


The program works just fine with the first variation, but I wonder what changes when the return is not 0.

- When the return is 1 there is no change
- When the return is '1' or 'i' there is no change ('i' was found by error)
- When the return is 1.0f there is no change.
- When return is True there is an error since the reserved word is true. Compiler sugests including stdbool.h. After adding this change the program still works. It makes me question if there will be no type error.
-  
