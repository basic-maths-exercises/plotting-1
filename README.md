# Plotting

In the first of these sets of exercises, you learned about how we can use Python to evaluate mathematical equations.  You then learned that we should always try to write short programs as if you make your programs short, you are less likely to have errors.  We thus learned to ways we can make codes shorter:

1. We can use NumPy arrays and thus have fewer variables.
2. We can use for loops as these tell Python to repeat some action multiple times.

In this exercise, we are going to learn about functions, which is another trick we can use to make our programs do more with fewer lines of code.  As in the previous exercise, (at least if we are writing programs to do maths), we can avoid writing functions and just write longer codes.  It is useful to use functions in your codes; however, as you can then prevent writing bits of code that do similar things multiple times.

Before we get on to this business of functions, however, lets first do an exercise that revises the material that was covered in the first programming exercise on sequences.  I want you to consider the following sequence:

![](https://render.githubusercontent.com/render/math?math=a_n=n^2\quad\textrm{for}\qquad\n=0,1,2,3,\dots)

__Write a program that produces a graph with x values that are the first 30 ![](https://render.githubusercontent.com/render/math?math=n) values and y values that are the first 30 values for ![](https://render.githubusercontent.com/render/math?math=a_n).__ 
