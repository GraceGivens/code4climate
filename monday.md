**Let us begin**
#
# Agenda
Today we will do some introductions, and maybe some simple programming.
# Learning objectives
By the end of today, you will
- know your team
- get familiar with the logistics of this summer experience program
- have a working knowledge of _git_ and repository management at [github.com](https://www.github.com)
- learn about the _air quality index_
- run a simple _Python_ code
- write a simple _Python_ code
#

## Few things before we start
This file and the README file and many other files in this repository will be written using _markdown_. You can think markdown as a simple text-based tool to organize thoughts!

It is recommended that you try using markdown yourself, too. At least for this program. And see if you like it.

To get you started, [here's a cheatsheet on Markdown (md)](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
pressing . will take you to editor.
print ('Hello World')
name=input("what is your name? \n")
print("hi!",name)
timespan=input("Give me a timespan.")
noun=input("give me a noun.")
print("Every",timespan," i wake up and get off my ",noun)
number_of_apples_neighbor = input("Enter the number of apples your neighbor gives you: ")
number_of_apples_mine = input("Enter the number of apples your already have with you: ")
print("total number of apples", (int(number_of_apples_neighbor)+int(number_of_apples_mine)))
add a bracket for each piece
variable_1=input("Give one number. ")# blocks for writing the calculator code.
variable_2=input("Give a second number. ")
print(int(variable_1)+int(variable_2))
read the notes if it does not run. There may be an error
number_1=input("Give me one number. ")# blocks for average calculation
number_2=input("Give me another number")
number_3=input("give me one last number")
print((int(number_1)+int(number_2)+int(number_3))/3)
be careful about where you put and don't put ()
do not forget int( when needed
variable_1=int(input("give me a percentage."))# Grade calculation codeblock
if variable_1>90:
  print("A")
elif variable_1>80 and variable_1<=90:
  print("B")
elif variable_1>=60 and variable_1<=80:
  print("C")
elif variable_1<60:
  print("D")