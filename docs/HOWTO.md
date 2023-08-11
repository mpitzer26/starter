# Sample HOWTO

CS 210 projects come with instructions in a HOWTO file, in Markdown 
format.  If you don't have a Markdown previewer, you can read the 
the instructions through github ... click on the "docs" link, then 
the "HOWTO.md" link, and you should see a nicely formatted version 
of the instructions. 

## Starter project

The starter project is very simple:  Create a Python program, test 
it, and turn it in through Canvas. 

**Note** 
These instructions reflect that the default development environment 
for CS 210 is IDLE, which comes packaged with Python.  Students are 
welcome to use another development environment, such as PyCharm or 
VSCode, but it will be up to them to re-interpret some directions 
for variations between tools. We will provide a few pointers to 
differences in this project, but in subsequent projects you will be 
on your own. 

## Create a Python program

You should be working _within_ the directory (folder) containing the 
project, which you will probably want to keep in another directory 
(folder) that holds all your CS 210 projects.  How you get there 
depends on whether you use MacOS, Windows, or Linux. 

One way to begin is to start idle3 (which might just be "idle" on 
Windows), create a new file, and then use the "save as" command to 
save it within your project directory. Save it as "sample.py". 

[!Note]
If you are using another IDE, the command for creating a new program 
file will be different.  For example, in PyCharm the `File` menu has 
a `new` choice, and within that submenu you can choose `Python file`. 

## Hello, world

Your new program `sample.py` starts out empty.  There is a tradition 
in programming that the first program you write when trying out a 
new system is "hello world", which is just a program that prints 
"hello, world".  Let's do that. 

In Python, this is a one line program: 
```python
print("Hello, world")
```
That's it -- the whole program.   Use idle to save it. 

## Test! 

Run your "hello world" program (use the "run module" command in the 
"Run" menu of Idle).  

[!Note]
In PyCharm you can use the `run` choice in the `run` menu. 

## Create a bug

This exercise wouldn't be realistic if the program just worked 
perfectly the first time.  That just _never_ happens.  So, let's 
make this program buggy, and at the same time make sure you're using 
the right version of idle.  Add the following line of code, but 
using your own name: 

```python
print "This is <your name here> practicing for CS 210"
```

Run your program again.  You should get an error message that looks 
something like this: 

![IDLE message popup says "missing parentheses in call to print"](
img/missing-parens.png)

[!Note]
In PyCharm, the error message will appear in a separate pane called 
"Run".

If you do _not_ get an error message, you are probably using the 
version of `idle` that comes with Python 2.7.   That is the wrong 
version for this class!  We want Python 3.10, which treats `print` 
as a function that you call like `print("something")`.  

## Fix the bug

Add the missing parentheses. 

Test again.  Now it works, I hope! 

## Turn it in

Save the completed program, and then turn it in using Canvas. 



