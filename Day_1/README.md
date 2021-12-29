# Server Support Linux Workshop

## Day 1 Agenda

| **Section** | **Module** | **Lesson** | **Topic** |
| :---------: | :--------: | :--------: | :-------- |
| Using RHEL | BASH CLI Shell | Logging in to the CLI shell | Local Terminals |
| " | " | " | Remote SSH Terminals |
| " | " | Understanding commands and their syntax | Shell Built-ins |
| " | " | " | External Commands and Scripts |
| " | " | " | Using the `$PATH`, `whereis` and `which`  |
| " | " | Understanding BASH metacharacters | Special Characters |
| " | " | " | Quoting and Escaping |
| " | " | " | Control Operators |
| " | " | Using timesaving BASH features | Tilde Expansion |
| " | " | " | **`<TAB>`** Autocompletion |
| " | " | " | Brace Expansion |
| " | " | " | Keyboard Shortcuts |
| " | " | Documentation | Built-in Help |
| " | " | " | Understanding  `man` Pages |
| " | " | " | Using GNU Info pages |
| " | Managing Files and Directories | Creating, copying, moving/renaming, and removing | GNU Coreutils |
| " | " | " | Filename Expansion (a.k.a. "globbing") |
| " | " | Archiving files an directories | GNU `tar` |
| " | " | Transferring files over a network | Using `sftp` and `scp` |
| " | Working with Text | Reading text files | Using `cat`, `less`, `tail`, `head`, `wc` et.al |
| " | " | Editing text using `vim` | VIM Modes |
| " | " | " | Using `vimtutor` |
| " | " | " | Timesaving Tips and Tricks |
| " | " | Searching for text using `grep` | RegEx Fundamentals |
| " | " | " | RegEx Documentation and Examples |
||||

## Day 2 Agenda

| **Section** | **Module** | **Lesson** | **Topic** |
| :---------: | :--------: | :--------: | :-------- |
| Linux System Administration | Users and Groups | Creating and managing users and groups | Using `groupadd`, `groupmod`, and `groupdel` |
| " | " | " | Using `useradd`, `usermod`, and `userdel` |
| " | " | Setting user passwords | Using `passwd` |
| " | " | " | Using `chage` |
| " | " | Elevating user privileges | Using `su` |
| " | " | " | Using `sudo` |
| " | Software Package Management | Adding and removing software | Using `yum` |
| " | " | " | Using `rpm` to query packages |
| " | " | Adding installation repositories | Understanding */etc/yum.repos.d/*.repo* files |
| " | File Ownership and Permissions | Identifying and interpreting ownership and permissions | Permission Basics |
| " | " | " | Understanding `stat` and `ls -l` output |
| " | " | Modifying ownership | Using `chgrp` and `chown` |
| " | " | Modifying permissions | Using `chmod` |
| " | " | " | Special Permissions |
| " | Searching Linux Logs | Understanding `rsyslogd` rules | Common Logs |
| " | " | " | Adding Custom Logs |
| " | " | Understanding log rotation | Using `logrotate` and */etc/logrotate.conf* |
| " | " | Searching the ***systemd*** journal using `journalctl` | Using `journalctl` |
| " | " | " | Persistent Journal Logging |
||||

## Day 3 Agenda

| **Section** | **Module** | **Lesson** | **Topic** |
| :---------: | :--------: | :--------: | :-------- |
| Linux System Administration | Collecting Troubleshooting Information | The `cockpit` Web Console | Connecting to Cockpit |
| " | " | " | Using Cockpit |
| " | " | Using `sosreport` | Collection and Extraction |
| " | " | " | Finding Information |
| Running Linux on PowerEdge | Supported Versions | Indentifying supported Linux versions | Finding OS version and release info |
| " | " | " | Locating support matrices |
| " | Identifying storage | Identifying disks and partitions | Disks and Partitions |
| " | " | Identifying LVM storage | PVs, VGs, and LVs |
| " | " | Identifying filesystems and mountpoints | Identifying Filesystems |
| " | " | " | Identifying Mountpoints |
| " | Configuring storage | Creating partitions | Using `fdisk`, `gdisk`, and `parted` |
| " | " | Creating XFS and EXT4 Filesystems | Using `mkfs`, `mkfs.xfs`, and `mkfs.ext4` |
| " | " | Mounting filesystems | Using `mount` and `umount` |
| " | " | " | Configuring */etc/fstab* |
| " | " | Creating and activating SWAP filesystems | Using `swapon` and `swapoff` |
| " | " | " | Using `mkswap` and configuring */etc/fstab* |
| " | " | Configuring LVM | LVM Basics |
| " | " | " | Using `pvcreate`, `vgcreate`, and `lvcreate`
| " | " | " | Using `vgexted` and `lvextend` |
||||

## Day 4 Agenda

