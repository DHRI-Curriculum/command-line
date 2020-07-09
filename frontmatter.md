# Frontmatter

## Abstract

By this point in our academic careers, most of us have figured out some ways we like to interact with computers. Whether that involves avoiding them as much as possible or constantly testing new software, we likely have some ideas about how we feel comfortable getting things done. How would you show a person who had never seen a computer, say [Kimmy Schmidt](https://youtu.be/LIdFa1qLgNQ) or [Brendan Fraser in *Blast from the Past*](https://youtu.be/Xq29uTtKW4M), how to *do* something on your computer?

Many of us would explain what a screen and a cursor are, and then show how to point and click on icons. This approach relies on a graphical user interface, or GUI (pronounced "gooey!").

Today we're going to explore another way to make your computer do things: through the command line. Instead of pointing and clicking, we'll be typing in either git bash (Windows) or terminal (macOS) to tell the computer directly what task we'd like it to perform.

While this new technique can seem intimidating if you haven't used text-based interfaces before, luckily, you can use 90% of the functionality of the command line by becoming comfortable with a very small set of the most common commands.

## Learning Objectives

In this workshop, you will learn the following skills:

- Learn common commands to create files (`touch` and `echo`)
- Learn commands to create directories (`mkdir`)
- Navigate our file structure using change directory (`cd`), print working directory (`pwd`), and list (`ls`)
- Move content from one place to another using redirects (`>`) and pipes (`|`)
- Explore a comma separated values (.csv) dataset using word and line counts, `head` and `tail`, and the concatenate command `cat`
- Search text files using the `grep` command
- Create and sort cheat sheets for the commands we learn

## Estimated time

3 hours.

## Prerequisites

To complete the workshop, you will need:

- A plain text editor, such as [VS Code](https://github.com/GC-DRI/install/blob/master/sections/vscode.md) installed
- To know what operating system you're using. If you are on a Mac, you will be using your Terminal. If you're using Windows, you won't be using its own non-UNIX version of the command line. You will need to install Git Bash, following [these instructions](https://github.com/DHRI-Curriculum/install/blob/master/sections/git.md), so that we can work in the cross-platform Unix command line for this session. 

## Contexts

### Pre-reading suggestions

- [Neal Stephenson, "In the Beginning Was the Command Line"](http://cristal.inria.fr/~weis/info/commandline.html)
- [Douglas Rushkoff, *Program or Be Programmed*](https://rushkoff.com/books/program-or-be-programmed/)
- [Free Code Camp, A Brief History of the Command Line](https://www.freecodecamp.org/news/the-command-line-1fdbc692b3bf/) 

### Projects that use these skills

Mastering the command line will prove useful in a great number of projects. 

- Most Python- and R-based projects will require you to have some knowledge of the command line. At a very basic level, you will be invoking a Python script and will be using values of command line arguments when creating and running your scripts.
- The command line is also useful for setting up installations of server side software like [Omeka](www.omeka.org). The command line will allow you to navigate the file structure of your server. Commands like ls, mkdir, rmdir, cd, etc. are really important. For example, grep could help you find a plugin directory that you might have accidentally placed in the wrong location.


### Ethical Considerations

"The command line" is also laden with masculine and military metaphors, which is reflective of the history of computing and programming. As Wendy Hui Kyong Chun discusses in ["On Software, or the Persistence of Visual Knowledge" (2004)](https://doi.org/10.1162/1526381043320741), almost all computers (as in human comput-ers) in the US during World War II were young women. Human computers received commands from analysts——predominantly men with the military—that they then had to interpret and act upon the machine. As Chun (p. 34) argues

> computation depends on 'yes, sir' in response to short declarative sentences and imperatives that are in essence commands ... The command line is a mere operating system (OS) simulation.

The command line (of computers today) receives these commands as text that is typed in.

## Resources 

- [Commands cheat sheet](sections/12-commands.md)  
- [More on text editors](sections/13-text-editors-ides.md)  
- [Other useful commands](sections/14-other-commands.md)   
- [Glossary](https://github.com/DHRI-Curriculum/glossary/blob/master/sections/command-line.md)
- [Bite Size Command Line (by Julia Evans)](https://jvns.ca/blog/2018/08/05/new-zine--bite-size-command-line/)
- [Basic UNIX commands](http://mally.stanford.edu/~sr/computing/basic-unix.html)

## Acknowledgements

- Current Author: Stefano Morello
- Contributing Author: Kelsey Chatlosh
- Contributing Author: Patrick Smyth
- Contributing Author: Mary Catherine McKinniburgh
- Contributing Author: Jojo Karlin
