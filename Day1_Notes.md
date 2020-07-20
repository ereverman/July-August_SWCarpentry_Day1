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
    * A program.
    * There are different shells, but Bash is the default on most systems and is the shell we will be working with.
    * Learning to use the shell is like learning to speak a new language.
     * Interacting with files and running code requires an understanding of the shell grammar and proper words that designate functions.
 
 
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

* Now we known where we are, we can look at the contents of the User directory:
```
ls
# lists the contects of directory
```

* One of the big mysteries when I started to learn how to use the shell was knowing what tools were available.
* Here are some quick reference resources that have useful basic functions:
https://github.com/kulibraries/swc-workshop-helps/blob/master/command-handout.md