| **Section** | **Module** | **Lesson** | **Topic** |
| :---------: | :--------: | :--------: | :-------- |
| Running Linux on PowerEdge | Identifying Networks | Identifying NICs | Using `ip link` and `ethtool` |
| " | " | " | Using `lsmod` and `modinfo` |
| " | " | Finding IP address, routing, and DNS info | Using `ip addr` and `ip route` |
| " | " | " | Using `dig` to query DNS |
| " | " | " | Using `nmcli` to find information |
| " | Configuring Ethernet Networks | Understanding the `NetworkManager` service | Devices and Connections |
| " | " | " | Using 'nmtui` and `nmcli` |
| " | Identifying additional hardware | Finding RAM information | Using `free` and */proc/meminfo* |
| " | " | " | Using `dmidecode` to identify RAM |
| " | " | Finding PCI device information | Using `lspci` and `lshw` |
| " | " | Finding USB device information | Using `lsusb` and `lshw` |
| " | " | Finding driver information | Kernel module basics |
| " | " | " | Using `lsmod`, `modprobe`, and `modinfo` |
| " | Using Dell Software on Linux | Booting to the SLI | Launching OMSA |
| " | " | " | Clearing Single Bit Errors from Event Logs  |
| " | " | " | Running Intel CPU Diagnostics |
| " | " | Installing the DSU repos on RHEL8 | Installing and Using `dsu` |
| " | " | Installing OMSA on RHEL8 | Using the DSU repos |
||||

## Day 5 Agenda

| **Section** | **Module** | **Lesson** | **Topic** |
| :---------: | :--------: | :--------: | :-------- |
| Running Linux on PowerEdge | Ubuntu Server | Idenfitying Supported Versions | Ubuntu "LTS" versions |
| " | " | " | What "Certified," "Validated," and "Fully Supported" mean |
| " | " | Important Ubuntu Differences | Logging differences from RHEL |
| " | " | " | Configuration differences from RHEL |
| " | Deploy and configure a server activity | Deployment | Resetting the hardware configuration |
| " | " | " | Installing RHEL8 manually |
| " | " | Configuration | Setting up users and groups |
| " | " | " | Configuring the network |
| " | " | " | Installing DSU and OMSA |
| " | " | Validation | Collecting a `sosreport` |
| " | " | " | Verifying system information using `sosreport` |
||||

*****
## Objectives Covered

- Using Red Hat Enterprise Linux
  - Using the BASH CLI shell effectively and efficiently
    - Logging in to the CLI shell
    - Understanding commands and their syntax
    - Understanding BASH metacharacters
    - Using time-saving BASH features   
  - Searching and Using Linux Documentation
    - Using built-in help
    - Understanding and searching `man` pages
    - Using `pinfo` and the GNU Info pages
  - Managing files and directories
    - Creating, copying, moving/renaming, and removing files and directories
    - Archiving files and directories
    - Transferring files over a network
  - Reading and editing text files
    - Reading text files
    - Editing text using `vim`
    - Searching for text using `grep` 
*****
- Performing System Administration Tasks in Linux
  - Managing users and groups
    - Creating and managing groups and users
    - Setting user passwords
    - Elevating user privileges for administrative tasks 
  - Adding and removing software
    - Using `yum` and `rpm` on RHEL8
    - Adding installation repositories on RHEL8
  - Managing ownership and permissions of files and directories
    - Identifying and interpreting ownership and permissions information
    - Using `chown` and `chgrp` to modify ownership
    - Using `chmod` to modify permissions 
  - Searching Linux logs
    - Understanding `rsyslogd` rules
    - Understanding log rotation
    - Searching the ***systemd*** journal using `journalctl`   
  - Collecting troubleshooting information
    - Using the Cockpit web console
    - Using `sosreport` 
*****
- Running Linux on PowerEdge Servers
  - Identifying supported Linux versions
    - Finding OS version and release info
    - Locating support matrices
  - Identifying storage
    - Identifying disks and partitions
    - Identifying LVM Physical Volumes, Volume Groups, and Logical Volumes
    - Identifying filesystems and mountpoints 
  - Configuring storage
    - Creating partitions
    - Creating XFS and EXT4 filesystems
    - Mounting filesystems
    - Creating and activating SWAP filesystems
    - Configuring LVM 
  - Identifying networks
    - Identifying NICs and finding their details
    - Finding IP address, routing, and DNS information
  - Configuring ethernet networks
    - Understanding the `NetworkManager` service
    - Using `nmtui` and `nmcli` 
  - Identifying additional hardware
    - Finding RAM information
    - Finding PCI device information
    - Finding USB device information
    - Finding driver information
  - Using Dell Software on Linux
    - Booting to the Support Live Image (SLI)    
    - Installing the Dell Server Update Utility (DSU)
    - Installing OpenManage Server Administrator (OMSA)

*****
*****
