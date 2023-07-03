# BASH CLI Shell > Understanding commands and their syntax > External Commands and Scripts
![image](https://user-images.githubusercontent.com/36435980/148658667-e28011bc-ce79-428b-b919-4879d5caadb6.png)

Once you can access the CLI shell, you must use commands to operate the system.  Each command has its own syntax, but there are some conventions that are helpful to remember.

- Commands are followed by **ARGUMENTS**
	- Arguments could be files, users, hosts/IP addresses, etc. depending on what the command does
	- Arguments may be `[OPTIONAL]` or `REQUIRED`
  
- Some arguments are “options” or “switches” that modify the command.
	- Options affect the output of a command, it’s behavior/operation, or both.
   
- There are both “long” and “short” options
	- Long options look like this:  ` ls --all --recursive --reverse `
	- Short options look like this: ` ls -aRr `
   
- If a command accepts multiple arguments the documentation will show you
    
	- `ARGUMENT` without the ellipsis points means 1 argument only
	- `ARGUMENT...` means 1 or more required arguments
	- `[ARGUMENT]...` or `[OPTIONS]` mean 0, 1, or more optional arguments or switches
      
> PRO TIP: Avoid mistakes in arguments by using **`<TAB>`** autocompletion when possible!	


![image](https://user-images.githubusercontent.com/36435980/148658606-a227d226-0e9b-418f-9c08-26062e10fad6.png)

*****
A Linux administrator needs to know a lot of commands, but in our introductory course we will start with some basics.  

There are lots of different quick-reference tools and cheat sheets for Linux commands available online that might be helpful as you begin to learn the CLI.

- Files and Directories
  - ` ls [<path>]... ` to list files/directories
    - `ls` is an EXTERNAL command  with an **alias**
  - ` pwd ` to show current working directory
  - ` cd [path] ` to change working directory
    - `cd` and `pwd` are BUILTIN commands 
- Users and Groups
  - ` who ` and ` w ` both show active logins
  - ` id [<username>] ` shows UID, GID and groups
  - ` whoami ` shows current user
- Reading Text
  - ` cat <filename> ` displays a text file in the terminal
  - ` less <filename> ` is a “text pager” with search features
  - ` grep ‘STRING’ <filename>  ` searches for the text STRING
- Editing Text
  - Save output into text with I/O redirection like this:  ` ls > file `
  - ` nano ` is an easy editor with built-in help
  - ` vim ` is a powerful, advanced editor

See the Linux commands cheat sheet from https://fosswire.com/post/2007/08/unixlinux-command-cheat-sheet/ for more.
Nearly all commands accept switches/options that modify the operation from the default, change the output, or both.

![image](https://user-images.githubusercontent.com/36435980/149020803-16eff2b3-f726-4edc-a762-6ac8448a68ef.png)


*****
## TRY IT - EXTERNAL COMMANDS

Run the following commands in a terminal on the Linux Desktop VM Console as user **student**:
1. `which cp `
2. `file $(which cp) `
3. `which zcat `
4. `file $(which zcat) `
5. `less $(which zcat) `

*****

> INSTRUCTOR NOTES:
> Refer to the following video(s) for more information: 
>  https://edutube.emc.com/html5/videoPlayer.htm?vno=PQW2sqJE7CIFXFpfrRquFw== 
>  https://edutube.emc.com/html5/videoPlayer.htm?vno=aRz95PUSU62BBVCMvicJAQ== 
> 
 *****
# Aliases

An **alias** is a feature of the shell that allows users or administrators to use a string to call a different command.
Aliases are often used to add an **option** to a command whenever it is run.  For example:
The command `ls` actually runs `ls --color=auto`

Another use is to create "shorthand" commands.  For example:
The alias `ll` actually runs `ls -l --color=auto`

To **override** an alias, place a backslash immediately before the "aliased" command.

![image](https://user-images.githubusercontent.com/36435980/148658624-2658f59c-8cdb-48e8-ac1c-88a1e52ec08c.png)

## TRY IT - BASH Aliases  
Run the following commands in a terminal on the Linux Desktop VM Console as user **student**:

1. `which ll `
2. `alias -p `
3. `grep 'alias' /etc/profile.d/*.sh `
4. `sudo -i `
  > Enter **P@ssw0rd** when prompted.
5. `alias -p `
  > Notice that root has aliases for `mv` and `rm` that student does not have.
6. `exit `
7. `help alias `
  > Take a moment to read the help.
8. `labtest `
  > This will result in a "command not found" error, which is expected.
9. `alias labtest='echo Hello world'  `
10. `labtest `
11. `which labtest `
12. `unalias labtest `
13. `which labtest `



[PREVIOUS](./topic_3.md)     [NEXT](./topic_5.md)
