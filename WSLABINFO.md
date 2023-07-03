# INTRODUCTION > Lab Environment Information

## Participant Lab Information


### PowerEdge Server Hardware Lab Environment

> NOTE: THIS ENVIRONMENT WILL BE USED FOR VIEWING AND COLLECTING LOGS, INSTALLING "OMSA", ETC.

1. Connect to the corporate LAN or VPN 
2. Launch the Remote Desktop client
    - Try "START > Run > `mstsc` " or **`<WINDOWS_KEY+r>`** then type `mstsc` in the "Run" box
3. Connect to the IP address provided by the instructor for your assigned lab station as user **AM01\BMEXXXSTXX** where **YY** is your station number, 01 through ??

| STATION # | RDP ADDRESS   | RDP USERNAME    | RDP PASSWORD | iDRAC ADDRESS | SERVER ADDRESS |
| --------: | :------------ | :-------------- | :----------- | :------------ | :------------- |
| xx        | 10.206.xx.yyy | AM01\BMExxxSTyy | ---------    | 192.168.1.xx  | 192.168.1.yy   |

4. After logging in to the Remote Desktop of the Windows Server "Jump Box" open a browser to your assigned iDRAC address
    1. Accept the self-signed security certificate if necessary
    2. Use the default credentials of **root / calvin**
![image](https://user-images.githubusercontent.com/36435980/148990489-ff93a78f-6c75-43bb-afdc-5397fbe3d06e.png)
    3. KEEP the default password when prompted
![image](https://user-images.githubusercontent.com/36435980/148990687-726a2256-6fb6-4159-ae0d-ee9ed332c2cb.png)
    4. Ensure the Virtual Console Settings are configured to use HTML5 and that the Keyboard/Mouse Attach State is "Auto-Attach" if needed
![image](https://user-images.githubusercontent.com/36435980/148991008-02895d55-c1d5-489a-ba71-4bdaf6640b00.png)
![image](https://user-images.githubusercontent.com/36435980/148991158-f2172173-92c3-45c1-923a-94f75d27bbdb.png)

5. On the "Jump Box" management station VM Download a bootable RHEL8.8 installer ISO from the link provided by the instructor
6. Use the iDRAC web interface to configure **and initialize** 2 RAID 0 arrays - 2 disks in the first R0 array (just under 300GB total) and a single disk R0 (just under 150GB) using the third disk
    ![image](https://user-images.githubusercontent.com/36435980/148991840-96e238f4-4bbf-42f2-9838-fcefddef8529.png)

7. Launch the HMTL5 Virtual Console, attach the downloaded RHEL8 ISO to the iDRAC's Virtual Media, then boot to the ISO
8. Follow along step-by-step as a group to complete the installation of RHEL8 on each server
9. Open the PuTTy SSH client and connect to your assigned server address using **student / Passw0rd** for the credentials
  
