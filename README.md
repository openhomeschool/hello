# The "hello" project
## openhome.school Computer Class

This project is all about saying hello.  You will say hello to your computer... or will your
computer actually say hello to you?

## Basic hello

**Python is a programming language**.  In python, this is the most basic way to say hello:

```python
print('hello')
```

This tells the computer to *print* the word 'hello'.

But, to actually see this work, you have to "run" the code.  Open a terminal, according to your
instructor's guidance.  You'll see a "prompt"

## The prompt

**A prompt is the terminal's way of telling you: "I'm ready for your command...".**  It looks
something like this:

```sh
pi@pineapple:~ $ 
```

A terminal prompt is often called the "command line" - it is where one line of text will communicate
your "command" to the computer; it must do as you command!  At that command-line prompt, type:

```sh
cd ohs
```

And push "Enter".  It will actually look something like this:

```sh
pi@pineapple:~ $ cd ohs
```

But I'll tend to just show what you type, and leave off the prompt itself.

Now type, and press "Enter" after:

```sh
cd hello
```

You just ran a program twice.  However, it wasn't the program that says "hello".  It was the program
called "cd", and it is used to "change directory".  You "changed" the directory in which you're
working, first to the ohs directory (or "folder"), and then to the "hello" directory within the
"ohs" directory.  Your instructor will guide you through using your file browser to see the same
folder structure.

## Finally, let's see it work...

Now that you're "in" the "hello" directory, you can run the code that is in the file called hello.py:

```sh
python hello.py
```

Ok, it isn't the most exciting program in the world, but it did what we asked it to do.  Technically
you just ran the program called "python", which read the code inside the "hello.py" file, and did
what that code said to do.

## Another way

Let's do it a different way.  Let's run python interactively.  Type, in your terminal:

```sh
python
```

This time, since we didn't give python a file to read, it opens up interactively.  You'll see
something like this:

```sh
Python 2.7.18 (default, Apr 20 2020, 20:30:41) 
[GCC 9.3.0] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

You are now "in" a python interpreter.  **A python interpreter is a program that interprets lines of
python code and obeys them**.  Your "prompt" now looks like three sideways carrots.  The carrots
show, here, but you just type what's after them:

```sh
>>> print("Hello") # or you can: print("hello, it's nice seeing you today!")
```

And push "Enter".  You'll see about the same thing you saw when you ran `python hello.py`, above. 
Still not very exciting, but you did just interact with the computer in two distinct ways, both of
which have years of heritage.

By the way, to exit from that python interpreter, you'll have to press Control+D.  That means: hold
down the "Control" button (far lower-left of your keyboard) and, while holding it down, press D.
Then let go of both.  Control+C is the most common way to "Cancel" something going on in a terminal
(or elsewhere), but Control+C will not work to escape from an interpreter because, within a python
interpreter, it means "cancel whatever python code might be running", rather than "cancel this
interpreter program".

Our computers have fancy pictures and menus and windows and all kinds of bells and whistles.  Long
ago, a computer only had a terminal prompt, if it even had that.  However, many computers,
*especially* these days, do not even have a terminal promt or a screen at all. This is often
called a "headless" computer.  As long as a computer knows what it is supposed to do, it can do
it's job; it doesn't have to have a display screen or buttons and bells and whistles.

## Promptly confused

Why the two different prompts?  What's the difference between a rudimentary terminal prompt, and a
fancy python prompt?  That could invite a very complicated answer, but, in short: python is a
programming language, which gives you one set of tools for certain kinds of jobs that can be done on
a computer, while a terminal prompt gives you another, different set of tools, for other kinds of
jobs that can be done on a computer.  You'll see the difference more later.

## More

For more investigation...

* [linux shell commands](https://www.hostinger.com/tutorials/linux-commands) - but note that many commands do have "easier", more modern, slick "graphical" interface equivalents
* [learn a little more python](https://docs.python.org/3/tutorial/introduction.html)
