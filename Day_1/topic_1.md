# BASH CLI Shell > Logging in to the CLI shell	> Local Terminals


![image](https://user-images.githubusercontent.com/36435980/148657684-2e1ac635-60d9-41a7-86d7-c7d06b2f8225.png)

- There are multiple simultaneous CLI user sessions available on the locally attached physical console
- Each local CLI session runs in a "Virtual Terminal" (VT) 
- Each Virtual  Terminal is attached to a "TTY" device (*/dev/tty# *)
- The TTY controlling terminal device is how the OS keeps I/O from each user session separate
-
- GDM graphical login manager runs on TTY1 for GUI RHEL systems
  - Press **`<CTRL+ALT+F[2-6]>`** to leave GDM and **`<ALT+F1>`** to return
-
- Switch between TTYs using **`<ALT+F#>`** key combinations or the `chvt` command
  - Run `chvt 1` or press **`<ALT+F1>`**  for VT1 on */dev/tty1* 
  - Run `chvt 6` or press **`<ALT+F6>`**  for VT6 on */dev/tty6*
- 
- Exit CLI session using `exit` or `logout` commands or press **`<CTRL+d>`**
 
``` WARNING!!!  Using **`<ALT+F4>`** to access */dev/tty4* will CLOSE YOUR BROWSER WINDOW!  ```


> INSTRUCTOR NOTES:
> BE SURE TO DEMONSTRATE AND CAREFULLY EXPLAIN PRECISELY WHICH KEYS YOU ARE USING AND WHY!  
> This concept may be confusing to those completely new to Linux/Unix systems..
> It may be helpful to use an on-screen keyboard to demonstrate what you are doing. 
> On Windows 10, try “START > RUN > osk” and suggest this option to students whose computers might bind some of these key combinations to other controls such as brightness, volume > controls, or display settings.

*****


[PREVIOUS](./README.md)     [NEXT](./topic_2.md)
