## Group-4
#CS 599 Group 4 Repo
Table of Contents
Getting Started
Usage
Contributing
License
Getting Started
To get started with this simplified version of Yahtzee, you will need a C compiler to compile and run the program. Follow these steps to set up and run the program:
Clone the repository:
git clone https://github.com/yourusername/yahtzee-simplified.git
cd yahtzee-simplified
Compile the program:
gcc -o yahtzee yahtzee.c
Run the program:
./yahtzee

Usage
The program will simulate rolling five dice and then categorize the result based on Yahtzee scoring rules. Here is a step-by-step guide on how to use the program:
Roll the Dice: The program will automatically roll five dice, generating random numbers between 1 and 6.
Display the Dice: The rolled dice will be displayed on the screen.
Categorize the Roll: The program will check the rolled numbers and determine the highest scoring category:
Yahtzee: All five dice show the same number.
Large Straight: A sequence of five consecutive numbers.
Small Straight: A sequence of four consecutive numbers.
Full House: Three dice show one number, and two dice show another number.
Four of a Kind: Four dice show the same number, and one die shows another number.
Three of a Kind: Three dice show the same number, and the other two dice show two other distinct numbers.
No Play: The roll does not match any of the above categories.

Contributing
Contributions are welcome! To contribute to this project, follow these steps:
Fork the repository
Create a new branch
Make your changes and commit:
Push to the branch:
git push origin feature-name
Create a Pull Request: Go to the repository on GitHub and create a pull request to merge your changes into the main branch.
