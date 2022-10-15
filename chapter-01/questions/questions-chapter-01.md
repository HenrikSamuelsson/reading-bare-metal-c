# Questions Chapter 1

Answers to questions found in the book Bare Metal C, chapter 1.

## Question 1

One piece of documentation for the GNU make build automation tool is the manual that can be found at the [GNU Make Manual web page](https://www.gnu.org/software/make/manual/).

The manual can be a bit dry to read so an alternative can be to go through a tutorial like the [Makefile Tutorial](https://makefiletutorial.com/).

## Question 2

C is portable between different types of machines. If using only standard C features and best practices for portability so can a C program be ported between different types of machines. This is done by compiling an executable for the desired machine.

## Question 3

Assembly languages are not portable due to being tied to a specific machine architecture. A program written in one assembly language would need to be rewritten for it to run on another type of machine. Portability is one of the main advantages of higher-level languages such as C.

## Question 4

Assembly language is designed to be a thin layer above the machine code to simplify coding compared to directly writing actual machine code. A single assembly statement will by design typically generate just one machine instruction.

C statements can generate many machine instructions due to that C is a high-level language with constructs that are more complex and will not be directly supported by the available, more basic, machine code instructions for a given machine.
