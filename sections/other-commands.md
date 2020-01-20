### Other useful commands

**Note to Windows users:** *Some commands below may not work in Git Bash. Microsoft is working on [a supposedly full-featured Linux terminal](https://github.com/microsoft/Terminal), but as of May 2019, it has not been officially released to the end user.*

`<tab>` - The `<tab>` key on your keyboard will complete names of commands and files. Start typing a filename and hit tab twice to see all possible acceptable completions. If there is only one possibility, the rest of the name will be filled in for you.

`<up>` - The `<up>` key will fill in the last command you ran. Hit it multiple times to cycle through the last commands you've entered.

`man <command name>` - The `man` or manual command will provide information on any UNIX command. Try `man ls`, `man grep`, or `man man`. **Note to Windows users:** unfortunately, `man` is one of those commands that does not work with Git Bash. You can attempt getting a smaller bit of help text by adding the `--help` flag to a command, such as `ls --help`. (To stop everything from scrolling past, append `| less` to the command, as follows `ls --help | less` -- just remember that when the help has come to an end, you must press `q` to get back to the command prompt.) If you need the fuller man pages, they can be searched online.

`exit` - Exit the terminal session. You can also use `<Control-d>`

`sudo` - Run before a command to run it as an administrator. You will need to enter your password, and note that no asterisks or special characters will appear as you type. 

`su` - Become the root user of the system. Your `$` prompt will change to a `#` prompt.

`!!` - Run the last command. To run the last command you entered with administrative privileges, use `sudo !!`

`*` - refer to all files and folders in a directory, i.e., `cat *.txt`

`clear` or `<Control-l>` - Clear the terminal window.

`which` - Show where a command is stored on your system, i.e. `which python`

`history` - See the previous commands you've entered in the terminal. Useful in conjunction with `grep`

`cp` - Copy a file. `cp file1 file2` will make a copy of `file1` named `file2`. Can be used with the `-r` flag to copy whole folders.

`rm` - This command can be dangerous, so use it carefully. Removes a file or files. If used with the wrong flags or in the wrong place, you can delete a lot of important files, so be careful with this one.

`rmdir` - Remove an empty directory.

`.` and `..` - `.` Refers to the folder you're in, while `..` refers to the folder above.

`.hello.txt` - Any file with a `.` in front of its name is a hidden file. You won't see it in `ls` or in the GUI. To reveal hidden files, use `ls -A`

`ping` - Use `ping google.com` to see if your internet is working.

`df -hl` - Tells you how much hard drive space you have left.

`top` - Monitor which processes are using up your memory

`kill` and `killall` - Kill a particular process or kill a category of processes by name. Try `killall chrome` or `killall firefox`

`sudo shutdown -r` - Reboot the computer. `shutdown -h` turns off the computer. 

`time` - Use before a command to find out how long that command takes to run.

`uptime` - Tells how long your computer has been on.

### Not particularly useful commands

`cal` - Show a calendar.

`telnet towel.blinkenlights.nl` - Watch Star Wars in the terminal. Because.

`say "Hello there"` - Have your computer talk to you. (Use `espeak` on Linux.)

Find so much more on the command line:

[Bash manual](https://www.gnu.org/software/bash/manual/bashref.html) - the no nonsense text descriptions of bash commands.  
[explain shell](https://explainshell.com/) - a site that explains commands you paste into the form. This site is fantastic for breaking down commands you find in the wild on the internet.  
[Easy shell guide](https://lucasviola.github.io/easyshell/) - a friendly, styled (pastel!) list of common commands you might want to try out.
