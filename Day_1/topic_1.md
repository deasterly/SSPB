# BASH CLI Shell > Logging in to the CLI shell	> Local Terminals

Once your Linux system has booted successfully, it’s time to log in and start using it. 
You may be presented with two options for logging in to a Linux system - CLI, or GUI.

Servers, network appliances, and VMs usually do not have a GUI and are CLI-only.

CLI user sessions require a **terminal** and a **shell**
- A terminal is an I/O device for a CLI user session
    - */dev/tty1 - /dev/tty6* for local consoles
    - */dev/pts/0 - /dev/pts/N* for GUI and remote
- See your Terminal Device with the command `tty`
- The shell is a command interpreter in the terminal
    - Default is usually GNU Bash
- See your shell with the command `echo $SHELL`

![image](https://user-images.githubusercontent.com/36435980/149010151-784a9587-473a-439e-a671-feab329e2e18.png)

- There are multiple simultaneous CLI user sessions available on the locally attached physical console
- Each local CLI session runs in a "Virtual Terminal" (VT) 
- Each Virtual  Terminal is attached to a "TTY" device (*/dev/tty#*)
- The TTY controlling terminal device is how the OS keeps I/O from each user session separate
     
- GDM graphical login manager runs on TTY1 for GUI RHEL systems
  - Press **`<CTRL+ALT+F[2-6]>`** to leave GDM and **`<ALT+F1>`** to return
  
- Switch between TTYs using **`<ALT+F#>`** key combinations or the `chvt` command
  - Run `chvt 1` or press **`<ALT+F1>`**  for VT1 on */dev/tty1* 
  - Run `chvt 6` or press **`<ALT+F6>`**  for VT6 on */dev/tty6*
  - WARNING!!!  Using **`<ALT+F4>`** to access */dev/tty4* will CLOSE YOUR BROWSER WINDOW!  
   
- Exit CLI session using `exit` or `logout` commands or press **`<CTRL+d>`**
 
![image](https://user-images.githubusercontent.com/36435980/148657684-2e1ac635-60d9-41a7-86d7-c7d06b2f8225.png)

![image](https://user-images.githubusercontent.com/36435980/149010490-215f47bd-bd8f-467d-a6ea-3570428931e5.png)


*****

> INSTRUCTOR NOTES:
> Refer to the following video(s) for more information: 
> https://edutube.emc.com/html5/videoPlayer.htm?vno=KXUlN4xpOnFJeGgpAoWe8g==  
> 
> 
> BE SURE TO DEMONSTRATE AND CAREFULLY EXPLAIN PRECISELY WHICH KEYS YOU ARE USING AND WHY!  
>  
> This concept may be confusing to those completely new to Linux/Unix systems.
>  
> It may be helpful to use an on-screen keyboard to demonstrate what you are doing. 
> 
> On Windows 10, try “START > RUN > osk” and suggest this option to students whose computers might bind some of these key combinations to other controls such as brightness, volume > controls, or display settings.

*****


[PREVIOUS](./README.md)     [NEXT](./topic_2.md)

