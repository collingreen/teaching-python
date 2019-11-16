# Getting Started

## Option 1 (harder but better) - Install git and clone this repository

There are many lessons worth of info about git and github but for now, install
git if you don't already have it on your computer (try `git --version` to
check) using the instructions here:

https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

When you have that working, you can 'clone' this project to your local machine
so you can get started playing with python.

`git clone https://github.com/collingreen/teaching-python`


## Option 2 (easier) - Download the repository manually

Download the following zip and unzip it into a folder.

https://github.com/collingreen/teaching-python/archive/master.zip


Either way, you now have this entire project copied to your local machine. Open
a terminal (might be 'command prompt' on windows) and move to this new folder
(maybe `cd c:/development/teaching-python` or `cd teaching-python`).


## Install python

Go to https://www.python.org/ and find/follow instructions to install python
(version 3) for your computer. When I wrote this page the right place to go was
"Downloads" in the top menu bar.

When you are done you should be able to open a terminal/command prompt and type
the following:

`python --version`

and get something like

`> Python 3.7.4`

If your python is version 2 instead of 3, start over :)

You may run into an issue with installing python but not being able to call it
from the command line. [This github issue](https://github.com/collingreen/teaching-python/issues/9)
has some details on how to include the directory where python is installed in
your 'path', which is how your terminal knows where to look for things when you
try to call them. If you can't get it working, ask for help!


## Install pip

There is a good chance you already have pip installed at this point. Try the
following command:

`pip --version`

if you see something like

`pip 19.1.1 from /usr/local/lib/python3.7/site-packages/pip (python 3.7)`

then you're good to go! If not, try to follow the relevant instructions
at https://pip.pypa.io/en/stable/installing/.


## Install Everything Else

You should be able to use pip to install all the other requirements that have
been set up for this project. Make sure you're in the root of this repository
and call the following command:

`pip install -r requirements.txt`

This will use pip to install everything written in the requirements.txt folder,
which should give you everything else you need.


