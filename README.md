# Terminals and Shell programs

### Learning Goals
- What is the terminal program?
- What is a shell program? (Bash, zsh, fish)
- How do the two work together?
- How configuration files work (.bashrc, .zshrc, .vimrc)
- What are shell environment variables ($USER, $PATH)
- What does adding to the PATH mean, and how is it done, and why is it useful?

### The Terminal

The terminal is the entry point to our demo. The terminal provides an application space for us to be able to
interact with out computer. The terminal's job is to load and run a shell program, like one of the several
listed above (zsh, bash, fish). These shell programs are called shells, because they 'wrap around' the terminal
in a way, allowing us to interact with the terminal. Before we had our fancy graphical user interface (GUI)
computers, everyone that wanted to use a computer was forced to use the terminal, or command line. Now that we
regularly use the mouse, shell programs aren't nearly as commonly used as they once were. As a software
developer, you will find the terminal to be the most effective way to write programs and develop software.

### Shell Programs

A shell program provides all of the functionality you are used to while using the terminal. This program,
at its most basic level, provides a prompt for the user to input commands, and each one is processed as it
is received. The command from the user could be a program, like `ls` or `cd`. Both of these 'commands' are 
actually programs that we call upon to do their jobs. 

![Screenshot](./assets/Screen-Shot-2022-10-25-at-12.45.05-PM.png)

Figure 1: The shell program used by macOS by default is zsh. This program, along with bash (a very popular shell)
are both stored in a folder called bin, which itself lies in the root folder of the operating system. Other
programs you may recognize here are `ls`, `cd`, `mkdir`, amongst others. There programs are provided by the
operating system, so they will work from the moment you start your computer for the first time.

Now, we can see how the terminal and a shell program interact with each other. The terminal allows for a place
for anything to happen, like an empty canvas when beginning to paint something. The paintbrush and paint are 
the shell, which in turn allow you to create whatever you wish. 

### Configuration files (not so bad)

Configuration files are what allow you, the user, to specify to your shell program everything it needs to 
start up. These files, usually ending in `rc`, only run when the shell program is started. You can actually
observe this process in real time. Go ahead and open a terminal window or tab. You will see a moment of hesistation
from the terminal before the input prompt appears. If your machine is too quick, take a look at mine below.


![Opening new tab](https://giphy.com/gifs/7mskkHwHN1ddKkbrDN)
