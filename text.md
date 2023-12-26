# All you need to know

Here, we are goint to talk about some of the things you need to know about python programming language.

# Running python code

Now, let's learn how to run python code on our machines. We will see different ways to run python programs on different OSs.
We will be primarily using linux to work on most of our programs, this is because it is easier to use and most of the work is already done for us.

## Windows machine


## MacOs machine

## Linux machine

First, create a directory/folder called "work_dir" and inside it, create a python file called "hello_world.py":

'''bash
#create a directory/folder
$ mkdir work_dir

#cd into the folder
$ cd work_dir

#create hello_world file
$ nano hello_world.py

   or

$ touch hello_world.py
'''

### Running hello_world.py

Open the file with a text editor,like nano or vim, i.e. "nano hello_world.py".
Inside the file "hello_world.py", write the following code:

'''python
print("Hello, world!")

'''

Save the file and run it as follows:

Note: this is on linux or macOs terminal

'''bash
$ python3 hello_world.py

'''

Upon successgul run, you should see the following output

'''bash
Hello, world!

'''
