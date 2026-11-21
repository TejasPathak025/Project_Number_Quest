# Project_Number_Quest

## Team Members
- Tejas Pathak (26CSU311)
- Divyansh Tyagi (26CSU170)

## Description
A console-based number guessing game in C. The computer picks a random number and the player tries to guess it within a limited number of attempts. After each guess the program gives a hint: too high or too low.

## Features
- Menu-driven (Easy, Medium, Hard, Exit)
- Random secret number based on the selected level
- Too high / too low hints after every guess
- Attempt tracking and score calculation
- Input validation, win and lose messages
- Play again from the menu, with total score shown on exit

## C Concepts Used
Functions, loops, conditional statements, switch, random number generation

## How to Compile and Run
Make sure GCC is installed, then run these commands in the project folder:

gcc -Wall -o number_quest number_quest.c
./number_quest

On Windows, run `number_quest.exe` instead of `./number_quest`.

## Screenshots
See the `screenshots/` folder.
