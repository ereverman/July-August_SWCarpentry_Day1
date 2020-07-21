### Notes for teaching Unix Shell, day 1: July 24.

Course website: https://kulibraries.github.io/2020-07-24-ku-online/
This etherpad: https://pad.carpentries.org/2020-07-24-ku-online

Syllabus:
* Introduction to File Organization
* Files and Directories
* History and Tab Completion
* Pipes and Redirection
* Looping Over Files


 ## Directory structure and file organization
 * refer to powerpoint
 
 * Using the Shell and terminal program, we move from a GUI (graphical user interface) to CLI (command line interface)
   * Advantages: Allows repetetive tasks to be automated and reduces errors, can be leveraged with scripts to make tasks much faster, can interact with supercomputers and high performance cluster systems like HPC at KU.
   * Disadvantages: Can be a little opaque, especially if you are only used to working with the GUI.
 
 * The Shell:
   * What is it:
    * A program with the primary purpose of reading commands and running other programs
    * There are different shells, but Bash is the default on most systems and is the shell we will be working with.
    * Learning to use the shell is like learning to speak a new language.
     * Interacting with files and running code requires an understanding of the shell grammar and proper words that designate functions.
 

## Navigating Files and Directories:

Refer to the powerpoint for an introduction to files and directories:
 * Let's take a look at the shell.
 * $ is the prompt symbol. When you see this, the shell is waiting for your input.
 * I asked you to try an figure out where in your terminal opened. There are 2 ways to figure this out:
  * Look at the information immediately preceeding prompt
  * Use a function:
 ```
 pwd
 # print working directory.
 ```
* On your map, you should move your marker to the "ME" spot. pwd is an especially useful tool. More often than not, when a series of tasks errors out, it's because either your position in your directory structure or your file directories are not referenced correctly.

* Now we know where we are, we can look at the contents of the User directory:
```
ls
# lists the contents of directory
```

* Most functions have additional options that make them more user friendly. For example, if we wanted the directory contents organized line by line:
```
ls -l
# lists the contents of directory line by line with a lot more information.

ls -F
# add a marker to file and directory names to indicate what they are
# / indicates a directory
# @ indicates a link
# * indicates executable
# Depending on your shell preferences, the shell might use colors to indicate whether each entry is a file or directory
```


* One of the big mysteries when I started to learn how to use the shell was knowing what tools were available.
* Here is a quick reference that has useful basic functions:
https://github.com/ereverman/July-August_SWCarpentry_Day1/blob/master/command-handout.md
* Here is an example of how to find the options for ls:
http://linuxcommand.org/lc3_man_pages/ls1.html

```
man ls
# to exit, q

ls --help
```

* What happens if you mistype:
```
ks
# Error message: command not found

ls-F
# spaces are important

ls -s
ls -S
# capitalization is important

ls -lh
# can combine flags

```

* Some suggestions for staying motivated and sane while learning to code:
 * Error messages are actually your friend. Get in the habit of looking at them closely. Sometimes, the problem is easily fixed (typo, path issue).
 * Everyone gets error messages, and code doesn't always run right the first time. More often than not, your error isn't new and someone has provided a solution online.
 

## Navigating Files and Directories:

* Let's get some data that we will use to practice on.
https://github.com/kulibraries/ku-swc-files.git




