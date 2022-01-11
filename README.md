# CLI RPN (Reverse Polish Notation) Calculator
It is a specific Calculator mostly design for testing someones coding skills.

## Running the program
In order to run the program you will be need to download and install Node.js on your computer and you will need to have
the Node package manager which is "npm" installed on your computer. In order to check if you have "node" and "npm" installed
on your computer, you can go to your terminal/command-line and type:

```D:\myComputer> node -- version```

```D:\myComputer> npm -- version```

Once you have checked and already have them installed, you can clone or download the calculator package onto your computer. On 
the terminal, cd to the folder and type:

``` calculator$ node app.js```

in order to run the program.

## Description 
The RPN calculator was a bit challenging, especially error testing it. Since it was not a huge project, I figured I code it entirely in one file; unless needed maximum two. I started off with the function in order to work on the algorithms first. As I went on, I decided to code the part which can obtain input from the user from the terminal. In order for the program to keep going, I decided to go with an infinite while loop unless needed exiting by some commands. I noticed I can filter some of the errors in the while loop before reaching the function itself to make it easier. Lastly, left an error message at the end of the function so if all goes wrong the program doesn't crash and instead return the "invalid input" at the end. 
Some trade-offs that I had to do was spending most of my time in making sure the program works and cutting of time from the user experience and the presentation of the program. If more time was available, I would try to fix the interface a bit more and make it more clean and friendly to use and also try to create more cases in order to test the code and reply messages in a more clear way to the user. The only main issue that bothered me personally the most was when you input letters or nonefunctional symbols first and then with space the right amount of numbers and signs, it does the calculation for those numbers but also presents a message saying please insert numbers and the right signs, which makes it a bit confusing. 
