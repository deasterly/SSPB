# INTRODUCTION > Lab Environment Information

## Participant Lab Information

### On Demand Lab Environment

> NOTE: THIS ENVIRONMENT WILL BE USED FOR LEARNING BASIC LINUX SKILLS

1. Go to https://dell.sabacloud.com and search the Learning Catalog for "Introduction to Linux - On Demand"
2. Locate the course with "ID: ES33INTROLINUX"
![image](https://user-images.githubusercontent.com/36435980/148849811-b7572c17-d933-43f2-96e4-e9dd33f25115.png)

3.  Register for and launch the course.
4.  Skip ahead to slide #4 and find the lab environment registration link
![image](https://user-images.githubusercontent.com/36435980/148850546-b7a1c14e-0fd0-4bbc-9440-fd7f9780ec3b.png)

5. Go back to slide #3 and watch "Demo 1: Introduction to the Lab Environment"
6. Follow the instructions in pages 1-7 of the "Manual" tab to log in to the **"Linux Desktop"** and **"JumpServer"** consoles
    - User login names and passwords are provided on pages 6 and 7 
7. Skip ahead to slide #19 and watch the video
8. Follow along with slide #20 and pages 11-13 of the "Manual" tab to manually install CentOS 7, making sure to use the console labeled **"MANUAL-INSTALL-CENTOS7"**  
9. Skip ahead to slide #22 and watch the video
10. Follow along with slide #23 and pages 14-16 of the "Manual" tab to perform an automated install of CentOS 7, making sure to use the console labeled **"KICKSTART-INSTALL-CENTOS7"** 


### PowerEdge Server Hardware Lab Environment

> NOTE: THIS ENVIRONMENT WILL BE USED FOR VIEWING AND COLLECTING LOGS, INSTALLING "OMSA", ETC.

1. Connect to the corporate LAN or VPN 
2. Launch the Remote Desktop client
    - Try "START > Run > `mstsc` " or **`<WINDOWS_KEY+r>`** then type `mstsc` in the "Run" box
3. Connect to the IP address provided by the instructor for your assigned lab station as user **AM01\BME102STXX** where **XX** is your station number, 01 through 10

| STATION # | RDP ADDRESS  | RDP USERNAME    | RDP PASSWORD | iDRAC ADDRESS | SERVER ADDRESS |
| --------: | :----------- | :-------------- | :----------- | :------------ | :------------- |
| 01        | 10.206.17.71 | AM01\BME102ST01 | d3ll$----    | 192.168.1.21  | 192.168.1.31   |
| 02        | 10.206.17.72 | AM01\BME102ST02 | d3ll$----    | 192.168.1.22  | 192.168.1.32   |
| 03        | 10.206.17.73 | AM01\BME102ST03 | d3ll$----    | 192.168.1.23  | 192.168.1.33   |
| 04        | 10.206.17.74 | AM01\BME102ST04 | d3ll$----    | 192.168.1.24  | 192.168.1.34   |
| 05        | 10.206.17.75 | AM01\BME102ST05 | d3ll$----    | 192.168.1.25  | 192.168.1.35   |
| 06        | 10.206.17.76 | AM01\BME102ST06 | d3ll$----    | 192.168.1.26  | 192.168.1.36   |
| 07        | 10.206.17.77 | AM01\BME102ST07 | d3ll$----    | 192.168.1.27  | 192.168.1.37   |
| 08        | 10.206.17.78 | AM01\BME102ST08 | d3ll$----    | 192.168.1.28  | 192.168.1.38   |
| 09        | 10.206.17.79 | AM01\BME102ST09 | d3ll$----    | 192.168.1.29  | 192.168.1.39   |
| 10        | 10.206.17.80 | AM01\BME102ST10 | d3ll$----    | 192.168.1.30  | 192.168.1.40   |

4. After logging in to the Remote Desktop of the Windows Server "Jump Box" open a browser to your assigned iDRAC address
    1. Accept the self-signed security certificate if necessary
    2. Use the default credentials of **root / calvin**
5. Open the PuTTy SSH client and connect to your assigned server address using **student / Passw0rd** for the credentials
  
