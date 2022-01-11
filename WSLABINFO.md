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
![image](https://user-images.githubusercontent.com/36435980/148990489-ff93a78f-6c75-43bb-afdc-5397fbe3d06e.png)
    3. KEEP the default password when prompted
![image](https://user-images.githubusercontent.com/36435980/148990687-726a2256-6fb6-4159-ae0d-ee9ed332c2cb.png)
    4. Ensure the Virtual Console Settings use HTML5 and that the Keyboard/Mouse Attach State is "Auto-Attach" if needed
![image](https://user-images.githubusercontent.com/36435980/148991008-02895d55-c1d5-489a-ba71-4bdaf6640b00.png)
![image](https://user-images.githubusercontent.com/36435980/148991158-f2172173-92c3-45c1-923a-94f75d27bbdb.png)

5. Open the PuTTy SSH client and connect to your assigned server address using **student / Passw0rd** for the credentials
  
## Instructor Lab Information

### On Demand Lab Environment
1. Learners only need to register for the labs once, and the environment can be launched from either the On Demand lab slides (i.e. slides 21, 24, 28, etc.) or from https://dell.sabacloud.com then clicking on "Me" then locating the "Launch" button for "Introduction to Linux - On Demand Lab"

![image](https://user-images.githubusercontent.com/36435980/148988720-2ad7be72-50c0-4519-93d0-759511dfff34.png)

![image](https://user-images.githubusercontent.com/36435980/148988873-1b794dd9-eaa2-420e-902e-ce752931e795.png)



### PowerEdge Server Hardware Lab Environment

1. Only the "BME102" (Bare Metal Equipment) server solution has been set up to support this workshop thusfar
2. All the BME102 servers will require additional configuration to support this workshop   

    1. Configure **and initialize** 2 RAID 0 arrays - 2 disks in the first R0 array (just under 300GB total) and a single disk R0 (just under 150GB) using the third disk
    ![image](https://user-images.githubusercontent.com/36435980/148991840-96e238f4-4bbf-42f2-9838-fcefddef8529.png)
    2. PXE boot each server using the Clonezilla imaging server    
    3. Select "device-image" from the first menu    
![image](https://user-images.githubusercontent.com/36435980/148992147-80ea26e4-62d0-4081-b334-d1b3f791d526.png)
    4. Use Clonezilla's "Beginner" mode
![image](https://user-images.githubusercontent.com/36435980/148992264-8d88b58c-aa9e-4ec0-a897-9204604459a9.png)
    5. Choose "restoredisk" to restore an image to local disk
![image](https://user-images.githubusercontent.com/36435980/148992422-743c916b-ee6f-44b0-9a79-20f75c250db9.png)
    6. Select the highest version # and date for the "RTLV_Workshop-vX.Y" image
![image](https://user-images.githubusercontent.com/36435980/148992703-443153e0-31c0-4ec1-b8b0-e2f5ab5bf194.png)
    7. Select "sda 292GB_PERC_H730_Mini__* " for the destination disk and skip checking the image before restoring
![image](https://user-images.githubusercontent.com/36435980/148992969-25e394fd-5767-47e5-81dd-9ed4f7d300ad.png)
![image](https://user-images.githubusercontent.com/36435980/148993081-35e8e372-f5b0-4787-a1c1-da22944bf1ee.png)
    8. Follow the prompts until the image is deployed and the server reboots
![image](https://user-images.githubusercontent.com/36435980/148993250-58b22485-d6ba-4b04-b1e5-87943cf8b19d.png)
![image](https://user-images.githubusercontent.com/36435980/148993373-113ac358-331b-44af-8fbb-3001c5fe84fd.png)
    9. If the server still boots to PXE, select "Local operating system" before the 10 second countdown timer runs out
![image](https://user-images.githubusercontent.com/36435980/148995410-1febf6e5-f07c-433b-874f-a60083a3f4ce.png)
